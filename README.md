# Bose Firmware

ced

Bose AE2 SoundLink = Isaac <a href="https://github.com/bosefirmware/ced/blob/master/isaac/README.md">(Firmware Info)</a><br>
Bose Frames = Celine <a href="https://github.com/bosefirmware/ced/blob/master/celine/README.md">(Firmware Info)</a><br>
Bose Frames = Celine2 <a href="https://github.com/bosefirmware/ced/blob/master/celine2/README.md">(Firmware Info)</a><br>
Bose Noise Cancelling Headphones 700 = Goodyear <a href="https://github.com/bosefirmware/ced/blob/master/goodyear/README.md">(Firmware Info)</a><br>
Bose OE SoundLink = Moonraker <a href="https://github.com/bosefirmware/ced/blob/master/moonraker/README.md">(Firmware Info)</a><br>
Bose On-Ear Wireless = Pascal <a href="https://github.com/bosefirmware/ced/blob/master/pascal/README.md">(Firmware Info)</a><br>
Bose QuietComfort 35 = Wolfcastle <a href="https://github.com/bosefirmware/ced/blob/master/wolfcastle/README.md">(Firmware Info)</a><br>
Bose QuietComfort 35 II = BayWolf <a href="https://github.com/bosefirmware/ced/blob/master/baywolf/README.md">(Firmware Info)</a><br>
Bose QuietControl 30 = Powder <a href="https://github.com/bosefirmware/ced/blob/master/powder/README.md">(Firmware Info)</a><br>
Bose SoundLink Color = Champ <a href="https://github.com/bosefirmware/ced/blob/master/champ/README.md">(Firmware Info)</a><br>
Bose SoundLink Color II = Foreman <a href="https://github.com/bosefirmware/ced/blob/master/foreman/README.md">(Firmware Info)</a><br>
Bose SoundLink Micro = Minnow <a href="https://github.com/bosefirmware/ced/blob/master/minnow/README.md">(Firmware Info)</a><br>
Bose SoundLink Mini Special Edition = M3 <a href="https://github.com/bosefirmware/ced/blob/master/m3/README.md">(Firmware Info)</a><br>
Bose SoundLink Mini II = KCup <a href="https://github.com/bosefirmware/ced/blob/master/kcup/README.md">(Firmware Info)</a><br>
Bose SoundLink Revolve = Folgers <a href="https://github.com/bosefirmware/ced/blob/master/folgers/README.md">(Firmware Info)</a><br>
Bose SoundLink Revolve+ = Harvey <a href="https://github.com/bosefirmware/ced/blob/master/harvey/README.md">(Firmware Info)</a><br>
Bose SoundSport Free = Levi <a href="https://github.com/bosefirmware/ced/blob/master/levi/README.md">(Firmware Info)</a><br>
Bose SoundSport Pulse = Flurry <a href="https://github.com/bosefirmware/ced/blob/master/flurry/README.md">(Firmware Info)</a><br>
Bose SoundSport Wireless = Ice <a href="https://github.com/bosefirmware/ced/blob/master/ice/README.md">(Firmware Info)</a><br>
Bose SoundWear Companion speaker = Kleos <a href="https://github.com/bosefirmware/ced/blob/master/kleos/README.md">(Firmware Info)</a><br><br><br>
<a href="https://github.com/bosefirmware/eb">eb</a></br>
<a href="https://github.com/bosefirmware/stetson">stetson</a></br>
<a href="https://github.com/bosefirmware/bosebuild">bosebuild</a></br>
<a href="https://github.com/bosefirmware/pro">pro</a></br>
</br></br>
The instructions provided below were modified from instructions <a href="https://www.reddit.com/r/bose/comments/ch6kxl/how_to_downgrade_your_bose_quietcomfort_35_ii/">found on reddit</a></br>
</br></br>
<b>BOSE DOWNGRADE PROCESS:</b> 
<ol>
  <li>Make sure you close the app before replacing the file. You can close it on the taskbar (right click -> exit)</li>
  <li><b>Windows</b> :
    <ol>
      <li>Download the edited BOSEUPDATER.EXE (version <a href="https://github.com/bosefirmware/ced/raw/master/BoseUpdaterInstaller_6.0.0.4388.exe">6.0.0.4388</a>) <a href="https://github.com/bosefirmware/ced/raw/master/BOSEUPDATER.EXE">here</a></li>
      <li>Copy and replace the file in "C:\Program Files (x86)\Bose Updater"
    </ol>
  </li>  
  <li><b>macOS</b> :
    <ol>
      <li>If you already have the "Bose Updater" app installed. Please Delete.</li>
      <li>Download the edited "Bose Updater" app (version <a href="https://github.com/bosefirmware/ced/raw/master/BoseUpdater_6.0.0.4388.dmg">6.0.0.4388</a>) <a href="https://github.com/bosefirmware/ced/raw/master/Bose%20Updater.zip">here</a></li>
      <li>Move "Bose Updater" to the "Applications" Folder</li>
      <li>Open up Terminal (located in "Applications/Utilities")</li>
      <li>In terminal type in : xattr -cr /Applications/"Bose Updater.app"</li>
    </ol>
  </li>  
  <li>Plug your headset or speaker and go to https://btu.bose.com</li>
  <li>When prompted launch the app.</li>
  <li>When you see this screen (<a href="https://imgur.com/a/xGijdYC">Screenshot 1</a>) press the following key combination: 'a' 'd' 'v' 'up arrow' 'down arrow' and you will see the following screen (<a href="https://imgur.com/a/yTLalsc">Screenshot 2</a>)</li>
  <li>Now you can select the firmware and click on Update.</li>
  <li>Wait for the update process to complete
    <ol>
      <li><b>WARNING</b> : If you have <b>QC35 II</b> headphones that end in <b>AZ</b>. <b>Do NOT</b> downgrade below 4.3.6. Doing so can <b>BRICK YOUR QC35 II!!!</b></li>
    </ol>
  </li>
  <li>Enjoy your OLDER FIRMWARE! Cheers!</li>
</ol>
</br></br>
<b>ADVANCED DOWNGRADE PROCESS:</b></br>
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
  <li>Run the app to see if it launches correctly. (It will show the icon on the bottom right on your taskbar) and then exit the app (right click and Select Exit)</li>
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
      <li><b>WARNING</b> : If you have <b>QC35 II</b> headphones that end in <b>AZ</b>. <b>Do NOT</b> downgrade below 4.3.6. Doing so can <b>BRICK YOUR QC35 II!!!</b></li>
    </ol>
  </li>
  <li>Wait for the update process to complete</li>
  <li>Enjoy your OLDER FIRMWARE! Cheers!</li>
</ol>

<a href="https://community.bose.com/t5/Portable-Archive/Upcoming-Changes-to-the-Bluetooth-Updater-Website/m-p/147819">Bose's statement on why they no longer allow software downgrades</a>
