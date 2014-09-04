# Abgrammer

Abgrammer is a flat sexy theme. Abs Core included. 

This version is improves the original version of [Brogrammer theme](https://github.com/kenwheeler/brogrammer-theme) to support SublimeText 3 plus other visual improvements.

![Brogrammer Screenshot](http://i.imgur.com/jU6MlRT.png)
![Brogrammer Screenshot](http://i.imgur.com/vxlmNYP.png)

## Install

### Via Package Control

At the moment this theme is __not__ included for SublimeText 3 for Will Bond's [Sublime Package Control](https://sublime.wbond.net). (This feature will be implemented as soon I learn how to do this..)

Instead, please use the manual installation below.

### Manual

1. [Download the .zip](https://github.com/bahit/brogrammer-theme/archive/master.zip)
2. Unzip and rename the folder to `Theme - BrogrammerST3`
3. Copy the folder into `Packages` directory, which you can find using the menu item `Preferences -> Browse Packages...` in Sublime Text

### Using Git
Alternatively, this can be installed using Git by cloning this repo directly into your `Packages` directory in the Sublime Text application settings area.

You can locate your Sublime Text `Packages` directory by using the menu item `Preferences -> Browse Packages...`.

While inside the `Packages` directory, clone the theme repository using the command below:

    git clone https://github.com/bahit/abgrammer-theme/ "Theme - Abgrammer"

## Setup

Activate the UI theme and color scheme by modifying your user preferences file, which you can find using the menu item `Preferences -> Settings - User` in Sublime Text or by clicking `cmd + ,` on a Mac.

### Example settings
```
{
  "theme": "Abgrammer.sublime-theme",
  "color_scheme": "Packages/Theme - Abgrammer/Abgrammer.tmTheme",
  "abgrammer_sidebar_font_normal": true,
  "abgrammer_sidebar_tree_xsmall": true,
}
```

## Additional Features

### Sidebar font size

This theme includes different label font size for the sidebar (choose one below):

```
{
	"brogrammer_sidebar_font_normal": true,
	"brogrammer_sidebar_font_large": true,
	"brogrammer_sidebar_font_xlarge": true,
}
```

### Sidebar Tree padding

This theme includes different label font size for the sidebar (choose one below):

```
{
	"brogrammer_sidebar_tree_xsmall": true,
	"brogrammer_sidebar_tree_small": true,
	"brogrammer_sidebar_tree_normal": true,
	"brogrammer_sidebar_tree_large": true,
	"brogrammer_sidebar_tree_xlarge": true,
}
```

## Credits

* Forked SublimeText 2 theme by Ken Wheeler, [Brogrammer-theme](https://github.com/kenwheeler/brogrammer-theme)
* Icons are shameless edits of the icons in the [Flatland theme](https://github.com/thinkpixellab/flatland) along with configurable visual options for the sidebar.

## License
This theme is licensed under the [Creative Commons Attribution-ShareAlike 3.0 License](http://creativecommons.org/licenses/by-sa/3.0/). You are free to share and remix the theme, however please abide by the license terms when doing so.

The following details apply to the Creative Commons license "author specified" components:

Attribution example: Based on the Abgrammer theme by @bahit

Naming guidelines: If you create and distribute a derivative theme, please give your theme a unique name that goes with 'bro' or muscle or exercise related themes or pure awesome things. :D
