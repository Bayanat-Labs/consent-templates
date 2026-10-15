---
title: "Bayanat Labs explicit biometric consent for sign-language video (template v1.0)"
lang: en
dir: ltr
---

> **Reviewed by counsel, October 2026. Adapt before use; not legal advice for your organisation.**
>
> Document ID: `BL-BIO-SSL` · Version: `{{BIO_CONSENT_VERSION}}`. **Use only for a sign-language video programme.** Under Bayanat Labs' rules this is the single exception to the rule against face and biometric datasets. It is used together with the Consent Form, Contributor Agreement, Privacy Notice and Cross-Border Statement.
>
> **Language.** The signer receives this consent in Saudi Sign Language through a recorded explainer by a Deaf interpreter (`{{SSL_EXPLAINER_VIDEO_REF}}`) and in written Arabic. A Deaf facilitator from `{{PARTNER_NAME}}` is present.

---

### BCSL-1 What we record

Video of your face, hands and upper body while you sign words and sentences, from a front camera and a side camera, with no sound. From the video we compute body and hand position points (pose keypoints).

### BCSL-2 Why this is sensitive

Your face is visible and identifiable. Video like this may count as biometric data. It may also show, or let people infer, that you are Deaf or hard of hearing, which may count as health data.

### BCSL-3 Explicit consent

Each box below is a separate, explicit consent. Nothing is ticked for you.

☐ **BCSL-3a Recording and internal processing.** I agree to be filmed as described and to the internal processing in the Consent Form (CF-5.1).
☐ **BCSL-3b Publication of identifiable video.** I agree that the video, with my face and hands visible, may be published under CC BY 4.0 for anyone to use, including commercially.
☐ **BCSL-3c Publication of pose keypoints.** I agree that position points computed from my video may be published under CC BY 4.0.
☐ **BCSL-3d Transfer abroad.** I agree to publication on Hugging Face (United States) and Zenodo (CERN; Geneva and Budapest) as the Cross-Border Statement describes.

Optional (leave empty if you prefer):
☐ **BCSL-3e** Publish that I am Deaf or hard of hearing (hearing status) as a label.
☐ **BCSL-3f** Credit me by my real name in the acknowledgements (never linked to individual clips).
☐ **BCSL-3g** Allow me to record remotely with the browser recorder instead of in the studio.

### BCSL-4 Risks

1. Anyone can download the videos. People who know you can recognise you.
2. CC BY 4.0 allows any use. Others could use your face for face recognition or to build signing avatars that look or move like you. Bayanat Labs cannot forbid this.
3. Published versions cannot be recalled (BCSL-7).

### BCSL-5 Adults only

Only signers aged 18 or older take part. `{{PARTNER_NAME}}` checks age by `{{PARTNER_AGE_CHECK}}`; Bayanat Labs does not store a copy of any ID document.

### BCSL-6 Cooling-off period

At least `{{COOLING_OFF_DAYS}}` days (default 14) pass between your last recording session and the first publication of your videos. During that time you can withdraw any box by telling the facilitator or `{{PRIVACY_CONTACT_EMAIL}}`, in sign language, writing or any other way.

### BCSL-7 Withdrawal and its limits

You can withdraw at any time. We remove your clips from internal storage and from all future versions within `{{WITHDRAWAL_SLA_DAYS}}` days. Earlier versions stay in Hugging Face history and on Zenodo (Zenodo keeps the DOI and address of withdrawn records); we rewrite history only after a legal takedown decision.

### BCSL-8 The partner organisation

`{{PARTNER_NAME}}` helps recruit signers, provides the facilitator and checks age. Its role under the PDPL (joint controller, processor or independent party) is `{{PARTNER_ROLE}}`, set out in the memorandum of understanding `{{PARTNER_MOU_REF}}`.

### BCSL-9 Confirmation

☐ The explainer was shown to me in Saudi Sign Language and I had the chance to ask questions.
☐ I am 18 or older.

Name (private): ____________  Date: ____________  Signature or recorded signed confirmation reference: ____________  Facilitator: ____________

---

*Changelog:* v1.0 (15 Oct 2026): first version.
