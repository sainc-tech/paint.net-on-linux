# Welcome to Paint.NET 3.5.11 in Bottles.

This project is all about HOW to run Paint.Net in linux.
This works with the latest version or maybe older version of bottles. Bottles is picked for a reason: its WAY simpler than wine AND i recommended USING it bc it does simpler setup than wine sooo..... LETS GET INTO IT!*

(*ALL WORK IS DONE VIA BOTTLES AND PAINT.NET NEEDS TO BE FOLLOWED BY THE RESPECTED AGREEMENTS PLZ DOTPDN LLC DONT BAN THIS PROJECT ITS OLD SOFTWARE ANYWAY...)

## okie dokie How to install bottles..
HARDNESS: very little

Just install flatpak in the link: [https://flathub.org/setup](https://flathub.org/setup)

then install bottles via this cmd: flatpak install com.usebottles.bottles

## Requirements
Hardness: little i think..

uhm .net 2.0 and .net 3.5 thats it.
WHY? WE NEED SP1 INSTEAD OF NORMAL .NET BC IT REQUIRED BY PAINT.NET 3.5.11!
well well well... INTRODUCING my reg file all it does is doing the .net 3.5
version to sp1 bc well sp1 is just tiny tweaks its .net 3.5 as the base tho 
why did i do this its a reason: THE INSTALLER OF NET 3.5 SP1 KEPT FAILING BY WINDOWS UPDATE HOOKS THAT WINE DOESNT HAVE SO I MADE THIS PROJECT TO HELP!
anyways...

## paint.net software
now this is the hard part listen, im giving u the software to install the LAST working version of paint.net so it works without scrambilng through the internet where some malware came some time so i recommend u install the one IN my repo for no malware so download it here.

# THE BOTTLES SETUP
Hardness: ez bc of my yaml file ;D

OK DOKIE this is the part that works. This is the part where the program is set up first things first we install the regs bc we need the version change but do the requirements first bc we need the things installled first ok dokie


its time to setup stepbystep:
- first get my .yml file bc it SETS EVERYTHING UP!
- second REPLACE add ur usrname here with linux username using find & replace in text editor <-- fun fact btw
- third IMPORT the .yml file main page > Import.. or Ctrl + I > Import a Bottle backup > Configuration
- fourth Add the reg via the registry editor
- fifth put this cmd: 
```bash
Paint.NET.3.5.11.Install.exe /x:C:\PDN_Extract 
```
(put it on drive_c dir bc it launches on drive_c)

### setup now
set paint.net as normal way and its old soooo ahh colourful back then.
set .NET 2.0 and .NET 3.5 as normal.
thats it. finally bc my brain is forgetting fast...

## Thats it!
uhm 1% of code is ai .-. but its WEAK NOT LIKE THE PRO ONE IM IN FREE TIER!
done in 2 hrs! its too much..
