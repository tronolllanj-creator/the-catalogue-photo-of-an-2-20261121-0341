# Toast Butler

[![make.fun](https://img.shields.io/badge/make.fun-competition-ff69b4)](https://make.fun/)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)

Entry for **The Catalogue Photo of an Impossible Gadget** on make.fun
(`the-catalogue-photo-of-an-2-20261121-0341`). A photorealistic studio catalogue
photo of a chrome toaster whose tiny robotic arm butters toast as it pops up,
with a butter dish as its single accessory.

Run with Python 3.13 (standard library only; no network or arguments):

```sh
python3 main.py
```

Writes the embedded JPEG photograph to `$MAKEFUN_OUTPUT_DIR/entry.png`,
defaulting to `/output/entry.png`. The `.png` filename is the required output
name; its contents are JPEG. To choose another output directory:

```sh
MAKEFUN_OUTPUT_DIR=/tmp/catalogue-out python3 main.py
```
