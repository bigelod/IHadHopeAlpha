I Had Hope
Copyright © 2011 - 2019, Jayjay (aka Daven Bigelow) & Bioked
View the development log at www.ihadhope.blogspot.com!
---------------------------------------------------------------------------------------------------------------------------------------
0.Table of contents
---------------------------------------------------------------------------------------------------------------------------------------
1. About the game
2. System requirements
3. Controls
4. Frequently Asked Questions
5. Known Bugs
6. Changelog
7. Credits
8. Licenses

---------------------------------------------------------------------------------------------------------------------------------------
1.About:
---------------------------------------------------------------------------------------------------------------------------------------
Arcade mode: You play as a lone survivor who tries to survive wave after wave of the undead 
shambling towards you while earning points to buy better weapons and build better defences. 
There may even be a few helpful powerups to aid you along the way.

Campaign mode: More details coming soon.

---------------------------------------------------------------------------------------------------------------------------------------
2.Estimated system requirements:
---------------------------------------------------------------------------------------------------------------------------------------
Minimum:
-1.8Ghz Pentium 4 processor
-64MB DirectX 9 compatible graphics card
-256MB RAM
-Windows XP

Recommended:
-2.8Ghz Pentium 4 processor
-128MB DirectX 9 compatible graphics card (pixel shader 2.0 support)
-512MB RAM (1GB RAM for Windows 7)
-Windows XP/7*

*Although the game will run on Vista, it crashes often with this version of Windows, use at your own (and our) frustration

---------------------------------------------------------------------------------------------------------------------------------------
3.Controls:
---------------------------------------------------------------------------------------------------------------------------------------
This game uses either the keyboard and mouse, or an xbox controller.

Keyboard/mouse controls:
--------------------------------------
W,A,S,D - Move
Mouse - Aim/Select item to buy at vending machine
Left click - Shoot/Purchase vending machine item
Right click - Throw grenade, proportional to mouse distance from player
Shift - Sprint
Control - Pick up or place a barricade
Spacebar - Melee
Tab - Toggle slow-mo (if unlocked)
E - Buy weapon at shop/Build barricade at workbench/Open vending machine view
R - Repair barricade/Add materials to workbench
Q - Switch between pistol and primary weapon
F - Throw a flare, proportional to mouse distance from player
M - Change song (when playing custom music)
Escape - Pause game/Exit vending machine
Ctrl + Y - Quit to title (while paused)

Xbox controls:
--------------------------------------
Left thumbstick - Move
Right thumbstick - Aim/Select item at vending machine
Left trigger - Sprint
Right trigger - Shoot
Left bumper - Melee
Right bumper - Throw grenade, right thumbstick controls strength
A - Pick up or place a barricade/Purchase vending machine item/Start game at menu
X - Buy weapon at shop/build barricade at workbench/open vending machine view
B - Repair barricade/Add materials to workbench/Exit vending machine
Y - Switch between pistol and primary weapon/Switch control mode at menu
Dpad down - Throw a flare, right thumbstick controls strength
Dpad up- Change song (when playing custom music)
Start - Pause game/Skip intros/Exit vending machine
Back - Slow-mo (if unlocked)/Quit to title (while paused)

---------------------------------------------------------------------------------------------------------------------------------------
4.FAQ:
---------------------------------------------------------------------------------------------------------------------------------------
Q: What custom music file types can I use?
A: You can play mp3 (.mp3), wma (.wma), and MOD (.mod, .it, .s3m, and .xm) files from the game

Q: I set my title song to a MOD file but it won't play
A: The menu screen music may only be in mp3 and wma formats

Q: Why isn't my controller working?!!
A: Unfortunately this game only supports Microsoft Xbox 360 controllers, so you will need to find a way to 
emulate one. The Vibmod emulator at TocaEdit is good, and works with I Had Hope when the DLL is renamed xinput9_1_0.dll.

Q: I have the right input device, but I still can't move
A: You may have selected the opposite control method to the one you had wanted

Q: If I spend points, does this lower my highscore?
A: No, score and shop points are treated seperately in this game. Think of points as cash

Q: While I'm playing, if I try to switch windows the game stays in front of everything?!
A: The game must be paused before switching applications

Q: My game just closed while I had it paused in the background
A: The game can sometimes continue to recieve input event while other programs are in front of it. 
There is currently no solution to this bug. A workaround would be to avoid pressing Ctrl + Y, or use a controller to play

Q: I minimized the game and now it won't open again
A: This is a bug that doesn't seem to have any solution as of yet

Q: Why is the music volume so loud?
A: Sadly there is no way to change the volume MOD format music plays at. If this problem occurs while using MP3's however, 
then please try using negative volume levels (as low as -80). This due to the sound plugin behaving differently on certain computers

Q: How do I mute the music and sound?
A: Set your music and sound volume to 0

Q: Sound cuts out while I'm playing?
A: This can happen when too many sounds are playing at once, try increasing the maximum sound channels option higher. 
If this causes crashes then you are trying to play more sound channels than your computer supports

Q: The title screen shows, but when I start a level it crashes
A: This can happen when your graphics card does not support Pixel Shader 2.0

Q: I enabled outlines, but can't see them
A: The outlines only show when your graphics card supports Pixel Shader 2.0

Q: The title screen messes up in FullScreen mode/the game lags in FullScreen mode
A: This mode is prone to glitches, try playing in windowed mode and maximize the window instead

Q: My game just crashed!?
A: This could be due to playing in FullScreen mode, or a bug that has not been found yet

Q: The game is really laggy for me
A: Try turning off outlines, and lower the maximum number of zombies alive at once, or run the FPS test to configure your game automatically for you

Q: Why does FullScreen mode cause so many problems?
A: This is a bug in Construct Classic. Unfortunately, there doesn't seem to be a work-around or fix for it yet.

Q: I have a bug that isn't solved here
A: Sometimes there may some bugs that haven't been reported yet. Visit the game blog (www.ihadhope.blogspot.com) and comment with the details of what happens, or tweet it to JayHadHope

---------------------------------------------------------------------------------------------------------------------------------------
5.Known Bugs:
---------------------------------------------------------------------------------------------------------------------------------------
-FullScreen mode can cause glitches
-Sometimes stuck zombies will flail around inside walls
-Vista hates this game
-Occasional crashes yet to be ironed out
-After throwing lots of flares the player will only throw the same flare around
-Vista hates this game
-Starting a level again screws the camera at the start
-Sometimes the game crashes trying to restart a level too fast
-Vista hates this game

---------------------------------------------------------------------------------------------------------------------------------------
6.Changelog:
---------------------------------------------------------------------------------------------------------------------------------------
21/06/2012 - Alpha V0.6
----------------------------------
-Vending machines now pause the game when used

29/02/2012 - Alpha V0.5
----------------------------------
-Added new vending machine graphic
-Added new intro screen system, skip with buttons/keys/mouse
-Fixed bullet shells and shotgun shells
-Added loading screens, temporary graphics until Louis does something awesome

28/02/2012 - Alpha V0.4
----------------------------------
-Mod every (graphical) object in the game!
-Shop objects actually load from the map file
-Vending machines no longer work through walls
-Barricades no longer take damage all at once

17/02/2012 - Alpha V0.3
----------------------------------
-Included new characters
-Added right handed character settings, but need right handed characters for testing before it's ready for use
-Added vending machines, graphics will change later
-Added vending machine purchase menu


11/11/11 - Alpha V0.2
----------------------------------
-Fixed some explosives crashes
-Building materials no longer pushed by carried barricade
-Added Zombie Rush alarm sound
-Added an optional explosion camera shake
-Added setting to disable controller vibration
-Added melee attacks
-Made flares and grenades throwable
-Added kill combos
-Fixed sound engine some more, much less crashes
-Added bullet casings that fly out of certain guns
-Edited player graphics
-Added Biokeds awesome shop graphics
-Did more fixing on the sound engine for an equal decrease in crashes
-Made zombies spawn a bit more often
-Sound engine fixed more. Hopefully less crashes!

25/09/11 - Alpha V0.1
----------------------------------
-Added ability to set title screen mp3
-Maximum difficulty level set to 6
-Switched to grenade icons, limit set to 5
-Player now regains stamina even when grasped by zombies
-Decreased zombie slowdown effect on player
-Lives limit set to 5
-Fixed walking over movable barricades
-Fixed pause screen
-Fixed flame objects
-Non-Flamer flames kill zombies again
-Switched to delayed player damage from fire
-Fixed most sound related crashes
-Switched to toggled slow motion
-Added setting to set maximum zombies on screen at once
-Added setting to set maximum sounds played at once
-Zombie Rush survival earns bonus points and score
-Zombie Rush now never starts within the first 3 waves
-Zombie Rush now only lasts (at maximum) 2 minutes
-Zombie Rush will only activate a minimum of 1 minute after the last one ended
-Zombie revolver now only lasts 30 seconds
-Barricades no longer make noise when carried over fire
-Blood splats from bullets are now randomly spawned on hit

---------------------------------------------------------------------------------------------------------------------------------------
7.Credits:
---------------------------------------------------------------------------------------------------------------------------------------
Made using an awesome 2D game creator, Construct Classic. 
Go get it at www.scirra.com (free & open source!)

Game engine: 
--------------------------------------
Jayjay

Game design:
--------------------------------------
Jayjay, Bioked

Story writing:
--------------------------------------
Bioked

Graphics:
--------------------------------------
Bioked, Jayjay

Alpha testing: 
--------------------------------------
Bioked, Tailswind, Lou Lou, Toxiclum, Tom, Jonesy, WilliG, ImRatherStartled (aka Asian James), 
Armand, Yann, Soldjah Boy, Gunshy, Miki B, Jawdz, The Commy Kid, CRAIG, Moh,
THE LORD ALMIGHTY CHARLIE ROBBINS (Louis Judge Ellis is his bitch) HE GOT THE SWAG, 
B_Dawg

Music:
--------------------------------------
From SoundClick.com:
Joergen Theodorsen - Precipitation
Velocity Stace - Nothings Without
Raph Gaudette - Shopping Cart To Hell
Entities - Throne Of Amorphous
Organic Shadows - Federation Of Awesome
Aesthetic Miasma - Obscura Scene
7 USA - The Freak Likes It
7 USA - Polite Kill
7 USA - Sirens
7 USA - Death Flower
7 USA - Madness

Sound effects:
--------------------------------------
Most sound effects created by www.freesound.org members: 
cognito, Koops, Srehpog, kevinkace, miregrobar, CGEffex, themfish, qubodup, acclivity, NoiseCollector, Shades, 
steveygos93, nthompson, PhreaKsAccount, jeseid77, kjackson, Benboncan, corpsehere, vtownpunks, Rock_Savage, 
DJ Chronos, guitarguy1985, nextmaking

Our recorded sound effects:
SwitchWep - Jayjay
Hurt1 to Hurt8 - Jayjay
Die1 to Die3 - Jayjay

---------------------------------------------------------------------------------------------------------------------------------------
8.Licenses:
---------------------------------------------------------------------------------------------------------------------------------------
I Had Hope demo EXE - free to redistribute, do not modify (Attribution-NoDerivs)

I Had Hope engine source - free to redistribute and modify (NEW 2019: Unlicense) 

I Had Hope sound/music - free to redistribute and modify (Attribution, to original authors)

I Had Hope graphics - free to redistribute and modify non-commercially (Attribution-NonCommercial to Bioked)

Need more clarification? Ask us about them at www.ihadhope.blogspot.com