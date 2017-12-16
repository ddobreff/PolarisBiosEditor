# PolarisBiosEditor v1.6.6

For donations or other requests please contact me by email: jk@jascha-knack.de

VirusTotal Report: https://www.virustotal.com/de/file/da96cd604093c686e8b1488726ae10a43a550aea5aaba0c0f308183b86f340f3/analysis/1505395469/

0/58. If your AV warns you about a virus/trojan, consider it as false positive.

Fork from lojkinKot

works on linux with mono, executable is build against .net 3.5

one click timing feature should be used with care, it maybe not stable for you

please build the executable yourself or decompile the existing one if you don't trust

rx5xx also supported

### v1.6.6
- support for rx550 device id 0x699F

### v1.6.5
- support up to 48 entrys in the timings table (more than 2 memory vendors)

### v1.6.4
- elpida timings fixed
- K4G41325FS memory support

### v1.6.3
- timing modification starts now at 1500 instead of 1750
- device id 67FF now also supported

### v1.6.2
- experimental: ubermix timings are now also applied to 4g SAMSUNG vram (K4G41325FC, K4G41325FE)
- timing modification starts now at 1750 instead of 2000

### v1.6.1
- hynix memory H5GC8H24MJ now recognized (same timings as H5GQ8H24MJ)

### v1.6
- window resizes properly now
- memory vendor detection
- one click timing patch (samsung, hynix, elpida, micron)

### v1.5
- added FanControlMode setting
- implemented some timing editor related code (not usable yet)

### v1.4.1
- replaced WPF components with Windows Forms to archive mono compatibility

Contribution from Sebohe:

### Dependencies

Ubuntu 16.04.2:

```
sudo apt-get install mono-complete
```

Arch Linux:

```
yaourt -Sy mono48
```

### Executing

Just change your working directory to the PolarisBiosEditor and execute:

```
./run.sh
```
