# Elden-Ring-Debug-Tool
A tool for testing and debugging mods in Elden Ring

 
# WARNING  
Backup your saves before using this tool, and restore the backups before going online.  

## Requirements 
* [.NET 5 Desktop Runtime x64](https://download.visualstudio.microsoft.com/download/pr/b1902c77-e022-4b3e-a01a-e8830df936ff/09d0957435bf8c37eae11b4962d4221b/windowsdesktop-runtime-5.0.15-win-x64.exe)  

## Known Issues
* Params that share defs don't come up. Working on it.  
* Loading params is a bit sow. I am working on that, as well.

## Installing  
* Extract contents of zip archive to it's own folder. You may have to run as admin if DS2S META crashes  

## Usage
* For a param to load there has to be both a def in `Resources/Params/Defs` and a definition in on of the files in `Resources/Params/Pointers`  
* The format for pointer is Offset:Name. You can organize these files however you want. They will all be opened, read, split and added to the Param list, if there is a corresponding def.
* Can add names to a file with the same name as the param in `Resources/Params/Names` to add row names. Default name will just be the Row ID.

## Libraries
My fork of [Property Hook](https://github.com/Nordgaren/PropertyHook) by [TKGP](https://github.com/JKAnderson/)  

## Thank You  
**[TKGP](https://github.com/JKAnderson/)** Author of [DS Gadget](https://github.com/JKAnderson/DS-Gadget) and [Property Hook](https://github.com/JKAnderson/PropertyHook)  
**[Pav]()** Author of one of the CE Tables I used to find pointers and offsets, as well as provided the pointer list  

**[King Borehaha](https://github.com/kingborehaha/DS-Gadget-Local-Loader)** Who's local loading system has worked really well for a lot of things, including this  

# Change Log  
### Beta 0.1  

* Reads most params. Can edit them, too.  
