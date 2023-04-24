<h1 align="center">Eye-Bee-M GNOME-Terminal</h1>

<p align="center">A retro <a href="https://wiki.gnome.org/Apps/Terminal">GNOME Terminal</a> color theme based on Paul Rand's iconic design.</p>

<p align="center"><a href="https://emoji-o-clock.pages.dev/"><img solid" width="80%" src="https://user-images.githubusercontent.com/94064167/216708576-f81266ac-0b2e-465a-bfb6-77a30624bffa.png"></a></p>

---

## Getting started

### Requirements

The installation script requires [`dconf`][dconf] and [`GNOME Terminal`][gnome terminal].

### Installation

1. Clone this repository

    ```sh
    git clone https://github.com/WebSnke/Eye-Bee-M-GNOME-Terminal
    cd Eye-Bee-M-GNOME-Terminal/source
    ```   
    
2. Run this command to apply the theme.
    
    ```sh
    dconf load /org/gnome/terminal/ < gnome-terminal-settings.txt
    ``` 

3. Restart GNOME Terminal.

4. Set your wallpaper to the [Eye-Bee-M poster](https://www.ibm.com/ibm/history/ibm100/images/icp/W141717T18176O09/us__en_us__ibm100__good_design__eye_bee_m__620x350.jpg).

5. Enjoy!

## License

<a href="https://opensource.org/license/gpl-3-0/">
  <img align="right" height="96" alt="GPL-3.0" src="https://upload.wikimedia.org/wikipedia/commons/9/93/GPLv3_Logo.svg" />
</a>

This project is licensed under the GPL-3.0.

The full text of the license can be accessed via [this link](https://opensource.org/license/gpl-3-0/) and is also included in the LICENSE file of this software package.

[dconf]: https://wiki.gnome.org/Projects/dconf
[gnome terminal]: https://apps.gnome.org/en/app/org.gnome.Console
