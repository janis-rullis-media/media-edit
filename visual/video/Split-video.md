# Split-video.md

```shell
#!/bin/bash

## 0-30 mins
ffmpeg -i file.mp4 -ss 0 -t 1800 -c copy file_1.mp4

## 30-rest
ffmpeg -i file.mp4 -ss 1800 -c copy file_2.mp4
```
