# Soltech3D
This is the setup repo for Soltech's firms 3D printer, Voron v.2.4r2 300^3mm

# Getting the software for the 3D printer / The slicer
 1. Go to this page: https://www.prusa3d.com/page/prusaslicer_424/ and download the latest slicer software for your operrating system
 2. 

# Importing the Config Bundle 
1. Download the "PrusaSlicer_config_bundle.ini"
2. Go to File -> import -> Import config bundle, and find the downloaded file.
3. You are ready to go. 


## Flashing the firmware

Good Commands to remmber, after you run the make config file. Istead of useing winscp to get the file, write the following cmd in the klipper directory:
```
cp out/klipper.bin ../klipper_config/firmware.bin
```
