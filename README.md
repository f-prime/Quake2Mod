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
