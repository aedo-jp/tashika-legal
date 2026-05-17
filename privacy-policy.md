---
layout: default
title: Privacy Policy — Taberu
---

# Privacy Policy — Taberu

**Last updated: May 2026**
**Effective date: Upon App Store release**

---

## Who we are

Taberu is developed and operated by Ash Every Design Office (Ashley Every), based in Yamanashi, Japan. For the purposes of applicable data protection laws, including the General Data Protection Regulation (GDPR), Ash Every Design Office acts as the **Data Controller** of your personal data.

**Contact:** hello@aedo.jp
**Location:** Yamanashi, Japan

This Privacy Policy explains how Taberu handles your information when you use our app. We have written this in plain language because we believe privacy policies should be readable by the people they protect.

---

## The short version

- **We do not collect or store your photos.** Images you scan are sent to Google's Gemini AI for analysis and are not retained after processing.
- **We do not collect personal information** such as your name, email address, or location.
- **Your preferences stay on your device.** Language settings, allergen selections, and dietary preferences are stored locally on your phone only.
- **We do not sell your data.** We never have and never will.
- **We do not show ads.** Taberu is a one-time purchase with no advertising.

---

## 1. What data Taberu processes

### 1a. Images you scan (camera data)

When you use Taberu's scanning feature, your device's camera captures an image of the food item, menu, or packaging you are pointing at. This image is:

- Compressed on your device before transmission
- Sent securely to Google's Gemini AI service for analysis
- Processed by Google to identify and translate the food content
- Returned to your device as translated text
- **Not stored by Taberu after analysis**
- **Not stored by Google after analysis** (as per Google's Gemini API terms)

**Purpose:** To provide the core functionality of Taberu — translating Japanese food content into your chosen language.

**Legal basis (APPI):** Processing is necessary to provide the service you have requested. You provide explicit consent via the in-app consent screen before your first scan.

**Legal basis (GDPR, for EU users):** Consent (Article 6(1)(a) GDPR). You may withdraw consent at any time by ceasing to use the scanning feature. Withdrawal does not affect the lawfulness of processing before withdrawal.

### 1b. App preferences (stored locally only)

Taberu stores the following information locally on your device using AsyncStorage (device-level storage). This data never leaves your device and is never transmitted to us or any third party:

- Your chosen translation language
- Your selected allergens
- Your dietary preferences
- Whether you have completed the onboarding process
- Your current scanning session (automatically cleared after 3.5 hours)

**Purpose:** To personalise your experience and remember your settings between uses.

### 1c. Crash and performance data (if analytics enabled)

If you have enabled analytics or crash reporting (Sentry), anonymised crash reports and performance data may be collected to help us identify and fix technical issues. This data:

- Does not include the content of your scans
- IP addresses are automatically scrubbed or anonymised upon receipt by Sentry before storage
- Is used solely for app improvement purposes

*Note: If you would prefer not to contribute crash data, you can contact us at hello@aedo.jp to request opt-out.*

---

## 2. Third-party AI processing — Google Gemini

**This is the most important section for you to understand.**

Taberu's core functionality depends on sending your food images to Google's Gemini AI service. Here is exactly what this means:

**What is sent to Google:**
- The compressed image you capture with your camera
- A text prompt instructing Gemini to translate and describe the food content
- Your chosen language preference (e.g. "English", "Korean")
- The specific allergen keywords you have selected in settings (e.g. "peanuts, gluten") — included in the prompt so Gemini can flag relevant items
- Your dietary preferences (e.g. "vegetarian", "no pork") — included in the prompt so Gemini can flag relevant items
- Any free-text dietary notes you have entered in settings

**Important:** These allergen and dietary keywords are sent as plain text instructions (e.g. "flag items containing peanuts") and are not linked to your identity. No name, account, or device identifier accompanies them.

**What is NOT sent to Google:**
- Your name, email address, or Apple ID
- Your location
- Any information that could identify you personally
- Any data beyond what is listed above

**Google's handling of your images:**
According to Google's Gemini API terms, images submitted via the API are processed to generate a response and are not used to train Google's AI models. Images are not retained after processing is complete. For full details, see Google's privacy policy at [https://policies.google.com/privacy](https://policies.google.com/privacy) and Gemini API terms at [https://ai.google.dev/gemini-api/terms](https://ai.google.dev/gemini-api/terms).

**Your explicit consent is required** before any image is sent to Google. This consent is obtained via the in-app consent screen shown before your first scan. You may decline consent and the app's offline features (phrase library, settings) will continue to function.

---

## 3. Data we do not collect

To be explicitly clear, Taberu does not collect:

- Your name, email address, or contact information
- Your location or GPS data
- Your Apple ID or device identifier
- Browsing history or usage patterns (beyond anonymised crash data)
- Payment information (handled entirely by Apple)
- Any information about you as an individual
- Biometric data
- Health or medical information

---

## 4. Cross-border data transfers

When you use Taberu's scanning feature, your food images are transmitted to Google's servers, which may be located outside Japan, Australia, or your home country. This transfer is necessary for the app to function.

**For users in Japan:** This transfer is conducted in accordance with Japan's Act on the Protection of Personal Information (APPI). Google maintains appropriate data protection measures for cross-border transfers.

**For users in the EU/EEA:** Transfers to Google are covered by Google's Standard Contractual Clauses and their compliance with applicable EU data protection law. Japan has received an EU adequacy decision, and Ash Every Design Office operates under APPI which aligns with GDPR principles.

**For users in Australia:** This transfer is conducted in accordance with the Australian Privacy Act 1988 and the Australian Privacy Principles (APPs).

---

## 5. Your rights

Depending on your location, you may have the following rights regarding your data:

**All users:**
- You can stop using Taberu at any time, which ends all data processing
- You can delete the app, which removes all locally stored preferences from your device
- You can contact us at hello@aedo.jp with any privacy concerns

**EU/EEA users (under GDPR):**
- Right to access the personal data we hold about you
- Right to rectification of inaccurate data
- Right to erasure ("right to be forgotten")
- Right to restrict processing
- Right to object to processing
- Right to withdraw consent at any time
- Right to lodge a complaint with your supervisory authority

*Note: Because Taberu does not collect personal data that identifies you, many of these rights have limited practical application. We do not hold a profile of you that can be accessed, corrected, or deleted. Your scan images are not retained.*

**Japan users (under APPI):**
- Right to disclosure of retained personal information
- Right to correction of incorrect personal information
- Right to cessation of use of personal information
- Right to cessation of third-party provision

**Australian users (under Privacy Act 1988):**
- Right to access personal information we hold about you
- Right to correct personal information that is inaccurate

**US users (including California residents under CCPA/CPRA):**
- We do not sell your personal information — ever
- We do not share your personal information for cross-context behavioural advertising
- We do not use your data for targeted advertising of any kind
- Because we do not collect personal identifying information such as names or email addresses, we cannot link app usage back to you as a verifiable consumer under CCPA definitions
- If you have privacy questions as a US resident, contact us at hello@aedo.jp

To exercise any of these rights, contact us at hello@aedo.jp. We will respond within 30 days.

---

## 6. Data security

We take appropriate technical measures to protect data in transit:

- All communications between Taberu and Google's Gemini API use HTTPS encryption
- Images are compressed on your device before transmission to minimise data exposure
- No scan data is stored on our servers — we do not operate servers that hold your images
- Your preferences are stored in your device's local storage, not transmitted to us

---

## 7. Data retention

**Scan images:** Not retained. Images are processed by Google's Gemini API and discarded after the response is generated.

**App preferences:** Stored locally on your device for as long as the app is installed. Deleted when you uninstall the app or clear the app's data.

**Crash/analytics data:** Retained for up to 90 days for the purpose of diagnosing technical issues, then deleted automatically.

We do not maintain a database of your scans, preferences, or usage history on our servers.

---

## 8. Children's privacy

Taberu is not directed at children under the age of 13 (or 16 in the EU). We do not knowingly collect personal information from children. If you are a parent or guardian and believe your child has used Taberu without appropriate supervision, please contact us at hello@aedo.jp.

Users under 18 must use Taberu under the supervision of a parent or legal guardian, as outlined in our Terms of Service.

---

## 9. Third-party services

Taberu uses the following third-party services:

| Service | Provider | Purpose | Privacy Policy |
|---------|----------|---------|---------------|
| Gemini AI | Google LLC | Food image translation | [policies.google.com/privacy](https://policies.google.com/privacy) |
| Sentry (if enabled) | Sentry Inc | Crash reporting | [sentry.io/privacy](https://sentry.io/privacy/) |
| Apple App Store | Apple Inc | App distribution and payment | [apple.com/legal/privacy](https://www.apple.com/legal/privacy/) |

We are not responsible for the privacy practices of these third parties. We encourage you to review their privacy policies.

---

## 10. Cookies and tracking

Taberu does not use cookies. Taberu does not track your behaviour across other apps or websites. Taberu does not use advertising identifiers or participate in any advertising network.

---

## 11. Changes to this policy

We may update this Privacy Policy from time to time. When we do, we will:

- Update the "Last updated" date at the top of this document
- Make the updated policy available at the same URL
- Notify users via an in-app notice for significant changes

Continued use of Taberu after changes are posted constitutes acceptance of the revised policy.

---

## 12. Applicable law and regulatory authorities

This Privacy Policy is governed by the laws of Japan, including the Act on the Protection of Personal Information (APPI).

**Regulatory authorities:**

- **Japan:** Personal Information Protection Commission (PPC) — [ppc.go.jp](https://www.ppc.go.jp)
- **EU/EEA:** Your local data protection authority — [edpb.europa.eu](https://edpb.europa.eu/about-edpb/about-edpb/members_en)
- **Australia:** Office of the Australian Information Commissioner (OAIC) — [oaic.gov.au](https://www.oaic.gov.au)
- **UK:** Information Commissioner's Office (ICO) — [ico.org.uk](https://ico.org.uk)

---

## 13. Contact us

For any privacy-related questions, requests, or concerns:

**Email:** hello@aedo.jp
**Developer:** Ash Every Design Office (Ashley Every)
**Location:** Yamanashi, Japan

We aim to respond to all privacy enquiries within 30 days.

---

*Taberu — Eat with confidence*
*© 2026 Ash Every Design Office. All rights reserved.*
