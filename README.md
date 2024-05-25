# crDroid-build-signed-script
Build script for creating signed crDroid OTA packages

## Disclaimer
This script only works for password-less keys. As the current purpose of the keys is Google shenanigans, password isn't necessary

## How to run
*Run the commands inside create_keys.txt to create your release-keys in ~/.android-certs (back up this directory to save your keys!)

*Place build-signed.sh in the root of your build environment
*Run ./build-signed.sh <device1> <device2> ...

## Known issues
<device>.json is not generated for OTA files, will fix soon
