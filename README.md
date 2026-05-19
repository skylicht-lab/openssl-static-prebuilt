# openssl-static-prebuilt

This repository provides automated, prebuilt static libraries for **BoringSSL** across multiple platforms. The builds are generated automatically using GitHub Actions to ensure consistency and availability.

## Supported Platforms

### Windows
- **Architectures:** x64, x86
- **Configurations:** Debug, Release
- **Artifacts:** Static libraries (`.lib`) built with Visual Studio 2022.

### Android
- **ABIs:** `armeabi-v7a`, `arm64-v8a`, `x86`, `x86_64`
- **Configurations:** Release
- **Artifacts:** Static libraries (`.a`) built with the Android NDK.

### iOS
- **SDKs:** `iphoneos`, `iphonesimulator`
- **Architectures:** `arm64`
- **Configurations:** Release
- **Artifacts:** Static libraries (`.a`)

### macOS
- **Architectures:** `arm64`
- **Configurations:** Release
- **Artifacts:** Static libraries (`.a`)

### Linux
- **Architectures:** `x64`
- **Configurations:** Release
- **Artifacts:** Static libraries (`.a`)

## Purpose
The goal of this project is to provide ready-to-use binaries for BoringSSL, allowing developers to easily integrate it into their projects without the need to set up complex build environments.
