# ClawfootMod
A Stardew Valley mod in which you can change the farmers into lizardfolk, based off of RetroPixelLizard's Clawfoot character.

## Minimum mod requirements:
* [Stardew Valley 1.3](https://stardewvalley.net/)
* [SMAPI 2.6-beta13](https://smapi.io/)
* [Content Patcher 1.4-beta.3](https://www.nexusmods.com/stardewvalley/mods/1915)

As of _**13 November 2019**_ it has been concluded that this mod still works correctly.
Though the minimum mod requirements do not change, let it be known that it still worked on:
* Stardew Valley 1.3.36
* SMAPI 2.11.3
* Content Patcher 1.9.2

It is assumed that as long as Content Patcher stays up to date with both the game and SMAPI, this mod should continue to work just fine.

As of _**Stardew Valley 1.4**_ a bunch of the farmer sprites have been changed. For this reason, the mod will throw errors regarding the positions of some of the edited sprites. Mostly, the pants.

I will look into this in the nearby future, though the game does not crash from this. It should simply no longer replace the pants.

## What the mod changes:
The male farmers get horns and clawed feet, going barefoot.
The female farmers are simply barefoot at the time.

To become closest like Clawfoot, pick the following settings:

### Skin:
* 18 -> A more brighter, lizardy green.

### Hair:
* 6 -> To have a mohawk like Clawfoot.
* 7 -> A slightly more stylized mohawk.

### Shirt:
* 24 -> To effectively be shirtless.

### Accessory:
* 20 -> To have a lizardface, rather than a duckface.

**Note:**
If you use SMAPI's Console Commands to change these, you will have use -1.
This is because SMAPI's count starts at 0, whereas the game starts at 1.
So 17 would be the lizard skin color, 23 the shirtless shirt.. and so on.

## Optional settings:
In config.json, you can change a few options.

### Add Shirt
(_Default: true_)
Replaces a boring green shirt with the 'shirtless' shirt.

### Add Skincolor
(_Default: true_)
Replaces the green skincolor with the greener lizard skincolor.

### Add Facemask
(_Default: true_)
Replaces the duckmask with the lizardmask.

### Add Hairstyles
(_Default: true_)
Replaces two kinda meh hairstyles with the mohawks.

### Fundoshi for Men?
(_Default: false_)
Will replace the men's bath towel with a fundoshi.
This was a request by RPL, specifically.

## Credits:
* Retro Pixel Lizard, aka RPL or Gyro Gun. He requested this mod, as well as later modifications.. Considering the default is based off of his character Clawfoot, I can hardly not credit him.
* PathosChild for helping out and for releasing Content Patcher, could not have finished this without him.
