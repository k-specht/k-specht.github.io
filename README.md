# What I can do!
I'm an Indie Game Developer, which means I do a little bit of everything.
Everything shown here is material from my work-in-progress game, Mutate (inspired by [Amorphous+](<https://www.kongregate.com/games/innocuousgames/amorphous>)).
It's made in the [Bevy Game Engine](<https://bevyengine.org/>), which means all of it is coded in Rust as a plugin (Bevy has no editor!).

## Effect Programming
![A slime trail that disappears naturally](https://raw.githubusercontent.com/k-specht/k-specht.github.io/main/assets/vid/Effects_compressed.gif)
Some effects are very specific or resource-heavy, and need a well-optimized implementation.
I made this [Marching Squares](<https://en.wikipedia.org/wiki/Marching_squares>) implementation for my mobile game for this reason!
With the right shaders, these can look even better on other platforms.

## Game Logic
Game Logic                 | Game Physics
:-------------------------:|:-------------------------:
![Character Eliminating Enemies](https://raw.githubusercontent.com/k-specht/k-specht.github.io/main/assets/img/Logic_compressed.gif)  |  ![Character Bumping Enemies](https://raw.githubusercontent.com/k-specht/k-specht.github.io/main/assets/img/Game_AI.gif)

Some game engines will have built-in logic for characters, physics, and even effects.
If yours doesn't, or more complex logic is needed, this is my forte!
![Simple game logs stating that an enemy was attacked, stunned, and defeated](https://raw.githubusercontent.com/k-specht/k-specht.github.io/main/assets/img/Game_Logs.png)

## Physics Baking
![A slime jiggle physics simulation](https://raw.githubusercontent.com/k-specht/k-specht.github.io/main/assets/img/Physics_Baking.gif){: style="float: left"}
Sometimes a game needs a "real-looking" animation that just can't be made with armature deforms, like a death animation or a dripping pipe.

## 3D Modeling
3D Modeling                | 3D Animation
:-------------------------:|:-------------------------:
![A simple humanoid armature pose](https://raw.githubusercontent.com/k-specht/k-specht.github.io/main/assets/img/3D_Modeling_and_Posing.png) | ![A slime ball rolling](https://raw.githubusercontent.com/k-specht/k-specht.github.io/main/assets/img/Rigging_Animation.gif)

My specialty isn't 3D-modeling, but sometimes a game needs a small animated object *fast*.
All the assets for the game I showcase here are ***100% made by me*** in Blender!

## Mod Support
![An asset editor with a lot of buttons](https://raw.githubusercontent.com/k-specht/k-specht.github.io/main/assets/img/Mod_Support.png)
Modding communities can be a huge boon of popularity for a game.
Making mod-friendly code isn't easy, but it can also make later updates to the game much faster.

## Level Design
![A tilemap editor that transforms into a 3D dungeon room](https://raw.githubusercontent.com/k-specht/k-specht.github.io/main/assets/img/Level_Editing.gif)
Open-source tools can make 3D dungeons easy!
This is a tilemap to 3D converting tool I made that makes use of a [Bevy tilemap editor](<https://github.com/StarArawn/bevy_ecs_tilemap>).
