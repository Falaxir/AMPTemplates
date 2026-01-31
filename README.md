# AMPTemplates

https://cubecoders.com/AMP

My custom templates for AMP game control panel by cubecoders

# Instructions

To add theses templates, follow the instruction on [AMP wiki](https://github.com/CubeCoders/AMP/wiki/Configuring-the-'Generic'-AMP-module#adding-custom-templates-to-amp)

Basically, it is under : `Configuration` -> `Instance Deployement` -> `Instance Management` And then on the "Configuration Repositories" you click plus icon and add `Falaxir/AMPTemplates:master`.

Now it should appear when your create a new instance (it will begin with `Falaxir - *GAMENAMEHERE*`, you might need to refresh the instances page and even clear your browser cache for it to be displayed)

# Games

List of supported games for this template

## Nanos world
![nanosworldbanner](https://shared.fastly.steamstatic.com/store_item_assets/steam/apps/1841660/acf79715867799df9b550eaceea6816f75309d3e/header.jpg)

https://nanos-world.com/

Play in unique, community-made game modes, create custom addons with Lua, and import assets from Unreal Engine 5. Host your own server and enjoy endless gaming possibilities with friends! 

### features
- [x] Installation
- [x] Launch
- [x] Update
- [x] Console
- [x] Custom launch variables
- [ ] Read and Edit config file*

## Team fortress 2 Classified
![tf2classifiedbanner](https://shared.fastly.steamstatic.com/store_item_assets/steam/apps/3545060/cede55b7156e2fc893d6eef6ecbe9c6cdfe52e9b/header.jpg)

Team Fortress 2 Classified is a new Team Fortress 2 experience built on its original inspirations and tone. Updated with refreshed visuals, new gamemodes and maps, new weapons, new teams, and a portly oil baron. 

### Important

For some reason, the first update when creating the instance (by clicking update button or start) may fail (always in my case for some reason), click on it again and it will work...

### Features
Same as tf2 officially supported as amp for my tests, even sourcemod works!

# Notes
*TOML files are not supported to be modified by AMP parameters. To edit this file for your own config (packages, ...), open it in your "File Browser" in AMP

