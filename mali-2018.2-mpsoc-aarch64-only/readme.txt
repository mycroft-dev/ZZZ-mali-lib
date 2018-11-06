Mali GPU Libraries Rootfs Install for Mark2
These are copied here from Xilinx

To install for ZU2EG-based Mark2 with Mali400MP2 GPU:
- cp all files in rel-v2018.1/r8p0-01rel0/aarch64-linux-gnu/x11/usr in the corresponding location in rootfs /usr
  i.e. sudo cp -r usr/* /usr/   (or alternate choice fbdev/usr, but Mark2 requires x11)

