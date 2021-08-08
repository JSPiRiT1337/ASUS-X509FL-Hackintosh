# ASUS X509FL Hackintosh
ASUS X509FL Hackintosh - macOS Monterey OpenCore EFI

# Configuration

## Specifications:

Computer model：ASUS X509FL

Processor：Intel Core i5-8265U Processor（Whiskey Lake）

Memory：8GB Samsung DDR4 2400MHz

Hard Disk：256GB SSD

Integrated Graphics：Intel UHD Graphics 620

Monitor：AUO21ED FHD 1920x1080 (15.6 inch)

Sound Card：Realtek ALC256 (layout-id:66)

Wireless Card：Realtek 8821CE Wireless LAN 802.11ac（Replaced with Intel AX200 Wireless）

## Non-working:

- d-GPU (Nvidia MX250)

- Trackpad（GPIO interrupt mode）

「Trackpad polling mode is working properly」

- Realtek 8821CE Wireless LAN 802.11ac

- Micro-SD Card USB Reader 

## Attention Points

The ELAN1200 touchpad on this machine cannot work normally. It will stop working randomly in macOS, although it will be restored after waking up the machine a few minutes after the machine goes to sleep. But this problem can't be solved after I try to study it.
#### Therefore, when using the machine, be sure to carry the mouse with you to avoid unnecessary trouble caused by using only the touch pad.

See the link for details

https://github.com/VoodooI2C/VoodooI2C/issues/321

## Untested availability:

- None

## Maintainer

© [Miracle樱乃.](https://github.com/Miracle-Sakuno), Released under the [MIT License](./LICENSE) .<br>
Authored and maintained by Miracle樱乃. with help from contributors ([list](https://github.com/Miracle-Sakuno/Asus-VivoBook-X509FB-Hackintosh/graphs/contributors)).

Tested with ASUS X509FL by [JSPiRiT](https://github.com/JSPiRiT1337/)
