---
layout: menu
title: Map Editor
description: Map editor tips
tags:
- creation
- map-editor
---

# Introduction to the Map Editor
The map editor is one of the famous features of the Trackmania (and now Maniaplanet) game serie. It gives you the possibility to create very easily maps for the game with a easy to handle thanks to the block system.

This article will explain you quickly the interface and few building tricks.

If you want to check all the shortcuts of the editor, please go [on this article][1].

# Interface

## Default interface
![Map Editor interface][2]

1. Save the map
2. Help about the map editor
3. Terraformation mode to change the landscape
4. Block mode: list all the blocks of the environment
5. Paint mode: used to change the image on panes and others blocks like them
6. Item mode: List all the items available in the [title pack][3] and/or in the folder `Documents\Maniaplanet\Items`
7. Macroblock mode: Allow you to add a previous registered macroblock in the map
8. Delete the block targeted
9. Undo/Redo
10. Select the block targeted on the map
11. Copy/paste mode
12. Switch to freelook mode
13. Underground mode: Allow you to see/add blocks underground
14. Offzone tool: Allow to add offzone in your map (for Shootmania only)
15. Plugin mode: Allow you to create/run plugins for the editor
16. Blocks/Items lists
17. Advanced mode: Give you extra features for the map editor
18. Mediatracker: Useful if you want to create a video introduction for your map or if you want to change the mood or the vision of the players
19. Test mode: Test instantaneously your map, can be loaded with a specific gamemode
20. Validation state: Give the state of the validation for the map
21. Give the current maptype of the map
22. Edit the properties of the blocks of the map
23. Name of the map
24. Name of the author
25. Weight of the map
26. State of the map

## Advanced Customization tools
![Map Editor Adv Options][4]

1. Set the MapType of the map
2. Set the map objectives
3. Edit the thumbnail of the map (use in the maplists)
4. Edit the comments of the map, useful if there is somthing special that you want to point about the map
5. A music can be played with this specific map instead the Maniaplanet or Trackmania default musics. The file must be in `.ogg` format.
6. Will create credible shadows on the map. Higher the shadows are computed, higher will be the accuracy of the shadows.
7. If you want to test the map with a specific gamemode
8. You can protect your map with a password if you don't want your map to be edited by someone else.
9. Allow you activate several experimental features like the *Air Mapping*, the *Mix Mapping* and the *Item Embedding*. **Those features are experimental because the maps created with one of these features can to not work after an update.**

# The MapType
A maptype is a file which list all the blocks required in order to be played with a specific gamemode. However, a gamemode can accept several maptypes if the gamemode creator has decided to do so.

To change the maptype of a map, you just need to click on the name of the maptype in the editor and a window will open listing all the maptypes available on your folder `Documents\Maniaplanet\Scripts\MapTypes` (and then `\Shootmania` or `\Trackmania` depending of the environment, create it if it doesn't exists). The maptype can be forced if you create a map from a Title Pack.

# Validation of a map
A map can be played online (and in LAN) only if the map has been validated for a maptype. To know which block(s) are required to make the map compatible with a maptype, the player must associate the desired maptype to his map.

The blocks required are specified when you click of the validation flag while it's red. Another thing to do to validate the map is to compute its shadows (to have relevant shadows on the map). This step is required each time you change (add/delete or modify) a block in a map.

The validation flag can have three states:

* Red: The map is not validated for the current maptype and so can't be played online.
* Orange: The required blocks are on the map but the map need to be tested at least once to make sure it's working (this state usually exists for Trackmania tracks, the builder must finish his race in order to validate it)
* Green: The map is validated and can be played online (and in LAN)

# Tips
About the weight of the map, it's recommend to have a map around 10 000/12 000 *coppers* maximum (metric used to name the weight of a map) to be sure that the map will run on almost all computers capable to run Maniaplanet at the minimum.
This isn't a software limit, you're free to create maps way heavier than that but in that case, only high-end PCs will be able to run these maps smoothly.

[1]: ../../client/shortcuts.html#Map-Editor
[2]: ./img/Map_Editor_UI_Edited.jpg
[3]: ../title/
[4]: ./img/Map_Editor_UI2_Edited.jpg
