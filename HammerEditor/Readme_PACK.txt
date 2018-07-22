=================================================================================================================================
Hammer improvement Pack unofficial 3.5.2 // version 2.0       made by Cellulo aka Kato-yuen   www.flat2d.com    November 30 2012
=================================================================================================================================

This pack is for Half-Life deathmatch and solo mapping or any mods under the goldsource engine. It's for accelerate the workflow under Hammer 3.5 , 

See the list change below:

- added new fgd file ( half-life_352.fgd ), edit the file to see the change.

- added some texture dev like in Half-life 2 editor made by JPolito, modified by me to add more texture dev 
  from others wads, new name file "jp_dev_plus.wad" , and i made "entity.wad" that regroup all textures dev entity found in others wads and maps.) 

- updated colors for weapons models (in red) , ammos models (in yellow) and some items 3D (in green,pink,blue), 
and removed smoothing groups polygons for better view inside worldcraft.

- updated colors for the static 3d model player for info_player_start, info_player_deathmatch and info_playercoop 
and removed smoothing groups polygons for better view inside worldcraft.

- added all compilers tools existing at this day ( ZHLT 34, SHLT 3.9, SHLT AO, Vluzacn 30 )

- added Hammer 3.5 beta with some new tweaks in the interface based on CSM HAMMMER Editor 0.3.8.1 (http://cs-fun-pro.com/load/35-1-0-313) 
  and VHE Neon ( http://gamebanana.com/cs/tools/5130).
     
	 New shortcuts keys:
	 
	 *_shortcut key    Ctrl+Shift+S  "Save &as"
	 *_shortcut key    Ctrl+Shift+M  "Save to .map"
     *_shortcut key    Ctrl+Shift+D  "Save to .DXF"
	 *_shortcut key    Shit+Escape   "Close opened map"
	 
	  	 
	 *_fixed bugs [block tool] primitive objects not corresponding(arch, wedge , block and spike) in hammer 3.5 (using tool hexadecimal editor)

     *_New cursors.

- added "scripts_docs folder" from planethalf-life made by Otis and Reaper ( thx webarchive )

- added new starting logo from the recent logo valve hammer editor 4.0.

- added the template map txt file from the death homepage of globalassault.com

- [ In folder "Patch" ]added hammer floating point patch and A hammer grid hack patch made by Vluzcan. 
(The first patch blocks Hammer from converting plane coordinates to integers when exporting *.map file and 
the second patch extends the limit of 4096 units to 16384 units, for bigger maps, but its recommended you 
use Vluzacn's custom compilers for this, and only use the extended grid to build world brushes*) 
Warning you must apply these patches to have a working floating and grid hack hammer version.

- added some new fgd files from others mods.


=================================================================================================================
Hammer improvement Pack unofficial 3.5.1 // version 1.0       made by Kato-yuen    www.flat2d.com    June 20 2009
================================================================================================================= 

- added Hammer 3.5 beta with some tweaks in the interface

- added New fgd to support the new change. ( half-life_351.fgd )

- added some sprites of the half-life 2's hammer editor, visible in the 3D view. 

- added new sprite ambient_generic.spr

- added and modified the static 3d model player for info_player_start, info_player_deathmatch and info_playercoop with arrow direction.

- added all weapons,ammos and items 3D models from the Half-Life SDK 2.3

- added some 3d models mdl for some entity, visible in the 3D view.(see the list below)

- added the missing tripmine ammo 3D model (w_tripmine.mdl) taked in the v_tripmine.mdl object from the sdk 2.3 to see it in the 3D view.

- added new Help file in chm format, i have upgrade the help
for hammer 3.5, insert the tutorial mapping of the help file of the worldcraft 2.1
with his rmf/bsp files in corrected version, added the env_beam.rmf/bsp from the SDK in corrected version. Some new pages and new screenshots, its the merge of the help file of hammer 3.4 and 2.1. 

- added setup installation without need to install hammer 3.4, all in one package.


These 3D models replace some entities:

- monster_generic.mdl
- scripted_sequence.mdl
- cycler_sprite.mdl
- cycler.mdl
- cycler_weapon.mdl
- env_global.mdl
- info_teleport_destination.mdl
- trigger_auto.mdl
- trigger_change_target.mdl
- game_team_set.mdl
- game_team_master.mdl
- game_score.mdl
- game_player_team.mdl
- game_player_hurt.mdl
- game_player_equip.mdl
- game_counter_set.mdl
- game_counter.mdl
- target_cdaudio.mdl
- trigger_camera.mdl
- path_corner
- path_track.mdl
- info_bigmomma.mdl
- monstermaker.mdl
- player_loadsaved.mdl
- player_weaponstrip.mdl
- world_items.mdl
- env_funnel.mdl
- env_laser.mdl
- env_blood.mdl
- env_beam.mdl
- infodecal.mdl
- info_node_air.mdl
- info_node.mdl
- Player_solo.mdl
- Player_deathmatch.mdl
- Player_coop.mdl


Just for information it's not a hack of hammer it's just only some tweaks in the interface made with resource hacker tool.



History of Hammer aka Worldcraft:

Hammer 3.5 BETA

    * Added pointfile viewing to the 3D view.
    * Modified Half-Life and DoD FGDs to add model viewing support
    * Improved the texture application tool and advanced compile mode dialog UI.
    * Separate pitch, yaw, and roll angle compasses added to entity properties
    * "animate models" toggle in 3d options.
    * Adjustable viewdistance for models in 3d options.
    * Selectable animation sequences.
    * Customizable 3D view background color.



Hammer 3.4

    *  your registry settings will be converted automatically
    * copy the *.wc files from your Worldcraft folder to your Hammer folder.
    * if you use custom prefabs, copy your prefabs folder from your Worldcraft folder to your Hammer folder.
    * other custom content, like sprites or map source files, will also need to be copied manually.


    *  Splitter view layout is now preserved from session to session.
    * Dialog bars now pop to the top when the mouse cursor floats over them.
    * No longer renders the 3D views when the editor is not the active application. 
(This will fix most people's problems with running Hammer and Half-Life at the same time causing the editor to freeze)
    * Added Copy to Clipboard button to the process window.
    * Sped up time to bring up the Face Properties dialog when many brushes are selected.
    * Sped up 2D view scrolling.
    * Added timed selection of objects by depth in the 3D view when the left mouse button is held down.

Fixed:

    * Fixed a random spinlock when rendering sprites.
    * Fixed texture rendering problems with sprites, etc.
    * Fixed freeze when starting map with sprites visible.
    * Fixed a crash in the path tool.
    * Fixed problem with texture shifts being reset when importing old MAP files.
    * Fixed black brushes caused by clipping.
    * Fixed a lockup when scaling certain brushes.
    * Fixed infinite lines in 3D view in vertex mode.
    * Fixed clipping causing duplicate solids.
    * Fixed decal repositioning.
    * Fixed camera angle view bug.
    * Fixed problem with running compile tools from paths with spaces.


Hammer 3.3

* OpenGL 3D Renderer. The real-time renderer is much faster, more robust, and allows for animating visuals in the 3D view. 

* Texture Locking. Texture alignment is now preserved through rotation, scaling, and flipping, allowing for the hassle-free construction of odd-angled geometry. 

* Powerful Texture Application Features. Automatic texture continuity is guaranteed when lifting and applying from one face to another. Textures can be fit across one face or multiple faces, or aligned to the left, right, top, bottom, and center of faces with a single button click. Textures can be projected onto faces from an arbitrary viewpoint, useful for texturing cliff faces or other irregular geometry. In addition, texture axes are now displayed in the 3D view. 

* Sprite Preview. Sprites are now automatically previewed in the 3D view, along with animation. Frame rate and scale key values are correctly reflected in the preview, eliminating the need to compile and run the map in the game engine when placing sprites. 

* Go To Brush Number. Brushes can now be found by entity / brush number for fast tracking down of compiler errors. 

* Iconic Entities. Any point entity can be set to render as a sprite icon in the 3D view through a specification in the FGD file, making it easy to distinguish between different entities in the 3D view. 

* 3D Preview of Tools. The brush creation, clipper, cordon bounds, and selection tools all render in the 3D view in real time, taking the guesswork out of previously painstaking operations. 

* Colored Solid Entities. Solid entities can now be given a render color in the FGD file, for easier identification in the 2D or 3D views. 

* 3D Grid. A new 3D grid allows for easy visualization of brush sizes in the 3D view. 

* Missing Texture Replacement. Added a Replace button to the texture bar, making it easy to replace textures when they are missing from the WAD file. 

* Texture Usage Report. Statistics on unique textures, total texture memory, and WADs used in are reported in the Map Information dialog 

* Enhanced Camera Controls. Real-time keyboard sampling gives smooth camera movement in the 3D view. Holding down both mouse buttons now enables dollying the camera forward and back. The mouse wheel now zooms both the 2D and 3D views. 

* Point and Click Entity Placement. Point entities can now be placed directly in the 3D view just by pointing and clicking. 

* Entity Key Browse Button. Added a browse button to the Entity Properties dialog for typo-free setting of sprite, sound, and model keys.




Legal notices
-------------
The Valve Hammer Editor is a trademark of Valve L.L.C., copyright 1996-2012, all rights reserved. 

Under no circumstances will Valve Software be liable for any damages 
or losses arising from the use or misuse of this software. If you use 
this software, you agree to these terms.


                                   ###