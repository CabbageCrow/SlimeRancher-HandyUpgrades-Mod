<img align="right" src="https://github.com/CabbageCrow/HandyUpgrades/blob/master/img/Logo/Handy_Upgrades_Logo.png">

# Handy Upgrades Mod
A Mod for Slime Rancher, which adds "Handy Upgrades" (and a few other things). They shall make ranching easier and quicker. Another term would be "Quality of Life" (QoL).  
The Handy Upgrades are only available in the game modes **Adventure** and **Casual**!

You already know the instructions? Then get it here, the first link: [Download the latest Release](https://github.com/CabbageCrow/HandyUpgrades/releases/latest) 

## Feedback is very welcome
Please give me feedback to the Handy Upgrades, their prices and unlock conditions.
Just drop by in the SR Wiki Discord and tag me: https://discord.gg/vv3szXr

## List of features
Get your unlocked Handy Upgrades at the Upgrade Terminal!  
You have to activate "Handy Upgrades" in "Packages/Other" for each save individually  
If you want to know the unlock conditions and don't care to be spoiled, you can find them here: [Unlock Conditions](https://github.com/CabbageCrow/HandyUpgrades#-spoiler-warning----unlock-conditions-for-the-handy-upgrades)

Consider **supporting me by spreading the word** or **[donating](https://github.com/CabbageCrow/SlimeRancher.HandyUpgrades-Mod#support-me--donate)** when you like what I'm doing.  

   * Selective Suction  
   For selectively vacuuming stuff up - the others wont get into your vacpack.  
   (To change between modes **configure the controls** in the Options menu.)  
   Modes:  
       * Normal = Normal mode  
       * Medium = **No big stuff** is vacuumed up **(crates, toys, largos)**  
       * Low = **Additionally normal slimes** won't be vacuumed up  
       * Plorts = *Only plorts* are affected  
       * Regulation Kit = Changes all modes so there is **much less bouncing off and muddle**  
   * Suction Booster  
   If enabled you can **vacuum up elated Largos**, recognizable by their big smiles.  
   It works **only on your ranch** and they use up 4 times the space in your vacpack.  
   * Memorizing Feeders  
   Auto feeders **keep the last piece of food**. This way you always know what to refill. And some busy buzzers too.  
   * Ginger Predictor  
   Three different levels **help with finding** the rare veggie. The better the upgrade, the narrower the prediction.  
   * Game Mode Switcher  
   Switches between Adventure and Casual  
   * Drone Firmware Update  
     Allows the busy buzzers to **collect plorts from gardens**  
   * Screenshot Extension  
     * Added screenshot types **"Scenery"** and **"With UI"**  
     (For the best pics without a blocked view! Or extra blocked! The latter is useful if you want e.g. capture your inventory too.)  
     * Screenshots will be **stored into a folder** on the desktop named "Slime Rancher - Screenshots".  
     * **Added buttons** for the new types **to the pause menu**, as well as for recording GIF  
     * **Naming of the files changed**. From 12-hour clock to 24-hour clock, so sorting doesn't get mixed up and added a second hyphens for easier reading.  
   * Silo Slot Self Switcher  
   Silos **switch to another slot** if the item can't be put into the selected one.  
   * Backup of the save file while the mod is active  

### In work / Planned
   * Quantum Transceiver
   * Extractor Storage

## Support me / Donate
If you like my work, spread the word so more people can enjoy it.  
You also can show your appreciation with a metaphorical coffee or cabbage donation:  
<a href='https://ko-fi.com/Q5Q0BT8U' target='_blank'><img height='55' style='border:0px;height:55px;' 
src='https://github.com/CabbageCrow/Miscellaneous/blob/master/img/Kofi_btn/kofi_btn_coffee.png?v=0' border='0' alt='Buy Me a metaphorical Coffee at ko-fi.com' /></a> 
<a href='https://ko-fi.com/Q5Q0BT8U' target='_blank'><img height='55' style='border:0px;height:55px;' 
src='https://github.com/CabbageCrow/Miscellaneous/blob/master/img/Kofi_btn/kofi_btn_cabbage.png?v=0' border='0' alt='Give the Crow a Cabbage at ko-fi.com' /></a>

## Install Instructions 
0. Maybe make a **Backup** of your save files - see [Backup save files](#backup-save-files).  
   (Although this Mod currently _doesn't_ do anything to the original save files directly - there is the small possibility that if it breaks something in the game itself, that could corrupt your save file.)



### Using the Installer
1. Try **using the new installer** inside the archive **HandyUpgrades_CabbageCrow_Installer_BETA.zip**  
Get it here, the first link: [Download the latest Release](https://github.com/CabbageCrow/HandyUpgrades/releases/latest)  
You can install it multiple times - it doesn't matter.  
(The installer handles all the prerequisites (UPM) and places the dlls into the right folder.)

### Manual installation
A manual installation is a bit more work and there are more possibilities for mistakes. Try using the Installer first.  

If you have Multi Mod installed, you shouldn't install UPM manually. Either put the .dll files into the "Mods" folder or use the Handy Upgrades Installer.  

This mod needs **UPM (Unity Plugin Manager)** to work. If you have UPM already installed, you can skipt the next step and continue with 2.

1. See its developer **[Install Instructions](https://www.reddit.com/r/slimerancher/comments/84ux68/official_thread_debug_menu_mod/)** and follow the first 3 steps of it - However if something is unclear, the following infos might help you:  
   
   * **Correct folder? Is it the "Slime Rancher game folder"?** See [Screenshot for UPM Installation](#screenshot-for-upm-installation).  
   * **How to find your Game folder?** Follow the [instructions here](https://support.steampowered.com/kb_article.php?ref=2037-QEUH-3335) in the link - BUT click **"Browse Local Files..."** instead of "Verify integrity of game files..." as the last step.  
   
2. Afterwards extract the content of the **"HandyUpgrades_CabbageCrow.zip"** from the [latest Release](https://github.com/CabbageCrow/HandyUpgrades/releases/latest) into the new **"Plugin" folder**  
(This zip-archive contains 2 .dll files. You can overwrite the old ones, if you have any.  
Make sure that there is only one version of "HandyUpgrades_CabbageCrow" in the folder.)
   
3. Access the content of the mod by using the **Vacpack Upgrade Terminal**.  
   There are two new Category-Tabs. With the rightmost you can activate Handy Upgrade Packages and by the middle one you can activate the actual Handy Upgrades.  
   (Currently it doesn't save what you have activated, so you have to re-activate all after a reload.)  
   Happy Sliming!
   
## Uninstall / Disable the mod
If you want to disable the mod just rename or delete the folder "Mods" in your game folder "Slime Rancher".  
(If you used the Installer or use Multimod, the Mod is located there. If you installed UPM manually, then you have to rename or delete the "Plugins" folder.)  
Note: That will affect all mods which use harmony. If there are more than 2 files within the plugin folder (HandyUpgrades and harmony). Alternatively you can just remove the HandyUpgrades file.  

### Complete Uninstall
If you need to uninstall your mods completely, follow the instuctions to [Verify Integrity of Game Files](https://support.steampowered.com/kb_article.php?ref=2037-QEUH-3335). 
This resets your game files to a clean state like a reinstall and doesn't affecting your saves.

## Backup save files
Go to the "Monomi Park" folder and make a **Copy** of your **"Slime Rancher" folder** to somewhere (e.g. your Desktop).

| System       | Location                                     |
|--------------|----------------------------------------------|
| Windows      | %UserProfile%\AppData\LocalLow\Monomi Park\  |
| macOS (OS X) | \~/Library/Application Support/Monomi Park   |
| Linux        | \~/.config/unity3d/Monomi Park               |

## Screenshot for UPM Installation
![Screenshot for UPM Installation](https://github.com/CabbageCrow/HandyUpgrades/blob/master/img/UPM_Helping_Screenshot.png)

## !!! SPOILER WARNING !!! - Unlock Conditions for the Handy Upgrades
* Selective Suction
  * Normal: From the start
  * Medium: 3h after unlocking either Moss Blanked or Indigo Quarry
  * Small: 3h after unlocking both Moss Blanked and Indigo Quarry
  * Plorts: 3h after unlocking Ancient Ruins
  * Regulation Kit: 7 days after unlocking the Lab expansion
* Suction Booster: 7 days after purchasing the Regulation Kit
* Memorizing Feeders: 3 days after unlocking the Lab expansion
* Ginger Predictor: Either after post credits reading Hobson Starmail or finding a Gilded Ginger
* Ginger Predictor Mk II: 7 days after finding the first Gilded Ginger
* Ginger Predictor Mk III: 7 days after buying Ginger Predictor Mk II
* Silo Slot Self Switcher: From the start

