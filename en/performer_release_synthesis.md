---
title: "Bayanat Labs synthesis and voice-likeness release (template v1.0)"
lang: en
dir: ltr
---

> **Reviewed by counsel, October 2026. Adapt before use; not legal advice for your organisation.**
>
> Document ID: `BL-SYNTH` · Version: `{{SYNTH_RELEASE_VERSION}}`. **This release is separate and optional. It is OFF unless the contributor actively opts in.**

---

### PRS-1 What this release is about

"Synthesis use" means using recordings of your voice to build or test systems that **produce speech that sounds like you**. Examples:

- text-to-speech (a computer reads any text aloud in a voice like yours);
- voice cloning or voice conversion (changing someone else's speech so it sounds like you);
- expressive or singing synthesis (a system that speaks or sings in your style);
- making synthetic or "spoofed" copies of your voice so that detection systems can learn to spot fakes (anti-spoofing research).

### PRS-2 The default is OFF

1. If you do not sign this release, your recordings are published only in **speech-recognition** sets, at 16 kHz, with a request on every dataset card that users do not use them for voice cloning.
2. Not signing has no effect on your pay, your other tasks or your Talent Network standing.
3. Even 16 kHz recordings can technically be used to imitate a voice. A "no" here reduces that use; it cannot prevent it (Consent Form CF-7).

### PRS-3 What you allow if you opt in

Tick only the parts you agree to. Each part is separate.

☐ **PRS-3a High-quality publication for synthesis.** Bayanat Labs may publish your recordings at full quality (48 kHz) in synthesis datasets under `{{RELEASE_LICENCE}}`. Anyone may then train systems that produce speech that sounds like you, including for commercial use.

☐ **PRS-3b Synthetic copies for detection research.** Bayanat Labs may create synthetic or converted versions of your voice and publish them, labelled as synthetic, in datasets that teach systems to detect fake speech.

☐ **PRS-3c Expressive and acted styles.** Bayanat Labs may publish recordings in which you perform emotions, styles or singing, for synthesis research. (Applies only to programmes with acted or sung tasks.)

Professional or studio voice talent sign a separate talent contract in addition to this release: `{{STUDIO_TALENT_CONTRACT}}`.

### PRS-4 Risks you should weigh

1. **Impersonation.** Someone could make a voice that sounds like you say things you never said.
2. **Fraud.** A cloned voice could be used to try to fool voice-authentication systems (for example, at a bank) or people who know you.
3. **Reputation.** Synthetic speech in your voice could appear in places you dislike.
4. **No recall.** Once published, the recordings and any models already trained on them cannot be withdrawn (PRS-8).
5. Bayanat Labs cannot stop misuse by others. The open licence does not forbid synthesis or imitation.

Please take time to decide. You can ask questions before signing.

### PRS-5 What Bayanat Labs will do

1. Never publish your name or link your name to your voice. Speaker IDs are random and change with every release.
2. State on every synthesis dataset card that people must not use the voices to impersonate real people or to deceive, and that synthetic speech should be disclosed as synthetic. This is a request, not a licence condition.
3. Never market a dataset or model as a way to 'clone this person'.
4. Accept misuse reports at `{{TAKEDOWN_EMAIL}}` and remove affected files from future versions.
5. Label every synthetic sample made under PRS-3b as `synthetic: true`.

### PRS-6 Voice likeness and personality rights

To the extent the law gives you rights over your voice or likeness, you agree that the users of a Release may use your recordings for the synthesis uses you ticked in PRS-3, on the terms of the open licence.

### PRS-7 Cooling-off period

Bayanat Labs waits at least `{{COOLING_OFF_DAYS}}` days (default 14) after your last session before your recordings first appear in a synthesis dataset. During that time you can switch this release off by a simple message, with no reason needed, and your recordings will go only to recognition sets.

### PRS-8 Withdrawal and its limits

You can withdraw this release at any time (Consent Form CF-9). Bayanat Labs will leave your recordings out of all future synthesis releases within `{{WITHDRAWAL_SLA_DAYS}}` days and will not create new synthetic copies of your voice. Bayanat Labs cannot recall published versions or models that others have already trained.

### PRS-9 Payment

`{{SYNTHESIS_PAYMENT_TERMS}}`

### PRS-10 Explicit opt-in

☐ I have read this release. I understand that people may build voices that sound like mine and that this cannot be undone after publication. I choose to opt in to the parts I ticked in PRS-3.

Name (private): ____________  Date: ____________  Separate signature / e-signature reference: ____________

At the end of the first session the recorder asks again: 'Do you still want your voice to be available for speech synthesis?' If you answer no, PRS-3 is switched off.

---

*Changelog:* v1.0 (15 Oct 2026): first version.
