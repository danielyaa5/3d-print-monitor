# 3D Print Monitor

Native 3D printer monitoring for iPhone, iPad, and Mac.

> **Beta.** Only the Bambu Lab H2D and Creality K1 Max have been checked on real hardware so far. If you try another printer, please [report from the app](#beta-testing-and-reporting-problems) whether it works.

**[Get 3D Print Monitor on the App Store](https://apps.apple.com/app/id6824940843)**

[Website](https://danielyaa5.github.io/3d-print-monitor/) · [Support](docs/support.md) · [Privacy](docs/privacy.md)

See print progress, time remaining, the current job, layers, available temperatures and camera snapshots. Add multiple printers and choose which one appears in a widget, or show two printer cameras side by side with the Two Cameras widget. The Mac app also includes a menu bar view.

## Downloads

| Platform | Download | Requirements |
| --- | --- | --- |
| iPhone and iPad | [App Store](https://apps.apple.com/app/id6824940843) | iOS / iPadOS 17 or later |
| Mac | Joining the same [App Store](https://apps.apple.com/app/id6824940843) listing; one purchase covers both | macOS 14 or later; Apple silicon or Intel |

The app is $0.99 with no account, subscription or in-app purchases. An older notarized Mac build (0.5.1) remains on the [releases page](https://github.com/danielyaa5/3d-print-monitor/releases) and is no longer updated.

## Supported connections

Bambu Lab LAN, Klipper / Moonraker, OctoPrint, PrusaLink, Duet / RepRapFirmware, Creality K1-series native status, and SDCP v3.

Compatibility depends on firmware and the interface your printer exposes. Bambu H2D and Creality K1 Max have been checked on hardware; other interfaces still need broader hardware testing.

## Setup

1. Connect your device to the printer's network, or a VPN that can reach it.
2. Open the app, choose **Add printer**, and follow the connection walkthrough.
3. Allow Local Network access when asked.

Use **Explore the demo** to try the interface without a printer.

## Widgets

Add the app from your device's widget gallery, then edit the widget to choose a printer. Apple schedules widget refreshes and may delay them. Every reading keeps its actual timestamp; open the app for a fresh update.

## Beta testing and reporting problems

| Status | Printers and connections |
| --- | --- |
| Checked on hardware | Bambu Lab H2D (local MQTT), Creality K1 Max (Moonraker and the native K1 interface) |
| Tested with fixtures, needs real printers | OctoPrint, PrusaLink, Duet / RepRapFirmware, Elegoo SDCP v3, other Klipper and Bambu models |
| Not supported | USB-only printers without a network host, vendor cloud services, Bambu A1 / P1 direct cameras |

**Report from the app.** Open **Settings and help → Report a problem** (on Mac, also **Help → Report a Problem…**). Choose whether a printer works, partly works or doesn't work, pick the printer, and tick what you checked. No account is needed. After adding a printer, the app also offers **Tell the Developer It Works**, and a failed connection offers **Report This Problem**.

**The diagnostics file.** Printer reports attach `App-diagnostics.txt` unless you turn it off, and you can preview it before sending. It lists the app version, device model, printer type, the kind of address (for example, "http, private IPv4, port 7125"), which credentials are set, the camera setup, which readings arrived and the last error. It never includes printer names, addresses, serial numbers, access codes, passwords, job names, camera images or logs. The [privacy policy](docs/privacy.md#support) lists everything it contains.

**Good to know before testing:**

- There are no push notifications. Widgets refresh when the system schedules them, which can be many minutes apart; open the app for a live reading.
- The app talks to printers on your local network, or over a VPN that reaches them. It never uses a vendor cloud login.
- Bambu Lab controls on newer firmware need LAN Only mode with Developer Mode. Status needs only the LAN access code.

## Support and source

This public repository contains the website, documentation and older downloads. App development is maintained in a private repository.

Read the [support guide](docs/support.md) for common problems. If you contact support by email, don't include printer credentials, serial numbers, network addresses or unredacted logs.

3D Print Monitor is an independent app and is not affiliated with printer manufacturers.
