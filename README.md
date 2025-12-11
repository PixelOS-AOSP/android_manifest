# PixelOS

## Getting Started

To get started with the PixelOS sources, you'll need to get
familiar with [Git and Repo](https://source.android.com/setup/build/downloading).

To initialize your local repository, run:

```bash
repo init -u https://github.com/PixelOS-AOSP/android_manifest.git -b sixteen-qpr1 --git-lfs
```

Then sync up:

```bash
repo sync
```

## Building the System

Initialize the ROM environment with the envsetup.sh script.

```bash
. build/envsetup.sh
```

Lunch your device after cloning all device sources if needed.

```bash
breakfast devicecodename
```

Start compilation

```bash
m pixelos
```
