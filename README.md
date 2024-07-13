# crDroid-build-signed-script
Script for creating a signing build environment

## Disclaimer
This script only works for password-less keys (DO NOT SET A PASSWORD) *This is due to building inline, other steps are necessary for a password*

*Works with crDroid 8.x+ or lineage19.1+*

## How to run
1. Download the script in your root build directory and run it

`wget https://raw.githubusercontent.com/306bobby-android/crDroid-build-signed-script/main/create-signed-env.sh`

`chmod +x create-signed-env.sh`

`./create-signed-env.sh`

2. Enter info for certificate subject line and confirm

3. Hit enter to set no password for each certificate. **Cannot set a password to build inline with this method!**

### Prep device tree (for other ROMs)
In your device tree (or common device tree) add:

`include vendor/lineage-priv/keys/keys.mk`

Build as usual!
