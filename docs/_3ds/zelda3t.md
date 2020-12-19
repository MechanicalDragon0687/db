---
author: nop90
autogen_scripts: true
categories:
- game
color: '#cac590'
created: '2017-08-17T18:53:01Z'
description: Port to 3ds of the Zelda fan game Zelda Time to Triumph
download_page: https://github.com/nop90/Zelda3T/releases/tag/v1.0
downloads:
  Zelda3T_3DSX_v1.0.zip:
    size: 28244793
    url: https://github.com/nop90/Zelda3T/releases/download/v1.0/Zelda3T_3DSX_v1.0.zip
  Zelda3T_v1.0.cia:
    size: 46773184
    url: https://github.com/nop90/Zelda3T/releases/download/v1.0/Zelda3T_v1.0.cia
github: nop90/Zelda3T
icon: https://raw.githubusercontent.com/nop90/Zelda3T/master/resources/icon.png
image: https://raw.githubusercontent.com/nop90/Zelda3T/master/resources/banner.png
layout: app
qr:
  Zelda3T_v1.0.cia: https://db.universal-team.net/assets/images/qr/zelda3t_v1.0.cia.png
scripts:
  Zelda3T.3dsx:
  - file: Zelda3T_3DSX.*\.zip
    message: Downloading Zelda3T_3DSX.zip...
    output: /Zelda3T_3DSX.zip
    repo: nop90/Zelda3T
    type: downloadRelease
  - file: /Zelda3T_3DSX.zip
    input: Zelda3T/Zelda3T.3dsx
    message: Extracting Zelda3T.3dsx...
    output: '%3DSX%/Zelda3T.3dsx'
    type: extractFile
  - file: /Zelda3T_3DSX.zip
    message: Deleting Zelda3T_3DSX.zip...
    type: deleteFile
source: https://github.com/nop90/Zelda3T
systems:
- 3DS
title: Zelda3T
update_notes: '<p><a target="_blank" rel="noopener noreferrer" href="https://user-images.githubusercontent.com/6418965/30785430-de03a4ba-a166-11e7-8ee4-c1a70f39968c.jpg"><img
  src="https://user-images.githubusercontent.com/6418965/30785430-de03a4ba-a166-11e7-8ee4-c1a70f39968c.jpg"
  alt="zelda3t_v1 0 cia" style="max-width:100%;"></a></p>

  <p>(QR code to dovnload and install the cia file with FBI)</p>'
updated: '2017-09-24T18:25:47Z'
version: v1.0
version_title: Added support for touchpad
wiki: https://github.com/nop90/Zelda3T/wiki
---