---
title: "Bayanat Labs contributor privacy notice (template v1.0)"
lang: en
dir: ltr
---

> **Reviewed by counsel, October 2026. Adapt before use; not legal advice for your organisation.**
>
> Document ID: `BL-PRIVACY` · Version: `{{PRIVACY_NOTICE_VERSION}}`. Scope: people who contribute recordings, texts, handwriting, video, labels or ratings to Bayanat Labs open-data programmes. It does not cover website visitors or users of Bayanat Labs tools.
>
> **Structure.** Sections PN-1 to PN-10 follow the ten elements of SDAIA's guideline on preparing a privacy policy (entity name and activity; contact details and update log; personal data collected; collection methods and purposes; processing; sharing; storage, retention and destruction; data-subject rights; complaints; availability of the policy). PN-11 to PN-16 add topics this programme needs.

---

### PN-1 Who we are and what we do

`{{LEGAL_ENTITY_NAME_EN}}` (trading as Bayanat Labs), Commercial Registration `{{CR_NUMBER}}`, `{{REGISTERED_ADDRESS}}`, Riyadh, Saudi Arabia. Bayanat Labs builds Arabic language data. Its open-data programme publishes datasets, benchmarks and tools under open licences. Bayanat Labs is the controller of the personal data described here. National-register status: `{{NDGP_REGISTRATION_STATUS}}`.

### PN-2 How to contact us, and changes to this notice

- Privacy questions and requests: `{{PRIVACY_CONTACT_EMAIL}}`
- Personal data protection officer (if appointed): `{{DPO_NAME_OR_ROLE}}`, `{{DPO_CONTACT}}`
- Removal and takedown requests: `{{TAKEDOWN_EMAIL}}` (Bayanat Labs: `hello@bayanatlabs.com`)
- Postal address: `{{REGISTERED_ADDRESS}}`

Update log: v1.0, 15 Oct 2026 (template). Each new version is listed here with its date and what changed. We tell active contributors before a change that affects them takes effect.

### PN-3 The personal data we collect

| Category | Examples | Required or optional | Published? |
|---|---|---|---|
| Identity and contact | Name, email, phone, country of residence | Required to take part | Never |
| Age confirmation | Date-of-birth declaration or a yes/no "18 or older" check | Required | Never (only an internal flag) |
| Contributions | Voice recordings, written texts, handwriting images, sign-language video (separate form), labels and votes | Required for the tasks you choose | Yes, if you ticked CF-5.2 |
| Descriptive labels | Age band, gender, dialect region, country of upbringing | Optional | Only with CF-5.4; never below country level |
| Session details | Device type, microphone type, room type you report, browser, time of recording | Required | Device and room type may be published; never browser or IP |
| Voice fingerprints | Speaker embeddings computed from your recordings | Optional (CF-5.5) | Never |
| Payment data (paid contributors) | Bank or wallet details, amounts, tax details | Required for payment | Never |
| Consent records | Form versions, boxes ticked, time, e-signature reference | Required | Never |
| Messages | Questions, complaints, withdrawal requests | When you contact us | Never |

We do not ask for, and ask you not to give us: tribe, sect, religion, political views, health information, or national ID or Iqama numbers (other than what a payment provider legally requires).

### PN-4 How we collect data, why, and on what legal basis

We collect data directly from you through the Bayanat Labs recorder or task portal (`{{RECORDER_HOST}}`), the e-signature tool (`{{ESIGN_PROVIDER}}`) and email.

| Purpose | Data used | Legal basis |
|---|---|---|
| P1 Run the programme: record, store, check, transcribe, validate | Contributions, session details, account | Your explicit consent (CF-5.1; PDPL Art. 5(1)) |
| P2 Publish open datasets | Contributions, pseudonymous ID, optional labels | Your explicit consent (CF-5.2) |
| P3 Transfer abroad for publication | Published files | Your explicit consent (CF-5.3); see the Cross-Border Statement |
| P4 Detect fraud and keep test sets clean | Voice fingerprints, account data | Your explicit consent (CF-5.5) |
| P5 Pay you | Payment data | Our agreement with you (PDPL Art. 6(2)) |
| P6 Prove consent and answer regulators | Consent records | A legal obligation |
| P7 Tell you about future projects | Email | Your explicit consent (CF-5.8; PDPL Art. 25) |
| P8 Test commercial speech and language services (benchmarks) | Copies of contributions | Your explicit consent (CF-5.9); see the Cross-Border Statement |
| P9 Keep held-back test sets and share them with named research partners | Unpublished contributions | Your explicit consent (CF-5.1) |

We do not rely on the research exception in PDPL Art. 27 for any of these purposes.

### PN-5 How we process your data

1. **Pseudonymous IDs.** In our systems your contributions are linked to a random ID. The key that links that ID to your name is stored separately, encrypted, and seen only by `{{KEY_HOLDER_ROLE}}`. Each public release uses a new random speaker ID, so IDs cannot be matched across releases.
2. **Quality checks.** Automatic checks (volume, noise, length, speech-recognition comparison) flag problems. A person decides whether to accept or reject a contribution. No decision about you is made by automated processing alone.
3. **Validation by other contributors.** Other contributors from your dialect region listen to or read your contributions and vote on them. They see your pseudonymous ID only.
4. **Removing personal details.** We scan transcripts and texts for names, numbers and other identifiers, and we delete recordings or images that contain them.
5. **Voice fingerprints (only with CF-5.5)** are used inside Bayanat Labs only, as the Consent Form describes.

### PN-6 Who we share data with

| Recipient | What they receive | Role |
|---|---|---|
| The public, worldwide | Published release files only | Recipients under the open licence |
| Hugging Face, Inc. (United States) | Published release files | Hosting platform |
| CERN, operator of Zenodo | Published release files | Archive and DOI service |
| `{{CLOUD_PROVIDER}}` (`{{STORAGE_REGION}}`) | All internal data | Processor (storage and computing) |
| `{{ESIGN_PROVIDER}}` | Name, email, signature | Processor |
| `{{PAYMENT_PROVIDER}}` | Payment data | Processor |
| Commercial speech and language services used for benchmark tests (only with CF-5.9) | Copies of recordings or texts | `{{BENCHMARK_VENDORS}}`; recipient under its own terms, which Bayanat Labs reviews before use |
| Research partners holding held-back test sets | Unpublished test contributions | `{{TEST_SET_PARTNERS}}`, under confidentiality |
| Other contributors acting as validators | Your contributions under a pseudonymous ID | Bound by confidentiality (CA-14) |
| `{{PARTNER_NAME}}` (only for partner programmes, such as sign-language recording) | As set out in that programme's form | `{{PARTNER_ROLE}}` |
| Authorities | Only what the law requires | — |

### PN-7 Storage, retention and destruction

Internal data is stored in `{{STORAGE_REGION}}` with encryption, access control and versioning. Retention periods are those in Consent Form CF-10. When a period ends we destroy the data, including backups, or keep it only in a form that cannot identify you.

### PN-8 Your rights

Under the Personal Data Protection Law you have the right:

1. to be informed about the legal basis and purpose of collection;
2. to access your personal data;
3. to request a copy in a readable and clear format;
4. to request correction, completion or updating;
5. to request destruction of your data when it is no longer needed, subject to legal retention duties;
6. to withdraw your consent at any time (see PN-15 for the limits).

Send requests to `{{PRIVACY_CONTACT_EMAIL}}`. We may ask you to confirm your identity. We answer within 30 days; if we need longer, we tell you why and answer within 30 more days at most.

### PN-9 Complaints

Please contact us first at `{{PRIVACY_CONTACT_EMAIL}}`; we aim to resolve complaints within `{{COMPLAINT_SLA_DAYS}}` days. You can also complain to SDAIA, the competent authority, through the National Data Governance Platform: https://dgp.sdaia.gov.sa/wps/portal/pdp/services/reportscomplaints. SDAIA's rules set a complaint window of 90 days from the incident or from when you became aware of it.

### PN-10 Where to find this notice

This notice is shown before you start, in Arabic and English, at `{{PRIVACY_NOTICE_URL}}`, and a short version appears in the recorder before each first session. A copy is sent with your consent record.

### PN-11 Adults only

Only people aged 18 or older may contribute. We do not collect data from children and do not accept a guardian's consent in their place. See Consent Form CF-3.

### PN-12 Transfers outside Saudi Arabia

Published files are stored on Hugging Face (servers in the United States) and Zenodo (CERN data centres in Geneva, with replicas in Budapest) and can be downloaded worldwide. Internal originals stay in `{{STORAGE_REGION}}`. Some processors may be abroad (`{{FOREIGN_PROCESSORS}}`). The Cross-Border Statement explains the purpose, safeguards and limits.

### PN-13 What "pseudonymous" means for you

A pseudonymous ID hides your name, but your voice, face, handwriting or style may still identify you. We therefore treat published contributions as personal data and ask for your explicit consent before publishing them.

### PN-14 Security and breaches

We use encryption, access controls and logging. If a breach is likely to harm you, we notify SDAIA within 72 hours of becoming aware of it and notify you without undue delay.

### PN-15 Withdrawing consent and its limits

Withdrawing is as easy as agreeing. We stop processing at once, delete internal copies within `{{WITHDRAWAL_SLA_DAYS}}` days and leave you out of future versions. We cannot recall copies already published or downloaded, and earlier versions remain in public repository history and archives. Full details: Consent Form CF-9.

### PN-16 Contributors who live outside Saudi Arabia

If you live in another country, its data-protection law may also apply: `{{NON_KSA_LAW_ANNEX}}`. We currently record only residents of Saudi Arabia, and record residents of another country only after its law has been reviewed.

---

*Changelog:* v1.0 (15 Oct 2026): first version. PN-4 states the legal basis Bayanat Labs adopted for each purpose; location labels limited to country level.
