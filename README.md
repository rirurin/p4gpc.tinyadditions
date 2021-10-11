# p4gpc.twitchplays
### AKA Twitch Plays Persona 4 Golden

[Cool tweet demonstrating the program](https://twitter.com/rirurinuser/status/1443487438375034881)

A [Reloaded-II](https://github.com/Reloaded-Project/Reloaded-II) Mod for Persona 4 Golden on PC that allows you or anyone else to control the game by typing into a Twitch chat. As this control is built into the game through the power of *assembly hooks and stuff*, this mod will allow the possibility of having the controls change depending on the actions happening in the game, though at the moment this hasn't been added in.
The code is based on [AnimatedSwine37's](https://github.com/AnimatedSwine37/) [Persona 4 Golden Tiny Additions](https://github.com/AnimatedSwine37/p4gpc.tinyadditions).

## Current features

- Control the game by typing select, start, up, down, left, right, square, cross/X, circle/O and triangle (equivalent to playing with a keyboard or a controller) or by typing the name of the action you want to do in the battle menu (Analysis, Tactics, Guard etc.)
- Set the channel to act as a bot and the channel that the bot reads messages from in the Config panel

The link to generate an OAuth token connected to the Twitch account that will read the messages can be found [here](https://twitchapps.com/tmi/).

## Build Instructions

This project is built from Visual Studio 2019. Open the project in Visual Studio and change the output path to the location of your Reloaded-II mods folder before building the mod (the option for this is located in the program *p4gpc.tinyadditions*, which all the .cs files will be inside of). For more detailed information on installing the mod, refer to the [Reloaded-II Quick Start Guide](https://github.com/Reloaded-Project/Reloaded-II/blob/master/docs/QuickStart.md) and the [Guide to Modding Persona 4 Golden](https://gamebanana.com/tuts/13379).

## The plan

~~- Change the commands available to chat depending on the field (e.g In combat, chat can type in Attack, Skill etc. to control battles)~~ Implemented in some form through executing a set of inputs
- ~~Lock the stream from controlling parts of the game so that they don't delete your save files or something dumb like that~~ At least partially done, will need more testing to confirm
