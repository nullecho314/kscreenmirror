# KScreenMirror

KScreenMirror is a simple Kindle → PC screen mirroring experiment.  
It captures Kindle's e‑ink framebuffer as PNG images and serves them through a lightweight HTML page that refreshes automatically.

## Features

- Capture Kindle screen every **500 ms** using `fbgrab`, frontend refreshes every **250 ms**
- Safe USBNet handling:
  - Warns if USBNet is not active
  - Stops USBNet automatically when capture ends

## Requirements

- Jailbroken Kindle with KUAL and USBNet installed. (tested on Kindle 4 NT)
- `fbgrab` tool available on Kindle
- A computer for viewing