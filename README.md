# Privacy Policy

Last Updated: August 15, 2026

## Overview

MapSwap ("the App") is a Safari Web Extension and iOS app that detects street addresses on webpages and makes them tappable to open in your preferred map app. Your privacy is important to us. This policy explains what data the App does and does not access.

## Data Collection

MapSwap does not collect any data. Specifically:

- No personal information is collected, stored, or transmitted.
- No browsing history is tracked or recorded.
- No webpage content is sent to any server.
- No passwords, cookies, or credentials are accessed.
- No analytics or tracking of any kind is used.
- We do not send your data to any analytics or advertising services. The only exception is your own choice of map app: if you select Google Maps or Waze, tapping an address opens that provider's website with the address you tapped (see "Opening Addresses in a Map App" below).
- No advertising identifiers are accessed.

## How the Extension Works

The extension runs entirely on your device. It:

- Scans the visible text on webpages to find patterns that match street addresses.
- Highlights detected addresses and makes them tappable links.
- Opens tapped addresses in your preferred map app (Apple Maps, Google Maps, or Waze).

All processing happens locally in Safari on your device. No webpage content, addresses, or browsing data is ever transmitted off your device by the App itself.

## Opening Addresses in a Map App

When you tap a highlighted address, the App opens it in the map app you selected:

- **Apple Maps** — opened through a local iOS URL scheme; the address stays on your device.
- **Google Maps or Waze** — opened by launching that provider's URL with the address as the search query. This means the address you tapped is sent to Google or Waze at that moment, solely to show you directions. This only happens when you tap, and only for the provider you chose. Their handling of that request is governed by their own privacy policies.

The App never sends addresses anywhere on its own — only the single address you tap, only to the map provider you selected.

## How the Share Extension Works

The MapSwap Share Extension lets you share an address or map link from any app to open it in your preferred map app. When you use it:

- The shared text or URL is read directly from the iOS share sheet.
- An address is extracted locally on your device.
- **Shortened map links:** if you share a shortened Google Maps link (for example, `goo.gl/maps` or `maps.app.goo.gl`), the App sends a network request to that link so it can be expanded to the full address. This request goes to the link's host (Google). It is the only time the Share Extension uses the network, it happens only for shortened links you explicitly share, and only the shortened link itself is sent.
- The extracted address is passed to your preferred map app via a URL scheme (see "Opening Addresses in a Map App" above for how Apple Maps, Google Maps, and Waze differ).
- To hand the address to the app, it is briefly stored in App Group storage on your device. It is not logged, and — apart from the shortened-link expansion described above — it is not transmitted anywhere except to the map app you've chosen.

## Data Stored on Your Device

The only data stored on your device is:

- Your preferred map app selection (Apple Maps, Google Maps, or Waze)
- App open count (used internally to time the optional review prompt)
- Review-prompt flag (so we don't ask twice)
- Address-tap count (used internally to time the optional tip prompt)

This data is stored using Safari extension storage and App Group shared storage, and never leaves your device.

## Webpage Access Permission

Safari requires the "All Websites" permission for the extension to scan pages for addresses. This permission is used solely to read page text and identify addresses. The extension does not modify webpage content beyond visually highlighting detected addresses, and does not record or transmit any webpage data.

## In-App Purchases (Tips)

MapSwap is free. If you choose to leave an optional tip via the in-app tip jar, the transaction is handled entirely by Apple's StoreKit framework. We never see your payment information. Apple processes the purchase and provides us with anonymous transaction information (no personally identifiable data) so we know the tip succeeded. No record of your purchase, or whether you tipped at all, is shared with any third party.

## Children's Privacy

The App does not collect any data from any user, including children under 13.

## Changes to This Policy

If we update this privacy policy, we will post the changes here with an updated date.

## Contact

If you have questions about this privacy policy, please contact:

rothsoftware@icloud.com
