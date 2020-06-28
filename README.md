## Titan.TF DLC
This is the optional content pack for Titan.TF servers. The installation of this pack is required in order to see and hear custom content on our servers. Content includes all items found in the Titan universe and Mann vs Machine icons, sounds and models.

### Installation
---
#### Automatic (Recommended)
If you would like an easy one click installation process, connect to our content distributor server (IP: **download.titan.tf:11111**). To connect to a TF2 server via the IP address, type `connect download.titan.tf:11111` into your Team Fortress 2 developer console.

#### Manual
1. Download [GitHub Desktop](https://desktop.github.com/) and install it.
2. Launch GitHub Desktop.
3. Press `CTRL + SHIFT + O`.
4. You will see 3 tabs (GitHub.com, GitHub Enterprise Server and URL). Click on `URL`.
5. Enter `TitanTF/DLC` under the first "Repository URL or GitHub username and repository" entry.
6. Find your tf/custom folder location and place it in the second entry below. For example, the standard Team Fortress 2 installation on a 64 bit OS under the C drive looks like this: `C:\Program Files (x86)\Steam\steamapps\common\Team Fortress 2\tf\custom`
7. Click on `Clone` and the content will start downloading.
8. Go to [Titan.TF Settings](https://titan.tf/settings) and click on the "Items" tab.
9. Check the `Custom Item Sounds` checkbox.

### Updating
---
When there is an update to the content pack, this repository will update. Our servers and website will also notify you about the update when you play.

#### Automatic
The process is the same as the installation. Simply connect to the content distributor server to automatically download updates.

#### Manual
1. Launch GitHub Desktop.
2. Under the "Current Repository" option at the top left of the interface, make sure it is set to `DLC`. If it is not, click on it and change to the DLC repository.
3. You will see "Fetch Origin" or "Pull Origin" 2 options to the right of Step 2.
4. If it says "Fetch Origin", click on it and it should show "Pull Origin" if there is an update.
5. If it already says "Pull Origin", click on it and it will start updating.
6. Go to [Titan.TF Settings](https://titan.tf/settings) and click on the "Items" tab.
7. Check the `Custom Item Sounds` checkbox.

## Troubleshooting
There may be some issues with your installation preventing you from seeing and hearing the custom content. But before that, make sure the `Custom Item Sounds` checkbox is checked in your [Titan.TF Settings](https://titan.tf/settings).

#### Simple Solution
Type ```snd_restart``` into your Team Fortress 2 developer console.

#### Guaranteed Solution
If the first method didn't work, try the following.
1. Close Team Fortress 2.
2. Go to ```C:/Program Files (x86)/Steam/steamapps/common/Team Fortress 2/tf/sound``` (may or may not have (x86) depending on your computer).
3. Delete the file named ```sound.cache```.
4. Go back to the ```tf/``` folder and go into ```downloads/sound```
5. Delete the file named ```sound.cache```.
6. Boot up Team Fortress 2.
7. If you still cannot hear it, type ```snd_restart``` into your Team Fortress 2 developer console.
