# metroidvania-observations
Observations of my favorite metroidvania games (in no particular order)

- Hollow Knight
- Ori and the Blind Forest
- Axiom Verge
- Guacamelee!
- Dust: An Elysian Tail
- Shovel Knight (not metroidvania but still inspirational)
- Hyper Light Drifter (not metroidvania but still inspirational)
- SteamWorld Dig

## Inventory/menus
### Hollow Knight
- SELECT: Inventory menu overlays the current scene (doesn't pause, sound effects continue to play). Tab for map, tab for inventory (i.e., abilities, key items), tab for charm system.
- START: Pause menu overlays the current scene. Freezes the background and sound effects.

### Axiom Verge
- SELECT: Same effects as start, just jumps into the map tab
- START: Pause menu overlays the current scene. The tiles and environment still animates in the background and sound effects/music continues to play. All objects are frozen.
- Inventory, Input Config, Map
- Inventory has a weapon/upgrades page, journal page for notes collected throughout the game, "hacking" page and map page.

## Character abilities
### Hollow Knight
- Dash, double jump, acid resistance, "shadow" dash, ground slam, wall jump, "extended" dash
- Weapon upgrades are available with hard to find pickups
- Charm system (i.e., talents) to modify player in smaller ways (e.g., larger melee hitbox)

### Axiom Verge
- Drill, grappling hook, drone launch/teleport, higher jump, pass through certain walls (i.e., lab coat), various other upgrades unique to this game (e.g., the "disruptor" to hack enemies)
- Health upgrades, bomb upgrades, ammo upgrades
- Ability to "hack" with certain passwords that can be found in the game to modify certain rooms

## Platforming
### Hollow Knight
- Variable jump height. Generous height
- Precise vertical and horizontal movement
- Friction along walls after unlocking wall jump
- Wall jumps happen at 45 degrees
- Ghost jumping? (~100ms)

### Axiom Verge
- Variable jump height, can be upgraded later to jump higher because there's no double jump
- No wall jump
- Platforming isn't the main focus of this game, it's just a utility to get around
- Definitely has ghost jumping, quite generous here

## Combat
### Hollow Knight
- Large part of the game. Precise hitbox, smooth attack animation
- Spells are in the game but not really necessary. 90% of combat is done with the melee weapon (nail)
- Satisfying hit/death
- Knockback when melee attack lands. This also enables bouncing vertically on top of enemies using the melee weapon (some platforming is solved this way too).
- Invincibility frames and knockback when hit
- Enemies leave corpses and drop currency. They also give you health when attacked
- Multi-phase boss fights are a highlight here. Each boss is unique and well scripted. All of them challenging and requires a few attempts to defeat. Save points are always a few rooms away.

### Axiom Verge
- Ranged weapons, large variety of weapons as they are found throughout the map
- Short invincibility frames for the player
- Hit animation for the enemy
- No knockback
- Enemies are quite strong late game, they take a lot of effort to kill
- Boss fights play a big role here. Not as well scripted as Hollow Knight but some of them are multi-phased and most are challenging too. Save points are always nearby.

## General design observations
### Hollow Knight
- Rooms are large but not continous. Enemy death is remembered temporarily
- Fast travel possible from certain points
- Charms only changeable from save locations
- If you die you restart at a save location
- Spikes restart you to the nearest platform (i.e., they aren't insta-death)
- Parallax background
- Insects, carapace, decay
- Character has an aura of light around him, scenes are dark
- Dust follows the character when walking and also when jumping. Dynamic direction (i.e., it briefly curves mid-air)
- Slower movement speed in town
- Lots of environment to interact with (i.e., breakables, detritus). Impressive amount of objects that can be cut with the weapon
- Press up to interact with environment (e.g., talk with NPC, enter a building)

### Axiom Verge
- Player is "rebuilt" (part of the story) at checkpoints. Always at these points, no matter how you died.
- Metro vibe is perfect. The graphics, controls, music. Plays like an old SNES game
- Level design here seems more attainable. Areas are segmented into variable sized rooms. Each room is made up of a certain number of same-size squares. e.g., most rooms are 1x1 but can also be 1x2, 2x3, etc. Then the map overay just renders the various squares rather than show specific details about each room. Also makes the camera logic easier because you are usually only going in one direction and the camera doesn't have to pan as much. For the most part it stays fixed on the player (unlike in Hollow Knight where it moves as soon as the player starts moving).
- Backgrounds are parallaxed lightly. Usually there's just a tiled background that moves very slowly when falling as opposed to the foreground which moves much faster.
- Many tiles and pieces of the environment are animated but not interactable

## Engine
### Hollow Knight
Unity

### Ori and the Blind Forest
Unity

### Axiom Verge
MonoGame

### Guacamelee!
Custom

### Dust: An Elysian Tail
XNA

### Shovel Knight
Custom

### Hyper Light Drifter
GameMaker Studio

### SteamWorld Dig
Custom
