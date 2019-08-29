# Loma3DS
*"Luma3DS but got modified by someone"*

## What it is

**Loma3DS** is a **Luma3DS** fork with a few small extra features:
* Most Luma3DS text changed to Loma3DS (apart from credits)
* The blue colours you see in menus etc. changed to red
* Files are saved into a directory called Loma insead of Luma

If you are going to use **Loma3DS** then i using this feature from the **Luma3DS** wiki: 
https://github.com/AuroraWright/Luma3DS/wiki/Optional-features#firm-payload-chainloader

---

## Compiling

First you need to clone the repository with: `git clone https://github.com/AuroraWright/Luma3DS.git`  
To compile, you'll need a recent commit of [makerom](https://github.com/profi200/Project_CTR) added to your PATH. You'll also need to install [firmtool](https://github.com/TuxSH/firmtool), its README contains installation instructions.
You'll also need to update your libctru and devkitARM installation to their latest releases.
Then, run `make`.
The produced file is called `boot.firm` and is meant to be copied to the root of your SD card, for usage with boot9strap.

---

## Setup / Usage / Features

See https://github.com/AuroraWright/Luma3DS/wiki

---

## Credits

See https://github.com/AuroraWright/Luma3DS/wiki/Credits

---

## Licensing

This software is licensed under the terms of the GPLv3.
You can find a copy of the license in the LICENSE.txt file.

Files in the GDB stub are instead double-licensed as MIT or "GPLv2 or any later version", in which case it is specified in the file header.
