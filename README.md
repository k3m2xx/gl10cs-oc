# ASUS ROG GL10CS - OpenCore Configuation


[![macOS](https://img.shields.io/badge/macOS-Monterey-brightgreen.svg?logo=apple)](https://developer.apple.com/documentation/macos-release-notes)
[![macOS](https://img.shields.io/badge/macOS-Ventura-brightgreen.svg?logo=apple)](https://developer.apple.com/documentation/macos-release-notes)
[![macOS](https://img.shields.io/badge/macOS-Sonoma-brightgreen.svg?logo=apple)](https://developer.apple.com/documentation/macos-release-notes)
[![macOS](https://img.shields.io/badge/macOS-Sequoia-brightgreen.svg?logo=apple)](https://developer.apple.com/documentation/macos-release-notes)
[![OpenCore](https://img.shields.io/badge/OpenCore-1.0.0-blue.svg)](https://github.com/acidanthera/OpenCorePkg)
[![License](https://img.shields.io/badge/license-MIT-purple.svg)](/LICENSE)

<p align="center">
   <strong>Status: Maintained</strong>
   <br />
   <strong>Version: </strong>1.0
   <br />
   <a href="https://github.com/k3m2xx/gl10cs-oc/releases"><strong>Download now »</strong></a>
   <br />
   <a href="https://github.com/k3m2xx/gl10cs-oc/issues">Report Bug</a>
   ·
   <a href="https://github.com/k3m2xx/gl10cs-oc/blob/main/CHANGELOG.md">View Changelog</a>
  </p>
</p>
</br>

## ⚠️ Disclaimer
This guide is only for the ASUSTek GL10CS. I am NOT responsible for any harm you cause to your device. This guide is provided "as-is" and all steps taken are done at your own risk.

&nbsp;

## 💻 Tested devices
Some users have reported that similar ThinkPads are compatible with this OpenCore configuration. Here is a list of these devices:

- ASUSTek ROG GL10CS

## Introduction

### EFI folders

This repo includes multiple EFI configuations for different macOS Versions.

| EFI               | Description                                                               | Type      |
| ----------------- | ------------------------------------------------------------------------- | --------- |
| `EFI`             | Supports macOS Monterey, Ventura, Sonoma & Sequoia                        | `Stable`  |

<a href="https://github.com/OpenIntelWireless/HeliPort/releases"><strong>
Download HeliPort app »</strong></a>

<details>
<summary><strong>💻 My Hardware</strong></summary>
<br>
These are the Hardware component I use. But this OpenCore configuation <strong>should still work</strong> with your device, even if the components are not equal.

Check the model of your WiFi & Bluetooth card. Intel cards should be compatible with itlwm (or AirportItlwm). If your card is from another manufacturer, please check if your card supports macOS. macOS Sonoma no longer supports Broadcom Wifi cards.

| Category  | Component                            |
| --------- | ------------------------------------ |
| CPU       | Intel Core i5-9400                   |
| GPU       | NVIDIA GeForce GTX1050 2GB           |
| SSD       | Crucial SSD 512GB                    |
| Memory    | 16GB DDR4 2677Mhz                    |
| Camera    | None                                 |
| WiFi & BT | Intel AC9560   Not Working           |

</details>  

</details>

&nbsp;

## Status

<details>  
<summary><strong>✅ What's working</strong></summary>
</br>
 
- [X] USB Ports 
- [X] HDMI
- [X] Dualbooting Windows 
</details>

<details>  
<summary><strong>⚠️ What's not working</strong></summary>
</br>

- [ ] Safari DRM 
  - Use Chromium powered Browser or Firefox to watch Amazon Prime Video, Netflix, Disney+ and others.
- [ ] Intel WiFi & Bluetooth
- [ ] AirDrop & Continuity 
  - Only devices with Intel WiFi affected
- [ ] Fingerprint Reader 
  - Disabled with NoTouchID kext
- [ ] Thunderbolt 3
- [ ] Sidecar Wireless
- [ ] Apple Watch Unlock

</details>

<details>  
<summary><strong>🔄 Not tested</strong></summary>
</br>

- [ ] WWAN

</details>

&nbsp;

## ⭐️ Feedback
Did you find any bugs or just have some questions? Feel free to provide your feedback using the Discussions tab.

&nbsp;

## 📜 License

OpenCore is licensed under the [BSD 3-Clause License](https://github.com/acidanthera/OpenCorePkg/blob/master/LICENSE.txt).

<hr>
<h6 align="center">© 2024 k3m2xx. All Rights Reserved. 
<br>
By k3m2xx
</p>
