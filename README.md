# Anytone AT-D878UVII Plus Codeplug

> [!CAUTION]
> The codeplug version, the CPS programming software version and the firmware version installed in the radio must all be from the same version.

## Table of Contents
 - [Background](#background)
 - [Features](#features)
 - [Usage](#usage)
 - [Acknowledgments](#acknowledgements)

## Background
This codeplug was started as a personal project, then added entries for the George County ARES group when they got their DMR repeater back on the air. Now the focus has been shifted to make something for the State of Mississippi ARES team. Our goal would be to add all Mississippi Counties to the codeplug.

Unofficial Mississippi Amateur Radio Emergency Services (ARES) codeplug for the Anytone AT-D878UVII Plus radio.

This codeplug is a work in progress, please reach out to me if you notice any inaccuracies or would like to add repeaters in your Mississippi County.

Mississippi ARES EC's please reach out to me and let me know how you would like your county's zone configured. This should reflect the VHF/UHF information in your ICS-205.

## Features
Mode 14 Codeplug:
 - 1295 Channels
 - 1165 Talk Groups
 - 65 Zones (so far)

Mode 7 Codeplug:
 - 1283 Channels
 - 1165 Talk Groups
 - 65 Zones (so far)

Most English language BrandMeister talk groups are included, I have just started adding talk groups from TGIF and FreeDMR networks.

 - George County zone included
 - Stone County zone is included
 - Forest County zone is in the works
 - Lamar County zone is also in the works

Did I mention that this is primarily a codeplug for the amateur's located in the state of Mississippi? But anyone is welcome to use it. Stop by the Mississippi Statewide or Lucedale talk group and say hi.

Is the frequency used on your hotspot coordinated with [SERA](https://sera.org/)? SERA has sliced out 10 simplex frequencies for hotspot use. These recommended frequencies are shared with Narrow Band FM Digital Simples users, and care should be taken to not choose a frequency already used locally. No amplifier or external antenna should be used with a hotspot, and the transmit power of the corresponding radio should be set to minimum.

|     |     |     |     |     |
| --- | --- | --- | --- | --- |
| 440.9250 | 440.9500 | 440.9750 | 441.0250 | 441.0500 |
| 441.0750 | 441.1000 | 441.1250 | 441.1500 | 441.1750 |

The simplex frequencies channelized in this codeplug are as listed in the [SERA](https://sera.org/) Frequency Utilization Plans, as the frequency coordination in Mississippi is provided by them. (Could they make their website any less user friendly?) The exception(s) to this is where specific requests by specific Emergency Coordinator's were made.

> [!Note:]
> These frequencies are for use in Mississippi, if you are traveling out of state please be aware of and avoid any possible interference with other stations. 

## Usage
Every setting in this codeplug is **Factory Default**. Please update the settings in the Optional Settings menu to suit your needs.

I've done this to provide a common starting point for everyone.

This repository hosts the codeplug for the AnyTone AT-D878UVII Plus radio. The codeplug is for:

 - CPS Version: 3.03 (Released 12/18/2023)
 - Firmware Version: 3.03

Model --> Model Information

This is an example showing Mode-14:
![](Images/Model_Information.PNG)

Use the codeplug that matches the mode that you are running. Either Mode 7 or Mode 14.

If your radio is not specifically configured for Mode 14, use the Mode 7 codeplug.

#### What??? You are not using 438.8000 in your ZumSpot?

Use your favorite text editor or spreadsheet software, search for the hotspot frequency of **438.8000** and replace it with the frequncy that you used in your hotspot. You will need to search and replace the entries in both the *channels.csv* and *zones.csv* files.
