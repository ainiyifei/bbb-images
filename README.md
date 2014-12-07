Autoflashable BBB images
==========

-----

*Latest image available* [here](https://mega.co.nz/#!aQ8FnB4B!CpqMmZdVyOWvryxdb9Hzvo2UnL44L-0JttPRswgC6Ek).

-----

Images are meant be be flashed with a microSD card of at least 8 GB. Typical command in Mac OS:
```bash
zcat erle-debian-9-10-14.img.gz | sudo dd of=/dev/disk1 bs=8m
```
In Ubuntu:
```bash
zcat erle-debian-9-10-14.img.gz | sudo dd of=/dev/sdc bs=8M
```


| Image | Date | Size | Description |
| ----------|--------|-------|------|
|[erle-debian-1-10-2014.img.gz](https://mega.co.nz/#!HBVShJxS!mDNTey0Wb7u0ugU5nVyC4PceClTqi8nIEgeG-5Qgqsg)| 9-10-2014 | 783.2 MB | Initial image |
|[erle-debian-5-10-2014.img.gz](https://mega.co.nz/#!KcVD1ShC!TIivBvf7WoQzR2tx3Aazk1KfXHJG2_bV8TU6Dg9yrVY)| 5-10-2014 | 1.24 GB | |
|[erle-debian-9-10-14.img.gz](https://mega.co.nz/#!aQ8FnB4B!CpqMmZdVyOWvryxdb9Hzvo2UnL44L-0JttPRswgC6Ek)| 9-10-2014 | 1.25 GB | UDP sockets, scripts updated |
|[erle-9-10-14-wCodiad.img.gz](https://mega.co.nz/#!4IEQ3TKA!FME387X71z8Z3T4PSp8wZ7X2k5yW1BiI1WNipamDbIM)| 14-10-2014 | 1.96 GB | Codiad added |
|[imx6-rex-debian.tar.gz](https://mega.co.nz/#!xxIhCQAT!CYaLGScwczgFKvgvuNTTmJsX2IJlmw0RAIwPVsMFOOY)| 21-11-2014 | 221.8 MB | imx6rex board Debian image, NOT for BBB |
|[erle-debian-6-12-14.img.gz ](https://mega.co.nz/#!idlARJrb!J7dYgGT0amHCm34VH6JK5lzcc56XO_XEKDrrXV6_N4c)| 6-12-2014 | 1.34 GB | Debian, ROS Hydro, mavros, WiFi |

