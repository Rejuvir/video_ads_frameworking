# Storyboard — "Cervicale" VSL (IT) — con tag ElevenLabs v3

4 generated clips, all ≤60s. Reference ad analyzed: 3:10 AI-presenter UGC selfie VSL (EN, sciatica).

---

## 1. Reference-ad blueprint

- **Format** — 4:5 vertical (360×450), photoreal AI "UGC selfie" video. Not animation, not B-roll-driven.
- **Hook device** — 0:00–2.8s: a borrowed viral clip (woman's lower back in red leggings, cervical/lumbar spine + nerves illustrated directly on the skin, a hand working a massage tool over it) under a white band with black bold text: *"Stop Drinking This If You Have Sciatic Nerve Pain?"*. The voiceover's first line plays over it, then a hard cut to the presenter.
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

## 3. ElevenLabs v3 — settings and tag rules

Each clip below carries two versions of the same voiceover:

- **Script section / voiceover text** — clean, untagged. This is what goes into the caption file and into the image-to-video prompt for lip-sync.
- **ElevenLabs v3 script (tagged)** — same words, identical order, with audio tags added. This is the only version you paste into ElevenLabs.

**Never paste the tagged version into the video model or the caption tool.** A lip-sync model will try to mouth `[serious]`, and a caption burner will print it on screen.

### Generation settings — identical for all four clips

| Setting | Value |
|---|---|
| Model | Eleven v3 |
| Voice | one single voice ID, reused for all 4 clips |
| Stability | **Natural** — keeps the four clips sounding like one take. Switch to Creative only if the tags aren't landing, and if you do, re-generate all four on Creative so they still match. |
| Speed | default, or +5% if the read comes back under 165 wpm |
| Style / speaker boost | off or minimal — both push voice drift across separate generations |
| Requests | one request per clip (each is ~1,000–1,300 characters: comfortably above the ~250-character floor where v3 stabilises, far under the 3,000-character cap) |

### Tag rules used here

- **English tag names.** v3 recognises the Italian equivalents far less reliably than `[serious]`, `[curious]`, `[sad]`. The Italian text is unaffected — only the tags are English.
- **A tag goes immediately before the words it should colour,** and it holds until the next tag. That is why there are stretches with no tag: they inherit the previous one.
- **5–11 tags per clip, no more.** Tagging every sentence destabilises v3 and makes the delivery lurch. Clip 01 carries the most (11, because the hook turns emotion every second line); Clip 04 the fewest (5, because `[excited]` is meant to hold across the whole solution block).
- **No sound-effect tags.** `[thunder]`, `[heartbeat]`, `[door slams]` and the rest of that family are deliberately unused — the reference ad runs voice-only on near-silence, and injecting effects into the voice track would break the "real phone recording" read that makes this format work. If you ever want them, add them as separate audio in the edit, not as v3 tags.
- **`[whispers]` is the one intensity tag used at full strength,** twice, on the two conspiratorial beats. Overusing it flattens the whole read.
- **Ellipses `…` are pause instructions,** not text. They are the only punctuation added to the original script.

---

## 4. Pre-roll overlay (edit element — not one of the 4 generated clips)

The reference's hook card is repurposed footage with a text band, not an AI generation. Build it in the edit and lay it over the first ~3.4 seconds of Clip 01's picture; Clip 01's audio keeps running underneath.

**Text-to-image prompt (if you'd rather generate it than source stock)**
Close-up of the back of a woman's neck and upper shoulders, cervical vertebrae and nerve branches drawn directly onto the bare skin in black outline with orange-yellow highlights, a hand holding a small massage tool pressing along the drawn vertebrae, red fabric visible at the lower edge, warm indoor light, photorealistic amateur phone footage look, 4:5 vertical framing.

**Overlay treatment**
White band across the top ~28% of the frame, black bold grotesque text, three lines, left-aligned:
`Smettila di usare questo / se hai dolore / alla cervicale?`

**On screen:** 0:00 → 0:03.4, then hard cut (no transition) to Clip 01's picture.

---

## 5. Clips

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

**ElevenLabs v3 script (tagged)**

```
[serious] Smettila di usare questo se hai dolore alla cervicale.
[curious] Qual è il modo migliore per rilassare la cervicale dopo i 50 anni?
Il cortisone? [serious] No.
I cuscini ergonomici? No.
Il Voltaren ogni sera? [sarcastic] Assolutamente no.
[excited] Ecco cosa funziona davvero.
La maggior parte delle persone prova ad alleviare il dolore cervicale cercando di ridurre l'infiammazione con la fisioterapia, il gel o le infiltrazioni.
Il problema?
[serious] L'infiammazione è solo un sintomo… non è la vera causa.
Questo significa che la maggior parte delle persone passa anni, a volte decenni, a gestire il fastidio invece di risolverlo.
[curious] Ti sei mai chiesto perché lo chiamano gestione del dolore?
[frustrated] Perché ti insegnano a convivere col dolore, non a eliminarlo.
La domanda che dovresti farti non è "come riduco l'infiammazione?"
[serious] La vera domanda è: cosa sta causando l'infiammazione?
[excited] Per fortuna, ricercatori nel campo muscolo-scheletrico hanno scoperto di recente qualcosa di importante.
[whispers] Un circuito nascosto fatto di tre guasti che si autoalimenta nella zona cervicale delle persone dopo i 50 anni.
```

Why these positions: `[serious]` opens flat and blunt so the hook lands as a warning, not a pitch. `[curious]` lifts the question. The two bare `No.` answers inherit `[serious]` and stay clipped; `[sarcastic]` on "Assolutamente no." is the one place the reference presenter smirks. `[excited]` turns the corner into the promise. `[serious]` marks the reframe — the single most important line in the first minute — and the ellipsis buys the beat before "non è la vera causa". `[curious]` → `[frustrated]` is the "pain management" jab. `[excited]` opens the discovery, and `[whispers]` closes the clip conspiratorially so the cut into Clip 02 feels like a secret being handed over.

**Text-to-image prompt**

An Italian woman in her early thirties, medium build, oval face with a soft jawline, warm olive skin, dark brown almond-shaped eyes, thick natural eyebrows, a small mole below her left cheekbone, straight dark-brown hair pulled back into a low ponytail with a few loose strands at the temples, minimal natural makeup, small gold stud earrings, wearing a plain slate-blue V-neck nurse scrub top with a chest pocket and a thin silver bracelet on her right wrist. She stands slightly left of centre in a bright modern hospital room, an empty made-up hospital bed with white linens angled across the right background, pale grey-green walls and a recessed fluorescent ceiling panel above, blurred monitors on the left edge; head-and-shoulders framing, chin slightly lifted, eyebrows raised, mouth open mid-word, looking straight into the lens, free arm relaxed out of frame. Photorealistic UGC selfie video still, shot on a front-facing smartphone held at arm's length, mild wide-angle lens distortion, bright natural clinical lighting, shallow depth of field with a softly blurred background, slight handheld feel, neutral true-to-life color grade, 4:5 vertical framing.

**Image-to-video prompt**

Animate the Italian woman in her early thirties with warm olive skin, dark brown eyes, a low dark-brown ponytail and a slate-blue V-neck nurse scrub top. She holds the phone at arm's length and walks slowly backwards through the room so the background drifts gently; keep her face, hair, scrub top and the hospital setting exactly as they are. She looks directly into the lens the whole time, blinking naturally, eyebrows lifting on each question and dropping flat on each answer, small confident head shakes on the negatives, her free hand rising once into the lower-right of frame with an open palm on the last two lines. Her mouth moves in precise natural synchronization as she speaks: "Smettila di usare questo se hai dolore alla cervicale. Qual è il modo migliore per rilassare la cervicale dopo i 50 anni? Il cortisone? No. I cuscini ergonomici? No. Il Voltaren ogni sera? Assolutamente no. Ecco cosa funziona davvero. La maggior parte delle persone prova ad alleviare il dolore cervicale cercando di ridurre l'infiammazione con la fisioterapia, il gel o le infiltrazioni. Il problema? L'infiammazione è solo un sintomo, non è la vera causa. Questo significa che la maggior parte delle persone passa anni, a volte decenni, a gestire il fastidio invece di risolverlo. Ti sei mai chiesto perché lo chiamano gestione del dolore? Perché ti insegnano a convivere col dolore, non a eliminarlo. La domanda che dovresti farti non è "come riduco l'infiammazione?" La vera domanda è: cosa sta causando l'infiammazione? Per fortuna, ricercatori nel campo muscolo-scheletrico hanno scoperto di recente qualcosa di importante. Un circuito nascosto fatto di tre guasti che si autoalimenta nella zona cervicale delle persone dopo i 50 anni." One continuous handheld selfie take, no cuts, brisk and confident tempo.

**Sound / voiceover direction**

On-camera dialogue, fully lip-synced, single speaker. Native Italian female voice, early thirties, warm mid-range mezzo timbre with a light bright rasp, neutral standard Italian with no strong regional accent, brisk conversational pace around 165 words per minute, confident and warm but urgent, friendly-authoritative "someone in healthcare telling you something they shouldn't" attitude, lifting energy on rhetorical questions and landing hard flat downbeats on the one-word answers. Tags carry the shape: `[serious]` → `[curious]` → `[serious]` → `[sarcastic]` → `[excited]` → `[serious]` → `[curious]` → `[frustrated]` → `[serious]` → `[excited]` → `[whispers]`. Check on playback that "No." / "No." / "Assolutamente no." land as three clipped falling beats with roughly 0.35s of air after each; if v3 runs them together, split them onto their own lines in the input. No music bed, no ambience, no sound effects — dry close voice on silence, −14 LUFS, −3 dBFS peak.

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

**ElevenLabs v3 script (tagged)**

```
Quando questo circuito è spento, il collo e il trapezio funzionano come dovrebbero — niente rigidità, niente tensione, niente dolore.
[serious] Ma dopo i 50 anni, soprattutto se hai fatto lavoro fisico per una vita, questi tre guasti si accendono uno dopo l'altro e iniziano ad attaccare la tua cervicale.
I nervi si ipersensibilizzano — alzano il volume del dolore al punto che anche girare la testa diventa un problema.
[frustrated] I muscoli del collo e del trapezio si contraggono per proteggere la zona — e non mollano più. Restano bloccati giorno e notte… come una morsa.
[serious] E siccome quei muscoli contratti strozzano la circolazione, i residui dell'infiammazione restano intrappolati lì. Non hanno dove andare. E continuano ad alimentare il circuito.
[whispers] Ed ecco la parte peggiore.
[sad] Una volta che questo circuito si consolida, la maggior parte dei medici ti dirà che dovrai conviverci per sempre.
[sighs] È per questo che la cervicale diventa una condanna per tante persone.
```

Why these positions: the opening sentence is deliberately untagged — it inherits the `[whispers]` energy from the end of Clip 01 and lets the voice settle back to neutral, which is what makes the clip junction inaudible. `[serious]` starts the mechanism. `[frustrated]` is the muscle-lock beat, and the ellipsis before "come una morsa" gives the image room to land. `[serious]` runs the circulation explanation flat and clinical. `[whispers]` on "Ed ecco la parte peggiore." is the second and last whisper in the ad. `[sad]` then `[sighs]` walk the clip down into the dread beat that Clip 03 picks up.

**Text-to-image prompt**

An Italian woman in her early thirties, medium build, oval face with a soft jawline, warm olive skin, dark brown almond-shaped eyes, thick natural eyebrows, a small mole below her left cheekbone, straight dark-brown hair pulled back into a low ponytail with a few loose strands at the temples, minimal natural makeup, small gold stud earrings, wearing a plain slate-blue V-neck nurse scrub top with a chest pocket and a thin silver bracelet on her right wrist. She stands slightly left of centre in a bright modern hospital room, an empty made-up hospital bed with white linens angled across the right background, pale grey-green walls and a recessed fluorescent ceiling panel above, blurred monitors on the left edge; head-and-shoulders framing, brow slightly furrowed in concern, lips parted mid-sentence, her free hand raised into the lower-right of frame with three fingers extended, looking straight into the lens. Photorealistic UGC selfie video still, shot on a front-facing smartphone held at arm's length, mild wide-angle lens distortion, bright natural clinical lighting, shallow depth of field with a softly blurred background, slight handheld feel, neutral true-to-life color grade, 4:5 vertical framing.

**Image-to-video prompt**

Animate the Italian woman in her early thirties with warm olive skin, dark brown eyes, a low dark-brown ponytail and a slate-blue V-neck nurse scrub top. Keep her face, hair, scrub top, the hospital bed and the lighting exactly as they are. The handheld phone drifts and sways gently; she stays looking straight into the lens, blinking naturally, her brow tightening through the middle of the take. Her free hand counts three fingers in the lower-right of frame as she names the three faults, then closes into a slow fist on "come una morsa", then drops out of frame. Her mouth moves in precise natural synchronization as she speaks: "Quando questo circuito è spento, il collo e il trapezio funzionano come dovrebbero — niente rigidità, niente tensione, niente dolore. Ma dopo i 50 anni, soprattutto se hai fatto lavoro fisico per una vita, questi tre guasti si accendono uno dopo l'altro e iniziano ad attaccare la tua cervicale. I nervi si ipersensibilizzano — alzano il volume del dolore al punto che anche girare la testa diventa un problema. I muscoli del collo e del trapezio si contraggono per proteggere la zona — e non mollano più. Restano bloccati giorno e notte, come una morsa. E siccome quei muscoli contratti strozzano la circolazione, i residui dell'infiammazione restano intrappolati lì. Non hanno dove andare. E continuano ad alimentare il circuito. Ed ecco la parte peggiore. Una volta che questo circuito si consolida, la maggior parte dei medici ti dirà che dovrai conviverci per sempre. È per questo che la cervicale diventa una condanna per tante persone." One continuous handheld selfie take, no cuts, steady explanatory tempo darkening toward the end.

**Sound / voiceover direction**

On-camera dialogue, fully lip-synced, single speaker. Native Italian female voice, early thirties, warm mid-range mezzo timbre with a light bright rasp, neutral standard Italian with no strong regional accent, brisk conversational pace around 165 words per minute, confident and warm but urgent, friendly-authoritative "someone in healthcare telling you something they shouldn't" attitude, lifting energy on rhetorical questions and landing hard flat downbeats on the one-word answers. Tags carry the shape: untagged neutral open → `[serious]` → `[frustrated]` → `[serious]` → `[whispers]` → `[sad]` → `[sighs]`. Check that "Non hanno dove andare." comes back short and flat; if v3 lifts it into a question, put it on its own line. The `[sighs]` must be a real breath, not a word — if it gets vocalised, move it to the end of the previous line. No music bed, no ambience, no sound effects — dry close voice on silence, −14 LUFS, −3 dBFS peak.

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

**ElevenLabs v3 script (tagged)**

```
[tired] Svegliarsi fa male.
Stare seduto fa male.
Stare in piedi fa male.
[sighs] Anche sdraiarsi, spesso, non ti dà nessun sollievo.
[serious] E secondo i dati recenti, il dolore cervicale è una delle prime ragioni per cui le persone perdono la propria autonomia con l'età.
[sad] Tanti smettono di guidare perché non riescono più a girare la testa per controllare lo specchietto.
Tanti smettono di fare le cose che amavano.
Tanti smettono di uscire… di vedere la famiglia.
E prima che te ne accorgi, la cervicale ti ha tolto tutto.
[frustrated] Tutto per colpa di quel circuito che nessuno ha mai interrotto.
[sarcastic] Nel frattempo, il medico continua a prescrivere pastiglie, infiltrazioni, e ti dice di gestire il dolore.
[serious] Ma le pastiglie non resettano un sistema nervoso ipersensibilizzato.
E le infiltrazioni non sbloccano i muscoli che stanno strozzando la circolazione nel trapezio.
[frustrated] Il che significa che hai bisogno di sempre più trattamenti che non risolvono mai il problema alla radice.
```

Why these positions: `[tired]` on the opening staccato run is the whole point of this clip — the three "fa male" lines have to sound worn down, not dramatic, and the two untagged lines after it inherit that. `[sighs]` gives the only real breath in the ad before the statistic. `[serious]` for the data line keeps it from sounding pitched. `[sad]` runs the entire "Tanti smettono…" cascade, with the ellipsis in "di uscire… di vedere la famiglia" as the softest moment in the script. `[frustrated]` snaps the tone back on "Tutto per colpa di quel circuito". `[sarcastic]` is aimed squarely at the doctor's prescription pad, `[serious]` cools it back down for the two mechanism lines, and `[frustrated]` closes on the treadmill of treatments.

**Text-to-image prompt**

An Italian woman in her early thirties, medium build, oval face with a soft jawline, warm olive skin, dark brown almond-shaped eyes, thick natural eyebrows, a small mole below her left cheekbone, straight dark-brown hair pulled back into a low ponytail with a few loose strands at the temples, minimal natural makeup, small gold stud earrings, wearing a plain slate-blue V-neck nurse scrub top with a chest pocket and a thin silver bracelet on her right wrist. She stands slightly left of centre in a bright modern hospital room, an empty made-up hospital bed with white linens angled across the right background, pale grey-green walls and a recessed fluorescent ceiling panel above, blurred monitors on the left edge; head-and-shoulders framing, head tilted slightly to one side, softened sympathetic expression with lowered brows and a small closed-mouth pause, free arm relaxed out of frame, looking straight into the lens. Photorealistic UGC selfie video still, shot on a front-facing smartphone held at arm's length, mild wide-angle lens distortion, bright natural clinical lighting, shallow depth of field with a softly blurred background, slight handheld feel, neutral true-to-life color grade, 4:5 vertical framing.

**Image-to-video prompt**

Animate the Italian woman in her early thirties with warm olive skin, dark brown eyes, a low dark-brown ponytail and a slate-blue V-neck nurse scrub top. Keep her face, hair, scrub top, the hospital bed and the lighting exactly as they are. The handheld phone sways gently and creeps a few centimetres closer through the take. She holds a soft, sympathetic expression, head tilted, giving a small slow nod after each short opening line, glancing briefly down and away on "di vedere la famiglia" before returning her eyes to the lens, then hardening into a flat level look for the last three sentences. Her mouth moves in precise natural synchronization as she speaks: "Svegliarsi fa male. Stare seduto fa male. Stare in piedi fa male. Anche sdraiarsi, spesso, non ti dà nessun sollievo. E secondo i dati recenti, il dolore cervicale è una delle prime ragioni per cui le persone perdono la propria autonomia con l'età. Tanti smettono di guidare perché non riescono più a girare la testa per controllare lo specchietto. Tanti smettono di fare le cose che amavano. Tanti smettono di uscire, di vedere la famiglia. E prima che te ne accorgi, la cervicale ti ha tolto tutto. Tutto per colpa di quel circuito che nessuno ha mai interrotto. Nel frattempo, il medico continua a prescrivere pastiglie, infiltrazioni, e ti dice di gestire il dolore. Ma le pastiglie non resettano un sistema nervoso ipersensibilizzato. E le infiltrazioni non sbloccano i muscoli che stanno strozzando la circolazione nel trapezio. Il che significa che hai bisogno di sempre più trattamenti che non risolvono mai il problema alla radice." One continuous handheld selfie take, no cuts, heavy and empathetic tempo.

**Sound / voiceover direction**

On-camera dialogue, fully lip-synced, single speaker. Native Italian female voice, early thirties, warm mid-range mezzo timbre with a light bright rasp, neutral standard Italian with no strong regional accent, brisk conversational pace around 165 words per minute, confident and warm but urgent, friendly-authoritative "someone in healthcare telling you something they shouldn't" attitude, lifting energy on rhetorical questions and landing hard flat downbeats on the one-word answers. Tags carry the shape: `[tired]` → `[sighs]` → `[serious]` → `[sad]` → `[frustrated]` → `[sarcastic]` → `[serious]` → `[frustrated]`. This is the only clip that is allowed to slow below 165 wpm — the four opening lines need roughly 0.4s of air between them, which is why the clip is budgeted at 58s rather than 56.5s. Keep `[sarcastic]` light: dry, not mocking, or the presenter stops sounding like she works in healthcare. No music bed, no ambience, no sound effects — dry close voice on silence, −14 LUFS, −3 dBFS peak.

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

**ElevenLabs v3 script (tagged)**

```
[excited] Ma tutto è cambiato quando un minerale poco conosciuto è stato scoperto capace di interrompere immediatamente questo circuito, aiutare a rilassare la muscolatura cervicale, e dare al tuo corpo quello che gli serve per calmare il dolore al collo.
Con questo semplice minerale, puoi dare sollievo a quel bruciore, a quella rigidità, a quella tensione cervicale che non ti molla, proteggere il collo e il trapezio, e riprendere la libertà di movimento che ti è stata tolta.
Tocca qui sotto per scoprire questo minerale e provarlo direttamente.
[serious] Non lasciare che passi un altro giorno mentre il circuito nella tua cervicale continua a rafforzarsi.
E non lasciare che quei tre guasti continuino a toglierti la forza e a mettere a rischio la tua autonomia.
[excited] Tocca qui sotto adesso. Migliaia di persone lo stanno già usando.
[serious] Basta svegliarsi col collo bloccato.
Basta avere paura di muoversi.
Basta organizzare la vita intorno alla cervicale.
Sei ancora in tempo… [excited] Tocca qui sotto adesso.
```

Why these positions: `[excited]` opens the turn and holds across the whole solution block — the two untagged sentences after it inherit the lift, which keeps the promise from sounding over-performed. `[serious]` grounds the two "Non lasciare…" warnings so the CTA has weight behind it rather than pure hype. `[excited]` returns for the first hard CTA plus the social-proof line. `[serious]` then runs the three "Basta…" lines as a rising, clipped ladder. The ellipsis after "Sei ancora in tempo" is the last beat of the ad, and the final `[excited]` closes on the call to action.

**Text-to-image prompt**

An Italian woman in her early thirties, medium build, oval face with a soft jawline, warm olive skin, dark brown almond-shaped eyes, thick natural eyebrows, a small mole below her left cheekbone, straight dark-brown hair pulled back into a low ponytail with a few loose strands at the temples, minimal natural makeup, small gold stud earrings, wearing a plain slate-blue V-neck nurse scrub top with a chest pocket and a thin silver bracelet on her right wrist. She stands slightly left of centre in a bright modern hospital room, an empty made-up hospital bed with white linens angled across the right background, pale grey-green walls and a recessed fluorescent ceiling panel above, blurred monitors on the left edge; head-and-shoulders framing, bright open expression with raised eyebrows and a warm wide smile, free hand raised into the lower-right of frame with the index finger angled downward, looking straight into the lens. Photorealistic UGC selfie video still, shot on a front-facing smartphone held at arm's length, mild wide-angle lens distortion, bright natural clinical lighting, shallow depth of field with a softly blurred background, slight handheld feel, neutral true-to-life color grade, 4:5 vertical framing.

**Image-to-video prompt**

Animate the Italian woman in her early thirties with warm olive skin, dark brown eyes, a low dark-brown ponytail and a slate-blue V-neck nurse scrub top. Keep her face, hair, scrub top, the hospital bed and the lighting exactly as they are. The handheld phone sways gently and drifts a little closer as her energy rises. Her expression brightens and opens through the take, eyebrows lifting, smiling more with each line, eyes locked on the lens. Her free hand comes up into the lower-right of frame and points downward past the bottom edge on each "Tocca qui sotto", holding the gesture on the final line. Her mouth moves in precise natural synchronization as she speaks: "Ma tutto è cambiato quando un minerale poco conosciuto è stato scoperto capace di interrompere immediatamente questo circuito, aiutare a rilassare la muscolatura cervicale, e dare al tuo corpo quello che gli serve per calmare il dolore al collo. Con questo semplice minerale, puoi dare sollievo a quel bruciore, a quella rigidità, a quella tensione cervicale che non ti molla, proteggere il collo e il trapezio, e riprendere la libertà di movimento che ti è stata tolta. Tocca qui sotto per scoprire questo minerale e provarlo direttamente. Non lasciare che passi un altro giorno mentre il circuito nella tua cervicale continua a rafforzarsi. E non lasciare che quei tre guasti continuino a toglierti la forza e a mettere a rischio la tua autonomia. Tocca qui sotto adesso. Migliaia di persone lo stanno già usando. Basta svegliarsi col collo bloccato. Basta avere paura di muoversi. Basta organizzare la vita intorno alla cervicale. Sei ancora in tempo. Tocca qui sotto adesso." One continuous handheld selfie take, no cuts, accelerating and lifting tempo.

**Sound / voiceover direction**

On-camera dialogue, fully lip-synced, single speaker. Native Italian female voice, early thirties, warm mid-range mezzo timbre with a light bright rasp, neutral standard Italian with no strong regional accent, brisk conversational pace around 165 words per minute, confident and warm but urgent, friendly-authoritative "someone in healthcare telling you something they shouldn't" attitude, lifting energy on rhetorical questions and landing hard flat downbeats on the one-word answers. Tags carry the shape: `[excited]` → `[serious]` → `[excited]` → `[serious]` → `[excited]`. Check that the three "Basta…" lines come back as separate rising beats with a short breath between; if v3 flattens them into one run, split them onto their own lines. The final "Tocca qui sotto adesso." must land fast, bright and closed — if `[excited]` overshoots into shouting, drop it and rely on the ellipsis before it. No music bed, no ambience, no sound effects — dry close voice on silence, −14 LUFS, −3 dBFS peak.

**Estimated length**

58 seconds

---

**Estimated total runtime: 3 minutes 52 seconds (232 seconds)**

---

## 6. Assembly notes

- **Order:** pre-roll overlay (0:00–0:03.4, over Clip 01's picture) → Clip 01 → Clip 02 → Clip 03 → Clip 04. Straight cuts, no transitions, no dip to black.
- **Production order:** generate the four ElevenLabs v3 tracks first, measure them, then lock the stills and run the lip-sync. The audio is what decides whether Clip 01 fits under 60s, so there is no point generating video before you have it.
- **Seams:** cut on the last consonant of each clip's final word, 200 ms room-tone crossfade only. Reference does the same and its seams are invisible.
- **Captions:** built from the clean untagged script, added in the edit, never baked into the generated frames. 2 lines, 3–5 words per line, white bold grotesque on a black rounded-rect box at ~90% opacity, centred at ~72% frame height, new card every ~2.2–2.5s, phrase-synced.
- **Production route:** generate one still per clip from the text-to-image prompt, render each clip's tagged script in ElevenLabs v3 with identical voice and settings, then drive each still with an audio-driven lip-sync generation. Where the platform supports it, feed the same character reference image and a fixed seed across all four so identity holds.
- **The 60s cap is tight.** Clip 01 is 164 words; at 165 wpm it lands at 59.5s. Measure the v3 render before committing: the `[whispers]` at the end of Clip 01 slows delivery, so if the file comes back over 60s, either raise Speed by 5%, or drop that `[whispers]` to `[serious]`, or split Clip 01 in two at "Per fortuna, ricercatori…" and ship five clips.
- **Claims:** everything spoken comes from the script as written. Deliberately not added: study screenshots, named journals, doctor credentials, a hospital name or logo on the scrub top, a name badge, before/after footage, review counts, or any product packaging. The presenter reads as clinical staff without the script claiming she is — worth confirming that framing against the ad platform's health-claims policy before running.
