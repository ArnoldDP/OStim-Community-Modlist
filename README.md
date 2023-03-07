# Unofficial Ostim Community Modlist

 [KNOWN ISSUES]
 
 This list is not finished, there might be more bugs than whatever is listed below.
 
 ENBSeries may fail to install throuhg wabbajack, but dont panic! Theres an easy workaround where you just have to manually download the ENB binaries and drop the .zip folder into the wabbajack download folder. After you do that, you need to create an empty text file with the exact same name as the enbseries zip file, and add a .meta extension to the end of it.
If done correctly, it should look like this

![image](https://user-images.githubusercontent.com/122011472/222934459-a70e81e6-259a-43a0-abf6-582e0e1a9a96.png)

If this *still* fails, DM me on Discord @Arnold#1526. ENBDev might have updated without me realizing it.

Theres a solid chance I didn't set up the auto-downgrade feature properly, if it fails then you can downgrade the game to 1.6.353 using this tool. If you're on version 1.6.640, the version you need is the second to last.
https://www.nexusmods.com/skyrimspecialedition/mods/57618
 
 There is an infinite loading screen if you enter the dlc1dimhollowcrypt01 cell (the first dungeon during the Dawnguard questline) ***AFTER*** starting the Awakening questline. For now, you're going to have to open the console and type coc dlc1dimhollowcrypt02, this will not break anything but your immersion. If you find the solution (or more bugs), please add me on discord @Arnold#1526 or ping me in the ostim discord
 
[ACTUAL README]

This is a vaguely lightweight modlist made for mid range computers. Most textures are 1k, with a few being 2k, and only skin textures and a few misc items that you will rarely see being 4k. The lowest my FPS dropped was around 50 in Falkreath. My system specs are: Ryzen 5 5600g, RX6600 8gb, and 16gbs of ram @ 2900 mhz. The only hard requirement is a CPU that supports at least AVX2. If you are having trouble running the modlist and dont really care for the enb, you can disable it through the mod organizer for a large performance upgrade.

While its not a neccessity, its encouraged to install this list on an SSD. It's a lot smoother.

This modlist should only require an installation of Skyrim SE through the Steam store, without any modifications done to the files that come stock with the game. If you have done any modifications to the base game files, you can validate your game through the steam store by right clicking the game -> properties > local files -> > verify integrity of game files. Alternatively, you can completely uninstall the game and all related folders and files, and reinstall it through Steam. 

Many of the included texture mods are compatible with ENB Complex Parallax. While its not a huge performance hit, its still turned off by default in this list's pre-packaged ENB. To enable it, right click Rudy - Zandgar Edit (bottom of the [root] seperator) -> open in explorer -> root -> enbseries.ini
Scroll down, just above [COLORCORRECTION] youll see the following lines

 1. EnableTerrainParallax=false
 2. EnableComplexGrass=true
 3. EnableComplexGrassCollisions=true
 4. EnableTerrainBlending=true
 5. EnableComplexParallax=false
 6. EnableComplexParallaxShadows=true
 7. EnableComplexTerrainParallax=false
 8. EnableComplexTerrainParallaxShadows=true

change them to look like the following

 1. EnableTerrainParallax=false
 2. EnableComplexGrass=true
 3. EnableComplexGrassCollisions=true
 4. EnableTerrainBlending=true
 5. EnableComplexParallax=true
 6. EnableComplexParallaxShadows=true
 7. EnableComplexTerrainParallax=true
 8. EnableComplexTerrainParallaxShadows=true
 
 If any of these lines are missing from the enbseries.ini, you can simply copy and paste the missing lines into the file. It will work just fine.

Pre-generated LODs are not included, both for performance reasons, and because we fully expect, and encourage you to add to this list. If you wish to generate your own LODs, make sure you disable everything in the [Flat World Map Framework] seperator before you do. After you're done generating, you can re-enable FWMF, but make sure you keep everything from FWMF *below* DynDOLOD and Occlusions in the load order. Your load order should look like this:

1. DynDOLOD
2. Occlusions
3. FWMF for Fantasy Paper Maps
4. FWMF Patches (evlas, weathers, etc)
4. Additional FWMF Maps

If you need a guide on LOD generation, you can follow this one https://github.com/LivelyDismay/Learn-To-Mod/blob/main/lessons/DynDOLOD%203.0%20and%20Grass%20Cache.md, you can also follow the STEP guide, or just Read the Funtastic Manual! There's a lot of guides on this.

NOTE FOR AMD USERS: If you are getting an OpenGL error while trying to run DynDOLOD 3.0, download and install the latest drivers from AMD's website, or downgrade to DynDOLOD 2.98

If you do decide to change weather and enb, make sure you disable [Rudy - Zandgar Edit] and [Rudy ENB Cathedral Weathers ADDONS and REQUiRED Files] in the mod organizer, then double check the Skyrim directory and [overwrite] to make sure that none of the enb files are still hanging around. Since this wabbajack uses the stock game method, the Skyrim directory is going to be in the same folder that you installed this list to. If you have trouble finding it, you can simply click the folder icon in the top right of MO2, and select open game folder

![image](https://user-images.githubusercontent.com/122011472/218272132-feec8b12-a456-43a8-be7b-7a4d495b3b1f.png)

You can either install your prefered ENB through the mod organizer (recommended), or by going to the Skyrim Special Edition 1.6.353 directory in the MO2 Portable Profile. If you want to use NAT, Azurite, Vivid Weathers, or Aequinoctium, you need to re-install [Flat World Map Framework] and select

1. Flat Map Markers AE (1.6.353)
2. All Skyrim Maps + DLCs + Worldspace Mods
3. FWMF for Fantasy Paper Maps
4. Weather overhauls requiring a patch + Yes on Water for ENB
5. Yes to ELVAS fix (beta)

Your load order needs to be adjusted to 

1. DynDOLOD (If you did generate your own LODS)
2. Occlusions (If you did generate your own LODS)
3. FWMF for Fantasy Paper Maps
4. FWMF Patches (evlas, weathers, etc)
5. Additional FWMF maps

To install an ENB through MO2 using Root Builder, do a manual install. When it asks you to select a data folder, right click and create a [Root] folder under <data>, then drag and drop enbseries, enbseries.ini, and enblocal.ini into the root folder that you just created. When done properly, it should look like this

![image](https://user-images.githubusercontent.com/122011472/218272401-8c469a5b-b246-4b13-929e-8e06fc7710d0.png)

Now just click ok, and then ignore when it warns you that the mod is probably not set up correctly.
For ENBs that require an evlas config, such as NAT or Skies Above, you can install the evlas config directly to Skyrim Special Edition\data, or install it as a seperate mod.

If you want to use Reshade, Sswaye has written an excellent guide on it. You can find that here at the bottom of the page https://www.nexusmods.com/skyrimspecialedition/mods/67966

Join the discord! https://discord.gg/ostim
