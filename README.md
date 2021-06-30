# vrc-game-inputs
Game input prefabs for VRChat

# About
A collection of simple UdonSharp scripts to lock the player in place so they can play games.

A problem with playing games inside VRChat is that your character movement keys might use the same inputs as the game you're playing. The input mapping collision makes it hard to play the virutal game, as your avatar might walk and jump around as you play. This repo attempts to solve this problem in different ways. These two prefabs are used in my current worlds. I'm still brainstorming more solutions! :)

# Prefabs list

### ExtraStickySeat
The infamous chair. Respawn to stand back up. Sitting on this chair will eat all your inputs so you can play the game!

### StickyRug
A slight improvement over ExtraStickySeat. With a larger surface area and no dependency on stations, the StickyRug allows full body users to play the game in whatever pose they like. Click the rug to lock yourself in place. Click again to free yourself.

# Usage
1. Install the [dependencies](#dependencies).
2. Add the vrc-game-inputs directory of this repo to Assets/ in your Unity project.
3. Drop the prefab of your choice into the scene to get a feel for how it will work.
4. Customize it to look and behave how you like!

# Dependencies
### Required
- VRCSDK3 for Worlds: Log into your VRChat account and download the official SDK off the website.
- UdonSharp by Merlin: https://github.com/MerlinVR/UdonSharp

### Suggested
- CyanEmu by CyanLaser: https://github.com/CyanLaser/CyanEmu
