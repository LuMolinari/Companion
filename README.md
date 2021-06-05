
# Summoner Support

### Introduction

Summoner Support is a an [Overwolf](https://www.overwolf.com/pages/homepage/) application designed to be used for League of Legends.
The application will provide amateur and ranked players with features that allow them to get an edge
over their competition by giving them meaningful statistics and champion guides.

Summoner Support was developed as a a senior design project at California State University, Northridge.
It is no longer under development. 

### Features

Desktop
* The app will launch automatically when League of Legends starts and Overwolf is running.
* The statistics tab provides in depth info about your most recent game, as well as general stats for last 15 games.
* The highlights tab provides video highlights captured from your latest 5 games. 

In-Game Overlay
* Item build order for your current champion.
* Recommended skill order for current champion.
* See runes all players have equipped(hover for rune description)
* See previous game stats for all players

### Project Setup
The project is set up using Vue.js. Each window is a Vue project that builds into the native folder.
[Yarn](https://yarnpkg.com/) is required to run this project.

Use `install.sh` to install install dependencies.

Use `build-all.sh` to build the Vue projects into the native folder. 

  To install the application through Overwolf a development account is required. You may find instructions on loading this app [here](https://overwolf.github.io/docs/start/sample-app-overview#5-install-the-app-as-unpacked-extension).

### Screenshots
_Home Tab_
![](misc\img\home.png)
_Statistics Tab_
![](misc\img\stats.png)
_Highlights Tab_
![](misc\img\highlights.png)
_In-Game Window_
![](misc\img\in-game.png)
