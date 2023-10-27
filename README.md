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
Contains the various modifications for the game that I enjoy using. Downloaded copies of zips and vpks on 10/26/23. Of course, you should download from the original source in case of any updates since then.
