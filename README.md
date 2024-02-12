# Granblue Fantasy: Relink Slimepede Farm
Simple AutoHotKey script I made for grinding the 'Slimepede' mission in Granblue Fantasy: Relink. Grinding it is a slog, and I wanted to automate that so that I can leave my pc when I go to sleep.

Written using AutoHotKey V2.
## General Information
This script was made with Rackham as your active character in mind. It will:
- Teleport to the quest counter using game's build-in teleport function.
- Start new Slimepede Quest.
- Move Rackham to the back of the room, where Rainbow Slime spawns.
- Rotare around and shoot, in hopes of aggroing as many slimes it can.
- After the mission ends, it will spam left mouse button and wait until you get back to town before repeating this whole loop.

This was made with consistency in mind. The idea is to have Rackham aggro as many slimes he can, so he, and the rest of your CPU team, can just nuke the remaining slimes in hopes of spawning the rainbow one. The spawn rate for him is very low though, but I still managed to get 3 killed when I left this script running during the night for testing.

I tried writting the version of this script that'd not go back into the town, but there was always the problem of everything getting slightly out of sync due to varying loading times and stuff across the machines. This is the most consistent version I came up with, so I hope it'll help someone else.

I've also attached another script for spamming left mouse button, so you can burn through your knicknack vouchers more easily after grinding, without developing the famous carpal tunnel syndrome.
## Setup
- Grab the newest release "Slimepede.Grinder.zip" from [releases page](https://github.com/Wielkimati/GBFR-Slimepede-Farm/releases).
- Extract the files anywhere you'd like on your computer and run the Slimepede Grind.exe.

You don't need to have AHK V2 installed if you use this script like this. Should work on any Windows machine out of the box.
## Compiling
You can also just download the repo and compile the scripts yourself using [AHK2EXE](https://github.com/AutoHotkey/Ahk2Exe/releases/tag/Ahk2Exe1.1.37.01c). It has the option of compiling V2 scripts.

Alternatively, running the scripts as-is, without compiling, is also an option if you have AHK V2 installed.

## Keybinds
This script expects you're using default keyboard + mouse keybinds provided by the game.
Apart from that, here's the keybinds used by scripts themselves.

- F1: Starts the script running
- Shift+ESC: Exits the script completely.
## Team Setup
First, get you Rackham up to the task. You definitely should have 100% crit rate, as well as the rest of your team. For other stats, go full damage, so you're hitting your damage cap. Slimes don't really take much damage if it's not a crit, so setuping your team with this in mind is mandatory.
Other than that, while not 100% required, I higly recommend getting the sigil for Rackham that increases his range.
Here's my example Rackham
![Example screenshot](https://github.com/Wielkimati/GBFR-Slimepede-Farm/blob/main/RepoImages/ExampleRackham.jpg)

As for the rest of the team, probably anything will work. I used Narmaya, Zeta and Ferry for this. But, after talking about it with other people using scripts to grind this quest, it seems like the best choice would be running Eugen, Id in your team.
## Usage
Following is optional, but I recommend before doing this, go to your settings and:
- Change your resolution to the lowest possible.
- Select windowed mode.
- Cap the FPS to 60.
- Change the graphic preset to standard.
After all, no point in making the PC eat more power than it's necessary.

Following settings are not optional:
- auto run disabled.
- assist options disabled.
- Quest Cutscene Auto-Skip disabled.
- Loading Screen Skip set to auto skip.

For actual script usage, it's like this:
- Go to Seedhollow (The second, bigger city).
- Go to the quest counter and take the Slimepede quest once, by selecting it from "By Difficulty -> Maniac" tab.
- After that, press 3, 3 again, and left mouse click, to abandon the quest.

And you're ready. The point of doing that is so Slimepede can be consistently selected from quest list with just left mouse clicks. If you want to test if you've done this correctly, then just go to quest counter again and see if you can accept new Slimepede quest using just left mouse clicks.

After that, you're pretty much done. Make sure to focus your game window and press F1 to begin the grind.
Currently the script sends the inputs to whatever window you have selected, so don't focus your Firefox window or something else by mistake.

You can end the grinding any time you'd like by pressing Shift + Escape combo. After that, the program will exit and will need to be run again from .exe to continue.
## Video example
Click the image below to be redirected to an example of this working on YouTube.

[![Video Example](https://img.youtube.com/vi/vcAemD-vFag/0.jpg)](https://www.youtube.com/watch?v=vcAemD-vFag "Video Example")
## Carpal Tunnel Begone
Just a cool nice-to-have I've included as a bonus, since I already made it. Useful if you don't want to develop carpal tunnel syndrome from transmuting sigils.
Basically spams left mouse click. Usage:
- Select transmute option you'd like.
- F1: Starts spamming LMB.
- F2: Stops the spam.
- Shift+ESC: Exits the script completely.

No need to restart the script from .exe when you disable it, like with Slime script.
## Contact
Created by [@Wielkimati](https://github.com/Wielkimati)

if you'd like to contact me, I prefer Discord: Wielkimati.
But if you'd like to ask about any issue you're having, PLEASE, PRETTY PLEASE, make sure you've followed all of the instructions listed here. My discord is getting spammed enough with those.
It's my first experience with writing anything on AHK, so feedback and tips are appreciated.
