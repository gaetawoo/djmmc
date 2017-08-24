---
title: "Infinite Items"
date: 2017-08-22T12:40:40-05:00
tags: ["commands","easy"]
slug:
share: true
draft: false
---
You will need a repeat command block to do this. Type in the following command: `/replaceitem entity @p slot.hotbar.0 cookie 30`. Then put a lever near the command block and turn it on. No matter how many times you try to get the cookies out of your inventory, you will always get more without your inventory completely filling up.

<!--more-->

#### Commands:

Syntax: `/replaceitem entity <selector> <slot> <item> [amount] [data] [dataTag]` OR `/replaceitem block <x> <y> <z> <slot> <item> [amount] [data] [dataTag]`.

1. `/replaceitem block ~ ~ ~-1 slot.container.13 diamond_sword 1 0 {ench:[{id:16,lvl:1000}],display:{Name:"Super Sword"}}`

2. `/replaceitem entity @a slot.inventory.8 arrow 12`

3. `/replaceitem entity @e[type=skeleton] slot.armor.chest iron_chestplate`

4. `/replaceitem entity @p slot.hotbar.0 stone 64 0 {display:{Name:"Rock"}}`

5. `/replaceitem block ~ ~ ~1 slot.container.0 book 1 0 {ench:[{id:19,lvl:2}],display:{Name:"Spellbook of Wind"}}`

6. `/replaceitem entity @a slot.hotbar.6 planks 64 3`

7. `/replaceitem entity @a slot.armor.head leather_helmet 1 0 {display:{Name:"Rainhat"}}`

***WARNING!*** The `/replaceitem` command will *replace* any items in your inventory, depending on the slot number you type. Be careful!
