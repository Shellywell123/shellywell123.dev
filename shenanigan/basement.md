# Basement.sav
Notes made during the making of an all-in-one PC gaming hub from the games in my basement.

This was achieved by dumping all my personal ROM's and save files on every console my Dad and I collected over the years. And then configuring all the files to run via the use of emulators running on a single PC (Windows). I found [LaunchBox](https://www.launchbox-app.com/download) to be the best soloution for multiple emulators as an all-in-one frontend.

<br>

<hr />

<br>

# LaunchBox Configs
 - I use PS4 dual shock controller with this [script](https://github.com/Shellywell123/BigBox_PS4_home_button_Launcher) to launch LaunchBox in BigBox mode
 - I set all emulators to launch the rom directly in full screen mode for Sega Saturn I used this [script](https://github.com/Shellywell123/Launch-Box_Yaba_Sanshiro_Fullscreen_AutoHotKey_Script)

# Recovering save game files
To transfer a game's progress from the orginal hardware to emulation, the save files need to be dumped. 

Different consoles use different formats and methods of storing these files. Typically a cartridge based console will store the save data on the cartridge its self (alongside the game ROM). Disc based consoles store the save data in a seperate location to the games files. (older consoles have dedicated memory cards).

N.B. I found all RetroArch cores to convert save file formats into `.srm`. I.e they need to be converted back to their orginal format if you want to use them with orginal hardware/non retroarch emulators.

<br>

<hr />

<br>

## Sony PlayStation Portable
 - How to dump save: cfw on psp sd card
 - Save File Location : on device
 - Save File Format : folder on binary files
 - My Emulator choice : [PPSSPP](http://ppsspp.org/)

<br>

<hr />

<br>

## Sony PlayStation 1/2
 - How to dump save: FreeMcBoot installed onto a ps2 mem card + usb stick
 <p float="middle">
  <img src="https://shellywell123.github.io/The-Shenanigans-of-Shellywell123/assets/FreeMcBoot.png" width="800" />
</p>
 - Save File Location : external memory cards
 - Save File Format : `.ps1`/`.ps2`
 - My Emulator choice : PS1 PCSX core in [RetroArch](https://www.retroarch.com/), PS2 [PCSX2](https://pcsx2.net/)

<br>

<hr />

<br>

## Sony PlayStation 3
 - How to dump save: jailbroken PlayStation 3 with cfw
 - Save File Location : in hdd0 of device
 - Save File Format : folder on binary files
 - My Emulator choice : [RPCS3](https://rpcs3.net/)

<br>

<hr />

<br>

## Nintendo DS
 - How to dump save: Nintendo DS + r4 card with cfw
 - Save File Location : 
 - Save File Format : `.sav`
 - My Emulator choice : DSume core in [RetroArch](https://www.retroarch.com/)

<br>

<hr />

<br>

## Nintendo Gameboy / Advance 
 - How to dump save: Nintendo DS lite + r4 with cfw or FlashBoy
 - Save File Location : in cartridge
 - Save File Format : `.sav`
 - My Emulator choice : mgba_libretro core in [RetroArch](https://www.retroarch.com/)

<br>

<hr />

<br>

## Nintendo Wii
 - How to dump save: cfw on a sd card
 - Save File Location : on device
 - Save File Format :
 - My Emulator choice : [Dolphin](https://dolphin-emu.org/)

<br>

<hr />

<br>

## Sega Megadrive / Genesis
 - How to dump save: custom dumper 
 - Save File Location : in cartridge (not all games have save features)
 - Save File Format :
 - My Emulator choice : blastem_libretro core in [RetroArch](https://www.retroarch.com/)

<br>

<hr />

<br>

## Sega Saturn
 - How to dump save: custom dumper 
 - Save File Location : on device or extenrnal cartridge memory
 - Save File Format :
 - My Emulator choice : Yaba SanShiro core in [RetroArch](https://www.retroarch.com/)

<br>

<hr />

<br>