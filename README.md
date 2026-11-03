# FPSensor local manifests

Local manifest to build LineageOS 20 for the Moto X4 (payton) on the
sdm660 4.19 kernel.

```
repo init -u https://github.com/LineageOS/android.git -b lineage-20.0 --git-lfs
git clone https://github.com/FPSensor/local_manifests .repo/local_manifests
repo sync
```
