# Privacy Policy

**Effective date: 2026-05-29**

This Privacy Policy explains how Pulse ("Pulse", "the app") handles your data.

The short version: **Pulse does not collect any data about you.** It is a local-first iOS app — your financial information stays on your device, with optional sync through your own iCloud account.

---

## 1. Who we are

Pulse is an independent iOS app. Contact: spruce.buffalo.6n@icloud.com.

## 2. What data Pulse handles

You enter financial information into Pulse — accounts, transactions, budget categories, portfolio holdings, property values, scheduled entries, and similar. **This data is stored on your device, in Apple's SwiftData persistence layer.** Pulse does not transmit any of this data to the developer or to any third-party server.

## 3. iCloud sync

If you have iCloud enabled on your device, Pulse uses Apple's CloudKit private database to sync your data between your own Apple devices (iPhone, iPad).

- **The data is stored in your private iCloud account, not on any server controlled by the developer.**
- The developer has **no access** to data in your private iCloud database.
- This sync is between you and Apple. See [Apple's Privacy Policy](https://www.apple.com/legal/privacy/) for how Apple handles iCloud data.
- You can disable iCloud sync at any time in iOS Settings → [your name at the top] → iCloud → Pulse.

## 4. Third-party services

Pulse fetches live market data from **Yahoo Finance** to display current prices for the shares, ETFs, and cryptocurrencies in your portfolio, and current foreign-exchange rates for multi-currency display.

- These requests contain only the ticker symbol or currency pair being looked up (for example, "AAPL", "BTC-USD", "EUR/USD").
- **No personally identifying information is sent.** Your identity, account balances, transactions, and holdings list are never transmitted.
- These are standard anonymous URL requests — equivalent to a weather app querying a forecast service.

Pulse does not embed any analytics SDKs, advertising networks, crash reporters, or other third-party tracking services.

## 5. Local authentication

If you enable Face ID, Touch ID, or device passcode lock in Pulse's settings, authentication is performed by Apple's `LocalAuthentication` framework on your device. **Biometric data never leaves your device** and is never accessible to Pulse or the developer.

## 6. Push notifications

Pulse uses Apple's Push Notification service to deliver reminders about upcoming vesting events for grants you have tracked. These notifications are scheduled on your device or via Apple's push service; the developer has no access to their content.

## 7. Data export and deletion

- **CSV export:** You can export your data to CSV files using Settings → Data → Export. These files are saved by you, locally; the developer never sees them.
- **Deletion:** To remove all your Pulse data, uninstall the app from your device. If you have used iCloud sync, also delete the app's data from iCloud: iOS Settings → [your name at the top] → iCloud → Manage Account Storage → Pulse → Delete.

## 8. Children's privacy

Pulse is rated 4+ in the App Store, meaning it is suitable for users of all ages. The app does not collect any data from any user, including children. Pulse does not participate in Apple's "Made for Kids" program and is not specifically directed at children under 13.

## 9. International users

Pulse has no servers and does not transfer your data anywhere — it stays on your device and (optionally) in your own iCloud account. If you use iCloud, your data is handled by Apple under Apple's privacy practices and the data-residency rules of your iCloud account.

## 10. Changes to this policy

If this policy is updated, the "Effective date" above will change.

## 11. Contact

Questions about this policy or about Pulse's privacy practices: **spruce.buffalo.6n@icloud.com**.
