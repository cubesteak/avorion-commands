# Avorion Commands Package
## Contribution
### Cubesteak's Update
Forked the fork so the command won't be forked in game. :)

A few simple updates to account for changes to the game since Deadonstick's great work.

Updates: Added Raw turrets, removed comments.

### Deadonstick's Prelude
Original version can be found here: https://github.com/nthirtyone/avorion-commands

This version was forked by Deadonstick to add features to the existing code. In all likelihood the author will have forgotten about this repo by the time you're reading this and will have added many more features by that time that he hasn't committed. As such feel free to contact the author for requests because he just might already have them.
## Commands
### /crew
Adds or removes crew to currently boarded ship. Usage:
`/crew help` or `/crew` for help
`/crew add <profession> [rank] [level] [amount]`
`/crew fill`
`/crew clear`
ADDED BY DEADONSTICK: `/crew epicfill` (gives maxed out crew to the ship along with a captain)
### /inventory
Alias: `/inv`
Modifies inventory of a player. Usage:
`/inventory turret <type> [rarity] [material] [tech] [amount]`
`/inventory upgrade <script> [rarity] [amount]`
### /price
Prints price of currently boarded ship. Usage: `/price`
### /sethome
Allows player to change home sector to current if friendly or own station is present. Usage: `/sethome`
### /whereis
Gets the position of a player. Usage: `/whereis <name>`
### /list
Lists possible variables for `/inventory`, `/crew` or `/fighter`. Usage: `/list [type]`. Use `/list` to print types.
`/list <type>`
`/list help` or `/list` for help.
### /disttocore
Display the distance in sectors between the player and the center of the galaxy. Usage `/disttocore`
### /agoods

Adds goods to currently boarded ship. Usage:

`/agoods <good name> <quantity>`

Must capitalize all names
Must replace spaces with _(underscore)
Can not add more then your hold can handle

#### Examples:

`/agood Steel 100`
`/agood Steel_Tube 10`

### /fighter
Adds a fighter to the payers hanger. Usage:
`/fighter add <weapons> [rarity] [material] [tech]`
