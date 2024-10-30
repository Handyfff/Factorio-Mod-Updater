# Factorio-Mod-Updater
A program for updating your Factorio mods to the latest versions. It does not download new mods or dependencies. It only updates the mods you have in your PC to the latest versions which means they only work on Factorio 2.0 or above if the developer of mods has updated them to 2.0 or above otherwise they may still be viable on older versions of Factorio.

To download new mods here's an easy method below. It works independently of the updater and supports old verions of Factorio.

# Downloading New Mods
Simply use this tool [factorio Mod Downloader](https://github.com/vaibhavvikas/factorio-mod-downloader)

If it doesn't work then use the method below.

For your browser of choice (Chrome, Firefox etc.), search and install "Tampermonkey" extension. Then click this [Script](https://re146.dev/factorio/mods/free-factorio-mods-downloader-en.user.js) It should bring up the install menu for Tampermonkey. Install the script and allow necessary permissions.

Now go to [Factorio Mods](https://mods.factorio.com/)    

Click on the mod of your choice and there should be a "Download from re146.dev" green button on the mod page. If you have a Factorio account logged in, make sure to log out otherwise the button wouldn't be functional. Clicking on that green button will take you to a webpage where you can download the latest or old versions of the mod.

# Installing the Mods 
After downloading the mods you like, you should have their .zip files. Use WinRAR, 7Zip or any other compression software to extract all those .zip files. There should be a separate folder for each .zip file after extraction.

Then copy all those folders to C:\Users\yourusername\Appdata\Roaming\Factorio\mods. Also, make sure to tick hidden files in the View section of your File Explorer to show AppData folder. 

If you are using any other OS than Windows then the mods folder should be here:
For Linux: ~/. factorio/mods.
For Mac OS X: ~/Library/Application Support/factorio/mods.

After copying and pasting the mods folders, simply launch the game.

If everything goes smooth without any errors then move to Update section below. Otherwise disable the mods causing the errors and make sure to delete their folders from the mods folder mentioned above. 

# Updating the Mods
# For Windows
To update the mods simply download the FactModUpdt.exe from [Releases](https://github.com/Handyfff/Factorio-Mod-Updater/releases) Open it. It will go through your mods folder and downloaded the updates if there are any. Updates will be in .zip files and you will extract those files and copy the folders to the mods folder. MAKE SURE TO DELETE THE PREVIOUS FOLDER OF THE MOD YOU'RE UPDATING.

You can update your mods anytime but make sure you've the latest version of the game before doing so.
If any problems, ask me by opening an issue.

# For OS other than Windows
Download the FactModUpdt.py from [Releases](https://github.com/Handyfff/Factorio-Mod-Updater/releases) I never used any ther OS besides Windows so edit the mods directory in the script file to whatever your OS has. If any errors, Consult ChatGPT or StackOverflow because I can't help you here, sorry.
