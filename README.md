# rp326-usb

A rust crate for interacting with a [Rongta
RP326](https://www.rongtatech.com/rp326-80mm-thermal-printer-for-receipt-printing_p68.html)
thermal printer connected over usb. Mostly vibe-slop. I might clean this up
later to incorporate it into some other tooling.

``` bash
$ cargo binstall rp326-usb
# Pass text directly
$ rp326-usb hello from rust
# Pipe from stdout
$ cat README.md | rp326-usb
# Print an image
$ rp326-usb --image linus.jpg
```
