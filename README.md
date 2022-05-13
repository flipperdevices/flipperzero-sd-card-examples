# flipperzero-sd-card-examples
Examples of all types of files stored on Flipper Zero SD card


## SD Card file structure

```
FLIPPER SD
├── favorites.txt # List of items displayed in Favorites
├── Manifest # Resource files list
├── badusb # Put Rubber Ducky scripts here
│   ├── demo_macos.txt  # MacOS sample script
│   └── demo_windows.txt # Windows sample script
├── dolphin
│   ├── L1_Furippa1_128x64
│   │   ├── frame_x.bm # Animation frame
│   │   └── meta.txt # Set of rules for playing frames
│   └── manifest.txt # Describes animation selection parameters
├── ibutton
│   ├── Cyfral.ibtn # Cyfral key
│   ├── Dallas.ibtn # Dallas key
│   └── Metakom.ibtn # Metakom key
├── infrared
│   ├── TV_bedroom.ir # Samsung remote
│   ├── Apple_tv.ir # Apple tv remote
│   └── assets # Signal libraries
│       └── tv.ir
├── lfrfid
│   ├── Em_marine.rfid # EM4100 sample key 
│   ├── Hid_prox.rfid # H10301 sample key EM4100
│   └── Indala.rfid # I40134 sample key
├── music_player # List of tunes to play
│   ├── Chasing.fmf # Sample tune
│   └── Marble_Machine.fmf # Sample tune
├── nfc
│   ├── Desfire.nfc # Desfire card
│   ├── Ntag_213.nfc # Ntag_213 card
│   ├── Ntag_216.nfc # Ntag_216 card
│   ├── Classik_1k.nfc # Classik_1k card
│   ├── RocketBank.nfc # Banking card
│   └── assets # NFC libraries
│       ├── aid.nfc
│       ├── country_code.nfc
│       ├── currency_code.nfc
│       └── mf_classic_dict.nfc
├── rwfiletest.bin # Creates after running SD benchmark
├── subghz
│   ├── ****.sub # Captured packet
│   ├── ****_raw.sub # Recordered raw signal
│   └── assets
│       ├── came_atomo
│       ├── keeloq_mfcodes
│       ├── keeloq_mfcodes_user
│       ├── nice_flor_s
│       ├── setting_frequency_analyzer_user
│       └── setting_user
├── u2f
│   ├── assets
│   │   ├── cert.der # Public certificate
│   │   └── cert_key.u2f # Private key
│   ├── cnt.u2f # Key counter
│   └── key.u2f # Device key
└── update
    └── f7-update-dev-29042022-0eac917f
        ├── backup.tar # Flipper configuration snapshot
        ├── flipper-z-f7-full-dev-29042022-0eac917f.dfu # Target firmware 
        ├── flipper-z-f7-updater-dev-29042022-0eac917f.bin # Updater image for RAM execution
        ├── resources.tar # Assets archive
        ├── stm32wb5x_BLE_Stack_light_fw.bin # Radio core firmware
        └── update.fuf # Update package manifest
```