# Airwaves 3D

Internet radio for the Nintendo 3DS. Spin a 3D globe, point at a city, and listen to what is on the air there right now.

This repo holds the downloads and the daily webcam list. The source code is not here.

**[Download the latest release](../../releases/latest)**

## What it does

- **12,000 radio stations** placed on a textured globe, plus a search that reaches about 50,000 more. Plays MP3, AAC, AAC+ and HLS, and shows song titles when a station sends them.
- **A real globe.** Day and night follow the actual sun, cities light up after dark, coastlines and borders are drawn in, 20 cities have their own skyline, and it all works in stereoscopic 3D.
- **Weather** for any city, with rain, snow and thunderstorms appearing in the sky behind the globe.
- **News** headlines for the city you are looking at, with a QR code to open the full story on your phone.
- **Live webcams** from open traffic and weather cameras in London, California, Spain, Finland, Hong Kong and Singapore. Add a free Windy key for cameras worldwide, including Japan and Korea.
- **Chat** with other listeners. Everyone shows up as a small glass figure standing on the globe where they are listening. Adults only, since the chat runs on Libera.Chat.
- **Bedside mode**: a large 3D clock, a radio alarm, a sleep timer, and a screens-off mode for listening in the dark.
- **Three-band equaliser** with presets, and a listening passport that tracks your time, your most played stations and the countries you have visited.
- **Six themes**, each with a day and a night version: Aqua, Metro, Citrus, Lavender, Dark Aero and Techno Zen.

## Install

You need a 3DS with custom firmware (Luma3DS) and FBI installed. Run DSP1 once so the console can play sound.

1. On the 3DS, open **FBI**, then **Remote Install**, then **Scan QR Code**.
2. Scan the QR code on the [latest release](../../releases/latest) page.
3. Airwaves 3D appears on the HOME Menu.

That QR code always installs the newest release, so it keeps working for future versions. If you use the Homebrew Launcher instead, download `Radio3DS.3dsx`.

Installing a new version over an old one keeps your settings, favourites, stats and Windy key.

## Webcams worldwide (optional)

The cameras listed above work with no setup. For cameras in the rest of the world, Windy needs a free key of your own, which takes about two minutes:

1. In the app, open the **Cams** tab and tap **Windy key**. The guide there has a QR code for the next step.
2. Scan it with your phone, or go to https://api.windy.com/webcams
3. Tap **Get API key**, sign up for free, and create a key for the Webcams API.
4. Either tap **Type key** in the app and type it in, or put the SD card in a computer and save the key as the only line of a text file called `windy_key.txt` in `/3ds/airwaves3d/`.

The key stays on your SD card.

## Test builds

The release above is the version to use. There is also a rolling **Test build (unstable)** in the [releases list](../../releases), built from whatever I am working on at the time. It can crash or change from one day to the next, and it has its own QR code on its page. If you report a problem, please say which of the two you were running.

## Credits

Stations from radio-browser.info. Weather from Open-Meteo.com (CC BY 4.0). News from Bing News and the GDELT Project. Cameras: Powered by TfL Open Data; Caltrans; DGT (CC BY); Fintraffic / Digitraffic (CC 4.0 BY); Transport Department, HKSAR; LTA Singapore (data.gov.sg); webcams provided by windy.com. Map data from Natural Earth. AAC decoding by Helix (RealNetworks RPSL/RCSL). Image decoding by stb_image. QR codes by Nayuki's QR Code generator.

Inspired by Radio Garden.

(c) 2026 SoulJustSad. All rights reserved.
