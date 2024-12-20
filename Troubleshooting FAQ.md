![img](https://s13.gifyu.com/images/SjBKh.png)
![img](https://s9.gifyu.com/images/SCGXK.png)

**⛔ STOP.** Do not try to remove or uninstall things by hand. Do not try to reinstall everything. Do not try to reinstall Vortex, Cyberpunk2077, or the collection when you see errors on Vortex.

# Frequently Asked Questions


- [Crashes](#crashes)
- [Troubleshooting](#troubleshooting)
- [Gameplay Questions](#gameplay-questions)
- [Bugs](#bugs)
- [Vortex Questions](#vortex-questions)
- [Other Questions](#other-questions)

![](https://s12.gifyu.com/images/Cyan-Rule.png)




## Crashes

<details>
<summary>My game is crashing when changing keybinds or loading a save</summary>

![img](https://i.imgur.com/wAJUpeU.png)

This is a wierd vanilla crash introduced in **2.11**. The following guide should help to rectify the crash.

**1**) Go to your main game folder.

**Steam**
```
DRIVE LETTER\Steam\steamapps\common\Cyberpunk 2077\bin\x64
```
**GoG**
```
DRIVE LETTER\GOG Galaxy\Games\Cyberpunk 2077\bin\x64
```

**2**) Now, find **CChromaEditorLibrary64.dll** file and rename it to something else (doesn't really matter what name you choose).

**3**) Once done you should be able to change your keybinds and launch the game without any crashes.

## [Other Bugs introduced in 2.11](https://youtu.be/QDUn_TuoTdg?si=3xhtgRk0W4Q_7eMk&t=109)

![img](https://i.imgur.com/wAJUpeU.png)

</details>


<details>
<summary>My game is crashing straight after launch</summary>

![img](https://i.imgur.com/wAJUpeU.png)

**1**) Check the install guide and make sure you follow the instructions.

**2**) Make sure the game is installed on an **SSD.**

**3**) Perform a **Cyberclean** Then boot up the game and see if the problem is resolved.

**4**) Disable the (Appearance mod menu) mod in **Vortex**.

**5**) Disable/Uninstall the reshade if you have installed and ran the program.

The following cases are rare but these can cause a crash on launch.
- Reshade
- (AMM) Apperance Mod Menu

![img](https://i.imgur.com/wAJUpeU.png)

</details>

<details>
<summary>My game crashes at the breaching screen</summary>

![img](https://i.imgur.com/wAJUpeU.png)

You need to disable **"Analytics"**

**1**) **Purge** the mods in **Vortex**

![img](https://s11.gifyu.com/images/Sg8LQ.jpg)

**2**) Launch the game 

**3**) Go to the settings menu and on the gameplay tab disable **"Analytics"**.

![img](https://s11.gifyu.com/images/Sg8LW.jpg)

**4**) **Deploy** the mods in **Vortex**

**5**) Launch the game.

![img](https://i.imgur.com/wAJUpeU.png)

</details>

<details>
<summary>Game is giving this error on startup</summary>

![img](https://i.imgur.com/wAJUpeU.png)

If you are crashing or experiencing errors on startup and a Cyberclean has not helped try the following.

![img](https://s9.gifyu.com/images/SF28Y.png)

Right-click on the following Mods in Vortex and select reinstall.

**1**) Cyber Engine Tweaks

**2**) redscript

**3**) Archive XL

**4**) Codeware

**5**) Tweak XL

**6**) Red4ext

![img](https://i.imgur.com/wAJUpeU.png)

</details>


<details>
<summary>My game is crashing after creating a character</summary>

![img](https://i.imgur.com/wAJUpeU.png)

For some users, these were able to fix their issues.

**1**) Make sure the game is installed on a **SSD**

**2**) Make sure the graphics driver is up to date/Reinstall the graphics driver 

**3**) Disable any overlay (steam or Nvidia/amd overlay for example) 

**4**) Disable the (appearance mod menu).

**5**) Run the game in windowed fullscreen.

**6**) Make sure these are upto date>
- Common Redist
- NET 7 Desktop Runtime

Another workaround is to start a vanilla game and then redploy the mods after.

**1**) **Purge** the mods in **Vortex**

**2**) Create a character without mods.

**3**) Save the game after the first mission.

**4**) Go back to **Vortex** and **Deploy** the mods this will enable all the mods. 

**5**) Start the game and load the save and see if you are able to play.

![img](https://i.imgur.com/wAJUpeU.png)

</details>


<details>
<summary>My game is crashing when loading a save</summary>

![img](https://i.imgur.com/wAJUpeU.png)

Make sure you have disabled **"cross-platform saves"** as shown below and you have the game installed on a **SSD**.  

![img](https://s12.gifyu.com/images/SWeJF.png)

If this doesnt fix the issue you can try the following. 

Play the game without mods and make a save and then reactivate mods and load the save.

**1**) In **Vortex** on the mods tab select **"Purge"** this will remove the mods from the game files.

**2**) Boot up the vanilla game load your save now save and close the game.

**3**) In **Vortex** on the mods tab select "**Deploy"**

**4**) Boot up the game and load your save.

![img](https://i.imgur.com/wAJUpeU.png)

</details>




## Troubleshooting

<details>
<summary>I get a message at the main menu saying that mods could not be loaded like in the picture below</summary>

![img](https://i.imgur.com/wAJUpeU.png)

![](https://s12.gifyu.com/images/Screenshot_2023-05-05_103305.png)

You didnt turn of **"redmod autoconvert"** read the installation guide and start from scratch.

**1**) Delete the collection and archives.

**2**) Turn of **"redmod autoconvert"**

![](https://s11.gifyu.com/images/Untitle44d.jpg)

**3**) Run a **"cyberclean"**

**4**) Delete the **"mod"** folder in the main game directory this is the redmods folder.

![](https://s12.gifyu.com/images/Redmod-folder.jpg)

**5**) Reinstall the collection


![img](https://i.imgur.com/wAJUpeU.png)

</details>

<details>
<summary>Reshade doesnt launch when I click it It tells me that it cant be found</summary>

![img](https://i.imgur.com/wAJUpeU.png)

Sometimes you need to relink **Vortex** to a tool.

**1**) Go to the dashboard tab in **Vortex**.

**2**) Scroll down untill you see tools.

**3**) Click the 3 dots next to the tool you need to relink ie (Reshade). and select "edit"

**4**) Now selct "target" and browse to where you have the tool installed this will be in the main cyberpunk directory.

![img](https://s12.gifyu.com/images/SQNLK.png)


![img](https://i.imgur.com/wAJUpeU.png)

</details>

<details>
<summary>I see this error when opening the Virtual Atelier</summary>

![img](https://i.imgur.com/wAJUpeU.png)

![img](https://s11.gifyu.com/images/SuJ1O.png)

Dont worry this is normall some shops haver the same items.

![img](https://i.imgur.com/wAJUpeU.png)

</details>

<details>
<summary>The Atelier Shop doesnt show up in game</summary>

![img](https://i.imgur.com/wAJUpeU.png)

**1**) Open **Vortex** 

**2**) On the mods tab search for **Virtual Atelier**

**2**) Right click on the mod and select reinstall.

**4**) Launch the game and see if the problem is  resolved.

![img](https://i.imgur.com/wAJUpeU.png)

</details>

<details>
<summary>My game wont launch after Collection Update</summary>

![img](https://i.imgur.com/wAJUpeU.png)

Always double-check Vortex to make sure it uninstalled/installed something properly during an update. If you are having any issues with crashing or mods not loading you can perform a Cyberclean.

![img](https://i.imgur.com/wAJUpeU.png)

</details>




## Gameplay Questions

<details>
<summary>HUD Elements are off the screen</summary>

![img](https://i.imgur.com/wAJUpeU.png)

This is due to a mod called **HUDitor** that allows you to move the HUD widgets where ever you would like. 

**1)** Once in game press **"F7"**  to make sure the HUD is toggled on then hold **SHIFT** and press **U** to customize the hud settings to suit you. 

**2)** To go to the next widget press the **LEFT** and **RIGHT** arrow keys.

**3)** To reset the widgets press **X**

https://i.imgur.com/odR9sZl.mp4
https://www.nexusmods.com/cyberpunk2077/mods/3315

![img](https://i.imgur.com/wAJUpeU.png)

</details>


<details>
<summary>Mini Map isnt showing up</summary>

![img](https://i.imgur.com/wAJUpeU.png)

Press **F6** to show the mini map and **F8** to tuggle the HUD


![img](https://i.imgur.com/wAJUpeU.png)

</details>


<details>
<summary>My Clothes are Clipping</summary>

![img](https://i.imgur.com/wAJUpeU.png)

There are a few reasons for this.

Female V
- 98 per cent of clothing is fitted to the Custom Fem V body we use.
If some clothes are clipping its because
- You are trying to fit Male V clothes to fem V.
- One Mod may have some clothing that fit and some that clip. As we can't separate some items in a single Mod this is just how it is.
- **Note** at this time not all Phantom Liberty clothing has been refitted for Fem V

Male V
- If you have enabled the Adonis body and clothes are clipping this is because you didn't enable the Refitted Adonis clothing from the optional Mods.
- If you do choose the Adonis body not all clothes are suited to that body so you will find some clip and some dont. This is also out of our control.

![img](https://i.imgur.com/wAJUpeU.png)

</details>


<details>
<summary>I cant shoot the drones in the car in the Heist Mission</summary>

![img](https://i.imgur.com/wAJUpeU.png)

You can fix this bug by 

**1**) Equip a pistol before getting into the car.

![img](https://i.imgur.com/wAJUpeU.png)

</details>


<details>
<summary>System-Ex Not working</summary>

![img](https://i.imgur.com/wAJUpeU.png)

You need to go to a ripperdoc and hover over a slot to buy more slots

![img](https://i.imgur.com/wAJUpeU.png)

</details>


<details>
<summary>The Cyberpunk 2077 splash screen will loop for a few minutes.</summary>

![img](https://i.imgur.com/wAJUpeU.png)

This can happen on the first few launches of the collection.

Things to note.

**1**) Make sure the game is installed on an **SSD**.

![img](https://i.imgur.com/wAJUpeU.png)

</details>

<details>
<summary>How do i change the Menu backgrounds</summary>

![img](https://i.imgur.com/wAJUpeU.png)

On the first installation, you will be able to choose your background from the installer if you would like to change this at any time follow the steps below.

**1**) Open **Vortex** and locate the **Menu Backgrounds-v2** mod.

**2**) Right-click the Mod and select **Reinstall**

**3**) Now you will be able to choose another background.

![img](https://i.imgur.com/wAJUpeU.png)

</details>


<details>
<summary>Wilson's Range not accessible</summary>

![img](https://i.imgur.com/wAJUpeU.png)

**1**) Go to the Blade Runner easter egg﻿
Take the lift to the roof and come back down

**2**) Wait for a minute or two for the music to finish and the scene to end

**3**) When you next visit the range it should be working as normal

You only need to visit the easter egg once, but repeated visits shouldnt break anything

![img](https://i.imgur.com/wAJUpeU.png)

</details>






## Bugs




<details>
<summary>My colours are all wrong</summary>

![img](https://i.imgur.com/wAJUpeU.png)

This is an error from Reshade.

It has enabled the same effect twice.

**1**) Run the Reshade installer from Vortex and uninstall the preset.
**2**) Run the Reshade installer again and reinstall the preset.

![img](https://i.imgur.com/wAJUpeU.png)

</details>


<details>
<summary>I can't exit out of the Settings Menu and other Menus</summary>

![img](https://i.imgur.com/wAJUpeU.png)

At this stage it seems that this bug is baked into older saves. You will need to start a fresh save.

![img](https://i.imgur.com/wAJUpeU.png)

</details>


<details>
<summary>My character and some female NPCs have weird texture lines on them</summary>

![img](https://i.imgur.com/wAJUpeU.png)

You need to set the texture quality to **"HIGH"**

**Note** This setting doesnt show when in game you must be in the main menu.

**1**) Launch the game 

**2**) Go to the settings menu and on the graphics tab set texture quality to high.

![img](https://i.imgur.com/wAJUpeU.png)

</details>

<details>
<summary>There is a weapon stuck in my inventory and i cant unequip it</summary>

![img](https://i.imgur.com/wAJUpeU.png)

**1**) Go to a Vendor and sort by all.

**2**) Locate the problem weapon and sell it.

![img](https://i.imgur.com/wAJUpeU.png)

</details>


<details>
<summary>My screen is zoomed in</summary>

![img](https://i.imgur.com/wAJUpeU.png)

Some times the camera can get stuck zoomed in. To fix this you can try the following. 

**1**) If you are stuck zoomed in with your scope on a weapon press **control** on your keyboard to toggle weapon zoom.

**2**) Save your game and reload. 

**3**) Change your FOV and then change it back. 

![img](https://i.imgur.com/wAJUpeU.png)

</details>

<details>
<summary>My character has 2 arms 2 different skin colours 2 tattoos 2 Hairstyles etc</summary>

![img](https://i.imgur.com/wAJUpeU.png)

This can happen if you change your character in the game (mirror or a ripperdoc). This is caused by the **Appearance Change Unlocker** mod this mod is needed to be able to change many things on your character like tattoos ect 

**1**) Reload your current save.
or
**2**) Restart the game.

![img](https://i.imgur.com/wAJUpeU.png)

</details>

<details>
<summary>Meredith Stout missing textures</summary>

![img](https://i.imgur.com/wAJUpeU.png)

This is a known issue. It will only occur in this scene.

![img](https://s12.gifyu.com/images/SYwNm.png)

![img](https://i.imgur.com/wAJUpeU.png)

</details>

<details>
<summary>Mistys Hair is Floating</summary>

![img](https://i.imgur.com/wAJUpeU.png)

If you find that Misty's hair is bugging out you can do the following.

**1**) Press **F11** 
**2**) Select **AMM** 
**3**) Scan Misty and select another appearance.

![img](https://i.imgur.com/wAJUpeU.png)

</details>


<details>
<summary>My character is T-Posing</summary>

![img](https://i.imgur.com/wAJUpeU.png)

This bug is caused by the DOWNTOWN Hair Salon.

If you can't deal with it you can disable the Mods until the author releases an update.

![img](https://s12.gifyu.com/images/SYwN1.png)

![img](https://i.imgur.com/wAJUpeU.png)

</details>





## Vortex Questions


<details>
<summary>How do i change the Mod Staging folder in Vortex</summary>

![img](https://i.imgur.com/wAJUpeU.png)

To enable **Hardlink Deployment** in **Vortex** the **Mod Staging folder** must be on the same drive as the game.

If you can't select **Hardlink Deployment** then this is why, you can follow the guide below to change the location of the Staging Folder.

**1**) Open **Vortex** and select **"settings"**

**2**) On the **"Mods"** tab you can select the folder icon.

**3**) Here you can change the location of the **Staging Folder** and make sure it is on the same drive as the game.

![img](https://i.imgur.com/wAJUpeU.png)

</details>


<details>
<summary>The Tools in Vortex are missing</summary>

If you don't see the Tools in **Vortex** this could be one of 2 issues.

**1**) The most common issue is Vortex being confused, so you can try to **Purge** and **Deploy** the Mods in **Vortex** a few times if this still doesn't show the Tools close and reopen **Vortex**.

**2**) Sometimes you need to relink **Vortex** to a tool.
or sometimes the toolbar isn't enabled.

- Go to the **"dashboard"** tab in **Vortex**.

- Scroll down until you see **"tools"**.

Make sure it's enabled.
If it is but the tools still arnt showing do the following

- Click the 3 dots next to the tool you need to relink ie Reshade. and select **"edit"**

- Now select **"target"** and browse to where you have the tool installed this will be in the main Starfield directory.

![img](https://i.imgur.com/wAJUpeU.png)

</details>


<details>
<summary>Where are the optional mods</summary>

![img](https://i.imgur.com/wAJUpeU.png)

**1**) Open **Vortex**

**2**) Select **"Collections"**

**3**) Select **"View"** on the collection.

![img](https://s11.gifyu.com/images/Sguez.png)

**4**) Select **"Mods"**

![img](https://s11.gifyu.com/images/Sgueb.png)

**5**) Now you can filter between **"Required"** and **"Recommended"** Recommended being the optional Mods.

![img](https://s11.gifyu.com/images/SgueM.jpg)

![img](https://i.imgur.com/wAJUpeU.png)

</details>


<details>
<summary>Vortex is giving me a Pop-Up error</summary>

![img](https://i.imgur.com/wAJUpeU.png)

**Vortex** can sometimes give errors. These can most of the time be fixed with the following methods.

- Restarting **Vortex**.
- Restarting your PC
- Logging out of **Vortex** and **Nexus** and signing back in.

![img](https://i.imgur.com/wAJUpeU.png)

</details>


<details>
<summary>Vortex is giving me a pop up that says error 403 ect</summary>

![img](https://i.imgur.com/wAJUpeU.png)

**Vortex** and **Nexus** can throw errors sometimes to fix this.

- Log out of **Vortex**
- Log out of **Nexus**

And then log back in

![img](https://i.imgur.com/wAJUpeU.png)

</details>


<details>
<summary>In Vortex it says 'Incompatible mods enabled'</summary>

![img](https://i.imgur.com/wAJUpeU.png)

This is because you have enabled 2 conflicting Texture Mods.

All you have to do is disable the variant of the texture you don't want either **2k** or **4k**.

![img](https://i.imgur.com/wAJUpeU.png)

</details>







## Other Questions

<details>
<summary>Where is the game located</summary>

![img](https://i.imgur.com/wAJUpeU.png)

```
Steam> Drive Letter\SteamLibrary\steamapps\common\Cyberpunk2077.exe
GOG>   Drive Letter\GOGLibrary\Games\Cyberpunk2077.exe
Epic>  Drive Letter\EpicLibrary\Cyberpunk2077.exe  
```
 
![img](https://i.imgur.com/wAJUpeU.png)

</details>

<details>
<summary>How do i Update the Collection</summary>

![img](https://i.imgur.com/wAJUpeU.png)

## HOW TO UPDATE

**1**) Create a new Profile in Vortex and enable it.

**2**) Go to the Collection page and ensure the most current revision number is displayed, then select select **"ADD TO VORTEX"**

- [HEAVY](https://next.nexusmods.com/cyberpunk2077/collections/dfvt7o/revisions/56?utm_medium=vortex&utm_source=vortex&utm_campaign=view_collection&utm_source=copy&utm_medium=social&utm_campaign=share_collection) 
- [LITE](https://next.nexusmods.com/cyberpunk2077/collections/ayfbwl/revisions/24?utm_medium=vortex&utm_source=vortex&utm_campaign=view_collection&utm_source=copy&utm_medium=social&utm_campaign=share_collection) 

**3**) When prompted to select which profile to install to, select the new profile you created in Step 1

**4**) Once the update is downloaded you can remove the old profile. But :no_entry:**DO NOT** remove the archives.

**NOTE** Don't worry you will **NOT** have to redownload the entire collection with this method.

## [Video Guide](https://youtu.be/8KyTd3YAaUM)

### :no_entry:DO NOT update any of the mods in this collection individually in Vortex when a mod gets updated we will update the collection.

Notes will be in the changelog.

![img](https://i.imgur.com/wAJUpeU.png)

</details>

<details>
<summary>My game Freezes for a second when i load into the game</summary>

![img](https://i.imgur.com/wAJUpeU.png)

This is completely normal. This is caused by the **"Simple Menu"** Mod initializing.

![img](https://i.imgur.com/wAJUpeU.png)

</details>

<details>
<summary>Can i use a Pirated Game</summary>

![img](https://i.imgur.com/wAJUpeU.png)

- ⛔ **NO** Mods will not work with a Pirated/Cracked version of the game.
- ⛔ **DO NOT** use a pirated game. It is against **Nexus** rules and is illegal and we will not provide any support.

![img](https://i.imgur.com/wAJUpeU.png)

</details>


