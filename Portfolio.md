# Game Development Portfolio

Below is a list of games I have developed or contributed to.

## Multiplayer FPS (Unreal Engine 5, 2023)

- C++
- Plugin
- Synchronization
- Anti-Cheat

<img />

## Hack and Slash (Unreal Engine 4, 2023)

- Vertex School
- Blueprint
- Paragon Assets

<img />

## OpenDuelyst (Cocos2D Engine, 2022)

I'm a maintainer for [_OpenDuelyst_](https://github.com/open-duelyst/duelyst), a game developed by Counterplay Games in 2016 and later open-sourced. The game uses the Cocos2d-HTML5 engine, and is written in CoffeeScript and JavaScript.

What have I done?

<img />

## Minecraft RCON Clients (Game Tools, 2021)

I developed and published open-source RCON (remote server console) libraries written in [Go](https://github.com/willroberts/minecraft-client), [C#](https://github.com/willroberts/minecraft-client-csharp), [Rust](https://github.com/willroberts/minecraft-client-rs), [TypeScript](https://github.com/willroberts/minecraft-client-ts), [Kotlin](https://github.com/willroberts/minecraft-client-kotlin), and [Scala](https://github.com/willroberts/minecraft-client-scala) for Minecraft, which uses Valve's `srcds` RCON protocol. These libraries enable players who are hosting Minecraft servers to control them remotely, for administration or moderation purposes.

Each library is designed to follow the best practices for its language, particularly around unit testing, linting, documentation, and packaging.

## OpenRVS (Unreal Engine 2, 2020)

OpenRVS is a mod for Tom Clancy's Rainbow Six 3: Raven Shield, which was developed by Red Storm Entertainment and published by Ubisoft in 2003. It was developed by [Twi](https://github.com/rvstwi) in 2016, after Ubisoft closed the multiplayer servers for the original game.

I joined the project in 2020, implementing classes for automated server registration (simply starting an OpenRVS server will make it appear for other players), asynchronous HTTP requests, version checking, performance timing, logging, and common string operations.

OpenRVS is implemented in UnrealScript, by overriding classes from the UnrealScript for the base game.

<img src="images/RavenShield.jpg" alt="OpenRVS" />

## Building Escape Game (Unreal Engine 4, 2017)

This is a simple first-person game where the player is tasked with finding the way out of a single room. The level makes use of starter content, light sources, and a trigger volume which powers a hidden pressure plate in the room.

All game logic is implemented in C++.

<img src="images/BuildingEscape.png" alt="Building Escape Game" />

## Pong Clone (Custom SDL2 Engine, 2017)

This game uses a custom game engine written in Go which makes use of the SDL2 library for graphics, input handling, and fonts.

<img alt="Photo currently unavailable." />

## Untitled RPG (Engo Engine, 2016)

This is a tile-based roguelike game inspired by [_Castle of the Winds_](https://en.wikipedia.org/wiki/Castle_of_the_Winds). The game is written in Go, using the [Engo](https://engoengine.github.io/) game engine.

The character can move around the map one step at a time, using a turn-based system which advances after the player's action. Moving into an enemy starts combat, and defeating enemies grants experience and levels.

Art assets are from Jesse Freeman's [Tile Crusader](https://web.archive.org/web/20161122175612/http://jessefreeman.com/articles/free-game-art-tile-crusader), released under a public license.

<img src="images/UntitledRPG.png" width="480" alt="Untitled RPG" />
