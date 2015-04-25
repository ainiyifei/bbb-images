Autoflashable BBB images
==========

-----

*Latest image available*
[here](https://mega.co.nz/#!vY8GzTTQ!pRdmdNJd1-rqdSDliD8SgKuHRrTFV_NRpxtF7p34Fhw).

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
|[erle-debian-6-12-14.img.gz (no funciona) ](https://mega.co.nz/#!idlARJrb!J7dYgGT0amHCm34VH6JK5lzcc56XO_XEKDrrXV6_N4c)| 6-12-2014 | 1.34 GB | Debian, ROS Hydro, mavros, WiFi, **NO FUNCIONA**|
|[erle-debian-11-12-14.img.gz](https://mega.co.nz/#!2JdwXaZC!YFb6Ox_xAGtaIZu3TMSQVGpnbJnPuif3CpHqO7hZzcs)| 11-12-2014 | 1.34 GB | Debian, ROS Hydro, mavros, WiFi, **NO FUNCIONA**|
|[erle-debian-8-1-15.img.gz](https://mega.co.nz/#!vY8GzTTQ!pRdmdNJd1-rqdSDliD8SgKuHRrTFV_NRpxtF7p34Fhw)| 8-1-2015 | 1.34 GB | Debian, ROS Hydro (not launched at init), mavros (not launched at init), WiFi (required from the APM binary) |
|[erle-debian-bootable-4-2-15.img.gz](https://drive.google.com/file/d/0B6D4e4nVvowdLWp0QVVIckpGUEU/view)| 8-2-2015 | 1.4 GB | **microSD card bootable** Debian, ROS Hydro, mavros (launched at init), WiFi (required from the APM binary) |
|[erle-snappy-25-3-15.img.gz](https://mega.co.nz/#!uckwnSqT!f_UBsgstZXjnq2cck3M3X9qHRoD2dQbtIq1Ykp8RLFo)| 25-3-2015 | 1.59 GB | **Snappy image**, ROS, mavros and pwm nodes launched |
|[erle-debian-25-4-15.img.gz](https://mega.co.nz/#!6EcDRTZI!y-msWeHYUsTtWdLTYcq8XNIs2BWlpc8sFK5SiOB5Zlg
)| 25-4-2015 | 964.9 MB | **Debian image**, ROS and mavros |

