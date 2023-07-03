# GNS3-VMware-M1-Mac

## Tools && Devices && Downloads
1. VMware 
2. Ubuntu iso ( live server )


## Steps I took to run GNS on my Macbook ( M1 )

1. Go to the [GNS github](https://github.com/GNS3/gns3-gui/releases/tag/v2.2.38) and download the ARM64 2.2.38 zip file && the dmg desktop application file.

2. Open VMware and select `create custom virtual machine` and select continue

3. Select Ubuntu 64-bit Arm `my version is Arm because im on Mac` choose your version for your machine and, select continue.

4. On the choose a virtual disk page select `use an existing virtual disk` and `upload the vmdk disk 1 from zip file` then `select continue`.

5. Once the disk is copied a box with selections to pick from choose hard disk and select add device in the top right corner and select existing hard disk and select add. `upload vmdk disk 2 and select apply`.

6. Once the disk is copied launch your VM and let the configuration run.

7. The next screen gives you your `login` for your `ssh and web-ui` to use in your browser

## to be continued for the configuration for the application 
