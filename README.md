# BleScanner
An Android app for Bluetooth Low Energy (BLE) scanning and sniffing with location capabilities.

## Demo Videos
### [BleScanner](https://github.com/Linterz/BleScanner/releases) Sniffer Demo
https://github.com/user-attachments/assets/dc48ebd4-aade-4bbe-979b-9b88a38d97bb

### [BleMapper](https://blemapper.pages.dev) Demo
https://github.com/user-attachments/assets/8e1bb9c3-ed33-48bf-b49c-ba9616ba8554

### [Image Gallery](https://imgur.com/a/GM5GVaD)

## Features
- **Bluetooth Scanner**: Discover and scan nearby BLE devices
- **Bluetooth Sniffer**: Capture BLE traffic with location data
- **Apple Continuity Data**: Decrypts [Apple Bluetooth Protocol](https://github.com/furiousMAC/continuity) 
- **Data Export**: Export sniffed data for further analysis
- **Integration**: Seamless integration with BleMapper web tool

## Getting Started
### Scanner View (Default)
The app launches in scanner view by default, allowing you to discover nearby BLE devices.

### Sniffer View
Switch to sniffer view by tapping the **map icon** in the top bar. This mode captures BLE addresses with their data and associates it with location data.

## Data Export & Analysis
### Exporting Data
1. Navigate to **Sniffer view**
2. Tap the **gears icon** (settings)
3. Select **"Export Data as CBOR"**

### Importing to BleMapper
For advanced analysis and search capabilities, use the exported data with BleMapper:
1. Go to [BleMapper](https://blemapper.pages.dev)
2. Click **"Import Data"** button (top right)
3. Select or drag your exported CBOR file

BleMapper provides enhanced search options and controls for analyzing your BLE data.

## Installation
1. Download the [APK](https://github.com/Linterz/BleScanner/releases)
2. Grant precise location and nearby device scan permissions

## Requirements
- Android 12+
- Location permissions (for BLE scanning)
- Bluetooth permissions

## Credits
* This project is inspired by [rfparty](https://rfparty.xyz/), but I was unable to build from source, so I created my own version with quality of life improvements
* Apple Continuity data decryption based on [furiousMAC/continuity](https://github.com/furiousMAC/continuity)
