
# No longer works

## ADVANCED DOWNGRADE PROCESS:</br>
</br>
Information:</br>
Bose uses the "Bose Update" software with conjunction to the website https://btu.bose.com</br>
</br>
Step 1: <b>Windows</b> - These instructions are for BOSEUPDATER.EXE found on Windows OS.</br>
Change the initial lookup link from the "Bose Update" app.</br>
<ol>
  <li>The Bose update app location is in "C:\Program Files (x86)\Bose Updater"</li>
  <li>Make an original backup of the file "BOSEUPDATER.EXE" and rename it to something like "BOSEUPDATER.EXE.backup"</li>
  <li>Download and install a hex editor. I used https://mh-nexus.de/en/hxd/</li>
  <li>Copy the BOSEUPDATER.EXE file to your desktop.</li>
  <li>Open the file you copied to your desktop with the hex editor.
    <ol>
      <li>Go to Search -> Find and in the tab "Search-string" search for the word "connected_device" (<a href="https://imgur.com/a/tJpp6k6">Screenshot 3</a>) (<a href="https://imgur.com/a/KWJ7shb">Screenshot 4</a>) </li>
      <li>You will see https://worldwide.bose.com/connected_device as this is the offical URL (notice it is 43 characters long)</li>
      <li>Now change the URL to https://cutt.ly/git-hub-bose-firmware-files (the new URL is also 43 characters long). This is because the URL must be exactly the same number of characters as the previous one. This will not change the size of the app.</li>
      <li>Save the file</li>
    </ol>
  </li>
  <li>Copy and replace it back to "C:\Program Files (x86)\Bose Updater"</li>
  <li>Run the app to see if it launches correctly. (It will show the icon on the bottom right on your taskbar) and then exit the app (right click and Select Exit). If you get a warning that says "Windows protected your PC". Select "More info" and click "Run anyway"</li>
</ol>

</br>
Step 1: <b>macOS</b> - These instructions are for BOSE UPDATER found on macOS.</br>
Change the initial lookup link from the "Bose Update" app.</br>
<ol>
  <li>The Bose update app location is in "Applications\Bose Updater"</li>
  <li>Right click and select "Show Package Contents"</li>
  <li>Go to "Contents\MacOS"</li>
  <li>Make an original backup of the file "Bose Updater" by right clicking on the file and selecting "Duplicate"</li>
  <li>Download and install a hex editor. I used https://apps.apple.com/us/app/ihex-hex-editor/id909566003</li>
  <li>Open "Bose Updater" with the hex editor.
    <ol>
     <li>Go to "Edit -> Find -> Find..." and select Text (do not put anything in the "Replace" field at the moment). Use "Find" to search for https://worldwide.bose.com/connected_device (<a href="https://imgur.com/a/tJpp6k6">Screenshot 3</a>) (<a href="https://imgur.com/a/KWJ7shb">Screenshot 4</a>). This is the offical URL (notice it is 43 characters long)</li>
      <li>Now in "Replace" enter the URL to https://cutt.ly/git-hub-bose-firmware-files (the new URL is also 43 characters long). This is because the URL must be exactly the same number of characters as the previous one. This will not change the size of the app.</li>
      <li>Select "Replace"</li>
      <li>Save the file</li>
    </ol>
  </li>
  <li>Open up Terminal (located in "Applications/Utilities")</li>
  <li>In terminal type in : xattr -cr /Applications/"Bose Updater.app"</li>
  <li>Run the app to see if it launches correctly. (It will show the icon on the top right on your taskbar) and then exit the app (right click and Select Exit)</li>
</ol>

Step 2: Update via Advanced method.</br>
<ol>
  <li>Be sure to have closed the "Bose Update app"</li>
  <li>Turn off your headset or speaker and connect it via USB.</li>
  <li>Plug your headset or speaker and go to https://btu.bose.com</li>
  <li>When prompted launch the app.</li>
  <li>When you see this screen (<a href="https://imgur.com/a/xGijdYC">Screenshot 1</a>) press the following key combination: 'a' 'd' 'v' 'up arrow' 'down arrow' and you will see the following screen (<a href="https://imgur.com/a/yTLalsc">Screenshot 2</a>)</li>
  <li>Now you can select the firmware and click on Update.
    <ol>
      <li><b>WARNING</b> : If you have <b>QC35 II</b> headphones with a serial number that ends in <b>AZ</b>. <b>Do NOT</b> downgrade below 2.1.3. Doing so can <b>BRICK YOUR QC35 II!!!</b></li>
    </ol>
  </li>
  <li>Wait for the update process to complete</li>
  <li>Enjoy your OLDER FIRMWARE! Cheers!</li>
</ol>


## ADVANCED DOWNGRADE PROCESS v2:

The instructions provided below were <a href="https://www.reddit.com/r/bose/comments/ch6kxl/how_to_downgrade_your_bose_quietcomfort_35_ii/">found on reddit</a></br>

Information:

I did this on Windows OS. This is for advanced users obviously, but feel free to ask question and i will try to answer back anyway i can.

Bose uses the "Bose Update" software with conjunction to the website https://btu.bose.com.

When you launch the app and the website it does the following things.
<ol>
  <li>Checks https://worldwide.bose.com/connected_device to find out based on your ID which next file to look at.</li>
  <li>Since our device (QC 35 II) has the codename BayWolf it goes to check the following link https://downloads.bose.com/ced/baywolf/index.xml</li>
  <li>This link shows the list of available firmwares for this device. As you can see for yourself it only shows the 4.5.2 version. This is because Bose doesn't allow to install other firmware at this moment. (meh)</li>
</ol>

You can find the log of the "Bose Update" app in "C:\Users\[your user]\AppData\Local\Temp\BoseUpdater.log"

If you cant see AppData folder you need to enable seeing hidden folders in Windows.

<b>Step 1: Change the initial lookup link from the "Bose Update" app.</b>
The Bose update app location is here "C:\Program Files (x86)\Bose Updater".
<ol>
  <li>Make an original backup of the file "BOSEUPDATER.EXE" and rename it to something like "BOSEUPDATER.EXE.backup"</li>
  <li>Download and install a hex editor. I used https://mh-nexus.de/en/hxd/</li>
  <li>Copy the BOSEUPDATER.EXE file to your desktop.</li>
  <li>Open the file you copied to your desktop with the hex editor.</li>
  <li>Go to Search -> Find and in the tab "Search-string" search for the word "connected_device" (<a href="https://imgur.com/a/tJpp6k6">Screenshot1</a>, <a href="https://imgur.com/a/KWJ7shb">Screenshot2</a>)</li>
  <li>Now change the URL with your own. I used VSCode to run a small web server in order the serve my altered XML file but you can use your own.Important: Your URL must be exactly the same number of characters as the previous one. This will not change the size of the app. Here is my modification. (<a href="https://imgur.com/a/4yrgwvw">Screenshot3</a>) As you can see i have put some extra 'a' characters to match the length of the initial URL.</li>
  <li>Save the file and copy and replace it back to "C:\Program Files (x86)\Bose Updater"</li>
  <li>Run the app to see if it launches correctly. (It will show the icon on the bottom right on your taskbar) and then exit the app (right click and Select Exit)</li>
</ol>

<b>Step 2: Run the webserver with your altered XML files.</b>

I used VSCode but you can use anything you feel comfortable with.
<ol>
  <li>Download and Install VSCode. https://code.visualstudio.com/</li>
  <li>After you install VSCode go to Extensions and install "Live Server" from Ritwick Dey. (installing VSCode extensions is out of the scope of this tutorial :P)</li>
  <li>Have the following folder structure in your desktop (<a href="https://imgur.com/a/exxkN6Q">Screenshot4</a>) Bose Mock----aaaaaaaaaa--------index.xml--------lookup.xml</li>
  <li>The lookup.xml file is the one from here (https://downloads.bose.com/lookup.xml) but i changed the part about my device (<a href="https://imgur.com/a/5gCMQgI">Screenshot5</a>)</li>
  <li>The index.xml file is the one from here (https://downloads.bose.com/ced/baywolf/index.xml) but i also added the 3.1.8 firmware (<a href="https://imgur.com/a/HmYzVUm">Screenshot6</a>) </br> EDIT: As corrected, if you want to use GitHub server follow this image https://i.imgur.com/jXfQ93m.png and not mine. Notes: I found the firmware from another post to this github page. https://github.com/avicoder/Boss-headphones-firmware it also has the 2.5.1 firmware (not tested). I didn't use VSCode web-server to serve the firmware files because it needs to be HTTPS. In my successful downgrade i didn't use GitHub but my own private server. I am guessing GitHub should also work fine.</li>
  <li>Right click on your "Bose Mock" folder in your desktop and select "Open with Code"</li>
  <li>In VSCode, right click on your index.xml file (or lookup.xml) and select "Open with Live Server" (<a href="https://imgur.com/a/Ab8dIXB">Screenshot7</a>)</li>
  <li>If everything is OK you should be able to open a browser and see your altered files via the following URLs http://127.0.0.1:5500/aaaaaaaaaa/index.xml http://127.0.0.1:5500/aaaaaaaaaa/lookup.xml</li>
</ol>

<b>Step 3: Update via Advanced method.</b>

Be sure to have closed the "Bose Update app"
<ol>
  <li>Turn off your headphones and connect them via USB.</li>
  <li>Go to https://btu.bose.com and wait until it prompts you to launch the app (or launch it manually from "C:\Program Files (x86)\Bose Updater"</li>
  <li>When you see this screen (<a href="https://imgur.com/a/xGijdYC">Screenshot8</a>) press the following key combination.'a' 'd' 'v' 'up arrow' 'down arrow' and you will see the following screen - (<a href="https://imgur.com/a/yTLalsc">Screenshot9</a>)</li>
  <li>Now you can select the firmware 3.1.8 and click on Update.</li>
  <li>Wait for the update process to complete</li>
  <li>Enjoy your OLD FIRMWARE HEADSET! Cheers!</li>
</ol>
