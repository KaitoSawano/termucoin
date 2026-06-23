# Termucoin Snap Packaging

Commands for building and uploading a Termucoin Core Snap to the Snap Store. Anyone on amd64 (x86_64), arm64 (aarch64), or i386 (i686) should be able to build it themselves with these instructions. This would pull the official Termucoin binaries from the releases page, verify them, and install them on a user's machine.

## Building Locally
```
sudo apt install snapd
sudo snap install --classic snapcraft
sudo snapcraft
```

### Installing Locally
```
snap install \*.snap --devmode
```

### To Upload to the Snap Store
```
snapcraft login
snapcraft register termucoin-core
snapcraft upload \*.snap
sudo snap install termucoin-core
```

### Usage
```
termucoin-unofficial.cli # for termucoin-cli
termucoin-unofficial.d # for termucoind
termucoin-unofficial.qt # for termucoin-qt
termucoin-unofficial.test # for test_termucoin
termucoin-unofficial.tx # for termucoin-tx
```

### Uninstalling
```
sudo snap remove termucoin-unofficial
```