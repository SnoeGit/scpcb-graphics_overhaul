Thank you for downloading the SCP - Containment Breach Graphics Overhaul mod!

Conceptualized, modded, and finalized by Placeholder Studios

----------------------------------------------------

We at Placeholder Studios hope you enjoy this mod and all of it's new updated and reworked graphics! 

This includes textures, normal maps, menus, icons, buttons, backgrounds, loadingscreens, and more!

For most change please enable bump mapping as we'd hate for all of our new normal maps to go unnoticed.

----------------------------------------------------

This mod will be updated semi-regularly until notice of it's full cocmpletion. 

For all updates, changelogs, and general information please consult our ModDB page:

https://www.moddb.com/mods/scp-containment-breach-graphics-overhaul-mod

----------------------------------------------------

Thank you once again for playing. We hope you like the mod.

-Placeholder Studios

----------------------------------------------------
Known Bugs:

- Weird, squished normal mapping: We are aware that some textures will appear odd and bubbly due to the texture
the normal map being applied to is squished in the map engine. Without modifying the map files themselves (which
may end up being a future endeavor) there is practically no way to fix this while keeping normal maps enabled.

- Camera lag: When looking at a live camera screen (some camera screens are just animated images, others are actual
live gameplay from a physical camera in game) such as the intro or light containment observation room, you may
experience some extreme lag, this is due to the game not having culling or mipmapping in live cameras, meaning the
game has to actually render two viewmodel cameras which can be very performance intensive.

- Not all of a certain texture having normal maps: Certain textures (such as active doors), are placed in code 
itself and not in the map editor. Internally we call these "live objects" and normal maps are not applied to them
as they are not part of the normal map baking step of the render pipeline. There is little or nothing that can be 
done about this. It is a fundamental flaw in the way that CB renders maps and objects.

- SCPs and other entities not having normal maps: SCPs and other entities (including items) that are placed into
the map after the generation process do not have normal maps. This is also due to them being "live objects" and
very little can be done about this.