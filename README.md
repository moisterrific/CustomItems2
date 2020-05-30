# CustomItems2
Custom Items plugin originally by [Johuan/Interverse](https://github.com/Interverse/CustomItems), updated by me.

Allows you to spawn an item with custom attributes These items will reset when you drop it, store the item in a chest or other container, or leave the server, so you cannot transfer it to another person.

## Commands
- `/customitem <itemid|"item name"> [parameters] [amount]`  or `/citem` for short
- `/givecustomitem <itemid|"item name"> <"player name"> [parameters] [amount]` or `/gcitem` for short

## Parameters
- `hexcolor` or `hc` 
  - Gives a custom color to an item (client side) Example of hex: 0000FF is blue 
- `damage` or `d` 
  - Custom damage to an item 
- `knockback` or `kb` 
  - Custom knockback 
- `useanimation` or `ua` 
  - Amount of time an item will linger when a player uses it Use with usetime so when an item has finished firing, the animation will finish at the same time 
- `usetime` or `ut` 
  - Amount of time it takes to use 
- `shoot` or `s` 
  - The projectile shot by an item 
- `shootspeed` or `ss` 
  - The speed of the projectile shot by an item 
- `width` or `w` 
  - Width of an item (client side) 
- `height` or `h` 
  - Height of an item (client side) 
- `scale` or `sc` 
  - The multiplier of an item's size when it is used (client side) 
- `ammo` or `a` 
  - Gives an item the ammo attribute useammo Tells when ammo an item uses useammo 0 means the weapon will not use ammo 
- `notammo` `na` 
  - Tells whether an item is not an ammo Either true or false 

Order doesn't matter when inputting parameters. You can put any parameters you need, however you want them.

## Examples 
- Give yourself a Chlorophyte shotbow that shoots cannonballs really fast
  - `/customitem "chlorophyte shotbow" scale 2 damage 400 useammo 0 shoot 162 shootspeed 25 usetime 4`
- Give moisterrific an ultra annoying Meowmere that does big damage
  - `/gcitem moisterrific meowmere ut 1 d 5000`

## Permissions
- `customitem `
- `customitem.give`
