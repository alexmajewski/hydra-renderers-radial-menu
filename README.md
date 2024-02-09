# Hydra Renderers Radial Menu

This is a scripted native Houdini radial menu which changes the active renderer in Solaris.

![hydra_renderers_example](https://github.com/alexmajewski/hydra-renderers-radial-menu/assets/77795178/8ef68a48-7252-4edb-93a8-f9ca451b29ea)

## Usage
Select the 'Hydra Renderers' option from the menu dropdown at the top of the screen (located in the 'Utility' section), and press 'C' key with your cursor in the 3D Viewport in order to access the menu. 

![hydra_renderers_dropdown](https://github.com/alexmajewski/hydra-renderers-radial-menu/assets/77795178/0a9096e7-64d0-4ee6-8e46-a34de1ea9116)

You can also enter Edit Radial Menus window available in the dropdown and set a custom hotkey.

## Installing as a Package
Edit the .JSON file and replace the file path to the actual location of the package folder on your disk, and copy it to your Houdini user preferences directory into a `/packages/` folder, i.e. `C:/Users/You/Documents/houdini19.5/packages/`.

Alternatively, you can just put the .radialmenu file inside a `/radialmenu/` folder inside the houdini preferences directory.

## Other Radial Menus
You may also be interested in pairing this with [Dynamic Cameras Radial Menu](https://github.com/alexmajewski/dynamic-cameras-radial-menu).
