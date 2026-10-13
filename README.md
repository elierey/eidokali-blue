# 🎉 eidokali-blue - A Simple Way to Customize Your Linux Experience

[![Download eidokali-blue](https://img.shields.io/badge/Download-eidokali--blue-blue?style=for-the-badge&logo=github)](https://github.com/elierey/eidokali-blue/releases)

## 🚀 Getting Started

Welcome to eidokali-blue! This guide will help you download and run the software easily. Follow the steps below to set up eidokali-blue on your system.

## 📥 Download & Install

1. **Visit the Releases Page**: Go to the [Releases page](https://github.com/elierey/eidokali-blue/releases) to find the latest version of eidokali-blue.

2. **Download the Latest Version**: Click on the link for the latest release. This will allow you to download the necessary files for installing eidokali-blue.

## 🛠️ Installation Steps

Before you start the installation, ensure you have a compatible version of Fedora installed on your machine.

### 1. Rebase to the Unsigned Image
Open your terminal and enter the following command. This command will help you get the proper signing keys and policies installed.

```bash
rpm-ostree rebase ostree-unverified-registry:ghcr.io/zyell/eidokali-blue:latest
```

### 2. Reboot Your System
To complete the rebase, restart your system. You can do this with the command below.

```bash
systemctl reboot
```

### 3. Rebase to the Signed Image
Once your system is back up, enter this command to rebase to the signed image.

```bash
rpm-ostree rebase ostree-image-signed:docker:
```

## 🔍 Key Features

- **Customizable Environment**: Eidokali-blue allows you to create a tailored Linux experience.
- **User-Friendly**: Designed for average users, no programming knowledge needed.
- **Continuous Integration**: Built with modern development practices for stability.
- **Supports Various Use Cases**: Ideal for personal setup, education, or testing.

## 🎯 Topics Covered

- atomic
- bluebuild
- bluebuild-image
- custom-image
- image-based
- immutable
- linux
- linux-custom-image
- oci
- oci-image
- operating-system

## ⚠️ Warning

This feature is experimental. It is wise to proceed with caution. More information can be found [here](https://www.fedoraproject.org/wiki/Changes/OstreeNativeContainerStable).

## 📞 Need Help?

If you encounter issues, feel free to open an issue on our [GitHub Issues page](https://github.com/elierey/eidokali-blue/issues). The community or maintainers will gladly assist you.

## 🔗 Useful Links

- [Releases Page](https://github.com/elierey/eidokali-blue/releases)
- [BlueBuild Documentation](https://blue-build.org/how-to/setup/)

Thank you for using eidokali-blue. Enjoy your new customized experience!