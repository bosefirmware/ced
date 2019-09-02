# Bose Firmware

ced

<a href="https://github.com/bosefirmware/ced/blob/master/isaac/README.md">Bose AE2 SoundLink = Isaac</a><br>
<a href="https://github.com/bosefirmware/ced/blob/master/celine/README.md">Bose Frames = Celine</a><br>
<a href="https://github.com/bosefirmware/ced/blob/master/celine2/README.md">Bose Frames = Celine2</a><br>
<a href="https://github.com/bosefirmware/ced/blob/master/goodyear/README.md">Bose Noise Cancelling Headphones 700 = Goodyear</a><br>
<a href="https://github.com/bosefirmware/ced/blob/master/moonraker/README.md">Bose OE SoundLink = Moonraker</a><br>
<a href="https://github.com/bosefirmware/ced/blob/master/pascal/README.md">Bose On-Ear Wireless = Pascal</a><br>
<a href="https://github.com/bosefirmware/ced/blob/master/wolfcastle/README.md">Bose QuietComfort 35 = Wolfcastle</a><br>
<a href="https://github.com/bosefirmware/ced/blob/master/baywolf/README.md">Bose QuietComfort 35 II = BayWolf</a><br>
<a href="https://github.com/bosefirmware/ced/blob/master/powder/README.md">Bose QuietControl 30 = Powder</a><br>
<a href="https://github.com/bosefirmware/ced/blob/master/champ/README.md">Bose SoundLink Color = Champ</a><br>
<a href="https://github.com/bosefirmware/ced/blob/master/foreman/README.md">Bose SoundLink Color II = Foreman</a><br>
<a href="https://github.com/bosefirmware/ced/blob/master/minnow/README.md">Bose SoundLink Micro = Minnow</a><br>
<a href="https://github.com/bosefirmware/ced/blob/master/m3/README.md">Bose SoundLink Mini Special Edition = M3</a><br>
<a href="https://github.com/bosefirmware/ced/blob/master/kcup/README.md">Bose SoundLink Mini II = KCup</a><br>
<a href="https://github.com/bosefirmware/ced/blob/master/folgers/README.md">Bose SoundLink Revolve = Folgers</a><br>
<a href="https://github.com/bosefirmware/ced/blob/master/harvey/README.md">Bose SoundLink Revolve+ = Harvey</a><br>
<a href="https://github.com/bosefirmware/ced/blob/master/levi/README.md">Bose SoundSport Free = Levi</a><br>
<a href="https://github.com/bosefirmware/ced/blob/master/flurry/README.md">Bose SoundSport Pulse = Flurry</a><br>
<a href="https://github.com/bosefirmware/ced/blob/master/ice/README.md">Bose SoundSport Wireless = Ice</a><br>
<a href="https://github.com/bosefirmware/ced/blob/master/kleos/README.md">Bose SoundWear Companion speaker = Kleos</a><br>
</br></br>
The instructions provided below were modified from instructions <a href="https://www.reddit.com/r/bose/comments/ch6kxl/how_to_downgrade_your_bose_quietcomfort_35_ii/">found on reddit</a></br>
</br></br>
<b>BOSE DOWNGRADE PROCESS:</b> (windows only)
<ol>
  <li>Download the edited BOSEUPDATER.EXE (version <a href="https://github.com/bosefirmware/ced/raw/master/BoseUpdaterInstaller_6.0.0.4388.exe">6.0.0.4388</a>) <a href="https://github.com/bosefirmware/ced/raw/master/BOSEUPDATER.EXE">here</a></li>
  <li>Copy and replace the file in "C:\Program Files (x86)\Bose Updater"</li>
  <li>Make sure you close the app before replacing the file. You can close it on the taskbar (right click -> exit)</li>
  <li>Plug your headset or speaker and go to https://btu.bose.com</li>
  <li>When prompted launch the app.</li>
  <li>When you see this screen (<a href="https://imgur.com/a/xGijdYC">Screenshot 1</a>) press the following key combination: 'a' 'd' 'v' 'up arrow' 'down arrow' and you will see the following screen (<a href="https://imgur.com/a/yTLalsc">Screenshot 2</a>)</li>
  <li>Now you can select the firmware and click on Update.</li>
  <li>Wait for the update process to complete</li>
  <li>Enjoy your OLDER FIRMWARE! Cheers!</li>
</ol>
</br></br>
<b>ADVANCED DOWNGRADE PROCESS:</b>

Information:</br>
These instructions are for BOSEUPDATER.EXE found on Windows OS.</br>
Bose uses the "Bose Update" software with conjunction to the website https://btu.bose.com</br>

Step 1: Change the initial lookup link from the "Bose Update" app.</br>
<ol>
  <li>The Bose update app location is in "C:\Program Files (x86)\Bose Updater"</li>
  <li>Make an original backup of the file "BOSEUPDATER.EXE" and rename it to something like "BOSEUPDATER.EXE.backup"</li>
  <li>Download and install a hex editor. I used https://mh-nexus.de/en/hxd/</li>
  <li>Copy the BOSEUPDATER.EXE file to your desktop.</li>
  <li>Open the file you copied to your desktop with the hex editor.</li>
  <li>Go to Search -> Find and in the tab "Search-string" search for the word "connected_device" (<a href="https://imgur.com/a/tJpp6k6">Screenshot 3</a>) (<a href="https://imgur.com/a/KWJ7shb">Screenshot 4</a>) </li>
  <li>You will see https://worldwide.bose.com/connected_device as this is the offical URL (notice it is 43 characters long)</li>
  <li>Now change the URL to https://cutt.ly/git-hub-bose-firmware-files (the new URL is also 43 characters long). This is because the URL must be exactly the same number of characters as the previous one. This will not change the size of the app.</li>
  <li>Save the file and copy and replace it back to "C:\Program Files (x86)\Bose Updater"</li>
  <li>Run the app to see if it launches correctly. (It will show the icon on the bottom right on your taskbar) and then exit the app (right click and Select Exit)</li>
</ol>

Step 2: Update via Advanced method.</br>
<ol>
  <li>Be sure to have closed the "Bose Update app"</li>
  <li>Turn off your headset or speaker and connect it via USB.</li>
  <li>Go to https://btu.bose.com and wait until it prompts you to launch the app (or launch it manually from "C:\Program Files (x86)\Bose Updater")</li>
  <li>When you see this screen (<a href="https://imgur.com/a/xGijdYC">Screenshot 1</a>) press the following key combination: 'a' 'd' 'v' 'up arrow' 'down arrow' and you will see the following screen (<a href="https://imgur.com/a/yTLalsc">Screenshot 2</a>)</li>
  <li>Now you can select the firmware and click on Update.</li>
  <li>Wait for the update process to complete</li>
  <li>Enjoy your OLDER FIRMWARE! Cheers!</li>
</ol>
