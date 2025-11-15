# KScreenMirror

KScreenMirror is a simple Kindle → PC screen mirroring experiment.  
It captures Kindle's e‑ink framebuffer as PNG images and serves them through a lightweight HTML page that refreshes automatically.

## Screenshots

<p align="center">
  <img src="screenshots/web-interface.png" alt="Web Interface" width="400"/>
  <img src="screenshots/kindle-capture.png" alt="Kindle Capture" width="400"/>
</p>

## Features

- Capture Kindle screen every **500 ms** using `fbgrab`, while the frontend refreshes every **250 ms**
- Safe USBNet handling:
  - Warns if USBNet is not active
  - Stops USBNet automatically when capture ends

## Requirements

- Jailbroken Kindle with KUAL and USBNet installed (tested on Kindle 4 NT)
- `fbgrab` tool available on Kindle
- A computer for viewing

## Installation

Extract the [about:blank](ksm.zip) file into the Kindle’s root directory.  
When you open KUAL, the KScreenMirror menu will be shown.

## Usage

1. Open https://nullecho314.github.io/kscreenmirror/ on your computer.
2. Open KUAL and start KScreenMirror (KUAL → KScreenMirror → Start).
3. Plug Kindle into your computer.

Your Kindle screen will appear on the PC.