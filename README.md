# Bayanat Labs contributor consent templates

> **Reviewed by counsel, October 2026. Adapt before use; not legal advice for your organisation.**

Six documents that Bayanat Labs has prepared for collecting speech, writing, annotations and sign-language video from consenting adult contributors for open Arabic datasets. Each comes in English and Arabic, as Markdown and as Word (DOCX). They are written for Saudi Arabia's Personal Data Protection Law (PDPL) and for releases on Hugging Face and Zenodo under open licences.

They are templates. Fields in `{{DOUBLE_BRACES}}` are for you to fill in (list below). If you use them for your own organisation, check them against the law that applies to you and take your own legal advice.

## The documents

| Document | What it is for | English | Arabic |
|---|---|---|---|
| **Consent form** (CF) | Asks each contributor for permission to record, process, publish and transfer their contributions, one box per purpose, with the risks and the limits of withdrawal in plain words. | [`en/consent_form.md`](en/consent_form.md) · [DOCX](en/consent_form.docx) | [`ar/consent_form.md`](ar/consent_form.md) · [DOCX](ar/consent_form.docx) |
| **Contributor agreement** (CA) | Covers copyright, performers' rights, tasks and pay: the open-licence grant (CC0 1.0 or CC BY 4.0, one per programme), rights in writing, transcripts and annotations, originality, confidentiality. Paid and volunteer variants. | [`en/contributor_agreement.md`](en/contributor_agreement.md) · [DOCX](en/contributor_agreement.docx) | [`ar/contributor_agreement.md`](ar/contributor_agreement.md) · [DOCX](ar/contributor_agreement.docx) |
| **Performer release for speech synthesis** (PRS) | A separate, optional release, off by default, for using a voice to build text-to-speech, voice conversion or anti-spoofing data. Separate signature and a cooling-off period. | [`en/performer_release_synthesis.md`](en/performer_release_synthesis.md) · [DOCX](en/performer_release_synthesis.docx) | [`ar/performer_release_synthesis.md`](ar/performer_release_synthesis.md) · [DOCX](ar/performer_release_synthesis.docx) |
| **Privacy notice** (PN) | Tells contributors what personal data is collected, why, on what legal basis, who receives it, how long it is kept and how to use their rights. Follows the structure of SDAIA's privacy-policy guideline. | [`en/privacy_notice.md`](en/privacy_notice.md) · [DOCX](en/privacy_notice.docx) | [`ar/privacy_notice.md`](ar/privacy_notice.md) · [DOCX](ar/privacy_notice.docx) |
| **Cross-border transfer statement** (CBS) | Explains what leaves Saudi Arabia when contributions are published (Hugging Face in the United States, Zenodo at CERN), what stays, the legal basis and the safeguards. | [`en/cross_border_statement.md`](en/cross_border_statement.md) · [DOCX](en/cross_border_statement.docx) | [`ar/cross_border_statement.md`](ar/cross_border_statement.md) · [DOCX](ar/cross_border_statement.docx) |
| **Explicit biometric consent for sign-language video** (BCSL) | For a sign-language video programme only: explicit consent per scope for identifiable video and pose keypoints, with a partner organisation, a recorded explainer in Saudi Sign Language and a cooling-off period. | [`en/biometric_consent_sign_language.md`](en/biometric_consent_sign_language.md) · [DOCX](en/biometric_consent_sign_language.docx) | [`ar/biometric_consent_sign_language.md`](ar/biometric_consent_sign_language.md) · [DOCX](ar/biometric_consent_sign_language.docx) |

## How they fit together

1. **Consent form**: personal data. One box per purpose: recording and internal processing (CF-5.1), public release (CF-5.2) and transfer abroad (CF-5.3) are needed for a publication programme; labels, voice fingerprints, credit, project updates and vendor tests are optional. Synthesis is never in this form.
2. **Contributor agreement**: rights and pay. One open licence per programme, set in Schedule 1.
3. **Performer release**: synthesis only, separate signature, off by default.
4. **Privacy notice** and **cross-border statement**: what happens to the data and where it goes.
5. **Biometric consent**: used with the others, only for a sign-language video programme.

## Rules built into the templates

- Adults only (18 or over); no guardian consent; suspected minors set aside.
- One box per purpose, nothing ticked in advance; optional boxes never affect pay.
- Synthesis needs a separate opt-in; without it, speech is published at 16 kHz with a "not for voice cloning" request.
- Pseudonymous speaker IDs that change with every release; names never published; location labels at country level only.
- Withdrawal stops future use and removes contributions from the next version within 30 days, but cannot recall copies already downloaded.
- Originals, identity, payment and consent records stay in Saudi Arabia; only release files leave the Kingdom.
- Contributors can complain to the organisation or to SDAIA.

## How to adapt them

1. Fill every field listed below, in both languages. Keep the clause IDs (CF-1, CA-4 and so on) so the documents can refer to each other.
2. Choose the options the templates offer: the open licence (CA-4), assignment or licence of work products (CA-8), the prevailing language (CA-18).
3. Check the legal basis, transfer and retention clauses against the law that applies to you. The legal references are to the Saudi PDPL, its Implementing Regulation and the Regulation on Personal Data Transfer outside the Kingdom.
4. Have a qualified native reader review the Arabic text for your context.
5. Remove Bayanat Labs' name and contact details and put in your own.

## Template fields

69 fields. Each appears in both languages, except the legal name, which has an Arabic and an English field.

| Field | What to fill in | Used in |
|---|---|---|
| `{{AGE_CHECK_METHOD}}` | How you verify that a contributor is 18 or older | CF |
| `{{AGREEMENT_VERSION}}` | Version ID of the contributor agreement | CA |
| `{{BENCHMARK_VENDORS}}` | Commercial speech and language services that receive test copies (only with box CF-5.9) | CF, CBS, PN |
| `{{BIO_CONSENT_VERSION}}` | Version ID of the sign-language biometric consent | BCSL |
| `{{CA8_OPTION}}` | Work-product option in CA-8: 1 (assignment) or 2 (licence) | CA |
| `{{CLOUD_PROVIDER}}` | Provider of private storage and computing | PN |
| `{{COMPLAINT_SLA_DAYS}}` | Days within which you aim to resolve complaints | PN |
| `{{CONSENT_VERSION}}` | Version ID of the consent form | CF |
| `{{CONTRACTOR_STATUS_TEXT}}` | Wording on independent-contractor status for paid contributors | CA |
| `{{COOLING_OFF_DAYS}}` | Days between the last session and first publication (the templates suggest 14) | BCSL, PRS |
| `{{COPY_DELIVERY_METHOD}}` | How the contributor receives a copy of their consent record | CF |
| `{{CREDIT_NAME_FORMAT}}` | How credited names appear in acknowledgements | CF |
| `{{CR_NUMBER}}` | Commercial Registration number of the controller | CF, CA, PN |
| `{{CURRENCY}}` | Payment currency | CA |
| `{{DISPUTE_FORUM}}` | Court or other forum for disputes | CA |
| `{{DPO_CONTACT}}` | Contact details of the personal data protection officer | CF, PN |
| `{{DPO_NAME_OR_ROLE}}` | Personal data protection officer, or the privacy lead's role | CF, PN |
| `{{EMBEDDING_RETENTION}}` | When internal voice fingerprints are deleted | CF |
| `{{ESIGN_METHOD}}` | How consent is captured (for example e-signature with a timestamp) | CF |
| `{{ESIGN_PROVIDER}}` | E-signature tool | CA, PN |
| `{{FOREIGN_PROCESSORS}}` | Processors located outside Saudi Arabia, or "none" | CBS, PN |
| `{{GOVERNING_LAW}}` | Law that governs the agreement | CA |
| `{{HF_ORG}}` | Hugging Face organisation that hosts the releases | CA |
| `{{IF_DECLINED_EFFECT}}` | What happens if a contributor leaves box CF-5.5 empty | CF |
| `{{KEY_HOLDER_ROLE}}` | Role that holds the key linking pseudonymous IDs to names | PN |
| `{{LANGUAGE_CHOSEN}}` | Language in which the contributor read the documents | CF |
| `{{LEGAL_ENTITY_NAME_AR}}` | Registered legal name in Arabic (Arabic texts) | CF, CA, PN |
| `{{LEGAL_ENTITY_NAME_EN}}` | Registered legal name in English (English texts) | CF, CA, PN |
| `{{LIABILITY_CAP}}` | Cap on liability to the contributor | CA |
| `{{MIRROR_PLATFORMS}}` | Other platforms where releases are mirrored, if any | CF, CBS |
| `{{NDGP_CERTIFICATE_NO}}` | Registration certificate number on SDAIA's National Data Governance Platform, if any | CF |
| `{{NDGP_REGISTRATION_STATUS}}` | Status on SDAIA's national register of controllers | CF, PN |
| `{{NON_KSA_LAW_ANNEX}}` | Annex for contributors resident outside Saudi Arabia (data-protection law) | PN |
| `{{NON_KSA_TRANSFER_ANNEX}}` | Annex for contributors resident outside Saudi Arabia (transfer rules) | CBS |
| `{{PARTNER_AGE_CHECK}}` | How the partner organisation checks age | BCSL |
| `{{PARTNER_MOU_REF}}` | Reference of the memorandum of understanding with the partner | BCSL |
| `{{PARTNER_NAME}}` | Partner organisation (for example a Deaf community organisation) | BCSL, PN |
| `{{PARTNER_ROLE}}` | Partner's role under the PDPL (joint controller, processor or independent party) | BCSL, PN |
| `{{PAYMENT_PROVIDER}}` | Bank or payment service used to pay contributors | CA, CBS, PN |
| `{{PAYMENT_PROVIDER_LOCATION}}` | Where the payment provider processes data | CBS |
| `{{PAYMENT_TERMS_DAYS}}` | Days from acceptance to payment | CA |
| `{{PAY_TABLE_REF}}` | Reference to the published pay table | CA |
| `{{PREVAILING_LANGUAGE}}` | Language that prevails if the Arabic and English texts differ | CA |
| `{{PRIVACY_CONTACT_EMAIL}}` | Mailbox for privacy requests and withdrawal | BCSL, CF, CA, PN |
| `{{PRIVACY_NOTICE_URL}}` | Public address of the privacy notice | PN |
| `{{PRIVACY_NOTICE_VERSION}}` | Version ID of the privacy notice | PN |
| `{{PROGRAMME_NAME}}` | Name of the contributor programme | CF, CA |
| `{{RECORDER_HOST}}` | Where the recorder or task portal is hosted | PN |
| `{{REGISTERED_ADDRESS}}` | Registered (and national) address of the controller | CF, CA, PN |
| `{{RELEASE_LICENCE}}` | Open licence of the programme: CC0 1.0 or CC BY 4.0 | CF, CA, PRS |
| `{{RESPONSE_DAYS}}` | Days a contributor has to respond before suspension | CA |
| `{{RETENTION_ACCOUNT}}` | Retention period for contact and account data | CF |
| `{{RETENTION_CONSENT_RECORDS}}` | Retention period for consent records | CF |
| `{{RETENTION_PAYMENT_RECORDS}}` | Retention period for payment records | CF |
| `{{RETENTION_RAW}}` | Retention period for private original recordings, images and texts | CF |
| `{{SENSITIVE_CONTENT_ANNEX}}` | Task annex for scripted offensive or unsafe content | CA |
| `{{SSL_EXPLAINER_VIDEO_REF}}` | Reference to the consent explainer video in Saudi Sign Language | BCSL |
| `{{STORAGE_REGION}}` | Provider and region of private storage (Bayanat Labs: inside Saudi Arabia) | CF, CA, CBS, PN |
| `{{STUDIO_TALENT_CONTRACT}}` | Separate contract for professional or studio voice talent | PRS |
| `{{SYNTHESIS_PAYMENT_TERMS}}` | Pay terms for the synthesis opt-in | PRS |
| `{{SYNTH_RELEASE_VERSION}}` | Version ID of the synthesis release | PRS |
| `{{TAKEDOWN_EMAIL}}` | Address for takedown and misuse reports (Bayanat Labs: hello@bayanatlabs.com) | PRS, PN |
| `{{TASK_TYPES}}` | Task types in the programme | CA |
| `{{TAX_TREATMENT}}` | Withholding tax, VAT and reporting wording | CA |
| `{{TEST_SET_PARTNERS}}` | Research partners that receive held-back test sets | CF, PN |
| `{{VENDOR_TERMS_REFS}}` | References to the vendor terms you reviewed | CF |
| `{{WITHDRAWAL_SLA_DAYS}}` | Days to act on a withdrawal request (the templates suggest 30) | BCSL, CF, CA, PRS, PN |
| `{{WITHDRAWAL_URL}}` | Withdrawal page | CF |
| `{{XBORDER_VERSION}}` | Version ID of the cross-border statement | CBS |

## Languages and review

English and Arabic (Modern Standard Arabic). The Arabic text has not yet been reviewed by a native Arabic writer; the English governs. When you adapt the templates, you choose in CA-18 which language prevails in the signed documents.

## Licence and citation

The templates are licensed under the [Creative Commons Attribution 4.0 International licence](LICENSE) (CC BY 4.0). Attribute "Bayanat Labs" and link to this repository. Cite them with [`CITATION.cff`](CITATION.cff).

## Contact

Questions, corrections and takedown requests: **hello@bayanatlabs.com**. More on the programme: <https://www.bayanatlabs.com/open>.

---

## ملخص بالعربية

> **روجعت من مستشار قانوني، أكتوبر 2026. عدّلها قبل الاستخدام؛ ليست استشارة قانونية لمؤسستك.** (Reviewed by counsel, October 2026. Adapt before use; not legal advice for your organisation.)

يضم هذا المستودع ست وثائق أعدّتها بيانات لابز (Bayanat Labs) لجمع الكلام والكتابات والتوسيمات وفيديو لغة الإشارة من مساهمين بالغين موافقين، لإعداد مجموعات بيانات عربية مفتوحة. وكل وثيقة متاحة بالعربية والإنجليزية، بصيغتي Markdown وWord (DOCX)، وقد كُتبت وفق نظام حماية البيانات الشخصية في المملكة العربية السعودية، وللنشر على Hugging Face وZenodo برخص مفتوحة.

| الوثيقة | الغرض منها |
|---|---|
| **نموذج الموافقة** (CF): [`ar/consent_form.md`](ar/consent_form.md) | يطلب من المساهم الإذن بالتسجيل والمعالجة والنشر والنقل، بخانة مستقلة لكل غرض، ويشرح المخاطر وحدود العدول عن الموافقة بلغة واضحة. |
| **اتفاقية المساهم** (CA): [`ar/contributor_agreement.md`](ar/contributor_agreement.md) | تنظّم حق المؤلف وحقوق المؤدين والمهام والأجر: منح الرخصة المفتوحة، والحقوق في الكتابات والتفريغات والتوسيمات، والأصالة، والسرية؛ بصيغتين بأجر وتطوعية. |
| **إذن تركيب الكلام واستخدام الشبه الصوتي** (PRS): [`ar/performer_release_synthesis.md`](ar/performer_release_synthesis.md) | إذن مستقل واختياري، غير مفعّل افتراضيًا، لاستخدام الصوت في تحويل النص إلى كلام أو تحويل الصوت أو بيانات كشف التزييف. |
| **إشعار الخصوصية** (PN): [`ar/privacy_notice.md`](ar/privacy_notice.md) | يبيّن البيانات الشخصية التي تُجمع، وأغراضها، ومسوغها النظامي، والجهات التي تتسلّمها، ومدد الاحتفاظ بها، وكيفية ممارسة الحقوق. |
| **بيان نقل البيانات خارج المملكة** (CBS): [`ar/cross_border_statement.md`](ar/cross_border_statement.md) | يوضح ما يخرج من المملكة عند النشر وما يبقى فيها، والمسوغ النظامي، والضمانات. |
| **الموافقة الصريحة على البيانات الحيوية لتسجيلات لغة الإشارة** (BCSL): [`ar/biometric_consent_sign_language.md`](ar/biometric_consent_sign_language.md) | لبرنامج فيديو لغة الإشارة فقط: موافقة صريحة لكل نطاق، مع جهة شريكة وشرح مرئي بلغة الإشارة السعودية ومهلة للتروي. |

الحقول بين قوسين معقوفين مزدوجين `{{...}}` تُملأ عند الاستخدام، وقائمتها في الجدول الإنجليزي أعلاه. وإذا استخدمت هذه القوالب لمؤسستك فراجعها في ضوء النظام الذي ينطبق عليك واطلب المشورة القانونية المناسبة. لم يراجع النصَّ العربي بعدُ كاتبٌ لغته الأم العربية، والنص الإنجليزي هو المعتمد.

الترخيص: رخصة المشاع الإبداعي، نسب المصنف 4.0 الدولية (CC BY 4.0)، مع نسب العمل إلى «بيانات لابز». للتواصل: **hello@bayanatlabs.com**.
