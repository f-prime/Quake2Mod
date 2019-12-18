# Quake 2 Pet Mod

Gives player the ability to spawn one of 3 different pet types. Pets can be assigned 3 of 10 different abilities.
Pets show up with a green halo around them and attack nearby enemies with you. They need to be fed occasionally as well.

# Deliverables

- 3 customizable base pets

- Pets that fight with you + 10 abilities

- Pet controls and maintinance

- Limit player weapons

# How to use mod

### New Console Commands

- pet_cmds - Returns a list of commands that you give give your pet.

- stay - Pet does not move

- move - Pet follows you or moves to enemies near it

- attack - Attacks enemies

- passive - Does not attack

- givepet [ability] [slot_index] - Gives a pet an ability in a particular ability slot. `givepet` run without arguments 
lists all available abilities

- eat - Pet eats meat near by if it wants to.

- killpet - Kills the pet 

### Spawning Pets

Spawning pets has been bound to the `h` `j` and `k` keys.

`h` spawns a basic pet

`j` spawns a tank pet

`k` spawns a flying pet

### Help Computer

When a pet is active pulling up the Help Computer (F1) will show stats on the pet such as its health, type, hunger, and current abilities.


### Sources

- http://moddb.com/games/quake-2/tutorials/monsters-fighting-each-other

### License Stuff

This is the complete source code for Quake 2, version 3.19, buildable with
visual C++ 6.0.  The linux version should be buildable, but we haven't
tested it for the release.

The code is all licensed under the terms of the GPL (gnu public license).  
You should read the entire license, but the gist of it is that you can do 
anything you want with the code, including sell your new version.  The catch 
is that if you distribute new binary versions, you are required to make the 
entire source code available for free to everyone.

The primary intent of this release is for entertainment and educational 
purposes, but the GPL does allow commercial exploitation if you obey the 
full license.  If you want to do something commercial and you just can't bear 
to have your source changes released, we could still negotiate a separate 
license agreement (for $$$), but I would encourage you to just live with the 
GPL.

All of the Q2 data files remain copyrighted and licensed under the 
original terms, so you cannot redistribute data from the original game, but if 
you do a true total conversion, you can create a standalone game based on 
this code.

Thanks to Robert Duffy for doing the grunt work of building this release.

John Carmack
Id Software
