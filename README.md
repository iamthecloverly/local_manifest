# Local Manifests for Realme 6 Series #

### Android 11 R based trees ###

```bash

# Grab Local Manifest
curl -o .repo/local_manifests/local_manifests.xml https://raw.githubusercontent.com/iamthecloverly/local_manifest/main/local_manifest.xml --create-dirs

# Sync
repo sync -j$(nproc --all) --force-sync
```
