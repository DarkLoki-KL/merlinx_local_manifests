# merlinx_local_manifests

### LineageOS S ###

Required patches for IMS: https://gerrit.pixelexperience.org/q/topic:%22mediatek-ims%22+(status:open%20OR%20status:merged)

```bash

# Grab Local Manifest
curl -o .repo/local_manifests/local_manifests.xml https://raw.githubusercontent.com/Redmi-MT6768/local_manifests/master/twelve.xml --create-dirs

# Sync
repo sync -j$(nproc --all) --force-sync
```
