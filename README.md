# FunkeeB Silakka54

A 54-key wired split ergonomic keyboard with a column-staggered layout, built by FunkeeB. Separate the two halves to suit your shoulders, and use layers to keep shortcuts, navigation and symbols within easy reach.

[View on Etsy](https://www.etsy.com/listing/4462598582/) · [Open Vial Web](https://vial.rocks/) · [Original Silakka54 project](https://github.com/Squalius-cephalus/silakka54)

## Getting started

1. Unplug the keyboard from USB before connecting the halves.
2. Connect the halves using a **TRRS cable** (four conductors, three black insulating rings). A TRS cable will not work.
3. Connect the left half to your computer with a USB data cable. The keyboard should be detected automatically.
4. Open a text editor and try the keys. Your operating system's keyboard language determines the characters produced by the keycodes.

> **Important:** Never connect or disconnect the TRRS cable while either half is powered. Unplug USB first to avoid a possible short circuit.

## Customize your layout with Vial

These instructions apply to the wired Silakka54 with Vial-compatible firmware.

1. Connect both halves and plug in the keyboard as described above.
2. Open [vial.rocks](https://vial.rocks/) in an up-to-date Chrome, Chromium or Edge browser.
3. Use the connection button and select your keyboard in the browser's device selection dialog. If a security unlock is requested, hold the keys shown on screen until the progress bar completes.
4. In **Keymap**, choose a layer, select a key on the diagram, then select a new key or function. Changes are normally written to the keyboard immediately.
5. Test the key in a text editor. You can also use Vial's matrix tester to check physical key presses.

### Layers

Layer 0 is usually the base layout. Additional layers can hold numbers, symbols, navigation keys and shortcuts. Assign a layer key such as **MO(1)** to temporarily activate layer 1 while held. Keep a way to reach your base layer. Your starting layout depends on the firmware installed on your keyboard.

Vial also supports macros, combos and tap dance where supported by the installed firmware. See the [Vial user manual](https://get.vial.today/manual/) for details.

### Save a backup

Use the [Vial desktop application](https://get.vial.today/) and **File → Save current layout** to keep a backup before making extensive changes or updating firmware. Firmware updates may erase your custom layout.

## Troubleshooting

- **Keyboard not detected:** Try a USB data cable, another USB port and a direct connection without a hub. Confirm the keyboard has Vial firmware. Try the [desktop Vial app](https://get.vial.today/) if the web app does not connect.
- **Only one half works:** Disconnect USB, check that the TRRS cable is fully inserted at both ends, then reconnect USB. Ensure the cable is TRRS, not TRS.
- **Vial cannot access the keyboard on Linux:** Check the [Vial Linux udev instructions](https://get.vial.today/manual/linux-udev.html), then reconnect the keyboard.
- **Wrong characters appear:** Check your operating system's keyboard language and layout. Vial assigns keycodes; the OS translates these into characters.
- **A key does not respond:** Use Vial's matrix tester to distinguish a mapping issue from a physical key issue. If your keyboard has hot-swap sockets, disconnect it before checking the switch and its pins.

## Firmware

Remapping with Vial does **not** normally require reflashing firmware. If an update is necessary, back up your layout first and follow the [original firmware instructions](https://github.com/Squalius-cephalus/silakka54/wiki/Firmware-Update) and [release notes](https://github.com/Squalius-cephalus/silakka54/releases). Check the instructions for the exact release and controller configuration before flashing either half. Flashing the wrong file may prevent the keyboard from working until corrected.

## Credits and support

Silakka54 was designed by [Squalius-cephalus](https://github.com/Squalius-cephalus/silakka54). This is an independent FunkeeB customer guide, not the original project. For questions about your FunkeeB keyboard, contact the shop through the [Etsy listing](https://www.etsy.com/listing/4462598582/).
