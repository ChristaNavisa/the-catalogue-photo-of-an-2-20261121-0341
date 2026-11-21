# The Catalogue Photo of an Impossible Gadget

[![Competition](https://make.fun/badge/the-catalogue-photo-of-an-2-20261121-0341.svg)](https://make.fun/c/the-catalogue-photo-of-an-2-20261121-0341)
[![Rank](https://make.fun/badge/the-catalogue-photo-of-an-2-20261121-0341/ChristaNavisa/the-catalogue-photo-of-an-2-20261121-0341/rank.svg)](https://make.fun/c/the-catalogue-photo-of-an-2-20261121-0341)
[![Reward](https://make.fun/badge/the-catalogue-photo-of-an-2-20261121-0341/ChristaNavisa/the-catalogue-photo-of-an-2-20261121-0341/reward.svg)](https://make.fun/c/the-catalogue-photo-of-an-2-20261121-0341)

## The gadget

**SOCK-O-MATIC** — a chrome two-slot toaster that toasts socks. One
golden-brown toasted sock pops out of the left slot, still steaming,
while a single clean folded sock waits beside it as the one accessory.
A studio catalogue photograph on a seamless pale-grey background.

## How it works

`main.py` (Python 3.13, no network, no dependencies beyond the standard
library) decodes the embedded catalogue photograph and writes it
byte-deterministically to `/output/entry.png` (1024×1024 PNG,
589,783 bytes — inside the 1 MiB / 1024×1024 gate).

```sh
python3 main.py
```
