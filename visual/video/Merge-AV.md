# [Merge-AV](https://superuser.com/a/277667)

```shell
ffmpeg -i DSC_0047.MOV -i DSC_0047.wav -c:v copy -c:a aac -map 0:v:0 -map 1:a:0 DSC_0047-1.MOV
```
