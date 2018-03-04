# Nexus 5x 4core LineageOS

Should work basically the same for any ROM if the zip image contains a `boot.img`

[Inspiration](https://github.com/xcnathan32/4Core-Android-O-5X/commit/a4814e7e9c05e09d41ad1621f9d95f7eea409d77)

Unpacked and Repacked using [AIK](https://forum.xda-developers.com/showthread.php?t=2073775)

`boot.img` is the modified boot file

the mofidied `boot.img` can either be put back in the flashable zip file and flashed using TWRP or directly flashed using fastboot:
```bash
fastboot flash boot boot.img
```