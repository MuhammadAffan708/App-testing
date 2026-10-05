# BUG-001: App icon has very low contrast and is hard to recognise on the home screen

| Field | Detail |
|---|---|
| **Bug ID** | BUG-001 |
| **Application** | AI Chatbot - Ask AI Anything (com.itechgemini.chatbot_ai) |
| **App Version** | from Play Store > About this app |
| **Platform** | Android |
| **Device** | Tecno Camon 19 Neo |
| **OS Version** | Android 13 |
| **Module** | UI  |
| **Type** | UI/UX |
| **Severity** | Low |
| **Priority** | Low |
| **Status** | Open |
| **Date Tested** | 05/10/2026 |

## Description

The app icon uses a dark blue background with a logo that is barely visible against it. On the home screen, the icon is difficult to recognise compared to neighbouring apps.

## Steps to Reproduce

1. Install the app from the Google Play Store.
2. Return to the device home screen.
3. Locate the app icon and compare it with other installed apps.

## Expected Result

The icon should have clear contrast between logo and background so users can identify the app quickly on both light and dark wallpapers.

## Actual Result

The logo blends into the dark blue background and is almost invisible, making the icon look like a plain blue square.

## Impact

Reduced brand recognition and harder app discovery on the home screen.

## Suggested Fix

Use a light-coloured logo or add an outline/gradient so the symbol stands out against the background.

## Evidence

<img width="702" height="1600" alt="image" src="https://github.com/user-attachments/assets/ba6ba5e3-05cf-4dad-a63f-c6ffe8fd51b8" />


# BUG-002: App name inconsistent between Play Store and device

| Field | Detail |
|---|---|
| **Bug ID** | BUG-002 |
| **Application** | AI Chatbot - Ask AI Anything (`com.itechgemini.chatbot_ai`) |
| **App Version** | [from Play Store > About this app] |
| **Platform** | Android |
| **Device** | Tecno Camon 19 Neo |
| **OS Version** | Android 13 |
| **Module** | UI  |
| **Type** | UI/UX |
| **Severity** | Low |
| **Priority** | Low |
| **Status** | Open |
| **Date Tested** | 05-10-2026 |

## Description

The app name shown on the device home screen differs from the name on its Play Store listing.

## Steps to Reproduce

1. Open the Play Store listing and note the app name.
2. Install the app and check the name under the home screen icon.

## Expected Result

The app name should match across the Play Store and the device.

## Actual Result

The Play Store shows "AI Chatbot - Ask AI Anything", but the home screen shows "Chatbot AI".

## Impact

Users may be unsure they installed the right app, and the inconsistent branding looks unprofessional.

## Suggested Fix

Use one consistent app name, or a clear short name derived from the store title.

## Evidence
<img width="702" height="1600" alt="image" src="https://github.com/user-attachments/assets/632cd1ad-3330-4264-a700-6b340d07af74" />


# BUG-003 — Email OTP Not Received

## Bug Information

| Field | Details |
|---|---|
| Bug ID | BUG-001 |
| Title | Email OTP Not Received |
| Application | NayaPay |
| Feature | Email OTP Verification |
| Severity | High |
| Priority | High |
| Status | Open — Requires Investigation |
| Reproducibility | Reproduced multiple times |

## Environment

| Environment | Details |
|---|---|
| Device | Tecno Camon 19 Neo |
| Operating System | Android 13 |
| Application Version | 3.7.7 |
| Network | Wi-Fi |

## Description

After entering a valid email address, the application displays the message "OTP has been sent to your mail." However, the OTP email is not received in the corresponding email account, preventing the user from continuing the verification process.

## Preconditions

- NayaPay application is installed.
- User has access to a valid email account.
- Device is connected to Wi-Fi.

## Steps to Reproduce

1. Open the NayaPay application.
2. Enter a valid email address.
3. Submit the email address.
4. Observe the confirmation message.
5. Open the corresponding email account.
6. Check the Inbox and Spam/Junk folders.
7. Search for NayaPay or OTP.
8. Wait for the OTP email.

## Expected Result

The OTP email should be delivered to the entered email address so the user can continue the verification process.

## Actual Result

The application displays "OTP has been sent to your mail," but the OTP email is not received.

## Reproducibility

The issue was reproduced multiple times, including with different email addresses.

## Severity

**High** — The issue prevents users from completing the email verification process.

## Priority

**High** — Investigation and resolution are required to restore the verification flow.

## Evidence

- Screen recording of the reproduction steps is available.

## Related Test Case

- TC-001 — Verify Email OTP Delivery

## Status

**Open — Requires Investigation**


https://github.com/user-attachments/assets/01287cb3-8117-48fe-9536-5744e1e317d9


 

