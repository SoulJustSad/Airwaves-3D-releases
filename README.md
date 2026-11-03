# Airwaves 3D

**Internet radio for the Nintendo 3DS**, with a spinning 3D globe, inspired by Radio Garden. Spin the Earth, point at a city and listen to its stations live.

This repo only holds the **downloads** (see [Releases](../../releases)) and the daily webcam list. It doesn't contain the source code.

## Features

- **12,000+ radio stations** worldwide on a textured 3D globe (with real-time day/night and stereoscopic 3D), plus online search of 50,000 more. MP3, AAC, AAC+ and HLS streams.
- **Weather** for any city (Open-Meteo), with rain, snow and storms in the sky.
- **News** headlines for the city you're looking at, with a QR code to read the full story on your phone.
- **Live webcams**: open traffic and weather cameras in London, California, Spain, Finland, Hong Kong and Singapore, plus worldwide webcams from Windy with your own free key.
- **Bedside clock, alarm, sleep timer** and screens-off listening.
- **Six themes** (Aqua, Metro, Citrus, Lavender, Dark Aero, Techno Zen), each with a day and a night look.

## Install

You need a 3DS with custom firmware (Luma3DS) and **FBI**. Run **DSP1** once so the 3DS can play sound.

1. On the 3DS, open **FBI → Remote Install → Scan QR Code**.
2. Scan the QR code on the newest [release](../../releases/latest). The `install-qr-latest.png` code always installs the newest build.
3. Airwaves 3D appears on your HOME Menu.

## Setting up Windy webcams (optional, free)

Windy has the world's largest collection of webcams (Japan, Korea, all over Europe...). Each user needs their own free key:

1. In the app, open the **Cams** tab and tap **Windy key**. It shows these steps and a QR code.
2. Scan the QR code with your phone, or go to **https://api.windy.com/webcams**.
3. Tap **Get API key**, sign up for free, and create a key for the **Webcams API**. Copy it.
4. Either tap **Type key** in the app and enter it, or put the SD card in a computer and save the key as the only line of a text file named **`windy_key.txt`** in **`/3ds/airwaves3d/`**.

The key stays on your SD card.

## Credits

Stations: radio-browser.info. Weather: Open-Meteo.com (CC BY 4.0). News: Bing News, GDELT Project. Cameras: Powered by TfL Open Data; Caltrans; DGT (CC BY); Fintraffic / Digitraffic (CC 4.0 BY); Transport Department, HKSAR; LTA Singapore (data.gov.sg); webcams provided by windy.com. Maps: Natural Earth. AAC decoding: Helix (RealNetworks RPSL/RCSL). Images: stb_image. QR codes: Nayuki's QR Code generator.

© 2026 SoulJustSad. All rights reserved.
