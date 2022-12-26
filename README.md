## Serious Sam Classic Plus Plus

What is Plus Plus?  
This is a modification for Serious Sam Classic The First Encounter.  
This mod required https://github.com/tx00100xt/SeriousSamClassic or https://github.com/tx00100xt/SeriousSamClassic-VK to run.  
Serious Sam Classic Plus Plus was created by fans of the game Serious Sam Classic and is distributed for free.    

Author:  
Created by El-ad 'IrCarX Iirion Claus' Amir, dtelad11@hotmail.com, ICQ#4213690  

Thank you for downloading Serious Sam++. This is a mod for the first  
person shooter game Serious Sam, designed to ease the work of mappers,  
by giving them more possibilites. If you've never designed maps, you'll  
barely notice the effect of the mod (especially if you played other FPSes  
like Duke Nukem 3D) but as a mapper I'm sure you'll find the new options  
very useful. This does not mean that average players shouldn't get the mod-  
vice versa. In order to play the new exciting maps people will build with  
this mod, you'll need to install it. So do so. NOW.  

![OW1](https://raw.githubusercontent.com/tx00100xt/SE1-TFE-PlusPlus/main/Images/samplusplus.png)


Download [SE1-TFE-PlusPlus.tar.xz] archive and unpack to  SeriousSamClassic/SamTSE/ directory.  
To start the modification, use the game menu - item Modification.

Building Serious Sam Classic Odd World modification (only for SS:TFE)
---------------------------------------------------------------------

### Linux

Type this in your terminal:

```
git clone https://github.com/tx00100xt/SE1-TFE-PlusPlus.git SE1-TFE-PlusPlus
cd SE1-TFE-PlusPlus/Sources
./build-linux64.sh -DTFE=TRUE              	# use build-linux32.sh for 32-bits
```
After that , libraries will be collected in the x32 or x64 directory .   
Copy them to SeriousSamClassic/SamTSE/Mods/OddWWorld/Bin folder.

### Gentoo

To build a game for gentoo, use a https://github.com/tx00100xt/serioussam-overlay containing ready-made ebuilds for building the game and add-ons.

### Arch Linux

To build a game under Arch Linux you can use the package from AUR: https://aur.archlinux.org/packages/serioussam

### Raspberry Pi

The build for raspberry pi is similar to the build for Linux, you just need to add an additional build key.

```
cd SE1-TFE-PlusPlus/Sources
./build-linux64.sh -DTFE=TRUE -DRPI4=TRUE	# use build-linux32.sh for 32-bits
```
### FreeBSD

Install bash. 
Type this in your terminal:

```
git clone https://github.com/tx00100xt/SE1-TFE-PlusPlus.git SE1-TFE-PlusPlus
cd SE1-TFE-OddWorld/Sources
bash build-linux64.sh -DTFE=TRUE	# use build-linux32.sh for 32-bits
```
After that , libraries will be collected in the x32 or x64 directory .   
Copy them to SeriousSamClassic/SamTSE/Mods/OddWWorld/Bin folder.

Windows
-------
* This project can be compiled starting from Windows 7 and higher.

1. Download and Install [Visual Studio 2015 Community Edition] or higher.
2. Download and Install [Windows 10 SDK 10.0.14393.795] or other.
3. Open the solution in the Sources folder, select Release x64 or Release Win32 and compile it.

Supported Architectures
----------------------
* `x86`
* `aarch64`
* `e2k` (elbrus)

Supported OS
-----------
* `Linux`
* `FreeBSD`
* `Windows`
* `Raspberry PI OS`

License
-------

* Serious Engine v1.10 is licensed under the GNU GPL v2 (see LICENSE file).


[SE1-TFE-PlusPlus.tar.xz]: https://drive.google.com/file/d/1cL4xfF0dnAO-rfc2c415n4rAPBNicjqC/view?usp=sharing "Serious Sam Classic PlusPlus Mod"
[Visual Studio 2015 Community Edition]: https://go.microsoft.com/fwlink/?LinkId=615448&clcid=0x409 "Visual Studio 2015 Community Edition"
[Windows 10 SDK 10.0.14393.795]: https://go.microsoft.com/fwlink/p/?LinkId=838916 "Windows 10 SDK 10.0.14393.795"
