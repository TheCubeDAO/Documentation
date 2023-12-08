---
title: Gameplay Features
description: 
published: true
date: 2023-03-23T19:53:03.913Z
tags: 
editor: markdown
dateCreated: 2022-10-08T17:24:48.878Z
---




>This page is outdated. Information may be missing or incorrect.

# 🏝️ LAND CLAIMING

A land claim is a piece of in-game land which belongs to you. No one else can interfere with your claimed land unless you grant them /trust access.

- Players receive **75** additional land claim blocks per hour.
- Player with the **VIP** rank will receive an additional **150** claim blocks per hour
- Players have a maximum of 300,000 accrued claim blocks.
- Players with the default rank will have **500 Claim Blocks** by default.
- Players with the **VIP** rank will have **1000 Claim Blocks** by default.
<br>
 
<font size="6">**How to claim land**</font>

To begin claiming land, you will need a Land Claiming Shovel (golden shovel) you should have received one when you first joined the Survival server. 

as of 29/01/23 you can now use /claim to toggle the claim mode.

1. Right-click on a block to choose the corner of your claim.
1. Right-click the opposite corner diagonally to claim within that area.
1. Your claim should now be complete!
<br>

<font size="6">**Commands**</font> 


### Claims

* [/gd abandon claim [identifier]](#gd-abandon-claim)
* [/gd abandon all](#gd-abandon-all)
* [/gd abandon top [identifier]](#gd-abandon-top)
* [/gd buy blocks [numberOfBlocks]](#gd-buy-blocks)
* [/gd buy claim](#gd-buy-claim)
* [/gd claim contract \<amount\> [direction] [identifier]](#gd-claim-contract)
* [/gd claim create \<radius\>|\<chunk\> [type]](#gd-claim-create)
* [/gd claim expand \<amount\> [direction] [identifier]](#gd-claim-expand)
* [/gd claim farewell \<message\> [identifer]](#gd-claim-farewell)
* [/gd claim greeting \<message\> [identifer]](#gd-claim-greeting)
* [/gd claim id \<identifier\>](#gd-claim-id)
* [/gd claim info [identifier]](#gd-claim-info)
* [/gd claim inherit](#gd-claim-inherit)
* [/gd claim inspect [\<area\>|\<hide\>|\<hideall\>]](#gd-claim-inspect)
* [/gd claim list [\<player\> [world]]](#gd-claim-list)
* [/gd claim displayname [name]](#gd-claim-displayname)
* [/gd claim rent create [\<rate\> [max_days]]|info|list|cancel](#gd-claim-rent)
* [/gd claim setspawn](#gd-claim-setspawn)
* [/gd claim spawn](#gd-claim-spawn)
* [/gd claim tax [balance|force|pay \<amount>]](#gd-claim-tax)
* [/gd claim transfer [player]](#gd-claim-transfer)
* [/gd claim we](#gd-claim-we)
* [/gd claimgroup admin [\<join\>|\<unjoin\>|\<create\>|\<delete\>]](#gd-claimgroup-admin)
* [/gd claimgroup player [\<join\>|\<unjoin\>|\<create\>|\<delete\>]](#gd-claimgroup-player)
* [/gd cuboid](#gd-cuboid)
* [/gd mode basic](#gd-mode-basic)
* [/gd mode subdivide](#gd-mode-subdivide)
* [/gd mode town](#gd-mode-town)
* [/gd player info \<player\> \<world\>|\<player\>|[world]](#gd-player-info)
* [/gd player transferblocks](#gd-player-transferblocks)
* [/gd player trapped](#gd-player-trapped)
* [/gd player unlockdrops](#gd-player-unlockdrops)
* [/gd sell blocks [numberOfBlocks]](#gd-sell-blocks)
* [/gd sell claim \<price\>](#gd-sell-claim-price)

### Flags

* [/gd flag debug](#gd-flag-debug)
* [/gd flag claim [\<flag\> \<target\> \<value\> [contexts]]](#gd-flag-claim)
* [/gd flag definition \<preset:group\> \<definition\> \<value\> [identifier]](#gd-flag-definition)
* [/gd flag group \<group\> [\<flag\> \<target\> \<value\> [contexts]]](#gd-flag-group)
* [/gd flag player \<player\> [\<flag\> \<target\> \<value\> [contexts]]](#gd-flag-player)
* [/gd flag reset](#gd-flag-reset)

### Options
* [/gd option claim [\<option\> \<value\> [contexts]]](#gd-option-claim)
* [/gd option group \<group\> [\<option\> \<value\> [contexts]]](#gd-option-group)
* [/gd option player \<player\> [\<option\> \<value\> [contexts]]](#gd-option-player)

### Trust  

Note: Use `public` if you want to trust all users.

* [/gd trust player \<player\>|public <accessor|container|builder|manager> ](#gd-trust-player)
* [/gd trust group \<group\>|public <accessor|container|builder|manager> ](#gd-trust-group)
* [/gd trustall player \<player\>|public](#gd-trustall-player)
* [/gd trustall group \<group\>|public](#gd-trustall-group)
* [/gd untrust player \<player\>|public ](#gd-untrust-player)
* [/gd untrust group \<group\>|public ](#gd-untrust-group)
* [/gd untrustall player \<player\>|public](#gd-untrustall-player)
* [/gd untrustall group \<group\>|public](#gd-untrustall-group)
* [/gd trust list](#gd-trust-list)

### Admin

* [/gd abandon world [world]](#gd-abandon-world)
* [/gd ban [hand | \<type\> \<target\> [message]]](#gd-ban)
* [/gd claim clear \<target\> [identifier]](#gd-claim-clear)
* [/gd toggle ignore](#gd-toggle-ignore)
* [/gd claim restore](#gd-claim-restore)
* [/gd claim schematic \<create|delete\> \<name\>](#gd-claim-schematic)
* [/gd delete claim [identifier]](#gd-delete-claim)
* [/gd delete all \<player\> [world]](#gd-delete-all)
* [/gd delete alladmin [world]](#gd-delete-alladmin)
* [/gd mode admin](#gd-mode-admin)
* [/gd mode nature](#gd-mode-nature)
* [/gd permission group \<group\> [\<permission\> \<value\>]](#gd-permission-group)
* [/gd permission player \<player\> [\<permission\> \<value\>]](#gd-permission-player)
* [/gd player adjustbonusblocks \<player\> \<amount\> [world]](#gd-player-adjustbonusblocks)
* [/gd player adjustbonusblocksall \<amount\>](#gd-player-adjustbonusblocksall)
* [/gd player setaccruedblocks \<player\> \<amount\> [world]](#gd-player-setaccruedblocks)
* [/gd debug \<on\>\<off\>\<record\>\<paste\> [player]](#gd-debug)
* [/gd reload](#gd-reload)
* [/gd unban [hand | \<type\> \<target\>]](#gd-unban)

### Main Command

* [/gd](#gd)

### Misc

* [/gd version](#gd-version)


<font size=6> Command Details</font>


### Claims
___
#### `/gd abandon claim`
**Arguments**: `[identifier]` 
Abandons a claim

___
#### `/gd abandon all`
Abandons ALL your claims

___
#### `/gd abandon top`
Abandons a claim and all its subdivisions

___
#### `/gd buy blocks`
**Aliases**: `buyblocks`  
**Arguments**: `<numberOfBlocks>`  

Purchases additional claim blocks with server money. Doesn't work on servers without any economy plugin.

___
#### `/gd buy claim`

View a list of claims for sale. Click [Buy] to purchase.

___
#### `/gd claim contract`
**Aliases**: `claimcontract`, `contractclaim`  
**Arguments**: `<amount> [direction] [identifier]`  
Contracts/Shrinks the claim from the direction you are facing.   

___
#### `/gd claim create`
**Aliases**: `claimcreate`  
**Arguments**: `<radius> [type]`  
Creates a claim around the player of the given type. If no claimtype (or an incorrect one) is specified, a basic claim will be created.   

___
#### `/gd claim expand`
**Aliases**: `claimexpand`, `expandclaim`  
**Arguments**: `<amount> [direction] [identifier]`  
Expands the claim in the direction you are facing.   

___
#### `/gd claim farewell`
**Arguments**: `<message> [identifier]`  
Sets the farewell message of your claim

To unset, `/gd claim farewell clear`

___
#### `/gd claim greeting`
**Arguments**: `<message> [identifier]`  
Sets the greeting message of your claim

To unset, `/gd claim greeting clear`


___
#### `/gd claim id`
**Arguments**: `<identifier>`  
Sets the friendly identifier of your claim.  


___
#### `/gd claim info`
**Aliases**: `claiminfo`  
**Arguments**: `[identifier]`  

Gets information about a claim you are standing in or by claim id.

___
#### `/gd claim inherit`
**Aliases**: `inherit`  

Toggles parent claim inherit mode

___
#### `/gd claim inspect`
**Aliases**: `claiminspect`  
**Arguments**: `[area|hide|hideall]`  

Inspects the target block player is looking at or nearby claims.

___
#### `/gd claim list`
**Aliases**: `claimlist`  
**Arguments**: `[<player> [world]]`  

List information about a player's claims.

___
#### `/gd claim displayname`
**Arguments**: `<name>`  
Sets the display name of your claim

___
#### `/gd claim rent`
**Arguments**: `create [<rate> [<max_days>]]|info|list|cancel]`  
Used to rent/list claims.  
Note: Requires economy plugin.

___
#### `/gd claim setspawn`
**Aliases**: `claimsetspawn`  

Sets the spawn of your claim to the location you are standing in.

___
#### `/gd claim spawn`
**Aliases**: `claimspawn`  

Teleports you to claim spawn, if available.

___
#### `/gd claim tax`
**Arguments**: `balance|force|pay <amount>]`  
Used to manage taxes of a claim.  
Note: The argument `force` allows an admin to pay a claim's tax balance for another player.  
Note: Requires economy plugin.


___
#### `/gd claim transfer`
**Aliases**: `transferclaim`  
**Arguments**: `<player> [identifier]`  

Transfer the claim you're standing in to a player.

___
#### `/gd claim we`
**Arguments**: `claim|clear|select [identifier]`  
`claim` - creates GD claim from WE selection.  
`clear` - clears worldedit selection.  
`select` - creates new WE selection from GD claim.

Used to manage GD claims with worldedit.  
Note: This command will not work unless the server has WorldEdit.

___
#### `/gd claimgroup admin`
**Arguments**: `join <group> [<identifier>]|unjoin [<identifier>]|create <group>|delete <group>`  
Used to manage admin claim groups. 


___
#### `/gd claimgroup player`
**Arguments**: `join <group> [<identifier>]|unjoin [<identifier>]|create <group>|delete <group>`  
Used to manage player claim groups. 


___
#### `/gd cuboid`
**Aliases**: `cuboid`  

Toggles 3D cuboid claims mode.

___
#### `/gd mode basic`
**Aliases**: `modebasic`

Switches the shovel tool back to basic claims mode.

___
#### `/gd mode subdivide`
**Aliases**: `modesubdivide`  

Switches the shovel tool to subdivision mode, used to subdivide your claims

___
#### `/gd mode town`
**Aliases**: `modetown`

Switches the shovel tool back to town claims mode.
___
#### `/gd player info`
**Arguments**: `<player> <world>|<player>|[<world>]`  

Gets information about a player and their claimblocks

___
#### `/gd player transferblocks`
**Aliases**: `transferblocks`  
**Arguments**: `<player> <amount>`

Gives claim blocks to another player

___
#### `/gd player trapped`  
**Aliases**: `trapped`  

Teleports the player to a safe location if stuck and unable to build.

___
#### `/gd player unlockdrops`  
**Aliases**: `unlockdrops`  

Allows other players to pickup any items dropped from death.  

___
#### `/gd sell blocks`
**Aliases**: `sellblocks`  
**Arguments**: `<numberOfBlocks>`  

Sell your claim blocks for server money. Doesn't work on servers without any economy plugin.

___
#### `/gd sell claim`
**Arguments**: `<price>`  

Puts your claim up for sale at the set price. To disable sale, set the price to -1 or set ForSale setting in /claiminfo to false.


### Flags

___
#### `/gd flag debug`
**Aliases**: `cfd`

Toggles claim flag debug mode

___
#### `/gd flag claim`
**Aliases**: `cf`  
**Arguments**: `[<flag> <target> <value> [<\contexts>]]`  

Gets/Sets claim flags in the claim you are standing in.


___
#### `/gd flag definition`
**Aliases**: `cf`  
**Arguments**: `<preset:group> <definition> <value> [identifier]`  

Sets claim flag definitions in the claim you are standing in or claim identifier.

___
#### `/gd flag group`
**Aliases**: `cfg`  
**Arguments**: `<group> <flag> <target> <value> [<\contexts>]]`  

Gets/Sets flag permission for a group in claim you are standing in.

___
#### `/gd flag player`
**Aliases**: `cfp`  
**Arguments**: `<player> <flag> <target> <value> [<\contexts>]]`  

Adds flag permission to player.

___
#### `/gd flag reset`
**Aliases**: `cfr`

Resets a claim to flag defaults.


### Options
___
#### `/gd option claim `
**Aliases**: `co`  
**Arguments**: `[<option> <value> [<contexts>]]`  

Gets/Sets options in the claim you are standing in.

___
#### `/gd option group`
**Aliases**: `cog`  
**Arguments**: `<group> [<option> <value> [<contexts>]]`  

Gets/Sets options for a group in claim you are standing in.

___
#### `/gd option player`
**Aliases**: `cop`  
**Arguments**: `<player> [<option> <value> [<contexts>]]`  

Gets/Sets options for a player in claim you are standing in.


### Trust
Note: `public` is for all users.
___
#### `/gd trust player`
*Accessor*: `Grants a player entry to your claim(s) and use of your bed`  
*Container*: `Grants a player access to your claim's containers, crops, animals, bed, buttons, and levers`  
*Builder*: `Grants a player edit access to your claim(s)`  
*Manager*: `Grants a player access to all of the above including claim settings`  
**Aliases**: `trust`  
**Arguments**: `<player>|public <trusttype>`  

Grants a player access to your claim(s).

___
#### `/gd trust group`
*Accessor*: `Grants a group entry to your claim(s) and use of your bed`  
*Container*: `Grants a group access to your claim's containers, crops, animals, bed, buttons, and levers`  
*Builder*: `Grants a group edit access to your claim(s)`  
*Manager*: `Grants a group access to all of the above including claim settings`  
**Aliases**: `trustgroup`  
**Arguments**: `<group>|public <trusttype>`  

Grants a group access to your claim(s)

___
#### `/gd trustall player`
*Accessor*: `Grants a player entry to ALL your claim(s) and use of your bed`  
*Container*: `Grants a player access to ALL your claim's containers, crops, animals, bed, buttons, and levers`  
*Builder*: `Grants a player edit access to ALL your claim(s)`  
*Manager*: `Grants a player access to all of the above including claim settings`
**Aliases**: `trust`  
**Arguments**: `<player>|public <trusttype>`  

Grants a player access to ***ALL*** your claim(s).

___
#### `/gd trustall group`
*Accessor*: `Grants a group entry to ALL your claim(s) and use of your bed`  
*Container*: `Grants a group access to ALL your claim's containers, crops, animals, bed, buttons, and levers`  
*Builder*: `Grants a group edit access to ALL your claim(s)`  
*Manager*: `Grants a group access to all of the above including claim settings`
**Aliases**: `trustallgroup`  
**Arguments**: `<group>|public <trusttype>`  

Grants a group access to ***ALL*** your claim(s).

___
#### `/gd untrust player`
**Aliases**: `untrust`  
**Arguments**: `<player>|public`  

Revokes a player's access to your claim.

___
#### `/gd untrust group`
**Aliases**: `untrustgroup`  
**Arguments**: `<group>|public`  

Revokes a group's access to your claim.

___
#### `/gd untrustall player`
**Aliases**: `untrustall`  
**Arguments**: `<player>|public`  

Revokes a player's access to ***ALL*** your claim(s).

___
#### `/untrustall group`
**Aliases**: `untrustallgroup`  
**Arguments**: `<group>|public`  

Revokes a group's access to ***ALL*** your claim(s).
___
#### `/gd trust list`
Lists permissions for the claim you're standing in


### Admin

___
#### `/gd abandon world`  
**Aliases**: `abandonworld`  
**Arguments**: `[world]`  

Special admin command used to abandon ALL user claims in world.  
___
#### `/gd ban`  
**Aliases**: `claimban`  
**Arguments**: `hand | <type> <target> [<message>]`  
Note: Valid types are `entity`, `item`, `block`  
Bans target or item in hand from all usage.  

___
#### `/gd player adjustbonusblocks`
**Aliases**: `adjustbonusblocks`  
**Arguments**: `<player> <amount> [world]`  

Adds or subtracts bonus claim blocks for a player

___
#### `/gd player adjustbonusblocksall`
**Aliases**: `adjustbonusblocksall`  
**Arguments**: `<amount>`  

Adjusts bonus claim block total for all online players by amount specified.

___
#### `/gd player setaccruedblocks`
**Aliases**: `setaccruedblocks`  
**Arguments**: `<player> <amount> [<world>]`  

Updates a player's accrued claim block total.

___
#### `/gd mode admin`
**Aliases**: `modeadmin`  

Switches the shovel tool to administrative claims mode

___
#### `/gd delete claim`
**Aliases**: `deleteclaim`  

Deletes the claim you're standing in, even if it's not your claim

___
#### `/gd delete all`
**Aliases**: `deleteall`  
**Arguments**: `<player> [world]`  

Delete all of another player's claims

___
#### `/gd delete alladmin`
**Aliases**: `deletealladmin`  
**Arguments**: `[world]`  

Deletes all administrative claims

___
#### `/gd claim ignore`
**Aliases**: `ignoreclaims`  

Toggles ignore claims mode

___
#### `/gd claim clear`
**Aliases**: `claimclear`  
**Arguments**: `<target> [<claim> [<world>]]`  
Allows clearing of entities within one or more claims.

___
#### `/gd permission group`
**Aliases**: `cpg`  
**Arguments**: `<group> [<permission> <value>]`  

Sets a permission on a group with a claim context

___
#### `/gd permission player`
**Aliases**: `cpp`  
**Arguments**: `<player> [<permission> <value>]`  

Sets a permission on a player with a claim context

___
#### `/gd mode nature`
**Aliases**: `rn`  

Switches the shovel tool to restoration mode

___
#### `/gd debug`
**Aliases**: `gddebug`  
**Arguments**: `<on>|<off>|<record>|<paste> [<player>]`  

Toggles debug

___
#### `/gd reload`

Reloads Grief Prevention's configuration settings

___
#### `/gd schematic`  
**Aliases**: `claimschematic`  
**Arguments**: `<create|delete> <name>`  

Manages claim schematics. Use '/claimschematic create \<name\>' to create a live backup of claim. 

___
#### `/gd unban`  
**Aliases**: `claimunban`  
**Arguments**: `hand | <type> <target> [<message>]`  
Note: Valid types are `entity`, `item`, `block`  

Unbans target id allowing it to be used again. 


### Misc

___
#### `/gd`

Lists detailed information on each command.

___
#### `/gd version`

Lists version information.

# ⚔️ SKILLS (Adapt)

Get started with the Adapt Skills system by right-clicking a bookshelf.

Adapt has a number of skills, all belonging to a type (category)
This list of skills is not static and may or may not update with varied frequency.


**Agility**
https://www.youtube.com/watch?v=30IhIoCqbDI
- Armor Up
- Super Jump
- Wall Jump
- Wind Up


**Architect**
https://www.youtube.com/watch?v=dFitlDhSYEg

- Foundation
- Glass
- Placement

**Axe**
- Chop
- Drop to Inventory
- Ground Smash
- Leaf Miner

**Brewing**
- Lingering
- Super Heated

**Crafting**
- Deconstruction
- XP

**Discovery**
https://www.youtube.com/watch?v=WeeaYdFANo8
- Unity
- World Armor
- Xp Resist

**Enchanting**
- Lapis Return
- Quick Enchant
- Xp Return

**Excavation**
https://www.youtube.com/watch?v=Hm93ya-QDjU
- Drop to Inventory
- Haste
- Omnitool

**Herbalism**
https://www.youtube.com/watch?v=-6sniin-rFg
- Drop to Inventory
- Growth Aura
- Hippo
- Hungry Shield
- Myconid
- Replant

**Hunter**
https://www.youtube.com/watch?v=-ttYCQA2bRw
- Adrenaline
- Drop to Inventory
- Invis
- Jump Boost
- Luck
- Regen
- Resistance
- Speed
- Strength

**Nether**
- Skull Toss
- Wither Resist

**Pickaxe**
https://www.youtube.com/watch?v=Ydw_473whrE
- Autosmelt
- Drop to Inventory
- Chisel
- Veinminer

**Ranged**
- Arrow Recovery
- Force
- Lunge Shot
- Piercing

**Rift**
https://www.youtube.com/watch?v=jI9LrIm8tAc
- Access
- Blink
- Enderchest
- Gate
- Resist

**Seaborn**
- Fishers Fantasy
- Oxygen
- Speed
- Turtles Mining Speed
- Turtles Vision

**Stealth**
- Ghost Armor
- Snatch
- Speed
- Vision

**Swords**
- Machete

**Taming**
- Damage
- Health
- Health Regeneration

**Unarmed**
- Glass Cannon
- Power
- Sucker Punch
- And more...

# ✨ PLAYER WARPS

Access player warps menu with /pw.
View help about player warps with /pw help.


# 🧙 ENCHANTMENTS
Custom enchantments can be found while enchanting normally through an Enchantment Table, trading with a villager, or by killing mobs.

Use the command **/customenchants** to view all available enchantments.

<font size="6">Slot Increaser</font>
Applying this item will increase the number of slots available on the item. Boundaries can be set to limit the total number of slots or how many increasers can be applied.

<font size="6">Enchantment Orbs</font>
Enchantment orbs can be applied to armor/weapons and will increase the amount of enchants you can apply on that item by the number specified in the orb command.

<font size="6">White Scroll</font>
Applying one of these to your item will protect it from being destroyed from a failed enchantment.

<font size="6">Secret, Mystery, and Magic Dust</font>
Increase book(s) success rate, while decreasing failure. The higher the success rate, the higher chance of the enchantment applying to the item.

<font size="6">Black Scroll</font>
Applying this item will take away one random custom enchantment from the item, and give a book of it with certain success & destroy rates.

<font size="6">Randomization Scrolls</font>
Applying one of these to the given custom enchant book will randomize the success and destroy rates.

<font size="6">Item Nametags</font>
Using one will let you rename items.

<font size="6">BlockTrak</font>
Apply a tracker on tools to track the number of blocks mined using the item.

<font size="6">StatTrak</font>
Applicable to weapons, to track player kills done with the item.

<font size="6">Soul Tracker</font>
"Stack" souls on items as fuel, then use for enchantments.

<font size="6">Transmog Scroll</font>
Organize enchantments on the item.

<font size="6">Holy White Scroll</font>
Save items after death.

<font size="6">Mob Trak</font>
Track how many mobs have been killed with an item.

<font size="6">Enchantment Slots</font>
Limit enchantment count per-item.

<font size="6">Enchanter</font>
Buy enchantment books, which when right-clicked will reveal the true enchantment.

<font size="6">Tinkerer</font>
Exchange your enchanted armor for experience, or exchange your custom enchant book for a fireball. A fireball has a chance of getting magic dust, which improves the success rate on a given rarity enchant book.

<font size="6">Alchemist</font>
Combine two dusts to receive a better rate. Combine two enchantment books for increased enchantment level (i.e. two Speed I books for Speed II)

<font size="6">How to obtain souls?</font>
Souls can be gathered by killing players using weapons with Soul Trackers applied on them. For every player kill with an item that has a soul tracker, they will gain 1 soul on the item. There is also a small possibility of receiving souls while mining.
<br>

# 🐟 FISHING

<font size="6">**Commands**</font>

Use these commands to help navigate the fishing features within the Survival server. Happy fishing!

- **/fish:** Brings up the basic help menu
- **/fish menu:** Brings up the main Fishing menu
- **/fish codex:** Brings up the codex
- **/fish shop:** Opens up the shop
- **/fish scales:** Opens the Scales GUI
- **/fish bag:** Opens the Fish Bag GUI
- **/fish gut:** Opens the Gutting GUI
- **/fish deliveries:** Opens the Deliveries GUI
- **/fish augment:** Opens the Augment GUI
- **/fish augments:** View all Blessing Augments in-game
- **/fish entropy:** View your entropy balance
- **/fish boosters:** View your active fishing boosters
- **/fish bait:** Opens the bait shop
- **/ft:** Fishing Tournaments
- **/ft info:** Shows information on the current tournament
- **/ft time:** Shows time until next tournament


<font size="6">Fish Merchant</font>
You can sell fish to the /fish shop for set prices, you can view the prices in that menu by hovering over the Map item.

<font size="6">Special Fish</font>
The special fish will reward a bonus multiplier for catching and selling that specific fish.
Every 240 minutes the special fish will reset and randomly choose another fish and multiplier combination.

<font size="6">Deliveries</font>
You can participate in Deliveries for every **180** fish that you catch. Deliveries have various rewards such as crypo tokens, to fishing rod upgrades!

Deliveries require varieties of fish so be sure to trade & sell to other players!

Upgrades can also be purchased for deliveries to allow them to be completed faster.

<font size="6">Skills</font>
You can earn Blessing Skill Points by passively fishing to purchase Upgradable Skills or One Time Purchase skills.

<font size="6">Upgradable Skills</font>
Cost Skill Points to upgrade and they gain diminishing returns with the more points you put into them.
Skill Points can also be returned at a cost of 50,000 Entropy to re-arrange.

<font size="6">One Time Purchase Skills</font>
Cost a set amount of Skill Points but are unlocked forever. These skills level up based on your overall Blessing Level.

<font size="6">Scaling</font>
You can weigh your fish in the scales to determine the exact weight of your fish. (/fish scales)
Knowing the exact weight of the fish will either increase its value or lower it depending on the weight.

**You have 4 options to determine the exact weight.**

- Low - 70% Success Rates / Potentially + or - 20% Value
- 
- Medium - 60% Success Rate / Potentially + or - 40% Value
- 
- High - 50% Success Rate / Potentially + or - 60% Value
- 
- Extreme - 40% Success Rate / Potentially + or - 80%


<font size="6">Augments</font>
Augments are "enchantments" for your fishing rod which will help you progress faster and earn more rewards from fishing. (/fish augments)


<font size="6">Crafting</font>
Augments can be crafted using specific recipes, you can view the augment crafting recipes using the /fish augments command.
Depending on the augment, it can require a specific Fishing Level and Entropy Cost before allowing you to craft it.

Once you are sure you have the correct resources, Fishing Level & Entropy required to craft the Augment, you will need to throw all of the ingredients (exactly) into a Cauldron filled with water and then right-click the cauldron with your Fishing Rod.
Assuming everything was done correctly, you should now have the augment you wanted.


<font size="6">Applying</font>
To apply your augment, type /fish augment and follow the steps to apply it to your Fishing Rod. You can also remove enchantments from your Fishing Rod from this menu for a cost of 25,000 Entropy
 


<font size="6">Fishing Parties</font>
Standing with other players & fishing will reward a party buff, this is capped at 5 players for the maximum buff. 
Players must be within 30 Blocks of each other to become a party.


<font size="6">Totems</font>
For the experienced fishers, you can build Totems which will reward a special power like effects & passive bonuses (/fish totem)
Building a totem can be expensive so this is recommended for the experienced fishers.



# 🏪 PLAYER SHOPS

This is not related to the servers market (/shop) this purely covers player based shops.
 
There are two types of shop systems a player can create in the game: a basic buy/sell sign shop and an advanced physical player shop.

The physical shop system is more complex and includes advanced economic market features such as buy limiting, sell limiting, dynamic pricing, and more.

<font size="6">Basic Sign Shop</font>
To create a basic sign shop, place any type of sign on the chest you wish to turn into a shop and follow the format below:

- **[Shop]**: This has to be the first line on the sign to indicate you are creating a shop.
- **64**: Set the amount of items you want the shop to buy or sell.
- **1000**: Set your desired price for the items you want to buy or sell.
- **Sell** or **Buy**: Set your shop type to either buy items from other players or sell your own items to other players.
- Then, punch the sign while holding whatever item you wish to buy or sell, and you will now have a sign shop.

<font size="6">Advanced Player Shop</font>
To create a physical player shop, hold the shop creation item and place it on the ground exactly where you want your shop to be. You will then receive a message in the chat box with the next steps.

To select the item you wish to sell or buy, hold shift and right-click the base of the player shop. To select your buy or sell price and other options, right-click the base of the player shop.


<font size="6">**Commands**</font>
- **/ShopList**: View all shops on the server.
- 
- **/ShopNotifications**: Toggle buy/sell shop notifications on/off.

# 🏘️ GANGS
Gangs are essential for teams who want to work together within the Sewer Side Survival server. 

There are many useful features the gangs system includes which will help your team progress, such as;  creating a gang bank account where your gang can deposit & withdraw funds to friendly fire so you don't accidently hit your teammates in a battle!

<font size="6">Information</font>
Creating a gang will cost $100,000 in-game cash (non refundable) 

You can create a gang with the /gang create (name) command 
Max Gang Name Length 24 Characters

By default a gang can hold up to 3 members

- **Level 2**: 5 Members / Cost $1,000,000 | +Level Up Reward
- 
- **Level 3**: 7 Members / Cost $4,500,000  | +Level Up Reward
- 
- **Level 4**: 10 Members / Cost $8,000,000 | +Level Up Reward
- 
- **Level 5**: 15 Members / Cost $25,000,000 | +Level Up Reward
  
<font size="6">Gang Home</font>
When you create a gang you gain access to set another “home” which can be considered your gangs base of operations.

By default a gang has 1 home, every level your gang gains will increase your gangs possible homes by 1 up to a maximum of 3 homes
  
<font size="6">Commands</font>
- **/gang list** - List all gangs on the server
- **/gang top** - List the top gangs on the server
- **/gang info (name)** - Show information about a specific gang
- **/gang create (name)** - Create a gang for $500,000
- **/gang disband** - Disband your current gang
- **/gang join (gang)** - Join a gang
- **/gang invite (name)** - Invite a player to your gang
- **/gang uninvite (name)** - Revoke a players invite to your gang
- **/gang kick (name)** - Kick a player from your gang
- **/gang leave** - Leave your current gang
- **/gang player (name)** - View a players gang information
- **/gang regroup (home name)** - Regroup with the gang at a specific home
- **/gang friendlyfire** - Toggle friendlyfire between gang members
- **/gang levelup** - Level up your gang
- **/gang promote (name)** - Promote a member of your gang
- **/gang demote (name)** - Demote a member of your gang
- **/gang withdraw (amount)** - Withdraw funds from the gang bank account
- **/gang listhome** - List your gangs homes
- **/gang home (home)** - Teleport to a gang home
- **/gang sethome (home)** - Set a gang home
- **/gang delhome (home)** - Delete a gang home
- **/gang ally (gang)** - Ally with another gang
- **/gang neutral (gang)** - Become neutral with another gang
- **/gc on/off** - Toggle Gang Chat
- **/gc (message)** - Send a message to the gang chat
- **/ac on/off**- Toggle Ally Chat
- **/ac (message)** - Send a message into the ally chat
- **/fight challenge (player amount) (money) (gang)** - Fight with another gang (not yet available)

# 🧑‍💼 JOBS
Jobs are a great way to start earning in-game money and exp.
 
You can have up to 5 Active Jobs at one time. By default you will be given the Woodcutter job.
 

<font size="6">Commands</font>
- **/jobs**: View a list of the server jobs you can choose from
- 
- **/jobs top (name)**:  List the top players by job name
- 
- **/jobs explored**: Check if the chunk you are standing in has been fully explored
- 
- **/jobs gtop**: List the top contributing players to all jbos
- 
- **/jobs leave (jobname)**: Leave a specific job
- 
- **/jobs join (name)**: Join a specific job
- 
- **/jobs quests**: Show your currently active job missions
- 
- **/jobs stats**: Show your job stats

# 📖 QUESTS
  

Players can initiate in-game quests to receive many epic rewards. There are 17 unique categories to choose from including the following;
VIP Exclusive, Farming, Mining, Collecting, Hunter, Enchanting, Brewing, Woodcutting, Building, Crafting, Digging, Activities, Miscellaneous, Fishing, Impossible, Weaponsmith & EXP.

There are over ~1300 total quests you can complete. Completing each quest will give a different reward depending on the difficulty of the quest, the category of the quest & which level of the quest you are on. 

Quests can be accessed using the **/quests** command in-game.
  
# 💳 WALLET

Crypto can be earned by doing most activites on our servers, they will be rewarded as physical tokens and can then be sold to other players using /ah, /trade or physically trading it. 

Right-Click an in-game Crypto token voucher and it will be claimed to your /wallet address on the Polygon Network

Payouts can be pending for an indefinite amount of time however they will always be processed.

<font size="6">Commands</font>
  
- **/wallet**: *View your wallet balance.*
- 
- **/wallet player (username)**: *View another players wallet info**
- 
- **/wallet gas**: *View current gas fee costs on the Polygon Network**
- 
- **/wallet blockchain**: *View current blockchain information**
- 
- **/wallet keys**: *View your private keys. This info is sensitive and should not be shared with anyone, not even staff.**
- 
- **/wallet transfer (TOKEN) (address) (amount)**: *Pay another player Crypto tokens.*
- 
- **/blackmarket**: *View the in-game crypto black market.*
  

# 🏁  BIOMES


The Overworld dimension has over 90+ biomes, there are currently randomly spawning structures containing loot such as Mineshafts underground to Pyramids in the desert throughout every biome!

Most biomes you encounter will be a custom generated biome unique to our server! Each of these biomes will include Sub-Biomes which include our custom smaller biomes and the regular vanilla biomes, you can locate vanilla biomes by matching it with a similar custom biome below. However you might have to look through a few locations before finding what you need since there are a lot of combinations of biomes!

<br>

## Frozen

**Frozen Peak**
Category: Icy

 

**Frozen Mountains**
Category: Extreme Hills
Sub-Biomes:
Frozen Peak
Mountain Cliffs
Frozen Mountain Middle

 

**Frozen Mountain Cliffs**
Category: Extreme Hills
Sub-Biome:
Mountain Cliffs Extended

 

**Frozen Mountain Middle**
Category: Icy

 

**Frozen Hills**
Category: Icy
Sub-Biome:
Hills Extended
Vander

 

**Frozen Pine Hills**
Category: icy

 

**Frozen Pine Plains**
Category: icy
Sub-Biomes:
Pine Hills 

 

**Frozen Pines**
Category: icy
Sub-Biomes:
Frozen Pine 
Plains Extended

 

**Frozen Plains**
Category: icy
Sub-Biome:
Frozen Hills

 

**Frozen Redwood Forest**
Category: icy
Sub-Biomes:
Frozen Redwood
Forest Extended

 

**Frozen Spruce Hills**
Category: icy
Sub-Biomes:
Frozen Spruce Hills Extended
Frozen Spruce Hills

 

**Frozen River**
Category: icy
Sub-Biome:
Frozen River


**Frozen Beach**
Category: icy

**Frozen Vander**
Category: icy

<br>

## Hot

**Hot Desert Dunes Red**
Category: unknown


**Hot Desert Dunes**
Category: unknown

**Hot Mountain Cliffs**
Category: unknown


**Hot Mountain Middle**
Category: unknown

**Hot Mountain Plains**
Category: unknown


**Hot Mountains**
Category: unknown


**Hot Oasis**
Category: unknown


**Hot Beach**
Category: beach


**Hot Beach Grass**
Category: unknown

**Hot Ocean Cliffs**
Category: unknown


**Hot Ocean**
Category: unknown
Sub-Biomes: 
Hot Ocean Cliffs
Hot river

<br>


##  Mesa

**Mesa Blue**
Name: Mesa Blue
Vanilla Derivative: badlands
ID: null
Category: unknown

**Mesa Cliffs**
Name: Mesa Cliffs
Vanilla Derivative: eroded_badlands
ID: null
Category: unknown

**Mesa Dark**
Name: Mesa Dark
Vanilla Derivative: eroded_badlands
ID: null
Category: unknown

**Mesa Green**
Name: Mesa Green
Vanilla Derivative: badlands
ID: null
Category: unknown

**Mesa**
Name: Mesa
Vanilla Derivative: badlands
ID: null
Category: unknown

**Mesa Plateau Dirt high**
Name: Mesa Plateau Dirt high
Vanilla Derivative: badlands
ID: null
Category: unknown

**Mesa Plateau Dirt**
Name: Mesa Plateau Dirt
Vanilla Derivative: badlands
ID: null
Category: unknown
Child: Mesa Plateau Dirt high

**Mesa Plateau**
Name: Mesa Plateau
Vanilla Derivative: badlands
ID: null
Category: unknown
Child: Mesa Plateau Dirt

**Mesa Red**
Name: Mesa Red
Vanilla Derivative: badlands
ID: null
Category: unknown

**Mesa Valley**
Name: Mesa Valley
Vanilla Derivative: badlands
ID: null
Category: unknown

**Mesa Yellow**
Name: Mesa Plateau
Vanilla Derivative: badlands
ID: null
Category: unknown
Child: Mesa Dark

**Mesa beach**
Name: Mesa beach
Vanilla Derivative: besert
ID: null
Category: unknown

**Mesa River**
Name: Mesa beach
Vanilla Derivative: besert
ID: null
Category: unknown
雅丹地貌

<br>

## Mountain

**Mountain Cliffs**
Name: Mountain Cliffs
Vanilla Derivative: old_growth_spruce_taiga
ID: null
Category: unknown
Child: Mountain Cliffs Extended
Vanilla Derivative: old_growth_spruce_taiga
ID: null

**Mountain Forest**
Name: Mountain Forest
Vanilla Derivative: old_growth_spruce_taiga
ID: null
Category: unknown

**Mountain Forest Hills**
Name: Mountain Forest Hills
Vanilla Derivative: old_growth_spruce_taiga
ID: null
Child: Mountain Forest

**Hills**
Name: Mountain Hills
Vanilla Derivative: old_growth_spruce_taiga
ID: null
Child: Mountain Forest

**Mountain Middle**
Name: Mountain Hills
Vanilla Derivative: old_growth_spruce_taiga
ID: null
Child: Mountain Cliffs

**Mountain**
Name: Mountain
Vanilla Derivative: windswept_hills
ID: null
Child: Mountain Cliffs

**Mountain Plains Hills**
Name: Mountain Plains Hills
Vanilla Derivative: plains
ID: null

**Mountain Plains**
Name: Mountain Plains
Vanilla Derivative: old_growth_spruce_taiga
ID: null

**Mountain River Soft**
Name: Mountain River Soft
Vanilla Derivative: river
ID: null

**Mountain River**
Name: Mountain River
Vanilla Derivative: river
ID: null

**Mountain Beach**
Name: Mountain River
Vanilla Derivative: old_growth_spruce_taiga
ID: null

<br>

## Mushroom

**Crimson Mushroom Swamp**
Name: Mountain Cliffs
ID: mushroom_crimson_forest
Category: mushroom
Child: Crimson Forest Extended

**Mushroom Forest**
Name: Mushroom Forest
ID: mushroom_forest
Category: mushroom
Child: Mushroom Forest Hills

**Mushroom Forest Hills**
Name: Mushroom Forest Hills
ID: mushroom_hills
Category: mushroom

**Mushroom Plains**
Name: Mushroom Plains
ID: mushroom_plains
Category: mushroom

**Mushroom Warped Forest**
Name: Mushroom Warped Forest
ID: mushroom_warped_forest
Category: mushroom
Child: Warped Forest Extended

**Mushroom Beach**
Name: Mushroom Beach
ID: mushroom_beach
Category: Unknown
Some of the biomes listed here don't have an ID, they use the vanillaDerivative instead
witch means minecraft:<vanillaDerivavtive>
  
**Mushroom Lake**
Name: Mushroom Lake
Vanilla Derivative: mushroom_fields
  
**Mushroom Ocean**
Name: Mushroom Ocean
Vanilla Derivative: ocean
  
  <br>

## Ocean
  
**Ocean Beach**
Name: Ocean Beach
Vanilla Derivative: plains
  
**Ocean Deep**
Name: Ocean Beach
Vanilla Derivative: deep_ocean
  
**Ocean**
Name: Ocean
Vanilla Derivative: ocean
  
**Ocean Warm Bottom**
Name: Ocean
Vanilla Derivative: warm_ocean
  
**Ocean Warm**
Name: Ocean
Vanilla Derivative: warm_ocean
Child: Ocean Warm Bottom
  
<br>
  
## Savanna
  
**Savanna Acacia Denmyre**
Name: Savanna Acacia Denmyre
ID: savanna_acacia_denmyre
Category: savanna
  
**Savanna Cliffs Extended**
Name: Savanna Cliffs
ID: savanna_cliffs
Category: savanna
Child: Acacia Denmyre
  
**Savanna Cliffs**
Name: Savanna Cliffs
ID: savanna_cliffs
Category: savanna
Child: |Acacia Denmyre Savanna Cliffs Extended
  
**Savanna Forest**
Name: Savanna Forest
ID: savanna_forest
Category: savanna
  
**Savanna Plateau**
Name: Savanna Plateau
ID: savanna_plateau
Category: savanna
  
**Savanna**
Name: Savanna
ID: savanna
Category: savanna
Some of the biomes listed here don't have an ID, they use the vanillaDerivative instead
witch means minecraft:<vanillaDerivavtive>
  
**Savanna Beach**
Name: Savanna Beach
Vanilla Derivative: savanna
  
  <br>
  
## Swamp
  
**Swamp Cambian Drift Exsended**
Name: Swamp Cambian Drift
ID: swamp_cambian_drift
Category: forest
  
**Swamp Cambian Drift**
Name: Swamp Cambian Drift
ID: swamp_cambian_drift
Category: forest
Child: Swamp Cambian Drift Exsended
Some of the biomes listed here don't have an ID, they use the vanillaDerivative instead
witch means minecraft:<vanillaDerivavtive>
  
**Swamp Denmyre**
Name: Swamp Denmyre
Vanilla Derivative: dark_forest
  
**Swamp Haunted Hands Forest**
Name: Swamp Haunted Hands Forest
Vanilla Derivative: dark_forest
  
**Swamp Marsh Rotten**
Name: Swamp Marsh Rotten
ID: swamp_marsh_rotten
  
**Swamp Marsh**
Name: Swamp Marsh
ID: swamp_marsh_rotten
Child: Swamp Marsh Rotten
  
**Swamp Roofed Forest Extended**
Name: Swamp Roofed Forest
Vanilla Derivative: dark_forest
Child: Swampy Marsh
  
**Swamp Roofed Forest**
Name: Swamp Roofed Forest
Vanilla Derivative: dark_forest
Child: |Swampy Marsh Swamp Roofed Forest Extended
  
**Swamp Roofed Wayward Extended**
Name: Swamp Roofed Wayward
Vanilla Derivative: dark_forest
Child: Swampy Marsh
  
**Swamp Roofed Wayward**
Name: Swamp Roofed Wayward
Vanilla Derivative: dark_forest
Child: |Swampy Marsh Swamp Roofed Wayward Extended
  
**Swamp Forest**
Name: Swamp Forest
ID: k530forestswamp
Child: Swamp Puddle
  
**Swamp Mangrove Forest**
Name: Swamp Mangrove Forest
ID: k530mangroveswamp
Category: forest
  
**Swamp Puddle**
Name: Swamp Puddle
ID: k530puddle
Category: forest
  
**Swamp Willow Forest Extended**
Name: Swamp Willow Forest
Vanilla Derivative: dark_forest
  
**Swamp Willow Forest**
Name: Swamp Willow Forest
Vanilla Derivative: dark_forest
Child: | |Swamp Willow Forest Extended Swamp Denmyre Swamp Marsh
  
**Swamp Beach**
Name: Swamp Beach
Vanilla Derivative: beach
  
**Swampy Marsh**
Name: Swampy Marsh
Vanilla Derivative: swamp
Child: Swamp Marsh
  
**Swamp Ocean tree**
Name: Swamp Ocean tree
Vanilla Derivative: ocean
  
**Swamp Ocean**
Name: Swamp Ocean tree
Vanilla Derivative: ocean
  
  <br>

## Temperate
  
**Temperate Birch Denmyre**
Name: Swamp Denmyre
Vanilla Derivative: birch_forest
  
**Birch Forest Extended**
Name: Birch Forest
Vanilla Derivative: birch_forest
Child: Birch Thin Forest
  
**Birch Forest**
Name: Birch Forest
Vanilla Derivative: birch_forest
Child: |Birch Thin Forest Birch Forest Extended
  
**Birch Thin Forest**
Name: Birch Thin Forest
Vanilla Derivative: birch_forest
  
**Combo Forest**
Name: Birch Forest
Vanilla Derivative: forest
  
**Temperate Flower Forest Extended**
Name: Temperate Flower Forest
ID: flower_forest
  
**Temperate Flower Forest**
Name: Temperate Flower Forest
ID: flower_forest
Child: Temperate Flower Forest Extended
  
**Temperate Highlands**
Name: Temperate Highlands
Vanilla Derivative: plains
  
**Temperate Island**
Name: Temperate Island
ID: island
Child: Wilds
  
**Long Tree Forest Extended**
Name: Long Tree Forest Extended
ID: longtree_forest
  
**Long Tree Forest**
Name: Long Tree Forest
ID: longtree_forest
Child: Long Tree Forest Extended
温带
  
  
## Tropical
  Not yet implemented
  
  
## Tundra
  Not yet implemented


  
