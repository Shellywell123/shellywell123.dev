# Basement.sav
Notes made during the making of an all-in-one PC gaming hub from the games in my basement.

This was achieved by dumping all my personal ROM's and save files on every console my Dad and I collected over the years. And then configuring all the files to run via the use of emulators running on a single PC (Windows). I found [LaunchBox](https://www.launchbox-app.com/download) to be the best soloution for multiple emulators as an all-in-one frontend.

<br>

<hr />

<br>

# LaunchBox Configs
<p float="middle">
  <img src="https://shellywell123.github.io/The-Shenanigans-of-Shellywell123/assets/basement/DS4.png" width="300" />
</p>
 - I use PS4 dual shock controller with this [script](https://github.com/Shellywell123/BigBox_PS4_home_button_Launcher) to launch LaunchBox in BigBox mode and have configured the same controller to each emulator.
 - I set all emulators to launch the selected ROM directly in full screen mode for Sega Saturn I used this [script](https://github.com/Shellywell123/Launch-Box_Yaba_Sanshiro_Fullscreen_AutoHotKey_Script)

# Recovering save game files
To transfer a game's progress from the orginal hardware to emulation, the save files need to be dumped. 

Different consoles use different formats and methods of storing these files. Typically a cartridge based console will store the save data on the cartridge its self (alongside the game ROM). Disc based consoles store the save data in a seperate location to the games files. (older consoles have dedicated memory cards).

N.B. I found all RetroArch cores to convert save file formats into `.srm`. I.e they need to be converted back to their orginal format if you want to use them with orginal hardware/non RetroArch emulators.

Below I have began detailing notes for different console emulators and save file recovery methods

<br>

<hr />

<br>

## Sony PlayStation Portable
<p float="middle">
  <img src="https://shellywell123.github.io/The-Shenanigans-of-Shellywell123/assets/basement/PSP.png" width="300" />
</p>
 - How to dump save: CFW on PSP's SD card
 - Save File Location : on device
 - Save File Format : folder on binary files
 - My Emulator choice : [PPSSPP](http://ppsspp.org/) (can use RetroArch core, but I prefer the Standalone)

<br>

<hr />

<br>

## Sony PlayStation 1
<p float="middle">
  <img src="https://shellywell123.github.io/The-Shenanigans-of-Shellywell123/assets/basement/PS1.png" width="300" />
</p>
 - How to dump save: ps3 mem stick converter (yet to try)
 - Save File Location : external memory cards
 - Save File Format : `.ps1`
 - My Emulator choice : PCSX core in [RetroArch](https://www.retroarch.com/)

<br>

<hr />

<br>

## Sony PlayStation 2
<p float="middle">
  <img src="https://shellywell123.github.io/The-Shenanigans-of-Shellywell123/assets/basement/PS2.png" width="300" />
</p>
 - How to dump save: FreeMcBoot installed onto a ps2 mem card + usb stick
 <p float="middle">
  <img src="https://shellywell123.github.io/The-Shenanigans-of-Shellywell123/assets/basement/FreeMcBoot.png" width="400" />
</p>
 - Save File Location : external memory cards
 - Save File Format : `.ps2`
 - My Emulator choice : [PCSX2](https://pcsx2.net/)

<br>

<hr />

<br>

## Sony PlayStation 3
<p float="middle">
  <img src="https://shellywell123.github.io/The-Shenanigans-of-Shellywell123/assets/basement/PS3.png" width="300" />
</p>
 - How to dump save: jailbroken PlayStation 3 with CFW (multiman)
 - Save File Location : in `hdd0\home\00000001\savedata` of device
 - Save File Format : folder of multiple files (typically contains: `ICON0.PNG`,`PARAM.SFO`,`USR-DATA` )
 - My Emulator choice : [RPCS3](https://rpcs3.net/)

<br>

<hr />

<br>

## Nintendo DS
<p float="middle">
  <img src="https://shellywell123.github.io/The-Shenanigans-of-Shellywell123/assets/basement/DS.png" width="300" />
</p>
 - How to dump save: Nintendo DS + [R4 card](https://en.wikipedia.org/wiki/R4_cartridge) with CFW
 - Save File Location : not sure if on cartridge or device
 - Save File Format : `.sav`
 - My Emulator choice : DSume core in [RetroArch](https://www.retroarch.com/)

<br>

<hr />

<br>

## Nintendo Gameboy / Advance 
<p float="middle">
  <img src="https://shellywell123.github.io/The-Shenanigans-of-Shellywell123/assets/basement/GB.png" width="300" />
  <img src="https://shellywell123.github.io/The-Shenanigans-of-Shellywell123/assets/basement/GBASP.png" width="300" />
</p>
 - How to dump save: Nintendo DS lite + [R4 card](https://en.wikipedia.org/wiki/R4_cartridge) with CFW or [FlashBoy](https://www.youtube.com/watch?v=aaEEqqJB3Ws&ab_channel=Trevorman5)
 - Save File Location : in cartridge
 - Save File Format : `.sav`
 - My Emulator choice : mgba_libretro core in [RetroArch](https://www.retroarch.com/)

<br>

<hr />

<br>

## Nintendo Wii
<p float="middle">
  <img src="https://shellywell123.github.io/The-Shenanigans-of-Shellywell123/assets/basement/Wii.png" width="300" />
</p>
 - How to dump save: CFW on a SD card
 - Save File Location : on device
 - Save File Format : `XXXX/data.bin` where `XXXX` is the games serial no.
 - My Emulator choice : [Dolphin](https://dolphin-emu.org/) (can use RetroArch core, but I prefer the Standalone)

<br>

<hr />

<br>


## Super Nintendo Entertainment System
<p float="middle">
  <img src="https://shellywell123.github.io/The-Shenanigans-of-Shellywell123/assets/basement/SNES.png" width="300" />
</p>
 - How to dump save: sanni cart reader or Snes mini + Classic 2 Magic or retrode/superfreak or SNES game back up device + floppy disk 
 - Save File Location : on cartridge
 - Save File Format : `.sfd`
 - My Emulator choice : ? core in [RetroArch](https://www.retroarch.com/)

<br>

<hr />

<br>

## Sega Megadrive / Genesis
<p float="middle">
  <img src="https://shellywell123.github.io/The-Shenanigans-of-Shellywell123/assets/basement/Megadrive.png" width="300" />
</p>
 - How to dump save: custom dumper such as [MD-DUMPER](https://www.tindie.com/products/xdeath/usb-megadrive-genesis-cartridge-readerwriter/)
 - Save File Location : in cartridge (not all games have save features)
 - Save File Format :
 - My Emulator choice : blastem_libretro core in [RetroArch](https://www.retroarch.com/)

<br>

<hr />

<br>

## Sega Saturn
<p float="middle">
  <img src="https://shellywell123.github.io/The-Shenanigans-of-Shellywell123/assets/basement/Saturn.png" width="300" />
</p>
 - How to dump save: yet to try
 - Save File Location : on device or extenrnal cartridge memory
 - Save File Format :
 - My Emulator choice : Yaba SanShiro core in [RetroArch](https://www.retroarch.com/)

<br>

<hr />

<br>