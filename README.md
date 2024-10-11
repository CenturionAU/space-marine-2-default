# Space Marine 2 Mod Collection
This is my personal collection of space marine 2 file modifications to tailor the game's experience to my own personal preference. This GitHub report serves as a central location to store and track my changes as well as to gain more familiarity with GitHub features.

This repo is made public so that anyone who wants to use these modifications can freely do so.

All rights to Saber Interactive, the developers of Space Marine 2. Game modification is not supported by Saber Interactive and anyone who chooses to acknowledges that they do so at their own risk.

## Credits
This modification collected was heavily inspired by MegaDux's own collection featured on the cfemen Discord server. A lot of my understanding about modifiying the game's files comes from MegaDux and other users within the Discord server.

## Prerequisites
To be able to use the modifications contained within this repo, you will need a means of bypassing the game's Easy Anti Cheat (EAC). The aforementioned Discord server contains one but you'll have to find your own access to the server.

## List of Modifications
The extent of file modification in this collection is limited. I wanted to keep the modifications close to the vanilla experience. MegaDux's collection contains much less limited modifications.

Modification of Space Marine 2 game files is primarily done through editing of .sso files within the game's .pak files, which are essentially just an archive - hence why they can be opened through WinRAR or 7-Zip, as an example. The modifications will be split up in their respective folders so you can pick and choose which ones you want to apply.

There will also be a folder for the unedited vanilla files in case you want to revert to the base files and you don't have a backup of them. Files not touched by any of the modifications in the list will be excluded from the folder.

These modifications are client-side and will only affect your player character but you can still play online with friends.

Some of these seperated folders will be modifying the same files so you'll either need to combine them individually (I recommend VS code's compare feature) or use the releases within this repo which have a combination of my preferred modifications.

### executions-restore-health
- Executions restore a small amount of player health, depending on the enemy type.

### guns-no-spread
- All player ranged weapons have zero spread. There's still recoil but all your shots will hit centre of your crosshair.

### guns-infinite-magazine
- All player ranged weapons have infinite magazines.

### melee-increased-speed
- All player melee weapons have had the small delay between each swing eliminated, resulting in faster attack speed.

## Installation Instructions
1. Download the latest release of ```my-values.zip```.
2. Open or extract ```my-values.zip```.
3. Open ```/Space Marine 2/client_pc/root/paks/client/default/default_other.pak```.
4. Copy the ```ssl``` folder from ```my-values``` to ```default_other```.

If you want to mix and match which modifications you want to use from this collection, you'll need to download the source code and apply the changes yourself. VS Code has a compare feature that highlights all the discrepencies between two files so you can edit or add in the specific modified values you want to your own game files.