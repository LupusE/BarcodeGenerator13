# BarcodeGenerator13

This is my try to add EAN-13 support to the Barcode Generator Plugin for the Flipper Zero.
Based on https://github.com/McAzzaMan/flipperzero-firmware/tree/UPC-A_Barcode_Generator/applications/barcode_generator

The Main issue is the backwards compatibblity to UPC-A ... Maybe I'll start over and write a EAN-13-only Barcode Generator first.

## HowTo

Put in your Flipper folder, in `...\flipper-firmware\applications\plugins\BarcodeGenerator13\`

Compile in `..\flipper-firmware\` with the command `./fbt fap_Barcode_Generator13` (./ftb fap_[AppID from application.fam])
See also https://github.com/flipperdevices/flipperzero-firmware/blob/dev/documentation/fbt.md

Copy the created plugin to your Flipper Zero.
