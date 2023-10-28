# Onion CFG
Big thank you to the entire scripting community. Over a decade of dissecting the source engine has made it even easier than ever to customize the game how you like. In my case there isn't anything crazy going on, no specialized alias frameworks or suites
just whatever particular scripts and cvars I liked most organized simply and in a way that makes sense to me. 

In particular, I found these people to be the best and most consistent sources of knowledge while redoing all of my CFGs and I reference them all throughout.
- Mastercom for thoroughly [documenting](https://github.com/mastercomfig/mastercomfig/blob/develop/config/mastercomfig/cfg/comfig/comfig.cfg) everything performace related to the game and making it easy to optimize with her [Mastercomfig](https://comfig.app/).
- JarateKing for the many useful scripts in his [Jarconfig](https://github.com/JarateKing/jarconfig) and the extensive scripting knowledge therein.
- Timepath. A very knowledgeable scripter with his own [Config](https://github.com/TimePath/tf2-config) and is a contributer to the [Tf2scripts reddit](https://www.reddit.com/r/Tf2Scripts/).
- [Genemilder](https://www.reddit.com/user/genemilder). High level scripter and prior moderator of [Tf2scripts reddit](https://www.reddit.com/r/Tf2Scripts/)

## Overrides Folder
__Execs Folder__ : Yoinked from [jarconfig](https://github.com/JarateKing/jarconfig/tree/master/cfg/execs) for the functionality of a handful of useful aliases.

__aliases__ : A collection of basic aliases used across all the classes with sources

__autoexec__ : Individual commands I found useful to change. One of the things I disliked most while trawling through other people's cfgs was the lack of documentation within, so everything in my autoexec is organized alphabetically underneath the cvar prefix (sv_, tf_, cl_, etc) with full documentation of defaults, min to max values, and functionality from the tf2 dev wiki and mastercomfig docs.

__binds.txt__ : the first cfg I worked on. Originally a bind reset cfg, it became a txt file I used as an all-class pure vanilla binds reference sheet to brainstorm what I wanted on my keyboard. Every other individual class has their own full keyboard bind setup.

__class cfgs & game_overrides__ : Individual keyboard binds and aliases for the classes. Mastercom's provided game_overrides is only used for a handful of commands that don't seem to work in autoexec or to revert some class specific cvars like tf_remember_activeweapon for demoman and medic or cl_hud_playerclass_use_playermodel for spy

__listenserver, modules, post_comfig, & pre_comfig__ : premade cfgs by mastercom. In the same order these cfgs run cvars when loading into a local server; control specific levels of settings in mastercomfig; run cvars at game launch, after mastercomfig core, but before presets, addons and modules; and run cvars at game launch, before mastercomfig.

__regen__ : Timepath script for keeping a resupply cabinet locked onto the player. Useful for practicing explosive jumps.

__vaccinator__ : a vaccinator script by [Tmob](https://gist.github.com/tmob03/fceddfa38ab324f91d6177a0771d11ab) which works very well. Gets you to the exact resistances you want with a single press and is very resilient to desyncs, besides dying.

## Custom Folder
Contains the various modifications for the game that I enjoy using. Copies of zips and vpks made on 10/26/23. Of course, you should download from the original source in case of any updates since then.

[Domination Removal](https://gamebanana.com/mods/36617) : 8 year old mod that removes a great deal of the domination sound and ui effects.

[Solarlight HUD](https://github.com/SolarLightTF2/SolarLightHUD/tree/b7059e253051b24b2b90b37576cbc35baec005c6) : Comfig.huds [mirror](https://comfig.app/huds/page/solarlight-hud/).

[TF2 Ultimate Visual Fix Pack](https://github.com/agrastiOs/Ultimate-TF2-Visual-Fix-Pack) : Contains both the 000 and .dir folder needed for the mod to work with a small edit to remove some arrow particles from the added jumper explosion sfx.

[Horsie's Viewmodel Editor](https://gamebanana.com/tools/10146) : Most powerful viewmodel editing tool for the game.

[ahud](https://github.com/n0kk/ahud) : Comfig.huds [mirror](https://comfig.app/huds/page/ahud/).

[Altered Short Circuit FX](https://gamebanana.com/mods/11900)

[Better Kill Icons](https://gamebanana.com/mods/406361)

[Disable Miss Pauling's Contract Alerts](https://gamebanana.com/mods/325900)

__hitsounds__ : Uses the classic quake hitsound for regular hits and the [Ultrakill parry sfx](https://youtu.be/rcXRwD9MPDI?t=7) for kills.

[loadouts](https://github.com/jooonior/tf2-loadouts-script) : Resupply script

[Mastercomfig](https://comfig.app/app/) : Contains the Medium-High preset, disable pyroland, flat mouse, no footsteps, no soundscapes, and no tutorial addons

__No Muzzle Flashes w/ Sentry MF visible__ : I sadly don't recall the original TFTV thread I downloaded this from.

[Transparent Flames](https://gamebanana.com/mods/348622) : Makes Flamethrowers and Dragon's Fury significantly less visually obstructive

## Misc
```
Mastercomfig medium high preset
addons: disable pyroland, no tutorial, null-cancelling movement, flat mouse, no soundscapes, no footsteps
i7-12700K P-cores 3.610 GHz - 5.00 GHz, GTX 1060 6GB, 16GB 3600MHz RAM, 1TB SK hynix Gold P31 PCIe NVMe Gen3 M.2 2280 Internal SSD
          E-cores 2.700 GHz -  3.80 GHz  
CPU is not overclocked, base values are what is being used
-w 1920 -h 1036 1.85:1 aspect ratio (1920x1036) gives max FOV gain http://casualhacks.net/Source-FOV-calculator.html
```
[Stabbystabby's everything pack](https://old.reddit.com/r/tf2/comments/6gyz69/stabbys_everything_pack_2017_editionevery_dang/) : [Internet Archive mirror](https://archive.org/details/stabby-everything-pack-2017-full)

[Antigen07's Mouse Optimization Guide](https://www.overclock.net/threads/cs-s-mouse-optimization-guide.173255/) : [Internet Archive mirror](https://web.archive.org/web/20230929222545/https://www.overclock.net/threads/cs-s-mouse-optimization-guide.173255/)

[Povohat and Kovaak's Mouse Accel Driver](https://www.kovaak.com/mouse-acceleration/)
