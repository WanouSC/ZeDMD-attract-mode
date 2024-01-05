# ZeDMD plugin for AttractMode front end

## DESCRIPTION:

ZeDMD plugin is for the [AttractMode](http://attractmode.org) front end (only support Windows version) that communicates with the hardware [ZeDMD](https://github.com/PPUC/ZeDMD). 
It will update the marquee whith a .jpg or .png file when transitioning to and from a game. It also update the marquee when screen saver start (file `$HOME/.attract/plugins/ZeDMD/Scripts/ScreenSaver.png`)


## Prerequisites
* Working ZeDMD hardware

## Port COM

You may need to update the port COM id in ligne 9 `$HOME/.attract/plugins/ZeDMD/plugin.nut` to communicate with ZeDMD.
This project was developed on a Windows platfrom and use a specific executable.

## Install Plugin

* Copy ZeDMD folder to `$HOME/.attract/plugins/`


## Usage

You can enable the ZeDMD plugin by running Attract Mode and pressing the tab key to enter the configure menu. Navigate to `Plug-ins -> ZeDMD -> Enabled`. 

## Notes

This plugin was developed for a personal need. You are free to improve it or make it compatible under Linux.
