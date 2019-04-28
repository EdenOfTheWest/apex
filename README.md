# Buer's autoexec.cfg and more! :)

These will change game features by disabling certain aspects of the game. Most of these have comments to help people understand what does what, and this is 100% safe to use.
Just be sure to change settings that are obviously tweaked based on my computer vs. yours. Example: **ctrl F** and search for "Nvidia".

I am currently working on trying to fix some sound issues!!! Please, **DO NOT USE** the commands for that unless you are having sound issues as well.


With the network commands, these .cfg's will compress packets and send them out faster.

My binds allow for bhopping through mouse wheel up/down(easier), Showing player POS(Position)/Velocity, fps, as well as a volume changer.
Side note: many of these binds work ONLY in game. Don't panic when you're testing them at the menu!

Theres also an extra command to Quick DC to login screen via F10 as I like to rage quit because hackers are stupid shit heads.
F1 will Ping Mozam, even when there is no Mozam. Don't be annoying or I'll delete your System32.




# How do I use these?
First, go to game properties on origin(must be closed out of the game)
<img src="https://i.imgur.com/twr3GFX.png"
     alt="https://i.imgur.com/twr3GFX.png"
     style="float: left; margin-right: 10px;" />




Now and edit your launch commands. To use the commands simply just add in **+exec autoexec**, but if you want to try and force fullscreen(the game hates it), add the second, and if you dont want vsync, then the third.
<img src="https://i.imgur.com/ZzJWKGN.png"
     alt="https://i.imgur.com/ZzJWKGN.png"
     style="float: left; margin-right: 10px;" />

Boom, magic. you did it. Now find where you installed your game. Mine is located in **G:\Origin Games\Apex\cfg** mine is located on an SSD dedicated to my games. From here, there is a cfg folder, this is where you will place the file(s).

## autoexec.cfg
This is what's needed for all the other .cfg's. This is the main tweak file, most of this stuff has comments. It decreases graphics by removing/lowering some stuff and not really needed effects such as disabling water splash particles, water reflections, etc. It compresses packets and sends them out faster, disables Ragdolls(if you want, you can even tweak this to make bodies flop around... but why?) This also disables some fog, shadows of certain objects(like ropes/ziplines) and lighting, such as flares, particles, dynamics and volumetric. This also boost's performance of some systems by enabling multithreading. As said, read through this one, ESPECIALLY.

**r_fastzreject** Please, change this setting to what it tells you to. There is one for Radeon/AMD(0) and one for NVIDIA(1), or let your system decide, aka the safeway(-1).

## AHud.cfg
This is all HUD changes. makes minimap rotate, makes HUD semi transparent. disables some shakiness of the screen, some health wheel/grenade tweaks on the wheel.


## Binds.cfg
Literally just my rebinds. **F10** to ragequit and go to login screen, **F1** for Mozam, **END** for pos/velocity, **Home** for FPS, **0** for volume 100% to 15%, **mousewheel up/down** for jump(bhops).


## Net.cfg
Don't use this unless you want to test shit or have broken audio, regardless of the name, this is not strictly network tweaks. It's mostly sound tweaks.
