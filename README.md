# AMPTemplates

My AMP template for custom game servers

# Instructions

To add theses templates, follow the instruction on [AMP wiki](https://github.com/CubeCoders/AMP/wiki/Configuring-the-'Generic'-AMP-module#adding-custom-templates-to-amp)

Basically, it is under : `Configuration` -> `Instance Deployement` -> `Instance Management` And then on the "Configuration Repositories" you click plus icon and add `Falaxir/AMPTemplates:master`.

Now it should appear when your create a new instance (it will begin with `Falaxir - *GAMENAMEHERE*`, you might need to refresh the instances page and even clear your browser cache for it to be displayed)

# Games

List of supported games for this template

## Nanos world
- [x] Installation
- [x] Launch
- [x] Update
- [x] Console
- [x] Custom launch variables
- [ ] Read and Edit config file*

*TOML files are not supported to be modified by AMP parameters. To edit this file for your own config (packages, ...), open it in your "File Browser" in AMP
