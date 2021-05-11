# Local Manifests for Realme Narzo 20A #

### Android 11 R based trees ###

```bash

# Grab Local Manifest
curl -o .repo/local_manifests/local_manifests.xml https://raw.githubusercontent.com/sarthakroy2002/local_manifest/master/local_manifest.xml --create-dirs

# Sync
repo sync -j$(nproc --all) --force-sync
```