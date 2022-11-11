-----------------------
Name: SNES Filters Hack
Creator: Cluster
Category: UI
-----------------------
This module allows to tweak video filters on SNES Mini or Super Famicom Mini (yes, only SNES, not NES/Famicom).

You need to add special command line arguments to make it work. Just add those arguments to game's command line or to global command line arguments.

Argument to enable bilinear filter in 4:3 or Pixel Perfect modes:  
  `--smooth43` or `--enable-smooth`

Argument to enable scanlines in 4:3 or Pixel Perfect modes:  
  `--enable-scanlines`

Argument to enable both bilinear filter and scanlines in 4:3 or Pixel Perfect modes:  
  `--crt-mode`

Argument to disable scanlines in CRT mode (bilinear filter only):  
  `--no-scanlines`

Argument to disable bilinear filter in CRT mode (scanlines only):  
  `--no-smooth`

*WARNING:* this mod can conflict with other mods, like RetroArch. Make sure that you are using latest versions.