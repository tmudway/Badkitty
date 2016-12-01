# Badkitty
Remake of the BadKitty druid addon through TellMeWhen scripts

## How to use
Current version has each spec as a seperate file. Will work on merging all into 1 addon script for ease of use.


1. Download the latest version of TellMeWhen
2. Open the TellMeWhen config by typing /tmw show
3. Right click on any icon (blank or otherwise) you see
4. Copy the entire text from whatever spec you want to add and paste it into the textbox at the bottom of the TMW config screen
5. Click import/export/restore -> from string -> Profile: [profile name] -> Copy Profile -> Create New Profile
6. Close that window and click "Exit config mode" in the other TMW window
7. If you want to enable numerical countdown on the icons, go to interface settings -> action bars -> check "Show Numbers for Cooldowns"


The scripts are currently set to only show during combat so you'll need to find a dummy/mob to test them on. To update, follow steps 2-6 but click Copy Profile - Overwrite <profile name> during step 5

TellMeWhen can be found on [Curse](https://mods.curse.com/addons/wow/tellmewhen) or on [WoWInterface](http://www.wowinterface.com/downloads/info10855-TellMeWhen.html)  
All scripts confirmed to work with TMW version 8.2.3

## Contributing

All contributions are appreciated, especially for other specs. Simply keep the same basic structure as the current script to make merging easier.

## Known bugs/issues

- Text on cooldown bars is somewhat thick
- No icon in top right of feral spec (any suggestions?)
- Icon for combo points doesnt match the original one on FC. If anyone can get me the spell/item name of the old icon I'd appreciate it
- No CD bar for clearcasting/bloodtalons/Predatory swiftness

## Changelog

### 1.01
- Fixed issues with tiger's fury/berserk not showing on the cooldown bars as well as only showing on the main grid once available (rather than 10s before with a countdown). 
- Clearcasting icon now shows when it should. 
- Moved Combo points/energy to the cd bar. 
  - Gave them icons
- Set transparencies to 70% of both groups
