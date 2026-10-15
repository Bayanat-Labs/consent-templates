---
title: "Bayanat Labs cross-border transfer statement for contributors (template v1.0)"
lang: en
dir: ltr
---

> **Reviewed by counsel, October 2026. Adapt before use; not legal advice for your organisation.**
>
> Document ID: `BL-XBORDER` · Version: `{{XBORDER_VERSION}}`.

---

### CBS-1 Why you are reading this

Bayanat Labs publishes open datasets on platforms hosted outside Saudi Arabia. Publishing your contributions there means your personal data leaves the Kingdom. This statement tells you what leaves, where it goes, why, and what protections exist and do not exist.

### CBS-2 What leaves the Kingdom and what stays

| Data | Leaves the Kingdom? | Where | When |
|---|---|---|---|
| Published release files: your audio, text, handwriting image or video, transcript, pseudonymous ID, optional labels | Yes | Hugging Face and Zenodo, then any downloader worldwide | At each release, only after quality, privacy and consent checks |
| Original full-quality recordings and images | No | `{{STORAGE_REGION}}` | — |
| Name, contact details, age confirmation, account ID | No, unless a processor abroad is used (`{{FOREIGN_PROCESSORS}}`) | `{{STORAGE_REGION}}` | — |
| Consent records and the key linking you to your pseudonymous ID | No | `{{STORAGE_REGION}}` | — |
| Voice fingerprints | No | `{{STORAGE_REGION}}` | — |
| Copies sent for benchmark testing (only with Consent Form CF-5.9) | Yes, if the vendor processes outside the Kingdom | `{{BENCHMARK_VENDORS}}` | During benchmark runs, under each vendor's reviewed terms |
| Payment data | Depends on the payment provider (`{{PAYMENT_PROVIDER}}`, `{{PAYMENT_PROVIDER_LOCATION}}`) | — | At payment |

### CBS-3 Destinations

1. **Hugging Face (United States).** Hugging Face's privacy policy states: "The Company and its servers are located in the United States." It also names an EU establishment, Hugging Face SAS in Paris.
2. **Zenodo (CERN).** Zenodo's terms state: "The Zenodo service (“Zenodo”) is offered by CERN as part of its mission to make available the results of its work." Its policies state: "All data files are stored in CERN Data Centres, primarily Geneva, with replicas in Budapest." CERN is an intergovernmental organisation; Geneva is in Switzerland and Budapest in Hungary (EU).
3. **Mirrors.** Where a programme also lists a release on another platform (for example a Kaggle mirror), that platform is named in the programme schedule: `{{MIRROR_PLATFORMS}}`.
4. **Everyone else.** Once published, files can be downloaded and copied from any country. Bayanat Labs cannot know or control where copies go.

### CBS-4 The legal basis for the transfer

Saudi Arabia's Personal Data Protection Law allows personal data to be transferred outside the Kingdom only for the purposes, and under the conditions, set out in its Article 29 and in the Regulation on Personal Data Transfer outside the Kingdom. The conditions include an adequate level of protection outside the Kingdom, limiting the transfer to the minimum personal data needed, and a transfer risk assessment in the cases the Regulation names.

Bayanat Labs relies on your explicit consent in Consent Form box CF-5.3 to publish your contributions abroad, and in box CF-5.9 to send copies to benchmark services. It applies the safeguards in CBS-5 and keeps your identity, payment and consent records in the Kingdom.

### CBS-5 Safeguards Bayanat Labs applies

1. Only release files leave the Kingdom; originals, keys, consent records and fingerprints stay in `{{STORAGE_REGION}}`.
2. Minimum data: no names, contact details, ID numbers or exact dates of birth; optional labels only with consent; no location below country level.
3. A personal-data audit (zero direct identifiers in a stratified 3,000-record sample) before every release.
4. A transfer risk assessment (Transfer Regulation Art. 7) and an entry in the records of processing before the first upload.
5. Nothing containing personal data is uploaded to any platform, including private repositories, before these checks pass.

### CBS-6 What you should understand

1. Data published on Hugging Face and Zenodo is subject to the laws of the countries where it is hosted and downloaded, which may protect it less than Saudi law.
2. We know of no published decision by the competent authority that these destinations provide protection equivalent to Saudi law.
3. Published copies cannot be recalled (Consent Form CF-9).

### CBS-7 Contributors who live outside Saudi Arabia

If you live in another country, your recordings may be transferred from that country to Saudi Arabia (for storage) and then to the destinations above. That country's law may set its own conditions: `{{NON_KSA_TRANSFER_ANNEX}}`. Bayanat Labs currently records only residents of Saudi Arabia, and records residents of another country only after that country's law has been reviewed.

### CBS-8 Your agreement

This statement explains the transfer that you agree to in Consent Form box CF-5.3. If you do not tick that box, your contributions will not be published.

---

*Changelog:* v1.0 (15 Oct 2026): first version. CBS-4 states the transfer basis Bayanat Labs adopted; location labels limited to country level.
