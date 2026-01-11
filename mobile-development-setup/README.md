# Mobile Development Environment Setup

## Introduction
This document outlines the setup process for React Native mobile development using Expo, including challenges faced and solutions.

## Tools Installed
- **Node.js**: v18.17.0 (LTS)
- **VS Code**: Version 1.85.0
- **Operating System**: Windows 11
- **Expo CLI**: Installed globally via npm

## Expo Go Installation

### Steps Followed:
1. **Android Device Setup**:
   - Visited https://expo.dev/go
   - Selected the latest SDK version (50)
   - Clicked "Install on Google Play Store"
   - Downloaded and installed Expo Go app on my Android device

2. **Initial Setup**:
   - Opened Expo Go app
   - Created a new Expo account
   - Logged in successfully
   - Scanned QR code from development server

### Challenges Faced:

1. **Network Issues**:
   - Initial connection failed due to firewall restrictions
   - **Solution**: Connected to a different network and disabled VPN

2. **QR Code Scanning**:
   - Camera had difficulty reading QR code in terminal
   - **Solution**: Used the "Send Link" feature in Expo Dev Tools to send link directly to device

3. **Android Permissions**:
   - Expo Go required location permission for certain features
   - **Solution**: Granted necessary permissions in Android settings

## Development Environment Verification

### Successful Tests:
- ✅ Expo CLI commands working
- ✅ QR code scanning functional
- ✅ Hot reload working on physical device
- ✅ Basic React Native app running on device

### Important Notes:
- Keep device and computer on the same Wi-Fi network
- Ensure Node.js is LTS version for compatibility
- Regularly update Expo Go app for latest features

# First Mobile App with Expo

## Project Setup Process

### Steps Followed:

1. **Navigate to Project Directory**:
   ```bash
   cd prodev-mobile-setup
   ```

2. **Initialize Expo Project:**
```bash
npx create-expo-app@latest .
```
- Selected blank template

- Enabled TypeScript

- Installed dependencies