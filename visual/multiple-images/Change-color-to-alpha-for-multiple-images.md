# Change color to alpha for multiple images

* [Batch replacing color with transparency](https://graphicdesign.stackexchange.com/a/16125).
* [ImageMagick Replace a Specific Color](http://www.imagemagick.org/Usage/color_basics/#replace).

```bash
convert anim.gif -fuzz 60% -transparent 'lime' balloon_trans.gif
```
