# Strange Objects v1.2.3
### Adds a new rarity tier of scrap items. These items are more valuable but also dangerous!

## Instructions
Place the ```StrangeObjects.dll``` file in your ```BepInEx/plugins``` folder.

Everyone in your multiplayer game needs a copy of the mod installed for it to work properly

A config has been added! Want strange objects to spawn more or less? Now you can change it!

See the Config section below for more information.

## Description
- Strange objects are worth over 30% more scrap than normal scrap items
- Strange objects can be identified by their red enemy-like color in scans
- There are 4 possible curses that could be in a strange object:
    - Curse of Pain: Damages the player
    - Curse of Sight: Makes the player a lil tipsy
    - Curse of Sloth: Reduces the player's movement speed
    - Curse of Midas: Lucky you! These objects change name and scrap value every time they're picked up
- Curses are removed when the strange object is dropped, at the end of a round, or death
- Curses can stack if you pick up more than one strange object so be careful!
- Multiple players can get the same curse from picking up the same item

## Config
When you launch the game with the mod installed a ```Bits.StrangeObjects.cfg``` file should generate in your ```BepInEx/config``` folder.

There are two general settings you can change in the config:
- SpawnRate - Controls how often strange objects spawn on average. Default: 20%
- ValueMultiplier - Controls how high the scrap values of strange objects are. Default: 0.3 or 30% higher scrap

You can also set curse specific settings such as the ones for Sloth:
- EnableCurseofSloth - Disables curse if false
- Level1MovementDebuff - Percentage of Movement Speed after Level 1 Debuff. Default is 0.75 or 75% less speed
- Level2MovementDebuff - Percentage of Movement Speed after Level 2 Debuff. Default is 0.5 or 50% less speed

## Known Issues
- Items revert back to regular scrap when a save file is loaded
- Strange objects sometimes don't trigger properly on pickup

## Special Thanks
- My boyfriend for helping me test the mod <3
- MrMiinxx for this [YouTube Tutorial](https://youtu.be/4Q7Zp5K2ywI?si=8dpUhJFCa6BvxkM5) that got me started
- [LC Modding Discord](https://discord.gg/ECvSzsPT7V)
