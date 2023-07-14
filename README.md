# DL-BRAKE
## Discrete Logarithm - Biometric Resilient Authenticated Key Exchange

### Installation & Dependencies

Follow the following steps to install `BRAKE`:

```bash
git clone https://github.com/dasec/BRAKE
cd brake
./install.sh
```

You should have the following dependencies before installing `BRAKE`:

- Openssl C library, which can be easily installed on Linux with:
```bash
sudo apt install openssl #Debian based distro
sudo pacman -S openssl #Archlinux based distro
brew install openssl #MacOS
```
- C++ build tools: CMake, make, GCC...

The installation script will setup the following libraries, which are requirements:
- [thimble library](https://github.com/btams/thimble), a Fuzzy Vault implementation
- [FingerJetFX library](https://github.com/FingerJetFXOSE/FingerJetFXOSE), a Minutiae Extractor

Tested on x86-64 devices only.

### Building

Move to the `build` directory and compile the app inside:
```bash
cd build
cmake ..
make
```
 
