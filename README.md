# HackPod v2

HackPod is my small MP3 player. It is inspired by iPod shuffle. I want a tiny music thing I can carry anywhere, so I made this. I am a middle school student. This project is for learning and for fun.

This is the second generation of [HackPod](https://github.com/wenfeng110402/HackPod).

## Why I made it

- I like simple music players.
- iPod shuffle is cool and cute.
- I want to learn electronics and code.

## What it does

- A 2.1" Touch Display (v2 feature!!!)
- Dedicated Hi-Fi DAC (TI PCM5100A) + 3.5mm headphone jack.
- 6-axis IMU (QMI8658A) for motion and gestures (v2 feature!!!).
- Plays MP3 songs from a micro SD card.
- Buttons: Play/Pause, Next, Previous, Volume Up, Volume Down, and one extra "Hack" button.
- I2S audio to DAC/amp.
- USB Type-C charging with battery management.

## Parts I use

- ESP32-S3R8 (microcontroller with 8MB PSRAM)
- TI PCM5100APWR (32-bit Hi-Fi DAC)
- QMI8658A (6-axis gyro/accelerometer)
- W25Q128JVPIQ (16MB NOR Flash)
- Micro SD card slot
- 3.5mm headphone jack
- Push buttons
- Battery (lithium) with TP4055 charger
- My custom PCB (see files in `Board/`)
- 3D printed shell (see `3DSHELL/`)

## Cost & BOM

- BOM file: [`Board/BOM_Board1_PCB1_2026-11-08.csv`](Board/BOM_Board1_PCB1_2026-11-08.csv)
- Total sourcing cost (calculated with minimum order quantities): **$21.18 USD** (¥153.15 CNY)

## Project files

- Firmware: `FIRMWARE/HackPod/`
- PCB files: `Board/`
- 3D Shell: `3DSHELL/SHELL.stl`

## Status

- Hardware works.
- Firmware is simple now. I will keep improving.

## Screenshots

![sc1](image.png)
![sc2](image2.png)
![sc3](image3.png)
