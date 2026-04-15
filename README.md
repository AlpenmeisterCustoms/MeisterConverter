# MeisterConverter
Tiny multi purpose converter running GP2040-CE or HID Remapper

<img width="594" height="470" alt="render0_0" src="https://github.com/user-attachments/assets/b223582f-38cd-4b54-81e1-20b2b26477e1" />

## What is this?
This is one of, if not the smallest and most affordable adapter / HID converter you can get with 3 USB-A "input" ports and 1 USB-A "output" port. It is using a RP2040 microcontroller to run either [HID Remapper](https://www.remapper.org/) or [GP2040-CE](https://gp2040-ce.info/) firmware.

## But what does it do?
So imagine you want to try out a leverless controller for fighting games on a Playstation 5. You still have a cheap keyboard lying around. What to do? Remove all the keyscaps you don't need, plug the keyboard into your MeisterConverter and off you go. The Meisterconverter functions as a controller and converts your inputs into console and PC compatible outputs, with the added benefit that you can plug in additional devices to authenticate them for consoles.
Maybe you have some other favorite input device that follows the HID specifications, but isn't PS5 compatible. Make it by plugging the MeisterConverter in between and adding an auth dongle. 

## What consoles is this compatible with?
PC, PS3, PS4, PS5, Nintendo Switch, Xbox360, Xbox One, Steam Deck, MiSTer and Android

## What authentication devices can I use?
Check the [HID Remapper](https://www.remapper.org/manual/) and [GP2040-CE](https://gp2040-ce.info/introduction) documentation. Either you use a dedicated auth dongle, like a Booter 5 or even a Wingman FGC or any licensed Playstation 4 "fighting stick". They will work for fighting games on Playstation 5. Newer authentication devices are fully Playstation 5 compatible, but not YET supported by the firmwares.  
Or as a PS5 specific workaround, you could either unplug the converter or push the reset button after every match before the 8 minute timout strikes.

## What firmware should I use?
"I depends." Ask yourself what you are trying to achieve and what firmware you are more familiar with. Here are two examples:
* Do you already use GP2040-CE and just want to use your keyboard, Xbox360 controller or Dualshock 4 as a controller on a PS5 or any of the listed compatible consoles, maybe in tournaments? Going with GP2040-CE and using the [keyboard](https://gp2040-ce.info/add-ons/keyboard-mouse-host) or [gamepad](https://gp2040-ce.info/add-ons/gamepad-usb-host) host add-on might be the easier option.
* Do you want to use your actual MIDI keyboard or any other device as a controller on a PS5 or other console? It might be worth using HID Remapper. It can convert basically every HID input device and is also compatible with the authentication devices. It is a more capable universal converter which can do more in that regard, but depending on your experience it might be more effort to configure (but there are built in "most used" templates to make it easier).

## How can I build this? / license
All necessary files can be found in the "production" and firmware folder. Just order an assembled board from your favorite PCB fab and get a nice resin printed case. Or print it yourself. Or get one CNCed. Or carve one out of wood. The more creative, the more interested I am in in getting to see a picture of it. So send them over please!
Then plug the converter into your PC, it should mount as an external USB storage device. Drag and drop the firmware into it. It will reboot, then follow the corresponding documentation.

## Who can build this? / license
This design is licensed under the [OPEN COMMUNITY LICENSE](https://github.com/OpenCommunityLicence/OpenCommunityLicence).
In short: you can use, modify and build it for non-commercial use. You can use, modify and build it for internal commercial use. You must NOT modify, build and sell it without my permission. I will grant this permission without any costs, I just want to know who is building and selling it and make an official list here.  

## Where can I buy this?

Recommended:
[Additive Arcade](https://additivearcade.com/products/meisterconverter), UK based, worldwide shipping

## How does it actually look like?

<img width="2857" height="2143" alt="MeisterConverter_colors" src="https://github.com/user-attachments/assets/2e4c8262-e9ce-42bc-884a-ba67304d8866" />
