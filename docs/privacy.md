# Privacy policy

Updated November 5, 2026.

3D Print Monitor (previously Print Progress on iPhone and iPad; still Print Progress on Mac) connects directly to the printers and local servers you configure. Printer monitoring does not use a developer-operated server. The app has no account system, advertising, analytics SDK, or tracking. An optional support form uses a support relay only when you tap Send request.

## Data on your device

Printer names, addresses, serial numbers, access codes, API keys, passwords, certificate fingerprints, and cached status readings are stored in the device's Keychain. The app and its widget share access through their signed Keychain group. These records do not sync through iCloud. Walkthrough completion and appearance preferences are stored locally using the operating system's preferences system.

Status readings may include print filenames, progress, remaining time, layers, temperatures, and printer error codes. They are used to display the app and widgets. Removing a printer deletes its saved connection and cached reading from the app's storage. Information already displayed by the operating system can remain visible until its next widget refresh.

## Network access

The app sends authentication and read-only status requests to the printer address you enter. It does not send printer data to the developer or to an analytics service. It does not use a vendor cloud login. Your printer or server may separately use its manufacturer's services according to its own settings and privacy policy.

When you explicitly tap Pause, Resume, or confirm Stop, the app sends that command directly to the configured printer or server. Background monitoring and widgets never trigger these actions. Stop uses the normal job-cancel operation. Controls do not upload files, start new prints, operate a camera, or send arbitrary G-code.

HTTP and ordinary WebSocket connections are unencrypted. Use them on a trusted local network or through a secure VPN. HTTPS and Bambu TLS connections use operating-system networking and security services. Bambu certificate fingerprints are pinned after the first successful pairing.

## Permissions and diagnostics

Local Network access lets the app reach your printers. No camera, microphone, contacts, photo library, or location permission is needed.

The direct-download Mac app checks mounted disk-image metadata after launch to identify its matching installer, then asks macOS to eject that disk. It does not eject the volume it is running from or force a busy disk to unmount. This local installer cleanup sends no data to the developer. The direct-download main app runs outside App Sandbox; its widget and the App Store builds remain sandboxed.

Apple may collect crash and diagnostic information according to your operating-system settings. Development builds can write local verification reports for testing; App Store release builds disable those reports. The built-in demo uses fictional readings and makes no printer connections.

## Support

When you tap Send request in Contact support, the app sends your summary, message, optional reply email, the displayed app and operating-system versions, and a random request reference to a Cloudflare Worker. The relay forwards the request through Resend to support@danielyakobian.com. The email provider and receiving mailbox process and retain the request so the developer can respond. Cloudflare processes the connection's IP address for rate limiting. The relay stores no report bodies and has application logging disabled.

No printer settings, credentials, status readings, logs, or camera images are attached. The form shows the information being sent before submission. Support is optional and is not required to monitor printers or use widgets. A success message means the service accepted the request for email delivery; it is not a read receipt. If sending fails, the form preserves your text while it remains open. Requests are used for support, not advertising or tracking.

If you contact support by email instead, the developer receives your email address and whatever you choose to send. To ask about or request deletion of a support request, email support@danielyakobian.com and include its reference if available.

If you voluntarily submit a GitHub issue, its contents are public and subject to GitHub's privacy policy. Do not include access codes, passwords, serial numbers, addresses, certificate fingerprints, or unredacted printer logs.

For questions, use the [support page](support.md).
