# Lanvio — Privacy Policy

**Effective date:** 2026-05-10
**App:** Lanvio (com.egeainc.lanvio)
**Developer:** EgeaINC — Gabriel Egea
**Contact:** gabriel600r@gmail.com

## Summary

Lanvio is a LAN speed test app. It does not collect, transmit, or share personal data with any external server controlled by us or by third parties. All measurements happen between devices on your local network.

## Data we DO NOT collect

- We do not collect your name, email, phone number, or any identifier.
- We do not have user accounts or logins.
- We do not collect your precise or approximate location for analytics, marketing or any commercial purpose.
- We do not show ads.
- We do not use third-party analytics, crash reporting or tracking SDKs.
- We do not transmit your measurements to any server controlled by us.

## Data the app uses locally on your device

- **Speed test results**: download/upload throughput, latency, jitter, packet loss, bufferbloat grade, timestamp, WiFi SSID and the server endpoint you tested against. Stored only in the app's local database on your device. Never leaves the device unless you explicitly use the Share feature to send a result yourself.
- **Server list and favorites**: hosts and ports you have manually added or auto-discovered on your LAN. Stored locally.
- **Settings**: your preferred language, theme, parallelism and test duration. Stored locally.

You can delete this data at any time by clearing app storage or by uninstalling the app.

## Network communication

Lanvio communicates only with:

1. Lanvio servers running on **your own local network**, that you choose to test against (either another device with the Lanvio app in server mode, or any compatible Lanvio-protocol server you set up yourself).
2. The Android operating system, for WiFi link info, network state, mDNS discovery and notifications.

No outbound connection is made to EgeaINC servers or any third-party server during normal operation.

## Permissions

- `INTERNET` and `ACCESS_NETWORK_STATE`: required to talk to LAN servers.
- `ACCESS_WIFI_STATE` and `CHANGE_WIFI_MULTICAST_STATE`: required for WiFi link info (SSID, link speed, frequency) and for mDNS discovery on the local network.
- `ACCESS_FINE_LOCATION`: requested by Android to expose WiFi SSID/BSSID. We do not read or transmit your GPS coordinates.
- `POST_NOTIFICATIONS`, `WAKE_LOCK`, `FOREGROUND_SERVICE`, `FOREGROUND_SERVICE_DATA_SYNC`: required so the in-app server mode stays alive while running and shows a status notification.

## Children's privacy

Lanvio is not directed at children under 13. It does not knowingly collect any data from anyone.

## Changes to this policy

If this policy ever changes, the new version will be published at this URL and the "Effective date" above will be updated.

## Contact

For questions about this policy, open an issue at https://github.com/gabriel600r/lanvio-feedback or write to gabriel600r@gmail.com.
