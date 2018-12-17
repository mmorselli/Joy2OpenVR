![language](https://img.shields.io/badge/Language-C%2B%2B-green.svg)  ![dependencies](https://img.shields.io/badge/Dependencies-SFML%202.5.0-green.svg)  ![license_gpl3](https://img.shields.io/badge/License-GPL%203.0-green.svg)
# Joy2OpenVR

Interface to [OpenVR Input Emulator](https://github.com/matzman666/OpenVR-InputEmulator) to translate any Direct Input controllers commands into VR Controller commands, used, for example, to play VR Games with Cabela TopShot Elite equipped with a Vive Trackers

# ===============================
# In order to work, you will need an old version of SteamVR that is no longer publicly distributed. To get it:

close SteamVR

open the Steam Console: steam://nav/console

write

```
download_depot 250820 250821 3421602455583112663 :(OpenVR Win32 - May 23, 2018 – 23:57:16 UTC 	7 months ago 	3421602455583112663)
download_depot 250820 250824 4898477677958363876 :(OpenVR Content - May 23, 2018 – 23:57:16 UTC 	7 months ago 	4898477677958363876)
download_depot 250820 250827 2641363748675296424 :(OpenVR Content 2 - May 3, 2018 – 18:54:29 UTC 	8 months ago 	2641363748675296424)
```

go to: 

C:\Program Files (x86)\Steam\steamapps\common\

rename actual SteamVR folder (i.e. SteamVR.org )

create new empty SteamVR folder

put the contents of the 3 downloaded folders (depot_250821, depot_250824, depot_250827) into new empty SteamVR Folder

restart SteamVR and check the version (should be v1527117754 )

save the downloaded folders, in case Steam auto updates SteamVR

# ===============================


# Usage

1. Download the newest .zip from the [release section](https://github.com/mmorselli/Joy2OpenVR/releases) and unzip it
2. open config.ini in a text editor and configure
3. execute Joy2OpenVR.exe

To use alternative config files use:

```
Joy2OpenVR.exe  filename.ini
```

![alt screenshot](https://github.com/mmorselli/Joy2OpenVR/blob/master/assets/screenshot.png)


# Building
1. Open *'Joy2OpenVR.sln'* in Visual Studio 2017.
2. Build Solution

# License

This software is released under GPL 3.0.
