**Welcome to C(ontinued)-MaNGOS Pi**

----------

** NOTE: due major changes in mangos-classic g3dlite library, the MangosPI.patch doesn't work anymore. The latest working commit (maybe also some newer, but not tested) is https://github.com/cmangos/mangos-classic/tree/f1d799b7299dd46fc3311e9b4209bf4542b814e9 . I'll update the patch ~~in next weeks~~, one day.. maybe.

[![Build Status](https://www.travis-ci.com/Morlackx/mangos-classic-raspberry-pi.svg?branch=master)](https://www.travis-ci.com/Morlackx/mangos-classic-raspberry-pi)

The purpose of this fork is to modify the original **CMaNGOS Classic** project in order to let it build and run on Raspberry Pi 3.

That has been possible thanks a [patch file](https://github.com/Morlackx/mangos-classic-raspberry-pi/blob/master/MangosPI.patch) from **katz1** (found this name in patch file). The original patch file is available in this [pastebin](https://pastebin.com/ZKNWcBPY).

I don't take any credit (nor MaNGOS, nor the patch, nor the WoW game). I'm just sharing some my hours of google search and my attempt to setup a Travis-CI in order to compile on arm image (QEMU workaround).

At the time of writing, this code was able to compile and it is running on Raspberry Pi 3 (Raspbian jessie) with RetroPie (256mb split memory). MySQL server is on another Pi 1. 

[CMaNGOS Classic](https://github.com/cmangos/mangos-classic)  is a free project focused on WoW-Emulation. This project is about developing a server software that is able to emulate a well known MMORPG service.
