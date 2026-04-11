# Privacy Policy - Money Manager

> **Last updated:** 7 April 2026

## Contents

- [Overview](#overview)
- [1. Controller and contact](#controller)
- [2. Data we collect](#data-we-collect)
- [3. How we use data](#how-we-use-data)
- [4. Legal bases](#legal-bases)
- [5. Third parties](#third-parties)
- [6. Retention](#retention)
- [7. Your rights](#your-rights)
- [8. Ads and tracking controls](#ads-and-tracking)
- [9. Children](#children)
- [10. Security](#security)
- [11. International transfers](#international-transfers)
- [12. Changes](#changes)
- [13. Contact](#contact)

<h2 id="overview">Overview</h2>

This policy describes how **Money Manager** handles information. The app in this repository uses the Dart package name `money_management_app`.

**Agreement.** By using the app, you agree to this policy.

**Why this file is on GitHub.** We publish this file in the repo for transparency. If a store listing points to a different privacy URL, use that version for store submissions when required.

<h2 id="controller">1. Controller and contact</h2>

- **Developer:** Joe Boulos
- **Privacy email:** joeboulos94@gmail.com

Use the email above for privacy questions, access or deletion requests, and complaints.

<h2 id="data-we-collect">2. Data we collect</h2>

### 2.1 Account information

When you sign up, sign in, reset your password, or confirm your email, we may process:

- Email address
- Display name (if you provide one)
- Authentication identifiers and session tokens
- Security-related metadata from our auth provider

### 2.2 Financial data you enter

The app processes data you enter or import, for example:

- Accounts and balances
- Transactions (income, expense, transfer), notes, categories, and corrections
- Budgets
- Savings goals and progress
- Bills and recurring entries
- Loans and loan payments

### 2.3 Device, connectivity, and local storage

We may process:

- Device type, OS version, and app build version
- Network reachability (for example online/offline state)
- Data stored **on your device** (preferences, cached exchange rates, feature flags)
- **Local notifications** you schedule in the app (handled by your OS)

Third-party SDKs (such as advertising or store libraries) may collect their own diagnostic or advertising data under their policies.

### 2.4 AI coaching (Google Gemini)

If this feature is enabled in your build, the app may send a **small numeric summary** (aggregates and codes **without** raw memos, account names, or personal identifiers in that payload) to **Google** (Gemini API) to generate short coaching text.

- Requests go over the internet to Google.
- Google's use of data is covered by **Google's** terms and privacy policy, not only by this document.

Links:

- [Google Privacy Policy](https://policies.google.com/privacy)
- [Gemini API documentation](https://ai.google.dev/gemini-api/docs)

If the feature is off or no API key is configured, we do not send coaching requests.

### 2.5 Exchange rates (Open Exchange Rates)

Currency conversion may call **Open Exchange Rates** (or a compatible API). Typical data involved:

- Your **IP address** and app/API identifiers (as seen by that service)
- **Rate data** returned by the API, which may be **cached on your device**

More information: [openexchangerates.org](https://openexchangerates.org/) (see their legal/privacy pages).

Without API credentials, the app may use cache-only or other fallback behavior as implemented.

### 2.6 Ads (Google Mobile Ads / AdMob)

If ads are shown, Google may process identifiers, approximate location, and ad interaction signals.

- [Google Privacy Policy](https://policies.google.com/privacy)
- [How Google uses data from partners](https://policies.google.com/technologies/partner-sites)

### 2.7 Subscriptions (RevenueCat; stores handle payment)

For paid plans or other in-app purchases, **RevenueCat** may process an app user id, subscription and entitlement status, product metadata, and store receipts.

**Payments** are processed by **Google Play** or **Apple's App Store**, not by RevenueCat.

- [RevenueCat Privacy Policy](https://www.revenuecat.com/privacy)

### 2.8 Backend (Supabase)

**Supabase** provides authentication, database, and related backend services for account records and your stored financial data, subject to our access rules.

- [Supabase Privacy Policy](https://supabase.com/privacy)

### 2.9 Share and export

When you share or export content, you pick the destination app or channel. We do not control what happens after you send it.

<h2 id="how-we-use-data">3. How we use data</h2>

We use information to:

- Run, secure, and improve the app
- Authenticate accounts and sync cloud data
- Provide optional AI coaching when configured
- Load exchange rates
- Manage subscriptions and feature gates
- Show ads where applicable
- Comply with law and respond to valid requests

**We do not sell your personal information.**

<h2 id="legal-bases">4. Legal bases</h2>

Where laws like the GDPR apply, we may rely on:

- **Contract** (providing the service)
- **Legitimate interests** (security, reliability, fraud prevention, product improvement), balanced against your rights
- **Consent** where required (for example some ad or tracking settings on your device)
- **Legal obligation**

<h2 id="third-parties">5. Third parties</h2>

We use processors as needed. Each processes data only on our behalf according to their role:

**Supabase** — Authentication, database, and core backend.

**RevenueCat** — Subscription and entitlement state (not payment card processing).

**Google (AdMob)** — Advertising, where enabled.

**Google (Gemini API)** — Optional AI-generated coaching text, where enabled.

**Open Exchange Rates** — Exchange rate data for currency conversion.

**Google Play / Apple App Store** — In-app purchases and receipts.

We may also disclose information when the law requires it, or to protect rights, safety, and integrity.

<h2 id="retention">6. Retention</h2>

We keep data while your account is active and as needed for the purposes above, including legal retention. If you ask us to delete data and we can verify your request, we delete or anonymize it from active systems where allowed. Some processors may keep limited billing or security records under their own policies.

<h2 id="your-rights">7. Your rights</h2>

Depending on where you live, you may have rights to access, correct, delete, restrict, or object to processing, to data portability, or to complain to a regulator. For requests, email **joeboulos94@gmail.com**. We may verify your identity before responding.

<h2 id="ads-and-tracking">8. Ads and tracking controls</h2>

You can often limit ad personalization or reset the advertising ID in your **Android** or **iOS** settings. That may not remove all ads.

<h2 id="children">9. Children</h2>

The app is **not aimed at children under 3**. We do not knowingly collect personal information from children under 13. Contact us if you believe we have.

<h2 id="security">10. Security</h2>

We use reasonable measures (for example encryption in transit, authenticated access, and database rules). **No online service is perfectly secure.**

<h2 id="international-transfers">11. International transfers</h2>

Providers may process data in other countries. Where required, we rely on appropriate safeguards (such as standard contractual clauses).

<h2 id="changes">12. Changes</h2>

We may update this policy and will change the **Last updated** date when we do. For important changes, we may add notice in the app or in this repository.

<h2 id="contact">13. Contact</h2>

- **Email:** joeboulos94@gmail.com
- **Developer:** Joe Boulos

---

*This file reflects this open-source project as of the last updated date. Store submissions or local laws may require extra wording or a separate legal version.*
