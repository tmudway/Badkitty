# Badkitty
Remake of the BadKitty druid addon through TellMeWhen scripts

## Preview

Full addon in edit mode  
<p align=center><a target="_blank" href="https://cloud.githubusercontent.com/assets/3653340/20781700/df20b1fc-b752-11e6-94a5-7146c266b03d.jpg"><img src="https://cloud.githubusercontent.com/assets/3653340/20781700/df20b1fc-b752-11e6-94a5-7146c266b03d.jpg" width=300></a></p>

Addon in use  
<p align=center><a target="_blank" href="https://cloud.githubusercontent.com/assets/3653340/20781701/df2aaaae-b752-11e6-935d-4ac4e2838711.jpg"><img src="https://cloud.githubusercontent.com/assets/3653340/20781701/df2aaaae-b752-11e6-935d-4ac4e2838711.jpg" width=700></a></p>

## How to install
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

## How to use

All icons will show if their current buff/debuff isnt applied or has come off cooldown. Each icon will also display if its about to drop off/come off cooldown (current timer starts at 7s)

Rip and Savage Roar will show as red if you have less than the threshold number of combo points (5 for rip, 4 for savage roar). This threshold can be changed by right clicking the icon, going to "Conditions" near the bottom left of the config window and moving the sider.

Ferocious bite only shows if savage roar has >12s left (can be changed the same way as above) and either rip has >12s left or rip is applied and the boss has sub-25% health

## Contributing

All contributions are appreciated, especially for other specs. Simply keep the same basic structure as the current script to make merging easier.

I can be contacted ingame on Proudmoore-NA on the Alliance char Ryytikki or through github itself. I'll check here regularly but I can near guarentee you'll contact me that day with an ingame mail

## Known bugs/issues

- Text on cooldown bars is somewhat thick
- No icon in top right of feral spec (any suggestions?)
- Icon for combo points doesnt match the original one on FC. If anyone can get me the spell/item name of the old icon I'd appreciate it
- No CD bar for clearcasting/bloodtalons/Predatory swiftness
- Resources always show at the top of the cooldown bar

## Changelog

### 1.01
- Fixed issues with tiger's fury/berserk not showing on the cooldown bars as well as only showing on the main grid once available (rather than 10s before with a countdown). 
- Clearcasting icon now shows when it should. 
- Moved Combo points/energy to the cd bar. 
  - Gave them icons
- Set transparencies to 70% of both groups
