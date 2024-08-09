# StenoWrite S1

-   Hardware Supported:
    -   StenoWrite V0.5
    -   StenoWrite V1 (Not made yet)
-   Hardware Availability: None yet
-   Using Raspberry Pi Pico W with the RP2040 chip

# Bootloader

Enter the bootloader by:

-   **Physical boot button**:
    -   First, unplug StenoWrite V1.
    -   Then press and hold the  BOOTSEL button on the Raspberry Pi Pico while you plug in the keyboard. This will make the keyboard act as a storage device on the computer.
    -   Copy and paste the .uf2 file in the top directory of the device. Once done, it will automatically reboot the keyboard.

Make examples for this keyboard (after setting up your build environment):

    qmk compile -kb stenowrite_s1 -km default

See the [build environment setup](https://docs.qmk.fm/#/getting_started_build_tools) and the [make instructions](https://docs.qmk.fm/#/getting_started_make_guide) for more information. Brand new to QMK? Start with our [Complete Newbs Guide](https://docs.qmk.fm/#/newbs).
