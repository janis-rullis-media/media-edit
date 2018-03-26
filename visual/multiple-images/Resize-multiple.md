# Resize multiple / Batch resize

* [How can I scale all images in a folder to the same width?](https://askubuntu.com/a/135489)
* [How to batch resize images in Ubuntu recursively within the terminal?](https://stackoverflow.com/a/10802693)

## With imagemagick

### Affects only images in the curent directory

Will not enlarge if is smaller than the resize value.

```shell
convert "*.png[250x>]" -set filename:base "%[base]" "%[filename:base]-250x.png"
```

### [res](https://github.com/janis-rullis/shell-scripts/blob/master/res.sh) - Affects images in all directories below

```shell
res
```