# Meisteradapter
Tiny multi purpose adapter running GP2040-CE or HID Remapper

## What is this?
This is the smallest and most affordable adapter / HID converter you can get, that has 3 USB-A "input" and 1 USB-A "output" ports. It is using a RP2040 microcontroller to run either [GP2040-CE](https://gp2040-ce.info/) or [HID Remapper](https://www.remapper.org/) firmware.

## But what does it do?
So imagine you want to try out a leverless controller for fighting games on a Playstation 5. You still have a cheap keyboard lying around. What to do? Toss away all the keys you don't need, plug the keyboard into your Meisteradapter, (plug in a supported* authentication device) and off you go. The Meisteradapter functions as a controller and converts your inputs into console and PC compatible outputs, with the added benefit that you can plug in more devices to authenticate them for consoles.

## What consoles is this compatible with?
PC, PS3, PS4, PS5, Nintendo Switch, Xbox360, Xbox One, Steam Deck, MiSTer and Android

## What authentication devices can I use?
Check the [GP2040-CE](https://gp2040-ce.info/introduction) and [HID Remapper](https://www.remapper.org/manual/) documentation. Basically any licensed Playstation 4 "fighting stick" will work for fighting games on Playstation 5. This is something most authentication devices make use of. Newer authentication devices are fully Playstation 5 compatible, but not YET supported by the firmwares.  
Or as a PS5 specific workaround, you could either unplug the adapter or push the reset button after every match before the 8 minute timout strikes.

## What firmware should I use?
"I depends." Ask yourself what you are trying to achieve and what firmware you are more familiar with. Here are two examples:
Do you already use GP2040-CE and just want to use your keyboard, Xbox360 controller or Dualshock 4 as a controller on a PS5 or any of the listed compatible consoles, maybe in tournaments? Go with GP2040-CE and use the keyboard or gamepad host add-on.
Do you want to use your actual MIDI keyboard as a controller on a PS5 or other console? Use HID Remapper. It can convert basically every HID input device and is also compatible with the authentication devices. It is more of an universal converter and can do more in that regard, but might demand more effort to configure.

## How can I build this? / license
All necessary files can be found in the "production" and firmware folder. Just order an assembled board from your favorite PCB fab and get a nice resin printed case. Or print it yourself. Or get one CNCed. Or carve one out of wood. The more creative, the more interested I am in in getting to see a picture of it. So send them over please!
Then plug the adapter into your PC, it should mount as an external USB storage device. Drag and drop the firmware into it. It will reboot, then follow the corresponding documentation.

## Who can build this? / license
This design is licensed under the [OPEN COMMUNITY LICENSE](https://github.com/OpenCommunityLicence/OpenCommunityLicence).
In short: you can use, modify and build it for non-commercial use. You can use, modify and build it for internal commercial use. You must NOT modify, build and sell it without my permission. I will grant this permission without any costs, I just want to know who is building and selling it and make an official list here.  

## Where can I buy this?

Recommended:
[Additive Arcade](https://additivearcade.com/), UK based, worldwide shipping
