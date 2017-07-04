
## Setup instructions

1. `sudo apt install python-opencv`
2. `sudo pip install python-gflags six`


## Run

./main.py --webcam=0 --preview

* type `q` while the preview window is focused to exit.
* by default, recognition will be done on webcam input. Run recognition on images by passing them as command line arguments.
* `--webcam=1`: you may want to use webcam=1 if you have >1 webcam.
* `--nopreview`: will disable the preview window, if you want to test recognition speed on a corpus of images.  Abort with Ctrl-C.

## To make things move

Fill in `Recognizer.do_action`. This code is intended to run on a laptop, not a
RPi.