# Privacy Policy — Lanvio

**Last updated:** October 1, 2026

## Introduction

Lanvio ("the App") is a speed test for your local network (LAN and Wi-Fi), developed by EgeaINC. This Privacy Policy explains how we handle information when you use the App.

## Your Test Results Stay on Your Devices

**EgeaINC does not collect, store, or receive your test results or anything about your network.** Everything the App measures stays on your devices.

The App stores the following data **locally on the device where it is installed**:
- **Test results:** download and upload speed, ping, jitter, packet loss, bufferbloat grade, latency at rest and under load, and the date and time of each test.
- **The device that ran each test:** when another device on your network tests against the phone or tablet running Lanvio as a server, the App keeps that device's local IP address and a short name derived from its browser (for example "Chrome · Windows"), so you can tell your tests apart in the history.
- **Wi-Fi network name:** only if you allow it (see "Location permission" below), the name of the Wi-Fi network each test ran on.
- **Servers:** Lanvio servers you added or that were found on your network.
- **Preferences:** language, test duration, number of parallel connections, server port and similar settings.

This data never leaves your devices unless you export or share it yourself (for example, a CSV export or a result image), and it is deleted when you uninstall the App or clear its data.

## How Tests Work

Lanvio turns your phone or tablet into a test server on your own network. Other devices (a computer, another phone, a tablet) open the address shown by the App in their browser, or use the Lanvio app, and the test runs between those devices over your local network. Test traffic and results travel only between your own devices on that network. No test traffic goes to EgeaINC servers or to any other server on the internet.

## Advertising

The free version of the App shows ads provided by **Google AdMob**, on the Server and History screens. Users with Lanvio Pro do not see ads, and the App does not start the ads service for them. The test page that other devices open in their browser never shows ads.

To show and measure ads, Google AdMob may collect and process:
- The device's advertising ID
- Approximate location derived from the IP address
- Device and app information (model, operating system, language, app version)
- Ad interactions (impressions and taps)

This data is collected and processed by Google under its own policies, not by EgeaINC. Your test results, your network details and the devices you test are never shared with AdMob.

- How Google uses information from apps that use its services: https://policies.google.com/technologies/partner-sites
- Google Privacy Policy: https://policies.google.com/privacy

**Your choices:**
- You can reset or delete your advertising ID, or opt out of personalized ads, in your device settings (Settings → Google → Ads, or Settings → Privacy → Ads, depending on the device).
- In the European Economic Area, the United Kingdom and Switzerland, the App asks for your consent before showing personalized ads, and you can change your choice at any time in Settings → Ad privacy.
- Lanvio Pro, a one-time purchase, removes all ads.

## Location Permission

Android only lets apps read the name of the Wi-Fi network you are connected to if they hold the location permission. Lanvio asks for it once, with an explanation, the first time you start the server, and uses it **only to read the Wi-Fi network name** shown in the history. The App does not read your GPS position, does not store your location and does not send it anywhere. You can decline it: everything else keeps working, only the Wi-Fi name is not shown.

## Notifications

While the server is running, the App shows a notification with its address, the test in progress and the last result, and a button to stop it. It is shown only on your device.

## Internet Usage

Apart from the tests on your local network, the App connects to the internet for:

1. **In-app purchases:** Processed entirely through Google Play Billing. When the App opens, it asks Google Play whether you own Lanvio Pro, so a reinstall or a new device keeps it. We do not have access to your payment information. Google's privacy policy applies to these transactions.
2. **Ads (free version only):** Loading ads from Google AdMob, as described above.

## Permissions

The App requests the following Android permissions:
- **Internet and network state:** Required to run the tests on your local network, for in-app purchases and for ads in the free version.
- **Wi-Fi state and multicast:** Used to show the Wi-Fi link (band, signal, link speed) and to find other Lanvio servers on your network.
- **Location (optional):** Used only to read the Wi-Fi network name, as described above.
- **Notifications:** Used to show the running server in the notification shade.
- **Foreground service (connected device) and wake lock:** Required to keep the server answering tests from your other devices while the screen is off or the App is in the background.
- **Advertising ID:** Used by Google AdMob to show ads in the free version.
- **Billing:** Used to buy Lanvio Pro through Google Play.

## Children's Privacy

The App is a network tool intended for adults. It is not directed at children and does not knowingly collect information from children.

## Changes to This Policy

We may update this Privacy Policy from time to time. Changes will be posted on this page with an updated revision date.

## Contact

If you have questions about this Privacy Policy, please open an issue at:
https://github.com/gabriel600r/lanvio-feedback/issues

or write to gabriel600r@gmail.com.

---

*Lanvio — LAN Speed Test by EgeaINC*
