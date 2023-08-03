# CLO Rom

## Getting started

To sync and build CLO Rom, Android R:
```
repo init -u git://github.com/SonicBSV/platform_manifest.git -b r
```
Then to sync up:
```
repo sync -c --no-tags --no-clone-bundle -j$(nproc --all)
```

## Devices

CLO Rom is designed for ASUS Zenfone Max Pro M1, sdm660.
