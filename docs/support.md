# Support

This guide is published at https://danielyakobian.com/3d-print-monitor/support/. This copy is kept for older links.

Read the [setup instructions](../README.md#setup) first. The quickest way to get help is from inside the app; no account or email app is needed.

## Report from the app

- **iPhone and iPad:** open **Settings and help → Report a problem**, or **Send feedback** for ideas.
- **Mac:** use the same items in the toolbar's **Settings and help** menu, or **Help → Report a Problem…**.
- **After adding a printer:** the app offers **Tell the Developer It Works** and **Something Looks Wrong**. A failed connection offers **Report This Problem**, even though the printer wasn't saved.

Choose whether a printer works, partly works or doesn't work, pick the printer, and tick what you checked: status, widgets, camera, or pause, resume and stop. Summary and message are optional for printer reports. You can type the printer model and firmware version, and add your email if you would like a reply.

Printer reports attach a diagnostics file, `App-diagnostics.txt`, which you can preview or turn off before sending. It never includes printer names, addresses, serial numbers, access codes, passwords, job names, camera images or logs. The [privacy policy](privacy.md#support) lists everything it contains. Nothing is sent until you tap **Send request**.

The success screen means the service accepted the request for email delivery. Keep its reference if you need to follow up. If delivery cannot be confirmed, your text stays in the open form so you can retry.

You can also email [support@danielyakobian.com](mailto:support@danielyakobian.com). If you write by email, include your app version, operating-system version, printer model, firmware version and connection type, and remove credentials, serial numbers, addresses and filenames from screenshots.

## Common problems

- **Couldn’t find a printer by that name:** use the printer’s IP address instead of its name.
- **Nothing accepted the connection on that port:** check the printer type and port number. For example, Moonraker usually uses port 7125 and the native K1 interface port 9999.
- **Self-signed HTTPS isn’t supported:** use `http://` on your local network.
- **Connected, but the status wasn’t recognized:** the printer answered in a format the app doesn’t know yet. Please send a report so it can be supported.
- **Bambu serial number rejected:** the access code was accepted but the serial number doesn’t match. Copy it again from the printer’s settings.
- **Cannot connect:** confirm the app and printer share a reachable network, Local Network permission is enabled, and the address matches the selected interface. A cloud account address is not a local printer endpoint.
- **Refresh needed:** open the app for a new reading. Widget refreshes are scheduled by the operating system and may be delayed.
- **Offline with a percentage:** the percentage is the last actual reading. Its timestamp is preserved; it is not current progress.
- **Missing temperature:** the printer did not report that sensor through this interface. A dash is deliberate.
- **Needs attention:** inspect the printer's screen or manufacturer app. 3D Print Monitor displays reported job errors and cannot diagnose or repair the printer.
- **Menu bar disappears:** quitting the Mac app stops monitoring. Close or hide its window to keep the menu bar running.
- **Certificate changed:** verify a legitimate firmware or certificate change before using the replacement-certificate option.

No printer is needed to explore the interface: use **Explore the demo** on the empty screen or in Preferences.

This is an independent project, not an official app from any printer manufacturer.
