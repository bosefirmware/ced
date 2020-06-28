
# No longer works

## ADVANCED DOWNGRADE PROCESS v2:</br>
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
