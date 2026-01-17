# Xin's GW2 Sharpness Shader

![GitHub repo size](https://img.shields.io/github/repo-size/Xinterp6196/Xin-s-GW2-Sharpness-Shader?logo=thunderstore&logoColor=white&label=Repo%20Size&color=green)
![GitHub commit activity](https://img.shields.io/github/commit-activity/m/Xinterp6196/Xin-s-GW2-Sharpness-Shader?logo=github&label=Commits%3A&color=green)
![GitHub last commit](https://img.shields.io/github/last-commit/Xinterp6196/Xin-s-GW2-Sharpness-Shader?display_timestamp=author&logo=githubactions&logoColor=white&label=Latest%20Commit)
[![Github All Releases](https://img.shields.io/github/downloads/Xinterp6196/Xin-s-GW2-Sharpness-Shader/total.svg)]()

## Description

Guild Wars 2 Shader for ReShade.
Anything updates to the shader will be updated as I see fit moving forward.

If you do not like the color correction to make the game feel more "Mature" or "Washed Out", once installed, hit Home, then uncheck "Tonemap".
<img width="889" height="161" alt="image" src="https://github.com/user-attachments/assets/099fedf5-1f34-4bac-aec1-012fd6cefe3a" />

## Installation

1. Login to GW2 and change Post Processing to FXAA, then exit game.
2. Download the [Sharpness Shader](https://github.com/Xinterp6196/Xin-s-GW2-Sharpness-Shader/archive/refs/heads/main.zip)
3. Unzip the Sharpness Shader wherever you see fit and open this folder. (Do not close this folder, you will need it open for step 5)
4. Install [ReShade](https://reshade.me/)
    1. Download without addons
    2. Browse to GW2 Directory and select Gw2-64.exe - Default is "C:\Program Files\Guild Wars 2"
    3. Select DX 10/11/12
    4. Hit Browse, then navigate to where you unzipped the Shader at
    5. Select "XIN_GW2_HighSharpColorCorrect.ini"
    6. Hit "Finish"
5. Migrate updated dxgi.dll to GW2 Root
    1. Open a new file explorer and browse to GW2 Directory and select Gw2-64.exe - Default is "C:\Program Files\Guild Wars 2"
    2. Copy and Paste the "dxgi.dll" into the folder containing "Gw2-64.exe"
    3. Close both the GW2 Directory and your Shader Folder.
6. Run GW2 through whatever means you normally would run it with, either with Nexus, Blish, or through default means.

## 📜 Changelog

See what's new in the [CHANGELOG.md](CHANGELOG.md).

## Photos - Without and With Shader
(Please ignore FishingBuddy, Event Timers, and Combat Rings. These are a part of my BlishUI setup and are not part of the shader)

Without Shader
<img width="2557" height="1076" alt="image" src="https://github.com/user-attachments/assets/a4e690c9-4f9a-45e0-888e-36efdd62857b" />
<img width="2559" height="1078" alt="image" src="https://github.com/user-attachments/assets/e02542a9-e489-4389-a842-16af239f3e51" />
<img width="2558" height="1078" alt="image" src="https://github.com/user-attachments/assets/c4640067-1f06-4ca5-82f5-3337ba43e74f" />

With Shader
<img width="2557" height="1078" alt="image" src="https://github.com/user-attachments/assets/fd39e495-b26b-4a17-9cde-9eeeee071c09" />
<img width="2558" height="1077" alt="image" src="https://github.com/user-attachments/assets/6b03a3c3-d6a8-4c10-a893-6f1ba7fe4fb8" />
<img width="2558" height="1078" alt="image" src="https://github.com/user-attachments/assets/babe96f1-6659-495f-84dc-93a25331a832" />
