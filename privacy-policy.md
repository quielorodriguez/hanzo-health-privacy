# Privacy Policy — Hanzo Health

**Hanzo Technologies Inc.**  
66 Cordova St W, Vancouver, BC, V6B 1C9, Canada  
Business registration: BC1576110 (British Columbia, Canada)  
Contact: quielo@hanzotechnologies.com  
Website: www.hanzotechnologies.com

**Effective date:** 2026-06-17  
**Version:** 2.1  
**Previous version:** 2.0 (2026-06-16) · 1.0 (2026-05-26)

---

## Summary

Hanzo Health is a private, on-device health journaling app. The short version: **your health data stays on your device — or in your own encrypted iCloud account if you enable sync.** We do not run servers that receive your health information. We do not sell, rent, or share your health data with anyone.

This policy describes in full what data exists, where it lives, who touches it, how long it is kept, and what rights you have. Please read it — your health data deserves this level of transparency.

---

## Section 1 — Information Collected and How It Is Used

### 1.1 Apple Health Data (HealthKit)

Hanzo Health requests read-only access to the following Apple Health data types, **if you grant permission** in the iOS Health permissions dialog:

- Sleep analysis
- Step count
- Heart rate (average, resting, and walking average)
- Heart rate variability (HRV SDNN)
- Oxygen saturation (SpO2)
- Respiratory rate
- Active energy burned (calories)
- Basal (resting) energy burned
- Exercise time and stand time
- Workout type and duration
- Menstrual flow
- Body weight
- Body mass index (BMI)
- Blood pressure (systolic and diastolic)
- Blood glucose
- Body temperature
- VO2 max
- Mindful session minutes
- Dietary energy consumed

**Where this data goes:** All of these values are read directly from Apple Health and stored locally on your device. If you enable iCloud sync, they are stored in your private encrypted iCloud account. Hanzo Health never transmits any of these values to our servers or to any third party.

**Permission is yours to control:** You can review and revoke any HealthKit permission at any time in iOS Settings → Privacy & Security → Health → Hanzo Health.

### 1.2 Journal and Health Log Data

When you use Hanzo Health's journaling features, the following is stored on your device:

- Daily mood, energy level, and symptom ratings you enter
- Free-text notes and entries you write
- Flare log entries (symptom severity and type)
- Condition tags and health categories you select
- Any custom fields you configure

### 1.3 Medication Tracking Data

If you use the medication tracking feature, Hanzo Health stores:

- The names and doses of medications and supplements you enter
- Daily logs of whether each medication was taken and at what time
- Notes you attach to medication logs

This information is stored locally on your device and, if iCloud sync is enabled, in your private encrypted iCloud account. Medication names and adherence logs are never shared with third parties or transmitted to Hanzo's servers. Medication names and adherence records are treated as sensitive health data and receive the highest level of privacy protection.

### 1.4 AI Conversation History

Hanzo Health uses Apple's on-device Foundation Models framework to provide AI insights and chat features. All AI processing happens entirely on your device — your questions and health data are never sent to Apple's servers or to any cloud AI service.

Your AI conversation history — including messages you send and responses you receive — is saved on your device so you can refer back to it. If iCloud sync is enabled, this conversation history is also stored in your private encrypted iCloud account. Conversation history is treated as health data and is never sent to Hanzo's servers or to Apple's AI servers.

You can delete your conversation history at any time in **Settings → Data → Delete All Data**.

### 1.5 AI-Generated Health Insights

Hanzo Health generates periodic AI health summaries based on your journal and health data. These summaries (up to approximately 4,000 characters of text describing patterns in your mood, energy, symptoms, and health metrics) are stored on your device and, if iCloud sync is enabled, in your encrypted iCloud account. They are not transmitted to Hanzo or any third party.

### 1.6 Article Reading History

If you read health articles within the app, a record of which articles you have read and when is stored on your device and in iCloud (if sync is enabled). This is used only to personalise your article feed and mark content you have already seen.

### 1.7 App Lock and Security Data

If you enable the app lock feature, Hanzo Health stores your chosen 6-digit passcode in your device's **secure iOS Keychain** — the same encrypted system storage used by iOS for passwords and credentials. Your passcode never leaves your device and is not shared with Hanzo or any third party. If you enable iCloud Keychain, your device may back up the passcode to your personal encrypted iCloud Keychain under your own Apple Account.

### 1.8 Biometric and Face ID Status

The app may read the availability of Face ID or Touch ID on your device (to determine whether biometric authentication is available for app lock). No biometric data is ever collected, stored, or transmitted.

---

## Section 2 — On-Device AI and Foundation Models

All AI features in Hanzo Health operate entirely on your device using Apple Foundation Models (Apple's on-device AI framework, available on supported iPhone and iPad models). This means:

- Your health questions and journal data are never sent to Apple's AI servers
- Prompts and AI responses are processed entirely on-device
- No third-party AI provider (such as OpenAI, Google, or Anthropic) receives your data

Your AI conversation history is saved on your device for continuity across sessions. If you enable iCloud sync, this history syncs to your private iCloud account. See Section 1.4 for details.

---

## Section 3 — Data Sync and Storage

### 3.1 Local Storage (Default)

By default, all Hanzo Health data — journal entries, health logs, medication records, AI conversations, AI insights, and article reading history — is stored on your device using Apple's SwiftData encrypted data storage.

### 3.2 iCloud Sync (Optional)

If you are signed into iCloud on your device, Hanzo Health can optionally sync your data across your Apple devices using CloudKit, Apple's encrypted cloud database. Data synced to iCloud includes:

- Journal entries (mood, energy, symptoms, notes, and all health metrics)
- Flare logs
- Medication names and daily adherence records
- AI-generated health summaries
- AI conversation history
- Article reading history

All data stored in iCloud is **end-to-end encrypted by Apple** — Hanzo cannot read it, and it is accessible only from devices signed into your Apple Account.

You can disable iCloud sync by signing out of iCloud on your device or by disabling Hanzo Health's access in **Settings → [Your Name] → iCloud** on your iPhone. Data stored in iCloud is governed by Apple's iCloud Terms and Conditions and Privacy Policy at https://www.apple.com/legal/privacy.

---

## Section 4 — Third-Party Services

Hanzo Health uses a small number of third-party services that handle non-health operational data. **None of these services receive your health journal content, HealthKit data, medication records, or AI conversations.**

### 4.1 RevenueCat (Subscription Management)

**RevenueCat, Inc. — United States**

We use RevenueCat to manage in-app subscriptions. When you launch the app, RevenueCat's SDK automatically sends the following to RevenueCat's servers in the United States:

- Your device's app-vendor identifier (IDFV — a non-advertising identifier assigned by Apple to this app on your device)
- App version and operating system version
- Your IP address (at time of SDK initialisation and subscription verification)
- Subscription transaction receipts (Apple-signed, containing original transaction ID, product ID, purchase date, and expiry date)
- Subscription status and entitlement state
- RevenueCat-assigned anonymous customer ID

This information is used solely to verify your subscription status and to enable the features you have paid for. It is not linked to your health data in any way.

RevenueCat acts as a data processor on our behalf and is bound by a data processing agreement. Their privacy policy is at https://www.revenuecat.com/privacy. Users in the EU/EEA, Quebec, and other jurisdictions with cross-border data transfer requirements should be aware that this processing occurs in the United States, subject to RevenueCat's standard contractual clauses.

### 4.2 Apple MetricKit (Performance Diagnostics)

**Apple Inc. — United States**

Hanzo Health uses Apple's MetricKit framework to receive anonymised app performance data, including:

- App launch times
- Memory usage statistics
- CPU usage statistics
- Crash reports (exception type, exception code, app version, iOS version at time of crash)
- Hang and performance exception data

This data is collected by Apple from your device and delivered to the app approximately once per day. It contains no health journal content whatsoever. We store a brief summary of the most recent report in the app's local settings storage on your device; this summary is visible in **Settings → About**. MetricKit data is not transmitted to Hanzo's servers.

This data collection is managed entirely by Apple's platform and is governed by Apple's privacy policy at https://www.apple.com/privacy.

### 4.3 Apple (App Store, CloudKit, HealthKit, Foundation Models)

Apple provides the infrastructure the app runs on. Apple's privacy policy governs how Apple handles data across all of their platforms. See https://www.apple.com/legal/privacy.

---

## Section 5 — Data Retention

Your journal entries, flare logs, medications, AI conversations, and all other health data are stored on your device and in your iCloud account (if sync is enabled) **for as long as you use the app**.

**Deletion:** You can delete all your data at any time from **Settings → Data → Delete All Data**. Deletion removes data from your device immediately. iCloud-synced data is also deleted from your iCloud account; however, Apple may retain deleted CloudKit records in an archived state for up to 30 days before permanent deletion, as governed by Apple's iCloud data retention policies.

**App deletion:** If you delete the app, all locally stored data is removed from your device. iCloud-synced data remains in your iCloud account until you delete it from Settings or delete your Apple Account.

**Diagnostics data:** App performance diagnostics (crash reports and usage statistics collected via Apple MetricKit) are retained in the app's local storage for up to 12 months and are not associated with your health data.

**Subscription records:** Subscription transaction records are retained by RevenueCat for the period required by applicable financial regulations (typically 7 years) to comply with tax and accounting obligations. These records contain no health data.

---

## Section 6 — Your Privacy Rights

### 6.1 In-App Data Controls

You can access, modify, export, and delete all your data directly within Hanzo Health:

- **Delete all data:** Settings → Data → Delete All Data
- **Export data:** Settings → Data → Export (PDF doctor report)
- **Revoke HealthKit access:** iOS Settings → Privacy & Security → Health → Hanzo Health
- **Disable iCloud sync:** iOS Settings → [Your Name] → iCloud → Hanzo Health

### 6.2 Contact — Privacy Officer

For any privacy question, data access request, correction, deletion, or complaint that cannot be completed within the app, please contact:

**Ezequiel Rodriguez, Privacy Officer**  
Hanzo Technologies Inc.  
66 Cordova St W, Vancouver, BC, V6B 1C9, Canada  
Email: quielo@hanzotechnologies.com  
Subject line: "Privacy Request — [your request type]"

We will acknowledge your request within 5 business days and respond substantively within 30 days.

### 6.3 California Users (CCPA / CPRA)

California residents have the right to know, delete, and correct personal information we hold about them, and to opt out of the sale or sharing of personal information.

**Hanzo Technologies does not sell, rent, or share personal information within the meaning of the California Consumer Privacy Act.** We do not use personal information for cross-context behavioural advertising.

California residents may submit verified requests to know, delete, or correct their personal information by emailing quielo@hanzotechnologies.com with the subject line "California Privacy Request." You have the right not to receive discriminatory treatment for exercising your CCPA rights.

### 6.4 Quebec Users (Law 25)

Quebec residents may exercise their rights under Quebec's Law 25 (Act Respecting the Protection of Personal Information in the Private Sector) by contacting the Privacy Officer at the address above.

Complaints about our privacy practices may be directed to the Commission d'accès à l'information du Québec: www.cai.gouv.qc.ca

### 6.5 EU / EEA Users (GDPR)

EU and EEA residents have rights under the General Data Protection Regulation including the right to access, rectify, erase, restrict processing of, and port your personal data, and the right to object to processing.

> **EU Representative:** Hanzo Technologies Inc. is a Canadian company serving EU users. We are in the process of appointing an EU Article 27 Representative. Until this appointment is complete, EU users may contact our Privacy Officer directly at quielo@hanzotechnologies.com. EU users may also lodge a complaint with their national supervisory authority. In France: Commission Nationale de l'Informatique et des Libertés (CNIL) at www.cnil.fr.

**Lawful basis for processing:** Where Hanzo Health processes health data belonging to EU users, the lawful basis is **explicit consent** (Article 9(2)(a) GDPR). You provide this consent when you grant HealthKit permissions in iOS and when you enter data into the app. You may withdraw consent at any time by revoking HealthKit permissions or deleting your data.

### 6.6 Japan Users (APPI)

Requests related to the disclosure, correction, cessation of use, or deletion of personal information under the Act on the Protection of Personal Information (APPI) may be submitted by email to quielo@hanzotechnologies.com. Please include "APPI Request" in the subject line.

Hanzo Technologies Inc. is the Personal Information Handling Business Operator for personal information of Japanese users.

### 6.7 Australia and New Zealand Users

Privacy complaints may be submitted to quielo@hanzotechnologies.com. We will respond within 30 days. If your complaint is not resolved to your satisfaction, you may contact:

- **Australia:** Office of the Australian Information Commissioner — www.oaic.gov.au
- **New Zealand:** Office of the New Zealand Privacy Commissioner — www.privacy.org.nz

---

## Section 7 — Children and Minors

Hanzo Health is intended for users aged **16 and over** (or **13 and over** in the United States and United Kingdom). The app is not designed for use by children. We do not knowingly collect personal information from anyone below the applicable minimum age for their country.

Given that Hanzo Health collects health data including menstrual cycle information, we strongly encourage parents to supervise app use by young people.

If you believe a minor below the applicable age threshold has created an account or is using the app, please contact us at quielo@hanzotechnologies.com and we will delete the relevant data promptly.

**EU/EEA users:** Consistent with GDPR Article 8, users aged 16 or under in the EU/EEA require parental or guardian consent to use the app and provide health data.

---

## Section 8 — Security and Data Breach Notification

We take the security of your health data seriously. Your data is protected at multiple levels:

- **On-device storage:** Encrypted by iOS using your device passcode
- **App lock:** Optional 6-digit passcode stored in iOS Secure Keychain
- **iCloud sync:** End-to-end encrypted by Apple; Hanzo cannot access your iCloud data
- **HealthKit access:** Read-only; the app cannot write unsolicited data to Apple Health

**Breach notification:** In the event of a data security breach affecting your personal information, we will:
- Notify affected users without undue delay
- Notify relevant regulatory authorities within the applicable statutory timeframes:
  - 72 hours under GDPR (EU/EEA)
  - 72 hours under Quebec's Law 25
  - Without unreasonable delay under Canada's PIPEDA Breach of Security Safeguards Regulations
  - Within 30 days under Australia's Notifiable Data Breaches scheme
  - Without undue delay under New Zealand's Privacy Act 2020

Notifications will be sent to the email address associated with your account or, where no email is held, through a prominent in-app notice.

To report a security concern or suspected breach, please contact: quielo@hanzotechnologies.com

---

## Section 9 — HealthKit Entitlements

Hanzo Health holds Apple's authorisation to access standard HealthKit data types (as listed in Section 1.1). The app does not access or query clinical health record data (EHR data from connected healthcare providers) in the current version. If this functionality is added in a future version, this policy will be updated and users will be notified.

---

## Section 10 — Changes to This Policy

We may update this Privacy Policy from time to time. When we make material changes, we will update the "Effective date" at the top of this page and, where required by law or where changes are significant, notify you via an in-app notice. Continued use of the app after an updated policy is posted constitutes acceptance of the updated terms. If you do not agree to a material update, you should delete your data and discontinue use of the app.

Previous versions of this policy are available by contacting quielo@hanzotechnologies.com.

---

## Jurisdiction-Specific Addenda

This base policy applies to all users worldwide. Jurisdiction-specific versions of this policy — with translated text, local regulatory authority references, and market-specific legal requirements — are available in the following languages and locales:

| Locale | Jurisdiction | File |
|--------|-------------|------|
| en-ca | Canada (PIPEDA + Bill C-27) | /en-ca/privacy-policy.md |
| fr-ca | Quebec (Law 25, French) | /fr-ca/politique-de-confidentialite.md |
| en-eu | European Union (GDPR + EU AI Act) | /en-eu/privacy-policy.md |
| de | Germany (GDPR + Impressum) | /de/datenschutzrichtlinie.md |
| fr | France (GDPR + CNIL, French) | /fr/politique-de-confidentialite.md |
| en-gb | United Kingdom (UK GDPR) | /en-gb/privacy-policy.md |
| en-us-ca | California, USA (CCPA/CPRA) | /en-us-ca/privacy-policy.md |
| pt-br | Brazil (LGPD, Portuguese) | /pt-br/politica-de-privacidade.md |
| ja | Japan (APPI, Japanese) | /ja/privacy-policy.md |
| ko | South Korea (PIPA, Korean) | /ko/privacy-policy.md |
| en-au | Australia (Privacy Act 1988 amended 2024) | /en-au/privacy-policy.md |
| en-nz | New Zealand (Privacy Act 2020) | /en-nz/privacy-policy.md |
| ar | UAE + Saudi Arabia (PDPL, Arabic) | /ar/privacy-policy.md |
| en-in | India (DPDP Act 2023) | /en-in/privacy-policy.md |

---

*Hanzo Technologies Inc. · Vancouver, BC, Canada · quielo@hanzotechnologies.com*  
*© 2026 Hanzo Technologies Inc. All rights reserved.*
