# Basement.sav
Notes made during the making of an all-in-one PC gaming hub from the games in my basement.

This was achieved by dumping all my personal ROM's and save files on every console my Dad and I collected over the years. And then configuring all the files to run via the use of emulators running on a single PC (Windows). I found L[LaunchBox](https://www.launchbox-app.com/download) to be the best soloution for multiple emulators as an all-in-one frontend.

<p float="middle">
  <img src="https://shellywell123.github.io/The-Shenanigans-of-Shellywell123/assets/files.png" width="400" />
</p>

# Recovering save game files
To transfer a game's progress from the orginal hardware to emulation, the save files need to be dumped. 

Different consoles use different formats and methods of storing these files. Typically a cartridge based console will store the save data on the cartridge its self (alongside the game ROM). Disc based consoles store the save data in a seperate location to the games files. (older consoles have dedicated memory cards).

N.B. I found all RetroArch cores to convert save file formats into `.srm`. I.e they need to be converted back to their orginal format if you want to use them with orginal hardware/non retroarch emulators.

## Sony PlayStation Portable
 - How to dump save: cfw on psp sd card
 - Save File Location : on device
 - Save File Format : folder on binary files
 - My Emulator choice : [PPSSPP](http://ppsspp.org/)

## Sony PlayStation 1/2
 - How to dump save: FreeMcBoot installed onto a ps2 mem card + usb stick
 <p float="middle">
  <img src="https://shellywell123.github.io/The-Shenanigans-of-Shellywell123/assets/FreeMcBoot.png" width="800" />
</p>
 - Save File Location : external memory cards
 - Save File Format : `.ps1`/`.ps2`
 - My Emulator choice : PS1 PCSX core in [RetroArch](https://www.retroarch.com/), PS2 [PCSX2](https://pcsx2.net/)

## Sony PlayStation 3
 - How to dump save: jailbroken PlayStation 3 with cfw
 - Save File Location : in hdd0 of device
 - Save File Format : folder on binary files
 - My Emulator choice : [RPCS3](https://rpcs3.net/)

## Nintendo DS
 - How to dump save: Nintendo DS + r4 card with cfw
 - Save File Location : 
 - Save File Format : `.sav`
 - My Emulator choice : DSume core in [RetroArch](https://www.retroarch.com/)

## Nintendo Gameboy / Advance 
 - How to dump save: Nintendo DS lite + r4 with cfw or FlashBoy
 - Save File Location : in cartridge
 - Save File Format : `.sav`
 - My Emulator choice : mgba_libretro core in [RetroArch](https://www.retroarch.com/)

## Nintendo Wii
 - How to dump save: cfw on a sd card
 - Save File Location : on device
 - Save File Format :
 - My Emulator choice : [Dolphin](https://dolphin-emu.org/)

## Sega Megadrive / Genesis
 - How to dump save: custom dumper 
 - Save File Location : in cartridge (not all games have save features)
 - Save File Format :
 - My Emulator choice : blastem_libretro core in [RetroArch](https://www.retroarch.com/)

## Sega Saturn
 - How to dump save: custom dumper 
 - Save File Location : on device or extenrnal cartridge memory
 - Save File Format :
 - My Emulator choice : Yaba SanShiro core in [RetroArch](https://www.retroarch.com/)
