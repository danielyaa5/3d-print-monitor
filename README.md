# Print Progress

Native 3D printer monitoring for iPhone, iPad, and Mac.

**[Download for iPhone and iPad on the App Store](https://apps.apple.com/app/id6824940843)**

[Download for Mac](https://github.com/danielyaa5/3d-printer-widget/releases/latest/download/Print-Progress.dmg) · [Website](https://danielyaa5.github.io/3d-printer-widget/) · [Support](docs/support.md) · [Privacy](docs/privacy.md)

See print progress, time remaining, the current job, layers, and available temperatures. Add multiple printers and choose which one appears in a widget. The Mac app also includes a menu bar view.

## Downloads

| Platform | Download | Requirements |
| --- | --- | --- |
| iPhone and iPad | [App Store](https://apps.apple.com/app/id6824940843) | iOS / iPadOS 17 or later |
| Mac | [Direct DMG download](https://github.com/danielyaa5/3d-printer-widget/releases/latest/download/Print-Progress.dmg) | macOS 14 or later; Apple silicon or Intel |

The Mac download remains available here while the Mac App Store version awaits approval. Open the DMG, drag Print Progress to Applications, then open the installed app. [Mac releases and checksums](https://github.com/danielyaa5/3d-printer-widget/releases/latest).

Features can differ between the App Store version and the direct Mac release.

## Supported connections

Bambu Lab LAN, Klipper / Moonraker, OctoPrint, PrusaLink, Duet / RepRapFirmware, Creality K1-series native status, and SDCP v3.

Compatibility depends on firmware and the interface your printer exposes. Bambu H2D and Creality K1 Max have been checked on hardware; other interfaces still need broader hardware testing.

## Setup

1. Connect your device to the printer's network, or a VPN that can reach it.
2. Open Print Progress, choose **Add printer**, and follow the connection walkthrough.
3. Allow Local Network access when asked.

Use **Explore the demo** to try the interface without a printer.

## Widgets

Add Print Progress from your device's widget gallery, then edit the widget to choose a printer. Apple schedules widget refreshes and may delay them. Every reading keeps its actual timestamp; open the app for a fresh update.

## Support and source

This public repository contains downloads, documentation, and the [issue tracker](https://github.com/danielyaa5/3d-printer-widget/issues). App development is maintained in a private repository.

Read the [support guide](docs/support.md) before reporting a problem. Do not include printer credentials, serial numbers, network addresses, or unredacted logs.

Print Progress is an independent app and is not affiliated with printer manufacturers.
