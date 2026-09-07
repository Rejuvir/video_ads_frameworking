# Storyboard — "Cervicale" VSL (IT)

4 generated clips, all ≤60s. Reference ad analyzed: 3:10 AI-nurse UGC selfie VSL (EN, sciatica).

---

## 1. Reference-ad blueprint

- **Format** — 4:5 vertical (360×450), photoreal AI "UGC selfie" video. Not animation, not B-roll-driven.
- **Hook device** — 0:00–2:8s: a borrowed viral clip (woman's lower back in red leggings, cervical/lumbar spine + nerves illustrated directly on the skin, a hand working a massage tool over it) under a white band with black bold text: *"Stop Drinking This If You Have Sciatic Nerve Pain?"*. The voiceover's first line plays over it, then a hard cut to the presenter.
- **Shot density** — effectively **zero cuts** after the hook card. ffmpeg scene detection found no transitions across 187 seconds. One continuous head-and-shoulders selfie take carries the entire ad. Three near-invisible seams (≈1:50, ≈2:06) sit on natural breath pauses.
- **Framing / camera** — arm's-length front-facing phone, mild wide-angle distortion, presenter slightly left of frame, empty made-up hospital bed filling the right background, shallow depth of field, constant micro-drift and sway. She occasionally lifts her free hand into the lower-right of frame to gesture.
- **Visual devices** — none. No diagrams, no metaphor animations, no stock inserts, no before/after, **no product shot anywhere in 3:10**. All persuasion is carried by voice + captions.
- **Caption treatment** — burned-in, 2 lines, 3–5 words per line, white bold grotesque (Helvetica/Arial Bold), black rounded-rect box at ~90% opacity, centered, sitting at ~72% frame height. Phrase-synced, new card every ~2.2–2.5s. Sentence case, punctuation kept.
- **Sound** — the distinctive finding: **no music bed, no ambience, no SFX**. During speech gaps the track drops to ≈−54 dB. Dry, close, voice-only on near-silence — it reads as a real phone recording, not an ad. VO is wall-to-wall, only 0.45–0.67s micro-pauses, ~155–165 wpm.
- **Narrative phases** — hook card → false solutions rejected → "inflammation is only a symptom" reframe → named hidden mechanism → daily-suffering montage (spoken, not shown) → loss-of-independence stakes → doctor's dead end → the discovery → CTA. CTA is verbal only: "tap below," repeated, no button graphic, no urgency timer.

---

## 2. Character, Voice, Sound and Style Consistency Lock

### Canonical subject — ELENA (presenter, the only recurring subject)

> An Italian woman in her early thirties, medium build, oval face with a soft jawline, warm olive skin, dark brown almond-shaped eyes, thick natural eyebrows, a small mole below her left cheekbone, straight dark-brown hair pulled back into a low ponytail with a few loose strands at the temples, minimal natural makeup, small gold stud earrings, wearing a plain slate-blue V-neck nurse scrub top with a chest pocket and a thin silver bracelet on her right wrist.

Repeat this block **verbatim** at the start of every text-to-image prompt. Never write "the same woman" or "Elena" alone.

**Short identity anchor** for image-to-video prompts (repeat verbatim):
> the Italian woman in her early thirties with warm olive skin, dark brown eyes, a low dark-brown ponytail and a slate-blue V-neck nurse scrub top

### Canonical style descriptor

> Photorealistic UGC selfie video still, shot on a front-facing smartphone held at arm's length, mild wide-angle lens distortion, bright natural clinical lighting, shallow depth of field with a softly blurred background, slight handheld feel, neutral true-to-life color grade, 4:5 vertical framing.

Repeat this block verbatim at the end of every text-to-image prompt.

### Canonical setting (invariant)

Bright modern hospital room: an empty made-up hospital bed with white linens angled across the right background, pale grey-green walls, a recessed fluorescent ceiling panel, blurred monitors and equipment on the left edge.

### Canonical voice descriptor — ELENA

> Native Italian female voice, early thirties, warm mid-range mezzo timbre with a light bright rasp, neutral standard Italian with no strong regional accent, brisk conversational pace around 165 words per minute, confident and warm but urgent, friendly-authoritative "someone in healthcare telling you something they shouldn't" attitude, lifting energy on rhetorical questions and landing hard flat downbeats on the one-word answers.

Repeat verbatim in every clip's sound direction. **Do not** change pitch, accent, age, timbre or pace between clips — the four clips must sound like one unbroken take.

### Speaker map

| Clip | Delivery mode | Speaker |
|---|---|---|
| Pre-roll overlay | Off-screen character voice (Elena, over borrowed footage) | Elena |
| 01–04 | On-camera dialogue, full lip-sync | Elena |

No second speaker anywhere. No off-screen narrator.

### Global sound lock

- **Music bed:** none. Silence. This is deliberate and copied from the reference.
- **Ambience:** none, or at most a −55 dB room tone to avoid digital dead air between clips.
- **Sound effects:** none.
- **Mix:** single dry voice track, close-mic character, light de-esser, no reverb. Target −14 LUFS integrated, −3 dBFS peak. Crossfade the room tone by 200 ms across every clip junction so the four generations join inaudibly.

### Product lock

There is no product. The script never names or shows one — the offer lives behind the "tap below" link. Do not invent packaging, a bottle, a label, or a brand mark in any frame.

### Scene variables (the only things allowed to change between clips)

Facial expression, eyebrow position, free-hand gesture, head tilt, and a few degrees of framing drift. Identity, wardrobe, hair, setting, lighting and lens stay fixed.

---

## 3. Pre-roll overlay (edit element — not one of the 4 generated clips)

The reference's hook card is repurposed footage with a text band, not an AI generation. Build it in the edit and lay it over the first ~3.4 seconds of Clip 01's picture; Clip 01's audio keeps running underneath.

**Text-to-image prompt (if you'd rather generate it than source stock)**
Close-up of the back of a woman's neck and upper shoulders, cervical vertebrae and nerve branches drawn directly onto the bare skin in black outline with orange-yellow highlights, a hand holding a small massage tool pressing along the drawn vertebrae, red fabric visible at the lower edge, warm indoor light, photorealistic amateur phone footage look, 4:5 vertical framing.

**Overlay treatment**
White band across the top ~28% of the frame, black bold grotesque text, three lines, left-aligned:
`Smettila di usare questo / se hai dolore / alla cervicale?`

**On screen:** 0:00 → 0:03.4, then hard cut (no transition) to Clip 01's picture.

---

## 4. Clips

### Clip 01

**Script section / voiceover text**

"Smettila di usare questo se hai dolore alla cervicale.
Qual è il modo migliore per rilassare la cervicale dopo i 50 anni?
Il cortisone? No.
I cuscini ergonomici? No.
Il Voltaren ogni sera? Assolutamente no.
Ecco cosa funziona davvero.
La maggior parte delle persone prova ad alleviare il dolore cervicale cercando di ridurre l'infiammazione con la fisioterapia, il gel o le infiltrazioni.
Il problema?
L'infiammazione è solo un sintomo, non è la vera causa.
Questo significa che la maggior parte delle persone passa anni, a volte decenni, a gestire il fastidio invece di risolverlo.
Ti sei mai chiesto perché lo chiamano gestione del dolore? Perché ti insegnano a convivere col dolore, non a eliminarlo.
La domanda che dovresti farti non è "come riduco l'infiammazione?"
La vera domanda è: cosa sta causando l'infiammazione?
Per fortuna, ricercatori nel campo muscolo-scheletrico hanno scoperto di recente qualcosa di importante.
Un circuito nascosto fatto di tre guasti che si autoalimenta nella zona cervicale delle persone dopo i 50 anni."

**Text-to-image prompt**

An Italian woman in her early thirties, medium build, oval face with a soft jawline, warm olive skin, dark brown almond-shaped eyes, thick natural eyebrows, a small mole below her left cheekbone, straight dark-brown hair pulled back into a low ponytail with a few loose strands at the temples, minimal natural makeup, small gold stud earrings, wearing a plain slate-blue V-neck nurse scrub top with a chest pocket and a thin silver bracelet on her right wrist. She stands slightly left of centre in a bright modern hospital room, an empty made-up hospital bed with white linens angled across the right background, pale grey-green walls and a recessed fluorescent ceiling panel above, blurred monitors on the left edge; head-and-shoulders framing, chin slightly lifted, eyebrows raised, mouth open mid-word, looking straight into the lens, free arm relaxed out of frame. Photorealistic UGC selfie video still, shot on a front-facing smartphone held at arm's length, mild wide-angle lens distortion, bright natural clinical lighting, shallow depth of field with a softly blurred background, slight handheld feel, neutral true-to-life color grade, 4:5 vertical framing.

**Image-to-video prompt**

Animate the Italian woman in her early thirties with warm olive skin, dark brown eyes, a low dark-brown ponytail and a slate-blue V-neck nurse scrub top. She holds the phone at arm's length and walks slowly backwards through the room so the background drifts gently; keep her face, hair, scrub top and the hospital setting exactly as they are. She looks directly into the lens the whole time, blinking naturally, eyebrows lifting on each question and dropping flat on each answer, small confident head shakes on the negatives, her free hand rising once into the lower-right of frame with an open palm on the last two lines. Her mouth moves in precise natural synchronization as she speaks: "Smettila di usare questo se hai dolore alla cervicale. Qual è il modo migliore per rilassare la cervicale dopo i 50 anni? Il cortisone? No. I cuscini ergonomici? No. Il Voltaren ogni sera? Assolutamente no. Ecco cosa funziona davvero. La maggior parte delle persone prova ad alleviare il dolore cervicale cercando di ridurre l'infiammazione con la fisioterapia, il gel o le infiltrazioni. Il problema? L'infiammazione è solo un sintomo, non è la vera causa. Questo significa che la maggior parte delle persone passa anni, a volte decenni, a gestire il fastidio invece di risolverlo. Ti sei mai chiesto perché lo chiamano gestione del dolore? Perché ti insegnano a convivere col dolore, non a eliminarlo. La domanda che dovresti farti non è "come riduco l'infiammazione?" La vera domanda è: cosa sta causando l'infiammazione? Per fortuna, ricercatori nel campo muscolo-scheletrico hanno scoperto di recente qualcosa di importante. Un circuito nascosto fatto di tre guasti che si autoalimenta nella zona cervicale delle persone dopo i 50 anni." One continuous handheld selfie take, no cuts, brisk and confident tempo.

**Sound / voiceover direction**

On-camera dialogue, fully lip-synced, single speaker. Native Italian female voice, early thirties, warm mid-range mezzo timbre with a light bright rasp, neutral standard Italian with no strong regional accent, brisk conversational pace around 165 words per minute, confident and warm but urgent, friendly-authoritative "someone in healthcare telling you something they shouldn't" attitude, lifting energy on rhetorical questions and landing hard flat downbeats on the one-word answers. Land "No." / "No." / "Assolutamente no." as three clipped, falling beats with roughly 0.35s of air after each. Slow and lower the voice on "L'infiammazione è solo un sintomo" — this is the reframe. Push tempo back up and lean slightly conspiratorial on the final sentence so the clip hands off on a cliffhanger. No music bed, no ambience, no sound effects — dry close voice on silence, −14 LUFS, −3 dBFS peak.

**Estimated length**

59.5 seconds

---

### Clip 02

**Script section / voiceover text**

"Quando questo circuito è spento, il collo e il trapezio funzionano come dovrebbero — niente rigidità, niente tensione, niente dolore.
Ma dopo i 50 anni, soprattutto se hai fatto lavoro fisico per una vita, questi tre guasti si accendono uno dopo l'altro e iniziano ad attaccare la tua cervicale.
I nervi si ipersensibilizzano — alzano il volume del dolore al punto che anche girare la testa diventa un problema.
I muscoli del collo e del trapezio si contraggono per proteggere la zona — e non mollano più. Restano bloccati giorno e notte, come una morsa.
E siccome quei muscoli contratti strozzano la circolazione, i residui dell'infiammazione restano intrappolati lì. Non hanno dove andare. E continuano ad alimentare il circuito.
Ed ecco la parte peggiore.
Una volta che questo circuito si consolida, la maggior parte dei medici ti dirà che dovrai conviverci per sempre.
È per questo che la cervicale diventa una condanna per tante persone."

**Text-to-image prompt**

An Italian woman in her early thirties, medium build, oval face with a soft jawline, warm olive skin, dark brown almond-shaped eyes, thick natural eyebrows, a small mole below her left cheekbone, straight dark-brown hair pulled back into a low ponytail with a few loose strands at the temples, minimal natural makeup, small gold stud earrings, wearing a plain slate-blue V-neck nurse scrub top with a chest pocket and a thin silver bracelet on her right wrist. She stands slightly left of centre in a bright modern hospital room, an empty made-up hospital bed with white linens angled across the right background, pale grey-green walls and a recessed fluorescent ceiling panel above, blurred monitors on the left edge; head-and-shoulders framing, brow slightly furrowed in concern, lips parted mid-sentence, her free hand raised into the lower-right of frame with three fingers extended, looking straight into the lens. Photorealistic UGC selfie video still, shot on a front-facing smartphone held at arm's length, mild wide-angle lens distortion, bright natural clinical lighting, shallow depth of field with a softly blurred background, slight handheld feel, neutral true-to-life color grade, 4:5 vertical framing.

**Image-to-video prompt**

Animate the Italian woman in her early thirties with warm olive skin, dark brown eyes, a low dark-brown ponytail and a slate-blue V-neck nurse scrub top. Keep her face, hair, scrub top, the hospital bed and the lighting exactly as they are. The handheld phone drifts and sways gently; she stays looking straight into the lens, blinking naturally, her brow tightening through the middle of the take. Her free hand counts three fingers in the lower-right of frame as she names the three faults, then closes into a slow fist on "come una morsa", then drops out of frame. Her mouth moves in precise natural synchronization as she speaks: "Quando questo circuito è spento, il collo e il trapezio funzionano come dovrebbero — niente rigidità, niente tensione, niente dolore. Ma dopo i 50 anni, soprattutto se hai fatto lavoro fisico per una vita, questi tre guasti si accendono uno dopo l'altro e iniziano ad attaccare la tua cervicale. I nervi si ipersensibilizzano — alzano il volume del dolore al punto che anche girare la testa diventa un problema. I muscoli del collo e del trapezio si contraggono per proteggere la zona — e non mollano più. Restano bloccati giorno e notte, come una morsa. E siccome quei muscoli contratti strozzano la circolazione, i residui dell'infiammazione restano intrappolati lì. Non hanno dove andare. E continuano ad alimentare il circuito. Ed ecco la parte peggiore. Una volta che questo circuito si consolida, la maggior parte dei medici ti dirà che dovrai conviverci per sempre. È per questo che la cervicale diventa una condanna per tante persone." One continuous handheld selfie take, no cuts, steady explanatory tempo darkening toward the end.

**Sound / voiceover direction**

On-camera dialogue, fully lip-synced, single speaker. Native Italian female voice, early thirties, warm mid-range mezzo timbre with a light bright rasp, neutral standard Italian with no strong regional accent, brisk conversational pace around 165 words per minute, confident and warm but urgent, friendly-authoritative "someone in healthcare telling you something they shouldn't" attitude, lifting energy on rhetorical questions and landing hard flat downbeats on the one-word answers. Deliver "niente rigidità, niente tensione, niente dolore" as three light, opening beats, then drop the tone for the three faults and press harder on each one. "Non hanno dove andare." is short, flat, final. Half-beat of silence before "Ed ecco la parte peggiore." and drop to near-confidential volume on the last two sentences. No music bed, no ambience, no sound effects — dry close voice on silence, −14 LUFS, −3 dBFS peak.

**Estimated length**

56.5 seconds

---

### Clip 03

**Script section / voiceover text**

"Svegliarsi fa male.
Stare seduto fa male.
Stare in piedi fa male.
Anche sdraiarsi, spesso, non ti dà nessun sollievo.
E secondo i dati recenti, il dolore cervicale è una delle prime ragioni per cui le persone perdono la propria autonomia con l'età.
Tanti smettono di guidare perché non riescono più a girare la testa per controllare lo specchietto.
Tanti smettono di fare le cose che amavano.
Tanti smettono di uscire, di vedere la famiglia.
E prima che te ne accorgi, la cervicale ti ha tolto tutto.
Tutto per colpa di quel circuito che nessuno ha mai interrotto.
Nel frattempo, il medico continua a prescrivere pastiglie, infiltrazioni, e ti dice di gestire il dolore.
Ma le pastiglie non resettano un sistema nervoso ipersensibilizzato.
E le infiltrazioni non sbloccano i muscoli che stanno strozzando la circolazione nel trapezio.
Il che significa che hai bisogno di sempre più trattamenti che non risolvono mai il problema alla radice."

**Text-to-image prompt**

An Italian woman in her early thirties, medium build, oval face with a soft jawline, warm olive skin, dark brown almond-shaped eyes, thick natural eyebrows, a small mole below her left cheekbone, straight dark-brown hair pulled back into a low ponytail with a few loose strands at the temples, minimal natural makeup, small gold stud earrings, wearing a plain slate-blue V-neck nurse scrub top with a chest pocket and a thin silver bracelet on her right wrist. She stands slightly left of centre in a bright modern hospital room, an empty made-up hospital bed with white linens angled across the right background, pale grey-green walls and a recessed fluorescent ceiling panel above, blurred monitors on the left edge; head-and-shoulders framing, head tilted slightly to one side, softened sympathetic expression with lowered brows and a small closed-mouth pause, free arm relaxed out of frame, looking straight into the lens. Photorealistic UGC selfie video still, shot on a front-facing smartphone held at arm's length, mild wide-angle lens distortion, bright natural clinical lighting, shallow depth of field with a softly blurred background, slight handheld feel, neutral true-to-life color grade, 4:5 vertical framing.

**Image-to-video prompt**

Animate the Italian woman in her early thirties with warm olive skin, dark brown eyes, a low dark-brown ponytail and a slate-blue V-neck nurse scrub top. Keep her face, hair, scrub top, the hospital bed and the lighting exactly as they are. The handheld phone sways gently and creeps a few centimetres closer through the take. She holds a soft, sympathetic expression, head tilted, giving a small slow nod after each short opening line, glancing briefly down and away on "di vedere la famiglia" before returning her eyes to the lens, then hardening into a flat level look for the last three sentences. Her mouth moves in precise natural synchronization as she speaks: "Svegliarsi fa male. Stare seduto fa male. Stare in piedi fa male. Anche sdraiarsi, spesso, non ti dà nessun sollievo. E secondo i dati recenti, il dolore cervicale è una delle prime ragioni per cui le persone perdono la propria autonomia con l'età. Tanti smettono di guidare perché non riescono più a girare la testa per controllare lo specchietto. Tanti smettono di fare le cose che amavano. Tanti smettono di uscire, di vedere la famiglia. E prima che te ne accorgi, la cervicale ti ha tolto tutto. Tutto per colpa di quel circuito che nessuno ha mai interrotto. Nel frattempo, il medico continua a prescrivere pastiglie, infiltrazioni, e ti dice di gestire il dolore. Ma le pastiglie non resettano un sistema nervoso ipersensibilizzato. E le infiltrazioni non sbloccano i muscoli che stanno strozzando la circolazione nel trapezio. Il che significa che hai bisogno di sempre più trattamenti che non risolvono mai il problema alla radice." One continuous handheld selfie take, no cuts, heavy and empathetic tempo.

**Sound / voiceover direction**

On-camera dialogue, fully lip-synced, single speaker. Native Italian female voice, early thirties, warm mid-range mezzo timbre with a light bright rasp, neutral standard Italian with no strong regional accent, brisk conversational pace around 165 words per minute, confident and warm but urgent, friendly-authoritative "someone in healthcare telling you something they shouldn't" attitude, lifting energy on rhetorical questions and landing hard flat downbeats on the one-word answers. Open with the four short lines as separate falling beats, roughly 0.4s of air between each — this is the only place in the ad that breathes. Warm and quiet through the "Tanti smettono…" run, with the softest reading of the whole ad on "di vedere la famiglia". Then flatten and cool the tone for the three medical-dead-end sentences. No music bed, no ambience, no sound effects — dry close voice on silence, −14 LUFS, −3 dBFS peak.

**Estimated length**

58 seconds

---

### Clip 04

**Script section / voiceover text**

"Ma tutto è cambiato quando un minerale poco conosciuto è stato scoperto capace di interrompere immediatamente questo circuito, aiutare a rilassare la muscolatura cervicale, e dare al tuo corpo quello che gli serve per calmare il dolore al collo.
Con questo semplice minerale, puoi dare sollievo a quel bruciore, a quella rigidità, a quella tensione cervicale che non ti molla, proteggere il collo e il trapezio, e riprendere la libertà di movimento che ti è stata tolta.
Tocca qui sotto per scoprire questo minerale e provarlo direttamente.
Non lasciare che passi un altro giorno mentre il circuito nella tua cervicale continua a rafforzarsi.
E non lasciare che quei tre guasti continuino a toglierti la forza e a mettere a rischio la tua autonomia.
Tocca qui sotto adesso. Migliaia di persone lo stanno già usando.
Basta svegliarsi col collo bloccato.
Basta avere paura di muoversi.
Basta organizzare la vita intorno alla cervicale.
Sei ancora in tempo. Tocca qui sotto adesso."

**Text-to-image prompt**

An Italian woman in her early thirties, medium build, oval face with a soft jawline, warm olive skin, dark brown almond-shaped eyes, thick natural eyebrows, a small mole below her left cheekbone, straight dark-brown hair pulled back into a low ponytail with a few loose strands at the temples, minimal natural makeup, small gold stud earrings, wearing a plain slate-blue V-neck nurse scrub top with a chest pocket and a thin silver bracelet on her right wrist. She stands slightly left of centre in a bright modern hospital room, an empty made-up hospital bed with white linens angled across the right background, pale grey-green walls and a recessed fluorescent ceiling panel above, blurred monitors on the left edge; head-and-shoulders framing, bright open expression with raised eyebrows and a warm wide smile, free hand raised into the lower-right of frame with the index finger angled downward, looking straight into the lens. Photorealistic UGC selfie video still, shot on a front-facing smartphone held at arm's length, mild wide-angle lens distortion, bright natural clinical lighting, shallow depth of field with a softly blurred background, slight handheld feel, neutral true-to-life color grade, 4:5 vertical framing.

**Image-to-video prompt**

Animate the Italian woman in her early thirties with warm olive skin, dark brown eyes, a low dark-brown ponytail and a slate-blue V-neck nurse scrub top. Keep her face, hair, scrub top, the hospital bed and the lighting exactly as they are. The handheld phone sways gently and drifts a little closer as her energy rises. Her expression brightens and opens through the take, eyebrows lifting, smiling more with each line, eyes locked on the lens. Her free hand comes up into the lower-right of frame and points downward past the bottom edge on each "Tocca qui sotto", holding the gesture on the final line. Her mouth moves in precise natural synchronization as she speaks: "Ma tutto è cambiato quando un minerale poco conosciuto è stato scoperto capace di interrompere immediatamente questo circuito, aiutare a rilassare la muscolatura cervicale, e dare al tuo corpo quello che gli serve per calmare il dolore al collo. Con questo semplice minerale, puoi dare sollievo a quel bruciore, a quella rigidità, a quella tensione cervicale che non ti molla, proteggere il collo e il trapezio, e riprendere la libertà di movimento che ti è stata tolta. Tocca qui sotto per scoprire questo minerale e provarlo direttamente. Non lasciare che passi un altro giorno mentre il circuito nella tua cervicale continua a rafforzarsi. E non lasciare che quei tre guasti continuino a toglierti la forza e a mettere a rischio la tua autonomia. Tocca qui sotto adesso. Migliaia di persone lo stanno già usando. Basta svegliarsi col collo bloccato. Basta avere paura di muoversi. Basta organizzare la vita intorno alla cervicale. Sei ancora in tempo. Tocca qui sotto adesso." One continuous handheld selfie take, no cuts, accelerating and lifting tempo.

**Sound / voiceover direction**

On-camera dialogue, fully lip-synced, single speaker. Native Italian female voice, early thirties, warm mid-range mezzo timbre with a light bright rasp, neutral standard Italian with no strong regional accent, brisk conversational pace around 165 words per minute, confident and warm but urgent, friendly-authoritative "someone in healthcare telling you something they shouldn't" attitude, lifting energy on rhetorical questions and landing hard flat downbeats on the one-word answers. Lift brightness and tempo from the first word — this is the turn. Hit each "Basta…" as a separate rising, clipped beat with a short breath between. Land "Sei ancora in tempo." warm and slow, then "Tocca qui sotto adesso." fast, bright and closed. No music bed, no ambience, no sound effects — dry close voice on silence, −14 LUFS, −3 dBFS peak.

**Estimated length**

58 seconds

---

**Estimated total runtime: 3 minutes 52 seconds (232 seconds)**

---

## 5. Assembly notes

- **Order:** pre-roll overlay (0:00–0:03.4, over Clip 01's picture) → Clip 01 → Clip 02 → Clip 03 → Clip 04. Straight cuts, no transitions, no dip to black.
- **Seams:** cut on the last consonant of each clip's final word, 200 ms room-tone crossfade only. Reference does the same and its seams are invisible.
- **Captions:** add in the edit, never bake into the generated frames. 2 lines, 3–5 words per line, white bold grotesque on a black rounded-rect box at ~90% opacity, centred at ~72% frame height, new card every ~2.2–2.5s, phrase-synced.
- **Production route:** generate one still per clip from the text-to-image prompt, render the full Italian VO as one continuous track, then split it at the four clip boundaries and drive each clip with an audio-driven lip-sync generation. Where the platform supports it, feed the same character reference image and a fixed seed across all four so identity holds.
- **The 60s cap is tight.** Clip 01 is 164 words; at 165 wpm it lands at 59.5s. If the VO comes back slower than ~164 wpm, Clip 01 overruns. Either direct the read to 165–170 wpm, or split Clip 01 in two at "Per fortuna, ricercatori…" and ship five clips.
- **Claims:** everything spoken comes from the script as written. Deliberately not added: study screenshots, named journals, doctor credentials, a hospital name or logo on the scrub top, a name badge, before/after footage, review counts, or any product packaging. The presenter reads as clinical staff without the script claiming she is — worth confirming that framing against the ad platform's health-claims policy before running.
