# FaultBlog Cluster Live

## Associated Notes

EXPERIMENTAL

## Provides

### Live ISO configuration containing:
* Debian Stretch (9.6)
* NVidia Drivers (CUDA non free)
* GCC/G++
* CUDA Development Libraries
* Mono/.NET (Deep Learning)
* OpenSSH Server
* Hook for connecting to Root Node for instructions

### Kernel Settings
* Linux Firmware
* BNX2 Firmware (Targeting HP DL380 Gen 6)

## Requires

* Debian (Possibly Ubuntu) Build Host
* Live Build (live-build)

## Generating ISO

```bash
git clone https://github.com/faultblog/ClusterLive.git
cd ClusterLive
lb build
```

## Result
```bash
live-image-amd64.hybrid.iso
```
