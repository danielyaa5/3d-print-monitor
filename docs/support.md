# Support

Read the [setup instructions](../README.md#setup), then email [support@danielyakobian.com](mailto:support@danielyakobian.com) if you need help. You can also [open an issue](https://github.com/danielyaa5/3d-print-monitor/issues) to report a bug or request a feature. GitHub issues are public.

In iOS version 0.5.2 and later, open **Settings and help → Preferences → Contact support** to write an email draft. It includes your message and app/system versions. Review and send it in your email app, or use **Copy email draft** to paste it into email or webmail. Nothing is sent automatically, and no printer settings, logs, or pictures are attached.

Include your app version, operating-system version, printer model, firmware version, connection type, what you expected, and what happened. Redact credentials, serial numbers, addresses, certificate fingerprints, filenames, and identifying information from screenshots and logs.

## Common problems

- **Cannot connect:** confirm the app and printer share a reachable network, Local Network permission is enabled, and the address matches the selected interface. A cloud account address is not a local printer endpoint.
- **Refresh needed:** open the app for a new reading. Widget refreshes are scheduled by the operating system and may be delayed.
- **Offline with a percentage:** the percentage is the last actual reading. Its timestamp is preserved; it is not current progress.
- **Missing temperature:** the printer did not report that sensor through this interface. A dash is deliberate.
- **Needs attention:** inspect the printer's screen or manufacturer app. Print Progress displays reported job errors and cannot diagnose or repair the printer.
- **Menu bar disappears:** quitting the Mac app stops monitoring. Close or hide its window to keep the menu bar running.
- **Certificate changed:** verify a legitimate firmware or certificate change before using the replacement-certificate option.

No printer is needed to explore the interface: use **Explore the demo** on the empty screen or in Preferences.

This is an independent project, not an official app from any printer manufacturer.
