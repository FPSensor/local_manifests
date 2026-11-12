# FPSensor local manifests: TWRP

Local manifest to build TWRP 12.1 for the Moto X4 (payton) on the sdm660
4.19 kernel.

```
repo init -u https://github.com/minimal-manifest-twrp/platform_manifest_twrp_aosp.git -b twrp-12.1
git clone -b twrp-12.1 https://github.com/FPSensor/local_manifests .repo/local_manifests
repo sync
```

The LineageOS manifest lives in the lineage-24.0 branch.
