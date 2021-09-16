# Bat2Exe
Windows user interface for converting your batch files into executables.                                                                                                                                                                                                                                                                   

The latest release has all the dependencies you need, including the Bat2Exe executable.                                                                          
Latest release can be found and downloaded [here](https://github.com/dehoisted/Bat2Exe/releases/tag/1.3).                                                                                                                                                   

Current version: 1.3

## Features
+ Compress File
+ Hide Console
+ Select icon for EXE
+ Two different methods for conversion

## Updates
**Update Log**
```
+ Updated UI
+ Fixed update checking
+ Improved batch parsing
+ Added batch obfuscation (2 methods)
```
Link for checking for updates can be found [here](https://pastebin.com/raw/DS0hgb0F).
                                                                                               
If the HTTP response is the current program version, then there are no updates, if the response is the next version, then there is an update available.

## Dependencies
All Bat2Exe needs is .NET Framework 4, and GunaUI2.

Guna is used for most of the user interface.                                                                                     
Bytepress is used for when you want to compress your generated EXE file.
+ Guna: https://www.nuget.org/packages/Guna.UI2.WinForms/                                                               
+ Bytepress: https://github.com/roachadam/bytepress/releases/tag/v1.0.0.2

## Images
When first opening:

![image](https://user-images.githubusercontent.com/75084509/133696989-b6670012-0408-465e-b3a2-87ac7c000ed0.png)


When selecting batch file & some options then pressing "Compile File":

![image](https://user-images.githubusercontent.com/75084509/133697306-d06b5a82-0c6b-4f0c-93a4-baf44cfe934c.png)

