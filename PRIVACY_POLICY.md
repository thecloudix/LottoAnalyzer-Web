# Privacy Policy

**Last updated: 2026-05-14**

This privacy policy describes how LottoAnalyzer ("the app") handles information.

## TL;DR

- The app does not collect, store, or transmit any personal information.
- The app makes a single network request to a public government dataset (data.ny.gov) when you tap "Refresh."
- Everything else stays on your device.

## What the app stores on your device

- **Cached lottery draw data** — at `Android/data/com.powerball.analyzer/files/draws_cache.json`. Public information from data.ny.gov.
- **Your scoring preferences** — toggles and weights you set in Settings, stored via Android DataStore. Not transmitted anywhere.

These files are removed automatically when you uninstall the app.

## Network requests the app makes

- **GET https://data.ny.gov/resource/d6yy-54nr.json** — when you press "Refresh data." This is a publicly accessible state government dataset. The request includes only standard HTTP headers; no identifying information about you is sent.

The app does not contact any other servers. It does not include analytics, crash reporting, advertising SDKs, or social media SDKs.

## Permissions the app requests

- **INTERNET** — required to fetch updated lottery data from data.ny.gov when you press Refresh.
- **ACCESS_NETWORK_STATE** — required by the OkHttp networking library to detect connectivity changes.

The app does not request: location, camera, microphone, storage, contacts, calendar, or any other sensitive permissions.

## Children

The app is not designed for or directed at children under 13. It does not knowingly collect any data from any user, including children.

## Data sharing with third parties

The app does not share any user data with third parties because it does not collect any user data.

## Changes to this policy

If this policy ever changes, the updated version will be available at the same URL where you found this one. The "Last updated" date at the top will reflect the change.

## Contact

For questions about this privacy policy or the app's behavior, contact: plainsightlogic@gmail.com
