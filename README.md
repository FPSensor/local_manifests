# Local manifests: crDroid

Local manifest to build crDroid 17.0 for the Moto X4 (payton) on the sdm660
4.19 kernel.

```
repo init -u https://github.com/crdroidandroid/android.git -b 17.0 --git-lfs
git clone -b 17.0 https://github.com/moto-sdm660/local_manifests .repo/local_manifests
repo sync
```

The LineageOS manifest lives in the lineage-24.0 branch, and the TWRP one in
twrp-12.1.
