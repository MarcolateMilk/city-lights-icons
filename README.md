# City Lights GTK+ 3 Icon Theme

Icon theme to go along with my [City Lights GTK+ 3 Theme](https://github.com/MarcolateMilk/city-lights-gtk).

## Notes

* I merely recolored and slightly changed the design of the Adwaita icons to make them more uniform, I do not take any credit for the icons' design
* There are no symbolic icons, since I barely changed the design the Adwaita symbolic icons work just fine with this theme
* There are no application icons since I don't need them. If you need them then you have to either choose some from a different icon theme or make do with the Adwaita ones

## Installation

### Requirements

* GTK+ 3
* git

### Linux

To install open your terminal and type:

```sh
mkdir -p ~/.icons/City-Lights && cd ~/.icons/City-Lights
git clone https://github.com/MarcolateMilk/city-lights-icons .
```

Then edit your `~/.config/gtk-3.0/settings.ini` like so:

```ini
[Settings]
gtk-icon-theme-name = City-Lights
```

## Credits

* [GNOME's Adwaita icon theme](https://gitlab.gnome.org/GNOME/adwaita-icon-theme)
