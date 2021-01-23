# English Version of Readme

Manual, Release, Discussion, and Support zone for the SDB16 keyboard.

<br>

## Latest Version • 2021-01-23

[Updated] Firmware/Windows@0.5.0

[Unchanged] Null

<br>

## Manual for firmware flashing

**1** Go to [Releases](https://github.com/wangyiwei2015/SDB16/releases) and download the corresponding firmware (The type is printed on the box);

**2** Download and launch [QMK Toolbox](https://github.com/qmk/qmk_toolbox/releases/latest), and ensure that MCU is *ATmega32u4*. Then load the downloaded HEX file;

**3** Connect the SDB16 keyboard, click RST button, and wait for QMK Toolbox to identify a DFU device;

**4** Click *Clear EEPROM* to initialize the device;

**5** Click *Flash* to complete flashing;

**6** Re-connect your device and enjoy.

<br>

## Common Issues

If the device does not behave as expected, please check the followings:

- The layout of the key caps is the same as what's printed on the box
- The flashed firmware is correct
- Clear EEPROM before flashing
- There's no errors when flashing

If you have problem connecting the device, please check the followings:

- The USB driver is installed
- The USB-C cable is capable of data transfers
- The cable and connectors are functional

About USB the USB drier: ATmega32u4/Arduino Leonardo, or any compatible (on Windows, installing an Arduino IDE can solve most of the driver problems, because Arduino Leonardo has the same MCU as this product does, which contains USB features).

<br>

## Submitting Issues/Bug Report

Please go to [issues](https://github.com/wangyiwei2015/SDB16/issues) page to submit and discuss your questions.

<br>

## More

If you need more technical support or help, feel free to contact us:

CEO and Sales：[NextB](mailto://)

Design and Materials：[casteil](mailto://)

Hardware and Functions：[wyw](mailto://wangyw.dev@outlook.com)

