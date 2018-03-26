# Crop video

## GUI

[Download Shtocut](https://www.shotcutapp.com/download/)

```bash
sudo apt install libsdl2-2.0-0
```

Open Shotcut

Add filters -> Rotate

## CLI

```bash
sudo apt install ffmpeg
ffmpeg -i 2.mp4 -vf "crop=300:200" 2-crop.mp4
```
