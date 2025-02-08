# Lenovo ThinkPad T480 - OpenCore Configuation

<img align="right" src="https://github.com/minaWesam/T480s-OC/blob/main/MacOS%20Seqioua.png" alt="macOS Sequoia running on the T480" width="425">


[![macOS](https://img.shields.io/badge/macOS-Sequoia-brightgreen.svg?logo=apple)](https://developer.apple.com/documentation/macos-release-notes)
[![OpenCore](https://img.shields.io/badge/OpenCore-1.0.0-blue.svg)](https://github.com/acidanthera/OpenCorePkg)

<p align="center">
   <strong>Status: Maintained</strong>
   <br />
   <strong>Version: </strong>15.3
   <br />
   <a href="https://github.com/minaWesam/T480s-OC/releases/tag/Release"><strong>Download now »</strong></a>
  
</br>



## ⚠️ Disclaimer
This guide is only for the Lenovo ThinkPad T480. I am NOT responsible for any harm you cause to your device. This guide is provided "as-is" and all steps taken are done at your own risk.

## 💻 Tested devices
T480s some other thinkpads with a simliar configurtion may work
<details>
<summary><strong>💻 My Hardware</strong></summary>
<br>
These are the Hardware component I use. But this OpenCore configuation <strong>should still work</strong> with your device, even if the components are not equal.

Check the model of your WiFi & Bluetooth card. Intel cards should be compatible with itlwm (or AirportItlwm). If your card is from another manufacturer, please check if your card supports macOS. macOS Sonoma no longer supports Broadcom Wifi cards.

| Category  | Component                            |
| --------- | ------------------------------------ |
| CPU       | Intel Core i5-8350U                  |
| GPU       | Intel UHD Graphics 620               |
| SSD       | Intel SSDPEKKF256G8L M.2 NVMe SSD    |
| Memory    | 16GB DDR4 2400Mhz                    |
| Camera    | 720p Camera                          |
| WiFi & BT |Intel Dual Band Wireless-AC 8265      |

</details>  

</details>

&nbsp;

## Status

<details>  
<summary><strong>✅ What's working</strong></summary>
</br>
 
- [X] Intel WiFi & Bluetooth (thanks to [itlwn](https://github.com/OpenIntelWireless/itlwm))
- [X] Brightness / Volume Control
- [X] Battery Information
- [X] Audio (Audio Jack & Speaker)
- [X] USB Ports & Built-in Camera
- [X] Graphics Acceleration
- [X] Trackpoint / Touchpad
- [X] Power management / Sleep
- [X] FaceTime / iMessage (iServices)
- [X] HDMI
- [X] Automatic OS updates
- [X] Handoff / Universal Clipboard
- [X] Sidecar (Cable) / AirPlay to Mac
- [X] SIP / FireVault 2
- [X] USB-C
- [X] Thunderbolt
 </details>

<details>  
<summary><strong>⚠️ What's not working</strong></summary>
</br>

- [ ] Safari DRM 
  - Use Chromium powered Browser or Firefox to watch Amazon Prime Video, Netflix, Disney+ and others.
- [ ] AirDrop & Continuity 
  - Only devices with Intel WiFi affected
- [ ] Fingerprint Reader 
  - Disabled with NoTouchID kext
- [ ] Sidecar Wireless
- [ ] Apple Watch Unlock
- [ ] Dualbooting Windows / Linux (with OpenCore) 
  - Theoretically this works, but the ACPI patches can make the operating system unstable.

</details>

<details>  
<summary><strong>🔄 Not tested</strong></summary>
</br>

- [ ] WWAN

</details>

&nbsp;

## ⭐️ Feedback
Did you find any bugs or just have some questions? Feel free to provide your feedback using the Discussions tab.

