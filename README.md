# flipperzero-sd-card-examples
Examples of all types of files stored on Flipper Zero SD card


## SD Card file structure

```
FLIPPER SD
├── favorites.txt # List of items displayed in Favorites
├── Manifest
├── badusb # Put Rubber Ducky scripts here
│   ├── demo_macos.txt 
│   └── demo_windows.txt 
├── dolphin
│   ├── L1_Furippa1_128x64
│   │   ├── frame_x.bm # Animation frame
│   │   └── meta.txt # Set of rules for playing frames
│   └── manifest.txt # Describes animation selection parameters
├── ibutton
│   └── Flipper_home.ibtn
├── infrared
│   ├── TV_bedroom.ir
│   └── assets # Signal libraries
│       └── tv.ir
├── lfrfid
│   ├── Home_entry.rfid
│   └── Visitor_pass.rfid
├── music_player # List of tunes to play
│   ├── Chasing.fmf
│   └── Marble_Machine.fmf
├── nfc
│   ├── Desfire.nfc
│   ├── Ntag_213.nfc
│   ├── RocketBank.nfc
│   └── assets
│       ├── aid.nfc
│       ├── country_code.nfc
│       ├── currency_code.nfc
│       └── mf_classic_dict.nfc
├── rwfiletest.bin # Creates after running SD benchmark
├── subghz
│   ├── PC_Led_color.sub # Captured packet
│   ├── Hall_Lights_off.sub # Recordered raw signal
│   └── assets
│       ├── came_atomo
│       ├── keeloq_mfcodes
│       ├── keeloq_mfcodes_user
│       ├── nice_flor_s
│       ├── setting_frequency_analyzer_user
│       └── setting_user
├── u2f
│   ├── assets
│   │   ├── cert.der
│   │   └── cert_key.u2f
│   ├── cnt.u2f # Key counter
│   └── key.u2f # Device key
└── update
    └── f7-update-dev-29042022-0eac917f
        ├── backup.tar
        ├── flipper-z-f7-full-dev-29042022-0eac917f.dfu
        ├── flipper-z-f7-updater-dev-29042022-0eac917f.bin
        ├── resources.tar
        ├── stm32wb5x_BLE_Stack_light_fw.bin
        └── update.fuf
```