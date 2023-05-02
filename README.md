Readme subjxt to change as autosplitter is being worked on.

Current Release: https://github.com/DreadSplit/Any-GL/releases/tag/autosplitter
-------------------------------------------------------------------------------------------------------------------------------------------------------------
Steps for setting up the auto splitter.

1. Go to https://github.com/Avasam/AutoSplit#tutorial and download the latest auto splitter release, and scroll down to Live Split Integration to get the .dll. Version at time of writing: v2.0.1

2. Place the downloaded "Autosplitter.exe" and the "Ready for Beta Testing" file in the same folder(this is for ease of use but not mandatory)

3. Place the .dll in your livesplits's components folder. 

4. Launch OBS and in the sources column right click your video capture and click "Windowed Projector (sources)"

5. Run the autosplitter and go to File > Settings to set up your Hotkeys, they should match whatever your have livesplit useing. Only other setting that might need a change is Comparison FPS limit which should be set to 60

6. Close the settings window, then click "Browse" in the main UI. Go to the file you downloaded containg all the split files, and select the category you will be running.

7. Click "Select Window" in the main UI and then click your Windowed Projector. You should now see your game feed on the left side of the Autospliter UI. The windowed projector cannot be minimzed during this or the autosplitter feed will freeze.
  7.1. go to File > Save profile as and name it the category. This lets you easily swap between categories later

8. Now close the Autosplitter and launch Livesplit. Right click the window and go to "Edit Layout". Click the + then go to Control > AutoSplit Intergration.

9. Now click "Layout Settings" and go to the AutoSplit Integration tab. Set the path of the .exe and the settings to the appropriate .toml.
  9.1. Save the layout the category name. Then do step 9 again for each category you want to use the sutosplitter for. This will let you just change your Livesplit layout and it'll be set to the right category.
  9.2. Make sure "Pause Game Time only" is checked, as this allows load removing if wanted/figured out consistantly. (there is an easy method for making it work but must be specialized to each person currently, reach out to Vale if load removal is something you want.)
  
10. You should now be ready to go. Only sure way to test is by starting your timer, and going to the first split. If everything is working then you should see the first split image on the right in AutoSplitter and it should split when you get your first item.

-------------------------------------------------------------------------------------------------------------------------------------------------------------
* Due to Speedrun.com time ruling and the way the auto splitter works, I cannot make the autosplitter start at the appropriate time. You will have to start your timer like normal then the autosplitter will take over until the very last split.
* The autosplitter does not prevent you from manually splitting, so if it misses a split you can manually do it and the autosplitter will adjust accordingly.
* Currently only supports english. If another launguage is wanted we can assist so long as we can get the images required.
* Current images are for splits for weapon upgrades. Further images will be updated and distributed and if needed instructions will be given on how to add them your livesplit!*
* Questions or Concerns, please do not hesitate to message BigSandwich#7909 or Vale#6704 - Or ask in the Coding the autosplitter thread in the Dread speedrun discord!*
