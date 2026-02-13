# Privacy Policy for CallCenterByeBye

**Last updated:** February 13, 2026

## Introduction

CallCenterByeBye ("we," "our," or "the app") is committed to protecting your privacy. This Privacy Policy explains how our call blocking application handles your data.

## Our Privacy Commitment

**CallCenterByeBye does NOT collect, transmit, or share any of your personal data with third parties or external servers.**

All data processing happens locally on your device. We have no servers, no cloud storage, and no data transmission capabilities.

## Data We Process (Locally Only)

CallCenterByeBye processes the following data **exclusively on your device**:

### 1. Phone Numbers
- **What:** Phone numbers from incoming calls, your contact list, and call log
- **Purpose:** To determine which calls to block based on your configured rules
- **Storage:** Stored locally in your device's database (Room/SQLite)
- **Sharing:** NEVER shared with anyone

### 2. Contact Information
- **What:** Contact names and phone numbers from your device's contact list
- **Purpose:** To allow contacts to bypass call blocking (if you enable this feature)
- **Storage:** Only contact names are cached locally; no contact data is transmitted
- **Sharing:** NEVER shared with anyone

### 3. Call Log Data
- **What:** Information about blocked calls (number, timestamp, block reason)
- **Purpose:** To show you a history of blocked calls within the app
- **Storage:** Stored locally in your device's database
- **Sharing:** NEVER shared with anyone

### 4. App Settings
- **What:** Your blocking preferences (enabled prefixes, blacklist, whitelist, settings toggles)
- **Purpose:** To remember your call blocking configuration
- **Storage:** Stored locally in SharedPreferences
- **Sharing:** NEVER shared with anyone

## Permissions Required

CallCenterByeBye requires the following Android permissions to function:

| Permission | Purpose | Required? |
|------------|---------|-----------|
| **READ_PHONE_STATE** | To detect incoming calls and read caller ID | YES |
| **READ_CONTACTS** | To check if caller is in your contacts (optional feature) | YES |
| **READ_CALL_LOG** | To allow adding numbers from call history to blacklist/whitelist | YES |
| **ANSWER_PHONE_CALLS** | To reject/block unwanted calls | YES |
| **CallScreeningService** | Android system permission to screen calls | YES |

All these permissions are used **exclusively for call blocking functionality** and data never leaves your device.

## Data Retention

- **While app is installed:** All data is stored locally on your device
- **When app is uninstalled:** All data is permanently deleted from your device
- **No cloud backup:** We do not backup your data to any cloud service

## Third-Party Services

### Current Version (Free)
CallCenterByeBye **currently does NOT use any third-party services**. No analytics, no ads, no tracking.

### Future Versions (If Monetization is Added)
If we add optional features in the future, we may use:

- **Google AdMob** (for ads in free version) - [AdMob Privacy Policy](https://support.google.com/admob/answer/6128543)
- **Firebase Analytics/Crashlytics** (for crash reporting) - [Firebase Privacy](https://firebase.google.com/support/privacy)
- **Google Play Billing** (for premium purchases) - [Google Play Privacy](https://policies.google.com/privacy)

**You will be notified of any changes via app update and updated privacy policy.**

## Children's Privacy

CallCenterByeBye does not knowingly collect data from children under 13. The app is not directed at children. If you believe a child has provided data to us, please contact us immediately.

## Your Rights

You have the right to:

1. **Access your data:** All data is visible within the app
2. **Delete your data:** Simply uninstall the app to permanently delete all data
3. **Control data collection:** You control which features to enable (contacts access, notifications, etc.)

## Data Security

- All data is stored in Android's secure SQLite database
- Data is protected by Android's app sandboxing
- No network transmission means no risk of interception
- No external servers means no risk of data breaches

## Changes to Privacy Policy

We may update this Privacy Policy from time to time. We will notify you of any changes by:
- Updating the "Last updated" date
- Showing an in-app notification (for significant changes)
- Requiring acceptance before using updated features

Continued use of the app after changes constitutes acceptance of the updated Privacy Policy.

## International Users

CallCenterByeBye is designed to comply with privacy regulations including:
- **GDPR** (European Union)
- **CCPA** (California, USA)
- **LGPD** (Brazil)

Since we do not collect or transmit any data, we are compliant by design.

## Contact Us

If you have questions about this Privacy Policy or our data practices:

- **Email:** [electricjimi.fc@gmail.com]
- **GitHub:** https://github.com/electricjimi/claude-code-call-blocker

## Legal Disclaimer

CallCenterByeBye is provided "as is" without warranties. We are not responsible for:
- Missed important calls due to incorrect blocking rules
- Any consequences of using the app's call blocking features
- Compatibility issues with specific devices or carriers

By using CallCenterByeBye, you acknowledge that you are solely responsible for configuring your call blocking rules appropriately.

## Summary (TL;DR)

✅ **All data stays on your device**
✅ **No data is sent to servers**
✅ **No sharing with third parties**
✅ **No tracking or analytics**
✅ **Data deleted when you uninstall**
✅ **Open source and transparent**

**Your privacy is our priority.**

---

*This privacy policy is effective as of February 13, 2026.*
