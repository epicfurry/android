# Android Device Management Tools

This repository contains essential tools for managing Android devices and extracting files, without including the full device data.

## Contents

- `device/tools`: Core device management tools
- `tools/extract-utils`: Utilities for extracting files from devices
- `prebuilts/extract-tools`: Prebuilt extraction tools

## Setup

1. Initialize the repository:
```bash
repo init -u https://github.com/LineageOS/android.git -b lineage-22.2 --git-lfs -m device-tools.xml
```

2. Sync the repository:
```bash
repo sync
```

## Usage

### Device Management

The device tools provide utilities for:
- Device detection and connection
- Device state management
- Basic device operations

### File Extraction

The extract utilities help with:
- Extracting files from device images
- Managing device-specific files
- Creating device trees

## Contributing

Contributions are welcome! Please submit patches via LineageOS Gerrit.

## License

This project is licensed under the same terms as LineageOS. 