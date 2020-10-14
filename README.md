# Bose Firmware

<a href="https://community.bose.com/t5/Portable-Archive/Upcoming-Changes-to-the-Bluetooth-Updater-Website/m-p/147819">Bose's statement on why they no longer offer software downgrades</a>

Current version: <b>7.0.6.4815</b>

<b>BOSE DOWNGRADE PROCESS:</b> 
<ol>
  <li>Make sure you close the app before replacing the file. You can close it on the taskbar (right click -> exit)</li>
  <li><b>Windows</b> :
    <ol>
      <li>Download the edited BOSEUPDATER.EXE <a href="https://github.com/bosefirmware/ced/raw/master/BOSEUPDATER.EXE">here</a> (Link to <b>unedited</b> full install of version <a href="https://github.com/bosefirmware/ced/raw/master/BoseUpdaterInstaller_6.0.0.4388.exe">6.0.0.4388</a>)</li>
      <li>Copy and replace the file in "C:\Program Files (x86)\Bose Updater"</li>
      <li>Open the file. If you get a warning that says "Windows protected your PC". Select "More info" and click "Run anyway"</li>
    </ol>
  </li>  
  <li><b>macOS</b> :
    <ol>
      <li>If you already have the "Bose Updater" app installed. Please Delete.</li>
      <li>Download the edited "Bose Updater" app <a href="https://github.com/bosefirmware/ced/raw/master/Bose%20Updater.zip">here</a> (Link to <b>unedited</b> full install of version <a href="https://github.com/bosefirmware/ced/raw/master/BoseUpdater_6.0.0.4388.dmg">6.0.0.4388</a>)</li>
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
      <li><b>WARNING</b> : If you have <b>QC35 II</b> headphones with a serial number that ends in <b>AZ</b>. <b>Do NOT</b> downgrade below 2.1.3. Doing so can <b>BRICK YOUR QC35 II!!!</b></li>
    </ol>
  </li>
  <li>Enjoy your OLDER FIRMWARE! Cheers!</li>
</ol></br>
The instructions provided were modified from instructions <a href="https://www.reddit.com/r/bose/comments/ch6kxl/how_to_downgrade_your_bose_quietcomfort_35_ii/">found on reddit</a></br>

## Menu
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
