# Anytone AT-D878UVII Plus Codeplug

> [!CAUTION]
> Codeplug version, CPS programming software version and firmware version installed in the radio must all be from the same version.

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

The simplex frequencies channelized in this codeplug are as listed in the [SERA](https://sera.org/) Frequency Utilization Plans, as the frequency coordination in Mississippi is provided by them. (Could they make their website any less user friendly?) The exception(s) to this is where specific requests by specific Emergency Coordinator's were made.

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

If your radio is not configured for Mode 14, use the Mode 7 codeplug.

#### What??? You are not using 438.8000 in your ZumSpot?

Use your favorite text editor or spreadsheet software, search for the hotspot frequency of **438.8000** and replace it with the frequncy that you used in your hotspot. You will need to search and replace the entries in both the *channels.csv* and *zones.csv* files.

## Acknowledgments
Thanks to [KC5DJR](https://docs.google.com/spreadsheets/d/1748U_gqH5I_LlhYrRuc8aT72tSeO-dq3/edit?rtpof=true&sd=true#gid=1402313308) for his exhaustive work in documenting the BrandMeister talk groups. He has [his own codeplugs](https://www.qsl.net/kc5djr/DMR%20Super%20USA%20Codeplug.html) too. If you don't like this one, you may like his.
