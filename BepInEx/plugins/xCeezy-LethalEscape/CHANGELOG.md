
# Lethal Escape 0.5

Mod released! Yippe :D

# Lethal Escape 0.7
Coil head can go outside
Enemies now shouldnt go through ship door
All AIs of the same type escape when 1 escapes
AIs now teleport to door that is closest to a player outside rather than only the main door
If an AI outside gets stuck they now teleport to the closest node
If the exit door is not next to a ainode it now teleports to the closest node
Added fail safes just incase the AI state of being outside desyncs
cleared all the annoying debug logs

# Lethal Escape 0.7.1
Added changed logs

# Lethal Escape 0.7.2
Because coil head lacks a Start event for now I will just make them spawn outside
Fixed certain AIs fail safe not working due to it being on the wrong event

# Lethal Escape 0.7.3
Fixed hoarding bug AI (whoops)

# Lethal Escape 0.7.4
Added Basic Configs
Hopefully fixed bracken causing lag when it escapes then switches targets
Coil head no longer auto escapes after escaping on one moon
Monsters now correctly escape through door the person escaped out of

Hopefully next update I can add proper networking so the configs sync and so theres less lag when the AI switches targets outside to a target that has not been targeted before

# Lethal Escape 0.7.5
Monsters now escape independently instead of all at once because the game creator changed how inside/outside AIs are handeled
Monsters can now attack/target the player again when outside (This bug was related to the change the game creator did)
Fixed Jester (jester is still somewhat broken when outside)

# Lethal Escape 0.7.6
Possible position de-sync fix?


# Lethal Escape 0.8

AI ownership/who calculates AI is forced to always be the host when AI escapes outside
Because of this
MOD NOW ONLY REQUIRES HOST TO HAVE THE MOD!!!!!
MOD NOW ONLY REQUIRES HOST TO HAVE THE MOD!!!!!
    Mod no longer works if your not the host/Host does not have mod
    Config is now solely based on the host
Added support for Puffer/Spore Lizard
Added support for Nut Cracker
Added support for Slime/Hygrodere (disabled by default in config because its not much of a threat I feel)
Added support for Spider
Added Lots of extra Config options
Mostly fixed jester
Puffer/Spore Lizard has chance to escape every minute (configureable)
Bracken/Flowerman has chance to escape every minute (configureable)
Hoarding Bug has chance to escape every minute (configureable)
Hoarding Bug has chance to nest next to ship
Escape Delay for Bracken and thumper are now adjustable
Jester Max outside speed and aceleration is now adjustable
Max/Min Spiderwebs outside per spider is adjustable
Made some monsters not spawn directly on the door (Mainly the ones with no escape delay such as jester , slime, and puffer)
Should run smoother now the weird failsafe debug thing is gone

known issues
Kill animations might not look correct when monsters escape outside

# Lethal Escape 0.8.1

Some major FPS improvements with Bracken, Hoarding bug, Puffer/Spore lizard (5 of these ais would cause a 40% fps drop for host but this is fixed now)

# Lethal Escape 0.8.2

Added options for all monsters (except coil head because he has not start function to patch onto) to have a chance to spawn outside which can be adjusted in the config
fixed error with jester
Made ownership override on bracken happen post and pre update tick instead of just pre (In theory it should reduce any mico stutters from gaining ownership with brackens if anyone had any)
very minor preformance buff if you set a monsters chance per minute to escape to 0

# Lethal Escape 0.8.3

Fixed Spider not spawning outside correctly
Fixed lag issues and weird interferance when multiple people had the mod
Fixed mod not having correct host check

# Lethal Escape 0.8.4

Fixed AIs that werent the bracken being unable to kill non host players

# Lethal Escape 0.8.5

Fixed fear level being set on host rather than person being attacked with thumper or coil head
Also fixed there being no dll in mod file (whoops)