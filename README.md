# Mooglian Madness Modpack Update Repository

This repository exists to distribute required modpack updates and to simplify the updating process for server members. The versions directory contains all modpack versions, and each version includes a changelog.txt as well as the update file required to update from the previous version to the selected version of the modpack.

## Modpack Update Checker

The modpack update checker allows the modpack to check for updates and warn you if an update has been released. It will also give you a link to this repository so that you can download the latest update file more easily. If an update is available you will see a large "Update Available" button on the main menu screen in Minecraft, as shown below.

![Minecraft Screenshot](https://i.ibb.co/nr5CCjx/Update-Avail-1.png)

If an update is available you want to click the "Update Available" button. Doing so will take you to the screen shown below which lists all of the available versions of the modpack.

![Minecraft Screenshot](https://i.ibb.co/hmD9HQ8/Update-Avail-2.png)

From this screen all you have to do is select the latest version of the modpack on the left-most menu. This will display the changelog and give you the ability to click the "Generic" button in the top-middle. Clicking that button will open this repository, and then you will navigate into the "versions" folder, and then into the folder for the modpack version you are updating to (for instance, 1.1.0). In  that folder you will find a download for the modpack update. The latest update file will also always be pinned in the Discord (the "modpack-update-guide" channel).

![Minecraft Screenshot](https://i.ibb.co/JK567gz/Update-Avail-3.png)
## Modpack Update Utility

The Modpack Update Utility is a simple, custom made application that handles automatically applying updates to the modpack. The user selects the path to the modpack itself and the update file, and the application handles the rest. This allows for easier updates and configuration changes without the user having to do too much extra work as configuration changes are especially difficult to explain / distribute on the client-side with a small-scope modpack like ours. The code is quick and dirty, but it should get the job done!

### Virus Total Results
![VirusTotal Results](https://i.ibb.co/km2jVwR/Virus-Total-Results.png)

To help people be a little more comfortable I've included the VirusTotal scan results for the Modpack Update Utility here. No malware here! The full results can be found here: [VirusTotal Results](https://www.virustotal.com/gui/file/9ce7b401d24d7b0c5095f078e57a5424beace3a94600d2dea1a4a8595f20d669)

---  
  
![Modpack Upgrade Utility GUI](https://i.ibb.co/gFSpNZG/Modpack-Update-Utility-Populated.png)

### Usage Guide
1. Make sure that your Minecraft is closed.
2. Download the latest modpack update from either the Discord or the versions folder in this repo.
3. Click in the "Modpack Instance Path" textbox. A selection box will open, and you want to choose the instance folder for the modpack we are using. The app should automatically put you in the Prism Launcher instances folder, so all you should have to do it select the folder for our modpack and then click the "Select Folder" button.
 - If you are unsure what folder you need to select or can't find it, you can right click on the instance inside of Prism Launcher and select "Folder". Doing so will open the folder that you want to select in the Modpack Update Utility.
4. After you have selected the instance folder you can click the "Open Update File" button. A file selection box will open- select the modpack update ZIP you downloaded in step 1 and click "Open".
5. The Modpack Update Utility will parse the update zip and display the changes that it is going to make for you.
6. The "Update Modpack" button should now be enabled- click it to perform the update. You should get a message popup letting you know that the update was completed successfully.
7. You're done! :D
