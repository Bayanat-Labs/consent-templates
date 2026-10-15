---
title: "Bayanat Labs contributor consent form (template v1.0)"
lang: en
dir: ltr
---

> **Reviewed by counsel, October 2026. Adapt before use; not legal advice for your organisation.**
>
> Document ID: `BL-CONSENT` · Version: `{{CONSENT_VERSION}}` · Programme: `{{PROGRAMME_NAME}}` · Language pair: this English text and the Arabic text (`ar/consent_form.md`). If the two texts differ, the language named in the Contributor Agreement (CA-18) prevails.

## How to read this form

This form asks for your permission to record and use what you contribute. It is written in plain language. Each permission has its own box. No box is ticked for you. Optional boxes can stay empty and you can still take part. Separate documents give more detail: the Contributor Agreement (`contributor_agreement`), the Privacy Notice (`privacy_notice`), the Cross-Border Statement (`cross_border_statement`) and, only if you choose it, the Synthesis Release (`performer_release_synthesis`).

---

### CF-1 Who is asking

The organisation responsible for your data (the controller) is:

- Legal name: `{{LEGAL_ENTITY_NAME_EN}}` (trading as Bayanat Labs)
- Commercial Registration number: `{{CR_NUMBER}}`
- Registered address: `{{REGISTERED_ADDRESS}}`
- Privacy contact: `{{PRIVACY_CONTACT_EMAIL}}`
- Personal data protection officer, if one is appointed: `{{DPO_NAME_OR_ROLE}}`, `{{DPO_CONTACT}}`
- Registration in SDAIA's national register of controllers: `{{NDGP_REGISTRATION_STATUS}}` (certificate number `{{NDGP_CERTIFICATE_NO}}`, if any)

### CF-2 What we are asking you to do

You will do one or more of these tasks in the Bayanat Labs recorder or task portal. The programme schedule tells you which ones apply.

| Task | What you do | What we keep |
|---|---|---|
| Read prompts | Read short sentences, numbers, dates or commands shown on screen | Your audio and the prompt text |
| Spontaneous speech | Answer an everyday question or describe a picture, up to 120 seconds | Your audio and a transcript |
| Role-play | Play a customer in a fictional service call, using made-up names and numbers | Your audio and a transcript |
| Writing tasks | Write or rewrite short texts in your dialect | Your text |
| Handwriting | Write lines or characters on paper or a tablet and upload an image | The image and its transcript |
| Rating and checking | Listen to or read other people's contributions and give votes or labels | Your votes and labels |

Sign-language video is covered by a separate form (`biometric_consent_sign_language`). Contributions that let people copy your voice for speech synthesis need a separate opt-in (`performer_release_synthesis`).

### CF-3 Who can take part: adults only (18 or older)

1. You must be 18 or older on the day you take part. We do not accept consent from a parent or guardian on behalf of anyone younger. We never record anyone under 18.
2. We check age by `{{AGE_CHECK_METHOD}}` (for example: a date-of-birth declaration plus the existing Talent Network contract check for paid contributors). We keep only a yes/no "age confirmed" flag in the contribution system. We never publish your age or date of birth.
3. If a reviewer thinks a recording or image may come from a person under 18, we set it aside at once, pause the account and check. If we cannot confirm the person is an adult, we delete the contribution.
4. Content made for children (for example, a story read aloud by an adult) is allowed. Recordings of children are not.

### CF-4 Your choice is free

1. Taking part is voluntary. You can stop at any time, without giving a reason.
2. If you are paid, your pay for completed tasks does not depend on ticking any optional box. Optional boxes never change your pay, your Talent Network standing or future invitations.
3. You may decline the publication boxes in CF-5.2 and CF-5.3. If you do, we cannot use your contributions in this programme, because its purpose is an open public release. We will tell you this before you start, and you will not be asked to record.
4. Nobody from Bayanat Labs may pressure you to tick a box. If you feel pressured, tell `{{PRIVACY_CONTACT_EMAIL}}`.

### CF-5 What you agree to (one box per purpose)

**CF-5.1 Recording and internal processing (needed to take part).**
☐ I agree that Bayanat Labs may record or receive my contributions and process them internally: store them in private storage in `{{STORAGE_REGION}}`, check their quality, transcribe them, have other contributors validate them, remove personal details, prepare them for release, and keep some contributions unpublished in held-back test sets used to evaluate speech and language systems (these are never shared outside Bayanat Labs except with research partners named in the programme schedule, `{{TEST_SET_PARTNERS}}`, under a confidentiality agreement).

**CF-5.2 Public release under an open licence (needed for this programme).**
☐ I agree that Bayanat Labs may publish my contributions in public datasets under `{{RELEASE_LICENCE}}` (CC0 1.0 or CC BY 4.0, as stated in the programme schedule). I understand that anyone in the world may then download, copy, change and use them for any purpose, including training artificial-intelligence systems and commercial use. I understand that **once a version is published, it cannot be recalled** (see CF-9).

**CF-5.3 Transfer outside Saudi Arabia for publication (needed for this programme).**
☐ I agree that the published files will be stored on Hugging Face (servers in the United States) and on Zenodo (operated by CERN, files stored in CERN data centres in Geneva with replicas in Budapest), and on any mirror named in the programme schedule (`{{MIRROR_PLATFORMS}}`), and can then be downloaded from any country. Details are in the Cross-Border Statement.

**CF-5.4 Publishing my descriptive labels (optional).**
☐ I agree that the following labels may be published next to my contributions under a pseudonymous ID: age band (18-29, 30-44, 45-59, 60+), gender (if I give it), dialect region and country of upbringing. No city or other location below country level is published.
If you leave this box empty, we publish your contributions without these labels.

**CF-5.5 Internal voice checks for fraud and fair splits (optional, internal only).**
☐ I agree that Bayanat Labs may compute a voice "fingerprint" (speaker embedding) from my recordings, only inside Bayanat Labs, to detect one person using several accounts, detect machine-generated or replayed audio, and keep the same speaker out of both training and test sets. These fingerprints are never published and are deleted `{{EMBEDDING_RETENTION}}`.
If you leave this box empty, we do not compute fingerprints from your recordings. `{{IF_DECLINED_EFFECT}}`

**CF-5.6 Speech synthesis and voice likeness (optional, separate form, off by default).**
This form does not give permission for anyone to build a voice that sounds like you. That needs the separate Synthesis Release. If you do not sign it, your recordings are published only in speech-recognition sets at 16 kHz.

**CF-5.7 Credit by name (optional, off by default).**
☐ I would like to be credited by name (`{{CREDIT_NAME_FORMAT}}`) in the dataset's acknowledgements. My name will never be linked to my recordings or my pseudonymous ID.

**CF-5.9 Testing commercial speech and language services (optional unless the programme schedule says it is required).**
☐ I agree that Bayanat Labs may send copies of my recordings or texts to the commercial speech and language services named in the programme schedule (`{{BENCHMARK_VENDORS}}`) to measure how well they work. These services may be outside Saudi Arabia and handle the data under their own terms, which Bayanat Labs reviews before use (`{{VENDOR_TERMS_REFS}}`).
If you leave this box empty, your contributions are used only with systems that Bayanat Labs runs itself.

**CF-5.8 Updates about future Bayanat Labs projects (optional).**
☐ Bayanat Labs may email me about future contributor projects. I can unsubscribe at any time.

### CF-6 What becomes public and what never does

| Published (if you agreed in CF-5) | Never published |
|---|---|
| Your audio, text, handwriting image or labels | Your name (unless CF-5.7, and then never linked to contributions) |
| The prompt or transcript | Phone number, email, address, national ID or Iqama number, date of birth |
| A pseudonymous speaker ID, generated at random and different in every release | Your Talent Network or account ID |
| Age band, gender, dialect region, country of upbringing (only with CF-5.4) | Payment details, bank details and amounts paid |
| Technical details: device type, room type you reported, sample rate | Your consent record and signature |
| | Voice fingerprints (speaker embeddings) |
| | Tribe, sect, religion, political views, health, nationality beyond country of upbringing |

A pseudonymous ID is not the same as anonymity. Your voice, handwriting or way of writing can still be recognised by people who know you.

### CF-7 Risks you should understand

1. **People may recognise you.** Your voice, accent, handwriting or writing style can identify you to people who know you.
2. **Anyone can use the data.** An open licence lets anyone use your contributions for any purpose. We cannot control what they do.
3. **Voice copying is possible.** Even the 16 kHz recognition sets can be used to imitate a voice. We ask users not to do this, but the licence does not forbid it. If you use voice authentication (for example, at a bank), consider this risk before you take part.
4. **Published copies stay available.** Earlier versions remain in public repository history and archives (see CF-9).
5. **What you say can reveal things about you.** Avoid personal details (see CF-8).

### CF-8 Protecting yourself and other people

1. Do not say or write your own name or anyone else's name, phone number, address, ID number, account number or email.
2. Do not talk about your own or anyone else's health, religion, political views, family disputes or legal cases.
3. In role-plays, use only the fictional names, companies and numbers on the card.
4. Two-person tasks happen only between two contributors who have both signed this form, each on their own device. We never record a third person.
5. Make sure no one else's voice is audible in your recording and no other person, document or screen appears in your images.
6. We check every contribution. We delete (never bleep or blur) any recording or image that contains a real person's identifying details or sensitive information, and we may pause tasks that keep doing so.

### CF-9 Changing your mind (withdrawal) and its limits

**How.** Email `{{PRIVACY_CONTACT_EMAIL}}`, use the withdrawal page `{{WITHDRAWAL_URL}}`, or tell the facilitator. Withdrawing is as easy as agreeing. You do not need to give a reason.

**What we do.**
1. We stop recording and processing new contributions from you at once.
2. Within `{{WITHDRAWAL_SLA_DAYS}}` days (default 30) we delete your contributions and voice fingerprints from our internal storage, except the minimum consent and payment records we must keep (CF-10).
3. Your contributions are left out of every **future** version of the dataset, and we publish a changelog entry with the count removed (never your identity).
4. We tell mirrors and partners who are bound by our terms to remove them too.

**What we cannot do.**
1. We cannot recall copies that were already published and downloaded. Under `{{RELEASE_LICENCE}}` the permission already given to the public cannot be taken back.
2. Earlier versions remain in Hugging Face repository history and on Zenodo. Zenodo keeps the record's DOI and address even when a record is withdrawn. We rewrite repository history only after a legal takedown decision.
3. Models that others have already trained cannot be "untrained".
4. Withdrawal does not undo processing that was lawful before you withdrew.

### CF-10 How long we keep things

| Item | Kept for | Then |
|---|---|---|
| Original recordings, images and texts (private) | `{{RETENTION_RAW}}` | Deleted, or kept only in published form |
| Published release files | For the life of the public release | Removed from future versions on withdrawal |
| Voice fingerprints (CF-5.5) | `{{EMBEDDING_RETENTION}}` | Deleted |
| Consent record (version, time, boxes ticked) | `{{RETENTION_CONSENT_RECORDS}}` | Deleted |
| Contact and account details | `{{RETENTION_ACCOUNT}}` | Deleted |
| Payment records | `{{RETENTION_PAYMENT_RECORDS}}` (as tax law requires) | Deleted |

### CF-11 Your rights and how to complain

You can ask to be informed, to see your data, to get a copy, to correct it, and to have it destroyed when it is no longer needed. We answer within 30 days (we may extend once, by up to 30 more days, and we will tell you why). See the Privacy Notice section PN-8.

If you are not satisfied, you can complain to the Saudi Data and Artificial Intelligence Authority (SDAIA) through the National Data Governance Platform: https://dgp.sdaia.gov.sa/wps/portal/pdp/services/reportscomplaints.

### CF-12 Record of your consent

We keep a record of: this form's version (`{{CONSENT_VERSION}}`) and its SHA-256 hash, the date and time (UTC), how you agreed (`{{ESIGN_METHOD}}`), and which boxes you ticked. You receive a copy by `{{COPY_DELIVERY_METHOD}}`. The record is stored separately from your contributions and is never published.

### CF-13 Confirmation

☐ I am 18 or older.
☐ I have read this form, the Privacy Notice and the Cross-Border Statement, in the language I chose (`{{LANGUAGE_CHOSEN}}`).
☐ I understand that published versions cannot be recalled.

Name (kept privately, never published): ____________________  Date: ____________
Signature or e-signature reference: ____________________

---

*Changelog:* v1.0 (15 Oct 2026): first version. Location labels limited to country level. Structure follows the order of topics in the Mozilla Common Voice terms (eligibility, contributions, account, communications, disclaimers, updates, termination, governing law); all wording is new.
