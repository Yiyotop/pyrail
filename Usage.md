# Introduction #

pyRO-RAIL is a GUI written in python using wxGlade/wxWidgets. Because it is written in python, it will run on all modern operating systems as long as python and wxwidgets are installed. The source is made available upon request.

# Details #
**Running the standalone GUI**

Download the .exe and run it.

**pyRO-RAIL standard usage**

1. Upon launching pyRO-RAIL.exe, a dialogue box will pop up prompting you to locate your RAIL\_State.homu.lua file. This file is typically located in your Ragnarok Online folder after you've run RO-RAIL first.

<img src='http://dl.dropbox.com/u/11565/wiki/dialogue.png'>

<font color='red'>Note:</font> If you do not see the RAIL_State.homu.lua, please install RAIL and initiate it using the /hoai command in game.<br>
<br>
In the future, when you launch pyRO-RAIL, your State file will automatically load from the location you specified. If you need to re-load values, click the 'Load' button and relocate your file.<br>
<br>
If you've done this correctly, the values from your State file will have populated the GUI.<br>
<br>
<img src='http://dl.dropbox.com/u/11565/wiki/basicai.png'>

2. Edit the values in the GUI to your liking. Each tab has information regarding <b>most</b> of the options that RO-RAIL has implemented.<br>
<br>
3. When finished, click 'Apply' to save your changes to the State File. RAIL will dynamically update while you're in game with the new values.<br>
<br>
<font color='red'>Note:</font> pyRO-RAIL writes out your state file in a short-hand version and RO-RAIL writes out the state file in explicit long-hand. RO-RAIL will re-write the State file into the long-hand format upon reading. Because of these two formats, pyRO-RAIL knows when the State file has been read by RO-RAIL and when it's not necessary to re-read the file with a Load command. If you are unable to get pyRO-RAIL to read your state file because the file is already in short-hand format, simply launch your game client and allow RO-RAIL to write the state file into long-hand format once again.