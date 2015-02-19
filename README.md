#pymontage

Python3 video montage maker

Required packages
---
* `python3-gst-1.0`
* `python3-pil`
* `libgstreamer1.0`


Suggested packages
---
* `gstreamer1.0-plugins-{good,bad,ugly}`
* `gstreamer1.0-libav`
* `gstreamer1.0-fluendo-mp3`
* `gstreamer1.0-nice`


Usage
---

```
usage: pymontage [-h] [-o OUTPUT_DIR] [-f FORMAT] [-m MARGIN] [-w NUM_COLUMNS]
                 [-n NUM_FRAMES]
                 input

Creates a montage for a given video file

positional arguments:
  input                 Video input file

optional arguments:
  -h, --help            show this help message and exit
  -o OUTPUT_DIR, --output-dir OUTPUT_DIR
                        Output directory. Default: source directory
  -f FORMAT, --format FORMAT
                        Output image format. Default: "png"
  -m MARGIN, --margin MARGIN
                        Margin between images in pixels. Default: 3
  -w NUM_COLUMNS, --num-columns NUM_COLUMNS
                        Number of columns. Default: 4
  -n NUM_FRAMES, --num-frames NUM_FRAMES
                        Number of frames. Default: 24
```