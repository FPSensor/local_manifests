# FPSensor local manifests

Local manifest to build LineageOS 22.2 for the Moto X4 (payton) on the
sdm660 4.19 kernel.

```
repo init -u https://github.com/LineageOS/android.git -b lineage-22.2 --git-lfs
git clone -b lineage-22.2 https://github.com/FPSensor/local_manifests .repo/local_manifests
repo sync
```

The LineageOS 20 manifest lives on the `main` branch.
