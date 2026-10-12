# Privacy Policy — Stone Knights

Last updated: October 12, 2026 / Version: 4

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

**Main changes in version 4:** The App's online match feature has been
discontinued, so the sections on information collected for online matches
(anonymous authentication, relayed communication, match records) have been
removed. We have also added that usage and crash information is collected to
improve the game and to find bugs (Section 2).

## 2. Information the App Collects

### Information stored only on your device

The stones, coins, shards, and achievements you own, your deck
configuration, story progress, and your settings (BGM/SE on or off,
statistics sending on or off) are stored only on your device (PlayerPrefs).
This information is never transmitted externally and is deleted when you
uninstall the App.

The App does not collect any personally identifying information such as
your name, email address, phone number, or address. No account
registration (entering an email address or password) is required.

### Usage information (Unity Gaming Services Analytics)

To make the game easier to play (for example, to learn where in the story
players get stuck because it is too hard), the App uses Analytics from Unity
Gaming Services (UGS), provided by Unity Technologies, to collect usage
information such as:

- The mode you choose (story, CPU match, puzzle, tutorial, and so on)
- When a match starts and ends, its result (win, loss, draw, resignation),
  the number of moves, the time taken, the story chapter, and the CPU level
- The result of puzzle attempts and the time taken
- How often you were stopped for lack of stamina, and how often you watched
  the stamina-recovery ad

This information is **not linked to personally identifying information**.
Because the App does not collect your name, email address, or similar
details, you cannot be identified from it. However, through Unity's
mechanism, an anonymous identifier automatically issued per app and device,
and information such as device model, OS version, app version, language, and
approximate region, may be sent along with it.

- **Collection starts only after you consent.** Nothing is sent before you
  agree to this policy.
- **You can turn it off at any time.** Turn off "統計送信" (Send statistics) in
  Settings and nothing further is sent.
- Records are not stored up and sent later (anything that happens while it is
  off, or before consent, is discarded).

### Crash and error information (Unity Cloud Diagnostics)

If the App terminates unexpectedly, it uses Unity Cloud Diagnostics to
collect crash information (the error details, a record of where it occurred,
and the device model, OS version, and app version) so we can find and fix
the cause. It contains no personally identifying information. Crash
information is sent separately from the "Send statistics" setting above.

This information is processed by Unity Technologies. Please also review
[Unity Gaming Services' privacy policy](https://unity.com/legal/game-player-and-app-user-privacy-policy).

### Information collected by Apple

If you have enabled both "Share iPhone Analytics" and "Share with App
Developers" under iOS Settings > Privacy & Security > Analytics & Improvements,
Apple may collect crash and usage information and make it available to us in
anonymised, aggregated form through App Store Connect. This is provided by
Apple's own mechanism and is not collected directly by us. You can turn it off
at any time from that same settings screen.

### Information collected for advertising (Google AdMob)

The App includes a rewarded video ad that lets you earn coins by watching
it. Ads are never shown automatically — they are shown only when you tap
the ad icon (a treasure-chest icon) and choose to watch. Ads are served
using the Google Mobile Ads SDK (AdMob), provided by Google.

Before the ad SDK is initialized, the App requests consent through
Google's User Messaging Platform (UMP) where required by law (e.g. in the
EEA), and on iOS it asks for permission through App Tracking Transparency.

- If you grant permission, identifiers such as an advertising ID may be
  sent to Google for ad delivery and measurement.
- If you do not grant permission, no processing based on those
  identifiers takes place, and ads are served in a non-personalized form
  instead. Either way, you can watch an ad and receive the reward.

For details on the information collected, please see
[Google's Privacy Policy](https://policies.google.com/privacy) and
[Google Mobile Ads' App Store data disclosure](https://developers.google.com/admob/unity/privacy/data-disclosure).

## 3. What the App Does Not Use

- Firebase Analytics / Crashlytics — not included (usage and crash information
  is collected through Unity's services, as described above)
- Communication, authentication, and match-record storage for online matches
  — discontinued
- In-app purchases — not included

## 4. Purpose of Use

- On-device data is used only for the App's operation (saving and
  restoring progress)
- Usage information is used only to improve the game's difficulty and
  playability
- Crash information is used only to investigate and fix bugs
- Information related to advertising is used only to serve the rewarded
  ad and measure its effectiveness

## 5. Disclosure to Third Parties

The information described in Section 2 is processed by Unity Technologies
(UGS) and Google (Google Mobile Ads), each under its own privacy policy.
No information is disclosed to any third party other than the above.

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
