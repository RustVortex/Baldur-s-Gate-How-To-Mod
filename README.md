# Baldur-s-Gate-How-To-Mod

## What this guide does
This guide walks you through installing mods for Baldur’s Gate 3 using Script Extender and BG3 Mod Manager, step by step.

---


## Advice
**MODS CAN BREAK EXISTING SAVES.** Always back up your saves before proceeding.

---

## Requirements

1. Have the game installed
2. Start **at least once** to create Profiles and Configs
3. Make sure you have [**NET 8.0**](https://dotnet.microsoft.com/en-us/download/dotnet/thank-you/runtime-desktop-8.0.22-windows-x64-installer?cid=getdotnetcore) and [C++ Redistributable](https://aka.ms/vs/17/release/vc_redist.x64.exe)

---

## Step 1 — Script Extender

**Official Source Here: https://github.com/Norbyte/bg3se**

1. Download the Script Extender below:

   [**SCRIPT EXTENDER**](https://github.com/CaioAugustus/Baldur-s-Gate-How-To-Mod/raw/refs/heads/main/Norbyte's%20Baldur's%20Gate%203%20Beta%20Script%20Extender-2172-2024April-30-1715333040.7z)

3. Place the `DWrite.dll` file into the game's **bin** folder:

   I. Open Steam  
   II. Right-click **Baldur’s Gate 3** → Properties  
   III. Go to **Installed Files**  
   IV. Click **Browse...**  
   V. Open the `bin` folder  
   VI. Paste the `DWrite.dll` file there


4. After placing the Script Extender on the bin folder **start the game once more** to register that you have the extender

### What is Script Extender?
The Script Extender allows more advanced mods to work on Baldur's Gate 3 - It expands the scripting support of the game. Without it, many mods that use more complex features may not work.

---


## Step 2 - Mod Manager

**Oficcial Source Here: https://github.com/LaughingLeader/BG3ModManager?tab=readme-ov-file** 

1. Install the [**Baldur's Gate 3 Mod Manager**](https://github.com/LaughingLeader/BG3ModManager/releases/latest/download/BG3ModManager_Latest.zip)

2. After downloading the Mod Manager, Extract it anywhere you want (Desktop is recommended), then run the `.exe`. After running the .exe the Mod Manager should automatically detect the pathways to the game data and exe.

If it fails, manually set the pathways in `Settings -> Preferences, click 'Save', then click the 'Refresh' button` so the campaign mod data is loaded.


<img width="800" height="498" alt="image" src="https://github.com/user-attachments/assets/428e3983-b185-4d25-b550-838fb564c526" />

3. Organize your active mods for the profile Public, then click the first export button (Export Load Order to Game), or click File -> Export Order to Game, to export your active load order to the game. This updates the modsettings.lsx file that the game reads.
<img width="1400" height="307" alt="image" src="https://github.com/user-attachments/assets/f67214d4-784b-4b8d-a039-40674d0629a5" />

---

## Step 3 - Mods

1. Download the mods from the [**Google Drive**](https://drive.google.com/file/d/1aSUw62ctiNki3l6NlOniYvB2JH924ICH/view?usp=sharing)

2. Extract them into the Mod Manager Aplication

3. After doing all of that, Export the mods to the game by pressing this button:
   <img width="1400" height="307" alt="image" src="https://github.com/user-attachments/assets/30e923a1-9b96-4534-93c4-5b35ff6cd95c" />

---

## Step 4 - Enabling the mods

After booting up the game, go to the mod manager option and enable all the mods, some mods may have update available, go ahead and update them, after enabling all of them go to the next step.

**You'll need to manually install the mod `Mystra's Spells` inside the mod manager part of the game**
---

## Final Step

 If you did all the steps correctly the game should be ready to go from the start, just start a new game and have fun !!!

---

 ## Extra - Client Side Mods

Maybe you want some mods that improve your gameplay client side, well, the [**Client Side Mod**](https://github.com/CaioAugustus/Baldur-s-Gate-How-To-Mod/releases/tag/Client-Side-Modding) may help you
