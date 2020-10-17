---
author: rverseTeam
categories:
- utility
created: '2020-04-18T01:16:12Z'
description: Miiverse clone framework, for 3DS and Wii U
download_page: https://github.com/rverseTeam/rverse-Releases/releases/tag/v3.0.0
downloads:
  rverse-3ds.7z: https://github.com/rverseTeam/rverse-Releases/releases/download/v3.0.0/rverse-3ds.7z
  rverse-3ds.zip: https://github.com/rverseTeam/rverse-Releases/releases/download/v3.0.0/rverse-3ds.zip
github: rverseTeam/rverse-Releases
image: https://avatars2.githubusercontent.com/u/38678735?v=4
layout: app
scripts:
  Latest Release:
  - file: rverse-3ds.zip
    message: Downloading the rverse package...
    output: /rverse.zip
    repo: rverseTeam/rverse-Releases
    type: downloadRelease
  - file: /rverse.zip
    input: ''
    message: Extracting rverse package... please wait.
    output: /
    type: extractFile
  - file: sdmc:/rverse.zip
    message: Deleting unneeded file.
    type: deleteFile
source: https://github.com/rverseTeam/rverse2
systems:
- 3DS
title: rverse
updated: '2020-04-18T20:45:33Z'
version: v3.0.0
version_title: Release 20200417
website: https://github.com/rverseTeam/rverse-Releases
---