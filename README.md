# hardware_arduboy

This is a boards.txt file necessary to make switching back and forth between a production and development Arduboy as easy as chosing an option from the Arduino IDE.

![What it looks like](https://raw.github.com/yyyc514/hardware_arduboy/master/example.png)


## How to use it

This repository goes in your `Arduino/hardware/` folder.

On Mac that folder should be at:

    (HOME)/Documents/Arduino

You'll likely need to create the hardware folder.  This reposity goes under that folder.  If you've done it right you should have:

	~/Documents/Arduino/hardware/hardware_arduboy/avr/...

Restart the Arduino IDE and you should see Arduboy in the board menu.  Select it and then choose the Tools menu again and now you will have a version menu that will allow you to pick the development kit or the release version of Arduboy.


## TODO

- Fuse settings
- USB name
- USB vendor id and product ID
