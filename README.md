# Solaris Renderers Radial Menu

This is a scripted native Houdini radial menu which changes the active renderer in Solaris.

![solaris_renderers_example](https://github.com/alexmajewski/hydra-renderers-radial-menu/assets/77795178/8ef68a48-7252-4edb-93a8-f9ca451b29ea)

## Usage
Select the 'Solaris Renderers' option from the menu dropdown at the top of the screen (located in the 'Utility' section), and press 'C' key with your cursor in the 3D Viewport in order to access the menu. 

![solaris_renderers_dropdown](https://github.com/user-attachments/assets/c2714771-5136-49e1-ac8d-2c7ab6b1ce17)

You can also enter Edit Radial Menus window available in the dropdown and set a custom hotkey.

## Known issues
When switching to a non-pathtraced renderer such as Houdini VK or Storm, the viewport will not update until you hover over a UI element, move the camera, or press Alt.

## Installation

First, download the [latest release](https://github.com/alexmajewski/hydra-renderers-radial-menu/releases/latest).

### Installing Manually
Just copy `radialmenu/solaris_renderers.radialmenu` into your `$HOUDINI_USER_PREF_DIR/radialmenu/`.

In other words, `C:/Users/You/Documents/houdini19.5/radialmenu/solaris_renderers.radialmenu`.

### Installing as a Package
Edit the `solaris-renderers-radial-menu.json` file and replace the file path to the actual location of the package folder on your disk, then copy it to your Houdini user preferences directory into a `/packages/` folder, i.e. `C:/Users/You/Documents/houdini19.5/packages/solaris-renderers-radial-menu.json`.

## Other Radial Menus
You may also be interested in pairing this with [Dynamic Cameras Radial Menu](https://github.com/alexmajewski/dynamic-cameras-radial-menu).
