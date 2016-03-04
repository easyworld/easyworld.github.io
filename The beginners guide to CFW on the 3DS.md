# The beginners guide to CFW on the 3DS
http://hackinformer.com/2015/07/03/beginners-guide-cfw-3ds/

For everyone new in the 3DS Scene and wondering what a CFW is or which CFWs exist. Then how to use CFW, this beginners Guide to custom firmware is for you. (You other guys can take a look at this too :P)

A CFW is also called “Custom Firmware”. It is a modified Firmware for your Device that uses the Official Firmware as a base. It allows you to use applications that aren’t allowed by the producer (Nintendo/Sony/Microsoft).

Yes this also means Piracy can be acchieved with CFWs -_-

![](https://raw.githubusercontent.com/easyworld/easyworld.github.com/master/songwriting-guide.jpg)

So If you want to have a CFW on your 3DS your Systemfirmware has to be 9.2 or below. Atm it is not possible to exploit 3DS systems with firmware 9.3+.

If you don’t have a 3DS on FW9.2 or below you can just buy one from Ebay or find one in a shop near you if you are lucky.
Now for the 3DS CFWs (I’m not going to cover Gateways EmuNAND here)

## 1. Palantine CFW v.1.0
Palantine CFW was the first 3DS CFW but it only works on Firmware 4.5.

It got leaked while it still wasn’t working good. It has a high rate of failing to start. It had signatures patched so that you could install Homebrew applications and also pirated content.It featured a way to install DevMenu or BigBlueMenu (CIA installer) over Wifi.

## 2.Palantine CFW v.1.1
It had a encrypted Loader so that it could be used with Gateways ROP Loader and a better ARM9 Loader that decreased the start failures but it was still unstable.It has the same functions as the original Palantine CFW.

## 3.RXTools

![](https://raw.githubusercontent.com/easyworld/easyworld.github.com/master/rxtools.png)

RXTools features a bunch of Utilities:
* rxMode, free 3DS custom firmware
* CTR Titles Decryption
* Title Keys Decryption
* Xorpad Generation
* NAND Dumping
* NAND Partitions Decryption/Injection
* NAND FAT16 Xorpad Generation
* System Titles Dumping
* NAND Files Dumping/Injecting, for various hacks/mods
* Much, much more

These are the features of RXTools:
* Full and free EmuNAND support, up to the latest version, **9.8**
* Access to the eShop and to online playing (requires an updated emuNAND)
* Support for 100% of the games (newer ones will require emuNAND)
* Support for sysNAND, in case an emuNAND is not found
* Support for the latest emuNAND version
* Signatures Checks disabled
* Support for installing FBI (a CIA Manager) in both emuNAND and sysNAND
* Dynamic ram dumping (just for debug purpouses)
* Support for sysNAND, in case an emuNAND is not found
* AGB (GBA Virtual Console) Support
* TWL (DSiWare/DS Cardriges) Support

It works from Firmware 4.1 to 9.2 and is maintained by Roxas75

For this CFW to work you will need slot0x25KeyX.bin  (3DS 7.x.x Decryption Key, Just google it) and firmware.bin (RXTools gives you a program to download it).

The Thread can be found [here](https://gbatemp.net/threads/release-rxtools-roxas75-3ds-toolkit-fw-2-0-9-2.382782/)

A Tutorial on how to install rxtools can be found [here](http://hackinformer.com/2015/06/23/official-rxtools-v2-5-disabled-signature-checks-released/)

If you want RegionFree it is explained [here](http://hackinformer.com/2015/06/28/rxtools-v-2-5-2-pre-release-adds-regionfree/) (Yes 3DS is region Locked -_- so if you want to play Games from another Region you will need RegionFree)
## 4.Pasta CFW
CFW that started from a unknown Pastebin. It boots into sysNAND and supports N3DS 9.0-9.2 and O3DS 4.1-9.2 . Has a high risk of bricking your 3DS if you do something stupid. It lets you use unsigned DSiWare, GBA Virtual Console, Homebrew and of course Piracy.

It needs Cubic Ninja (3DS Game) to work on N3DS. It can be used on O3DS up to Firmware 4.5 with MSET ([DS Profile Exploit](http://wiki.gbatemp.net/wiki/3DS_Homebrew#The_MSET_exploit)) and if you have 5.0+ you will also need Cubic Ninja.

The latest Beta added FIRMLAUNCH. It is a method to load a newer Firmware.bin to play games that you normally can’t play on your 3DS Firmware.

This is the Team behind Pasta CFW:

**Team**: capito27, AlbertoSONIC, motezazer, felipejfc, nop90, dela

**Contributors**: crusard, FrozenFish24

[Pasta CFW Thread](https://gbatemp.net/threads/pasta-cfw-a-cfw-that-allows-unsigned-cia-to-be-installed-on-old-and-new-3ds-required-ninjhax.388925/)

[Here is the Method on how to install Pasta CFW with MSET](https://gbatemp.net/threads/release-pasta-cfw-without-cubic-ninja-mset-4-x-old3ds.389498/)

## 5. CakesFW
![](https://raw.githubusercontent.com/easyworld/easyworld.github.com/master/cakesFW.png)

CFW by mid-kid and b1l1s.

Features right now:
* Spider 4.x-9.2 and MSET 4.x and 9.0-9.2 support. Only for o3ds.
* Options to boot to sysNAND (for GBA/DSi) and emuNAND up to 9.8.
* Emunand supports redNAND, toshiba and samsung GW emuNANDs.
* Sig patches
* Patches are contained in “cakes”. The .cake format is a simple format that bundles FIRM patches, and tells the patcher what those patches need to work.

At the moment it is basically the same as rxtools but without the decryption tools.

Thread can be found [here](https://gbatemp.net/threads/release-cakesfw.391200/)

## 6.ReiNand CFW
Developed by Reisyukaku. It’s the first CFW that has slot0x25keyX.bin and firmware.bin build in so that you don’t have to search for them online. This also means that the CFW is “illegal” so I can’t link to the CFW directly.

Features as of Right Now
* O3ds Only
* Ninjhax only
* Emunand Support
* Region Free
* Eshop
* Firm for above 9.x
* Signigture patches
* Memory Debugger similar to NTR’s
* Ram Dumping

N3DS support is being added later together with MSET support.

If you want to use this CFW google for “Reisyukaku Pastebin” and then open the “ReiNand 1.0 Beta” Post. There you will find the download link. But atm you will need Cubic Ninja with NinjHax installed.

## 7.NTR CFW
![](https://raw.githubusercontent.com/easyworld/easyworld.github.com/master/ntr-cfw.png)

This is a anti-piracy CFW for the N3DS. Anti-Piracy means **no pirated cias (Signatures aren’t patched) Idk if the Sky3DS card is working.**

Features:

**Region Free.** Region-locked games could be launched in Home Menu directly.

**CFW Menu.** Press X+Y in games or Home Menu will show the NTR CFW Menu, to take screenshots or interact with plugins.

**Plugin support.** Users can develop or install their own plugins with libntrplg, plugin will run in the background and is callable via NTR CFW Menu. (screenshot is a built-in plugin now)

**Realtime Debugger.** Debugging your plugins on wi-fi directly with NTR Debugger

**Savegame Manager.** Manage your savegame of genuine gamecards, support migrating savegame from NTR 1.0 to NTR 2.0

For this CFW you will need A **EU/AUS/JP/USA** New 3DS with firmware 8.1.0/9.0.0/9.1.0/9.2.0 and a Cubic Ninja Gamecard or the e-shop version.

The NTR  CFW Thread can be found [here](https://gbatemp.net/threads/release-ntr-cfw-2-2-anti-piracy-region-free-cfw-on-jp-eu-us-aus-new-3ds.385142/).
