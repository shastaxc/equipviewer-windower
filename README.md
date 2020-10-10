Originally created by ProjectTako https://github.com/ProjectTako

EquipViewer
Overlays your currently equipped items onto the screen anywhere. Basically just shows your equipment screen, but smaller, anywhere you want, and you can make it translucent.

Commands (prefix: equipviewer or ev)
ev pos x y - Moves the equipment overlay to the desired location, where x and y are number of pixels from top left of screen.
ev position x y - Same as above
ev size s - Sets the icon size to the given size, where s is a number of pixels.
ev reset - Reinitializes the display
ev clear - Same as above

To use:
Must use Windower. Does not work with Ashita.
Start by creating a folder in your addons folder called equipviewer.
Place the equipviewer.lua file in your equipviewer folder.
Unzip the file in the icons folder.
  Your directory structure should look like this:
  equipviewer/
    -equipviewer.lua
    -icons/
      -32/
        -Lots of images

Adding new equipment icons:
When new gear is released, you may be missing the icon for that piece of equipment.
Once you have obtained a new image of the appropriate size, you can simply drop it into the correct size folder in the icons folder.
The default size is 32 and the images found on FFXIAH are of the correct size so the easiest way to obtain new images is to pull them from there. Go to the item page, right click the icon, and save it in the icons folder. It's already named the correct name and everything.