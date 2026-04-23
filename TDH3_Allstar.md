# TD-H3 with AOIC Board and nicSure Firmware for AllStar

This document covers using a Tidradio TD-H3 radio with an AOIC board running nicSure firmware for AllStar linking.

The TD-H3 is ideal for an AllStar node because the nicSure firmware adds the ability to indicate COS (Carrier Operated Squelch) over one of the K1 plug pins. The AIOC (All-In-One-Cable) board can detect this signal directly, enabling reliable squelch detection without relying on audio-based methods.

## TODO

- [ ] Add section: Configuring the AIOC board
- [ ] Add section: Configuring ASL3 to work with the TD-H3 and AIOC

## Flashing and Configuring the TD-H3

### Prerequisites

1. Download the latest nicSure firmware `.bin` file: https://www.patreon.com/posts/132054141?collection=1499403
2. Download the older firmware package (contains the flashing and programming tools): https://www.patreon.com/posts/131364692?collection=1499403
3. If the radio does not appear when plugged in via USB-C, download and install the USB-C driver: https://www.wch-ic.com/downloads/CH343CDC_ZIP.html

### Flash the Firmware

4. Plug the radio in and note the COM port assigned in Device Manager.
5. Open the Programming tool from the zip downloaded in step 2.
6. Click **FLASH**.
7. Select the firmware `.bin` file downloaded in step 1.
8. Select the COM port from step 4.
9. Power the radio off, then back on while holding PTT to enter flash mode.
10. The tool will flash the firmware automatically.

### Load and Configure

11. Click **LOAD** and select the `default25.nfw` file.
12. Click **WRITE** to write the default configuration to the radio.
13. Make your desired changes:
    - Enable AllStar COS output in settings
    - Delete any channels you don't need and add the channel(s) you do need
    - Disable Dual Watch
14. Save the configuration file.
15. Click **WRITE** to write the updated configuration to the radio.
