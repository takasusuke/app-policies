# Privacy Policy — Stone Knights

Last updated: August 11, 2026 / Version: 2

**The Japanese version of this policy is the authoritative (governing) version.**
If there is any conflict or discrepancy between this translation and the
Japanese version, the Japanese version controls.
[日本語版はこちら](../)

**This policy is a general template and has not been reviewed by a lawyer.**
Before any release beyond internal TestFlight distribution, please confirm
that its content matches the App's actual implementation and operation,
consulting a professional if needed.

## 1. Introduction

Stone Knights ("the App") is a board game in which players move stones
against each other. This policy explains what information is collected
when you use the App and how it is handled.

## 2. Information the App Collects

### Information stored only on your device

The stones, coins, shards, and achievements you own, your deck
configuration, and your settings (BGM/SE on or off) are stored only on
your device (PlayerPrefs). This information is never transmitted
externally and is deleted when you uninstall the App.

The App does not collect any personally identifying information such as
your name, email address, phone number, or address. No account
registration (entering an email address or password) is required.

### Information collected for online matches (Unity Gaming Services)

The online match feature uses Unity Gaming Services (UGS), provided by
Unity Technologies.

- **Anonymous authentication**: When you use online matches, an anonymous
  player ID (an identifier not linked to personal information such as an
  email address) is issued for your device.
- **Relayed communication**: Communication with your opponent is relayed
  through UGS Relay. Information about the moves played is exchanged
  between the two matched devices through this relay.
- **Match record storage (Cloud Save)**: To detect abuse through
  intentional stalling (repeated timeouts or abandoned connections), the
  number and timestamps of matches ended due to stalling are recorded in
  UGS Cloud Save, linked to your anonymous player ID. The developer can
  view this record from the Unity Dashboard, and online match access may
  be restricted if a threshold is exceeded (see the Terms of Service for
  details).

### Crash and error information

**The App does not include any crash-reporting mechanism.** Unity Cloud Diagnostics
(crash reporting), Unity Analytics, and Firebase Crashlytics are all disabled. If an
unexpected error occurs, the details are shown on the device's screen only and are
never transmitted off the device.

However, if you have enabled both "Share iPhone Analytics" and "Share with App
Developers" under iOS Settings > Privacy & Security > Analytics & Improvements, Apple
may collect crash and usage information and make it available to us in anonymised,
aggregated form through App Store Connect. This is provided by Apple's own mechanism
and is not collected directly by us. You can turn it off at any time from that same
settings screen.

This information is processed by Unity Technologies. Please also review
[Unity Gaming Services' privacy policy](https://unity.com/legal/game-player-and-app-user-privacy-policy).

## 3. What the App Does Not Use

- Advertising SDKs (e.g. AdMob) — the current version does not include a
  real ad SDK, only a development placeholder screen (this policy will be
  updated once one is implemented)
- Usage analytics and crash collection such as Firebase Analytics / Crashlytics —
  not included (see "Crash and error information" above)
- In-app purchases — not included

## 4. Purpose of Use

- On-device data is used only for the App's operation (saving and
  restoring progress)
- Information sent to UGS is used only to establish online match
  connections and to detect and prevent stalling abuse

## 5. Disclosure to Third Parties

The information described in Section 2 is processed by Unity Technologies
(UGS) under its own privacy policy. No information is disclosed to any
third party other than the above.

## 6. Children's Privacy

The App is not directed at children under 13. We do not knowingly collect
information from children under 13.

## 7. Changes to This Policy

If this policy is changed, this page and the version number shown in the
App will be updated. When the version changes, the App will ask you to
re-consent the next time it starts.

## 8. Contact

For questions about this policy, please contact:

Contact: gendaijin44435@gmail.com
