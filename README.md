Realme 8s 5G Device Tree - apollow
================================================================

## Specifications

Basic   | Spec Sheet
-------:|:-------------------------
CPU     | Octa-core (2x2.4 GHz Cortex-A76 & 6x2.0 GHz Cortex-A55)
Chipset | MediaTek Dimensity 810 (6 nm)
GPU     | Mali-G57 MC2
Memory  | 6/8 GB
Shipped Android Version | Android 11, realme UI 2.0 
Storage | 128 GB (UFS 2.1)
MicroSD | Up to 512 GB 
Battery | Li-Po 5000 mAh, non-removable
Dimensions | 162.5 x 74.8 x 8.8 mm (6.40 x 2.94 x 0.35 in)
Display | 1080 x 2400 pixels, 6.5" IPS LCD 90 Hz, 20:9 ratio (~405 ppi density)
Rear Camera  | Triple : 64 MP; 2MP(depth); 2MP(macro)
Front Camera | Single: 16 MP

## Building TWRP

To build:

0. Setup envirnoment
```bash
. build/envsetup.sh
```

1. Then prepare
```bash
lunch twrp_apollow-eng
```

2. Finally, make the image
```bash
m recoveryimage
```

## Locate the built image
```bash
cd $OUT
```
see **recovery.img**

Copyright (C) 2021 Team Win Recovery Project
