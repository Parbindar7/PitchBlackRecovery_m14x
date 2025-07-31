Pitch Black Recovery (UNOFFICIAL) for Samsung Galaxy m14x

Note:
The Samsung Galaxy M14 5G and F14 5G share the same device tree. Therefore, if you use the M14X device tree to build PBRP, the resulting build will also be compatible with the F14 5G.

| 📦 Device Info

    Device Codename: m14x
    Maintainer: PARBINDAR7

🛠 HOW TO BUILD

    # Initialize the latest stable branch
    repo init -u https://github.com/PitchBlackRecoveryProject/manifest_pb -b android-12.1

    # Sync the latest stable branch
    repo sync

📂 Clone Device & Common Trees

    # Clone the device tree 
    git clone https://github.com/TeamWin/android_device_samsung_m14x.git device/samsung/m14x

    # Clone the common tree 
    git clone https://github.com/TeamWin/android_device_samsung_s5e8535-common.git device/samsung/s5e8535-common

⚙️ Build

    # Set up build environment
    source build/envsetup.sh

    # Choose your device
    lunch twrp_m14x-eng

    # Start the build
    mka pbrp

⚠️ Disclaimer

This is an unofficial build. If you encounter any issues or features in the recovery that do not work as expected, please be aware that troubleshooting and fixes are your own responsibility.
