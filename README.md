
Ubuntu minecraft AFK fishing (auto right click) bash script

## AFK fishing - Minecraft +++ (Right Mouse Button) V-1.2

Version 2021 - "mcversion" == the window title of minecraft game window

# -- Instructions:

# -- Install 'xdotool': 

just use your distribution's package manager to install it.

-$ sudo apt install xdotool

-$ mkdir ~/bin   (make bin dir)

save script ~/bin/AFKtoggle (nano,vim,etc)

-$ cd ~/bin

-$ chmod +x AFKtoggle

-$ nano ~/.bashrc (edit bash profile to add /bin to global path)

   add at the end: export PATH="/home/YOURUSERNAME/bin:$PATH" 
   
-$ source ~/.bashrc  (reloads bash profile)

# -- Disable autopause:
open the options.txt file in the Minecraft installation folder (it's usually /home/USER/.minecraft/options.txt)
look for the line: **pauseOnLostFocus** and replace true with **false**

# -- Launch Minecraft
go in front of your fish farm, equip your fishing rod and aim carefully for the sweet spot
Alt-Tab out of Minecraft without pausing the game

# -- open terminal
-$ AFKtoggle  <-- turns on/off
