# Stream Temps 
![Logo](./stream_temps/images/logo_120x120.png "Logo")

Let your viewers know that you are sweating

## Requirements

 * Raspberry Pi 2, 3, or 4 with Raspberry Pi OS. You can find the setup video [here](https://www.youtube.com/watch?v=NAqBgF0swYo).
 * DHT-22 Sensor
 * Python Version `3.7.3+` installed

## Setup
### Hardware

TODO fritzing image

### Bundle with PyInstaller

Bundling has to take place on a Raspberry Pi

```bash
python3 -m pip install pyinstaller
python3 -m PyInstaller stream_temps.spec
```

### Command Line

```bash
python3 -m pip install -r requirements.txt
python3 stream_temps.py
```

## Credits
![K0nze Logo](./stream_temps/images/k_logo_30x30.png "Logo") Created by Konstantin (Konze) Lübeck

 * Discord: [discord.k0nze.gg](https://discord.k0nze.org) 
 * Twitch: [twitch.tv/k0nze](https://twitch.tv/k0nze) 
 * Youtube: [youtube.com/k0nze](https://youtube.com/k0nze) 
 * Twitter: [twitter.com/k0nze_gg](https://twitter.com/k0nze_gg) 
 * Instagram: [instagram.com/k0nze.gg](https://instagram.com/k0nze.gg) 
