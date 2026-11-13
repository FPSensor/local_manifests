# Local manifests

Local manifest to build LineageOS 24.0 for the Moto X4 (payton) on the
sdm660 4.19 kernel.

```
repo init -u https://github.com/LineageOS/android.git -b lineage-24.0 --git-lfs
git clone -b lineage-24.0 https://github.com/moto-sdm660/local_manifests .repo/local_manifests
repo sync
```

The TWRP manifest lives in the twrp-12.1 branch.
