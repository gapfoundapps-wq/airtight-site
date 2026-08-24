# Airtight — Privacy policy

Effective 25 August 2026 · [Support](README.md)

---

## In short

Airtight collects the records an Australian business needs to show a work health and safety regulator. That includes **health information about workers**, because the law requires health monitoring for people who work with crystalline silica.

We do not sell data. We do not share it with third parties. We do not use it for advertising, and there are no advertising or analytics trackers in the app.

## Who we are

Airtight is published by Gapfound. For any privacy question, email **gapfound.apps@gmail.com**.

## Business and account information

| What | Why | Kept for |
| --- | --- | --- |
| Business name, ABN, trade, state | Identifies the business on every plan, record and audit pack | Life of account + 7 years |
| Your name and email | Signing in, and the "prepared by" line on plans | Life of account |
| Password | Signing in. Stored only as a bcrypt hash — we never hold the plain text | Life of account |
| Workplace names and addresses | A silica risk control plan is workplace-specific | Life of account + 7 years |
| Subscription status | Access to paid features | Life of account + 7 years |

## Worker information, including health information

This is the sensitive part of the app, and the part we deliberately keep smallest.

| What | Why | Kept for |
| --- | --- | --- |
| Worker name and role | To know who does high risk silica work, and so who is owed health monitoring and training | Up to 30 years, as the Regulations require |
| Date they started high risk silica work | Sets the health monitoring due date and the Silica Worker Register deadline | As above |
| **Health monitoring: the date it happened** | To schedule the next round and evidence the duty was met | 30 years |
| **Health monitoring: the practitioner** | The law requires monitoring by a registered medical practitioner with experience in health monitoring; the record shows who | 30 years |
| **Whether a report was received, whether it was adverse, whether it was given to the worker, whether the regulator was notified** | These four facts are the compliance record | 30 years |
| Training course, provider, completion date | The law requires a training record | 5 years after the worker leaves |
| Air monitoring results attributed to a worker | Personal exposure records | 30 years |

### What we deliberately do not collect

No chest X-ray or CT images. No spirometry or lung function values. No respiratory questionnaire answers. No diagnoses or findings. No medical history, medications or smoking history. No Medicare or health fund numbers. No date of birth by default.

Airtight records **that** health monitoring happened, **when**, **by whom**, and **whether the report was adverse**. The clinical record stays with the medical practitioner and in the employer's own confidential file, which is where the Regulations require it to be kept.

**Health monitoring must be performed by a registered medical practitioner.** Airtight does not perform, interpret or advise on it.

## Who we share it with

**Nobody.** Worker health information is never sent to any third party.

| Service | What it receives |
| --- | --- |
| RevenueCat | An anonymous account identifier and subscription events. No worker or health data. |
| Apple / Google | Payment processing, handled entirely by the platform. We never see card details. |
| Apple App Attest / Google Play Integrity | An app authenticity check. No personal data. |
| Safe Work Australia, SafeWork NSW | **Nothing.** Airtight reads their public documents; it never sends anything to them. |

Notifications to a regulator are made by you, through the regulator's own portal. Airtight records what is due and what you tell it you submitted. It never submits on your behalf.

## How it is protected

- **In transit:** every request uses HTTPS/TLS.
- **At rest:** records are held server-side and are readable only through the authenticated account that owns them.
- **On your phone:** the only credential the app stores is your session token, held in the iOS Keychain or Android Keystore. Records are displayed from the server, not cached to the device.
- **No keys in the app:** the app ships with no API keys or third-party credentials. Every third-party call is made by the server.

## Your rights

**Access and export** — you can export everything held about your business, including worker records, as an audit pack and a data file.

**Correction** — every record is editable by the business that owns it.

**Deletion** — email us and we will delete your account and business data within 30 days, *except* records under a statutory retention period. Air monitoring results and health monitoring records must be kept for 30 years, and training records for 5 years after a worker leaves. A business cannot discharge that duty by asking a supplier to delete the records, so those are exported to you and then held in a restricted archive until the period expires.

**Workers** — a worker may ask their employer for their own records. A health monitoring report must not be disclosed to anyone else without the worker's written consent, and Airtight's access model reflects that.

**Complaints** — email us first. If you are not satisfied, you may complain to the Office of the Australian Information Commissioner at [oaic.gov.au](https://www.oaic.gov.au).

## Children

Airtight is a workplace tool and is not directed at children. We do not knowingly collect information from anyone under 16 other than as a worker record entered by their employer.

## Changes

If this policy changes materially we will say so in the app before the change takes effect. The date at the top always reflects the current version.

---

Airtight is published by Gapfound. Last updated 25 August 2026.
