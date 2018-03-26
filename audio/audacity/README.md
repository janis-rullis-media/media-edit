# Audacity

## Fade out

Effect -> Fade Out.

## [Reduce size](https://www.churchbuzz.org/2015/how-to-compress-audio-files/)

* Ctrl + Shift + E - File -> Export -> Export as MP3
* Select a lower quality.

In my case, it reduced from 20 MB to 8 MB.

## Crop

Just mark the redundant part, delete it and export the rest.

## Add silence at the beginning

Click at the begining of the track.
Alt + G / Silence.

## Setup

* [omgubuntu: install-audacity-2-2-0-on-ubuntu](https://www.omgubuntu.co.uk/2017/11/install-audacity-2-2-0-on-ubuntu).

```bash
sudo add-apt-repository ppa:ubuntuhandbook1/audacity -y
sudo apt update && sudo apt install audacity -y
```

## Enable dark theme

Edit -> Preferences -> Interface -> Theme -> Dark.

## Open file from terminal

```bash
audacity audio.mp3
```