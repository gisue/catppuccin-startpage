https://github.com/pivoshenko/catppuccin-startpage/assets/40499728/d96c8bd6-168e-408f-b4f0-0e339569c696

## Overview

Aesthetic and clean startpage in [**Catppuccin Mocha**](https://catppuccin.com/palette) style, hosted on GitHub Pages. This start page is based on the [`dawn`](https://github.com/b-coimbra/dawn) and [`tartarus-startpage`](https://github.com/AllJavi/tartarus-startpage), which has even more functionality.
I've tweaked the page's style to match [Catppuccin](https://github.com/catppuccin/catppuccin) palette and my [`dotfiles`](https://github.com/pivoshenko/dotfiles).

### Main principles

- Minimalism in everything
- Consistency
- Simplicity
- One style
- Reduced visual noise

## Usage

1. Fork this repository and clone it

2. Remove `.github` directory as it contains only PR templates, issue labels etc that are linked to this repository

3. Update [`userconfig.js`](userconfig.js):
   - Set your location for the weather widget
   - Update the number of pages and their banners
   - Update bookmarks and quick links for the one you are using the most :3

> [!TIP]
> You can find icons for your bookmarks using [`tabler-icons`](https://tabler.io/icons)
>
> If you want to reduce the loading time of the icons, you could install the icon [font](src/fonts) locally and activate the option `"localIcons": true` in the config to disable the remote styles

#### As Homepage

- Click the menu button and select `Options/Preferences`
- Click the home panel
- Click the menu next to the homepage and new windows and choose to show custom URLs and add your GitHub Pages link

#### As New Tab

You can use different Add-ons/Extensions for it
- If you use Firefox: [Custom New Tab Page](https://addons.mozilla.org/en-US/firefox/addon/custom-new-tab-page/?src=search) and make sure you enable "Force links to open in the top frame (experimental)" in the extension's preferences page

- If you use Chromium (Brave, Chrome): [Custom New Tab URL](https://chrome.google.com/webstore/detail/custom-new-tab-url/mmjbdbjnoablegbkcklggeknkfcjkjia)
