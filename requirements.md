# Requirements

## Device

- Samsung Galaxy A02
- Model: SM-A022F/DS
- Bootloader unlocked
- USB debugging enabled
- OEM unlocking enabled in Developer Options

## PC tools

- Any Windows PC that can run ADB and Odin
- Samsung USB drivers (`https://odindownload.com/samsung-usb-driver/`)
- Odin Odin 3.13.1 (`https://odindownload.com/download`)
- ADB and Fastboot platform tools (`https://developer.android.com/tools/releases/platform-tools`)
- 7-Zip or any archive tool you want.
- Fastboot driver (`https://developer.android.com/studio/run/win-usb`)

## Recommended GSI format

Use a GSI that matches your device class:

- `arm32_binder64`
- `vndklite` preferred
- `ab` build only if the image is known to work for your layout

Example:

- `system-squeak-arm32_binder64-ab-vndklite-vanilla.img`

## Files to keep as backup

- Original `boot.img`
- Patched `magisk_patched.img`
- Stock firmware package
- Working GSI image
