# Storyboard — "Spalla / 5 Anni" VSL (IT)

30 b-roll clips, 95.0 s total. Format reference analysed: `mamabear_5years.mp4` — 58.9 s, 9:16, 29 shots, UGC b-roll + voiceover (EN, neuropathy / topical magnesium lotion).

Voiceover audio already exists and is supplied by the client. No lip-sync anywhere in this ad — every clip is silent b-roll cut under a continuous narrator track.

---

## 1. Reference-ad blueprint

- **Format** — 9:16 vertical (360×640), no presenter, no talking head. The entire ad is **b-roll + voiceover**: sourced-looking UGC live action intercut with 3D medical animation. Nobody on screen ever speaks.
- **Hook device** — 0:00–3.5 s, one unbroken clinical shot: blue-gloved hands examining a bare diabetic foot with a bloodied gauze square on the table. Two caption cards fire over that single shot — `this is what neuropathy looks like` (keyword in **red**), then `after 5 years of ignoring it` (keywords in **yellow**). Visceral medical image first, condition named second, time-cost named third. The 5-year frame is stated in the first 3.5 seconds.
- **Shot density** — 29 shots in 58.9 s: **mean shot 2.03 s, ~29.5 cuts/min**. Hard cuts only — no dissolves, no wipes, no transitions of any kind. Shortest 0.6 s, longest 6.0 s (the end card).
- **Two-act visual grammar** — Act 1 (0:00–25 s) is live-action UGC: handheld phone footage of real older people in real homes, failing at ordinary tasks. Act 2 (25–37 s) switches hard into **3D medical CGI** — glowing nerves, neurons, anatomical legs on deep teal-navy — the instant the VO moves from symptom to mechanism (`here is what is happening`). Act 3 returns to UGC for product and CTA, with one more CGI insert for the absorption mechanism.
- **The "Year N" card device** — three inserts of a **handwritten white card**: `Year 1` (black marker, wooden surface, blurred plant leaves in front), `Year 3` (blue marker, pale shelf, soft afternoon light), `Year 5` (black marker, hard diagonal window-light shadows). Each is a real photographed card with shallow depth of field — deliberately homemade, never a graphic title. 0.6–1.5 s each. They are the spine of the timeline.
- **Cast** — no recurring protagonist. A rotating cast of different real-looking people (blonde woman in bed, woman rubbing toes, woman at the mailboxes, bald bearded man, grey-haired man mid-stumble, woman on the stairs). The format reads as "people like you", not "one person's story".
- **Caption treatment** — burned-in, **all lowercase**, bold italic grotesque, white with a hard black outline and soft drop shadow, 1–2 lines, 3–6 words per line, centred, sitting at ~74 % frame height. One or two keywords per card are colour-filled: **red only in the hook**, **yellow for the entire rest of the ad**. No terminal periods. New card every ~1.5–2 s, phrase-synced.
- **Sound** — continuous music bed wall-to-wall: `silencedetect` at −35 dB found **no silence at all until 55.8 s**. Integrated **−15.2 LUFS**, true peak **−3.0 dBFS**, **LRA 3.8 LU** — heavily compressed, loud and flat, built for muted-autoplay feeds. VO sits clearly on top of a ducked minor-key bed.
- **Narrative phases & CTA** — visceral hook → Year 1 / Year 3 / Year 5 decline ladder → "this is not a scare story" tone-reset → CGI mechanism → product reveal in hand → application → CGI absorption → `no pills` → urgency → `tap the link` over a shot of someone actually tapping a phone → static designed end card with the jar and three benefit bullets.

---

## 2. Character, Voice, Sound and Style Consistency Lock

### Deliberate deviation from the reference

The reference rotates through unrelated people. This script does not: it is one continuous second-person timeline — *your* shoulder, *year 1 → year 5*. So Act 1 is locked to **one recurring protagonist, MARCO**, whose decline we watch across five years. Everything else about the format — b-roll only, no lip-sync, card device, caption style, CGI act, sound profile — is copied from the reference.

### Canonical subject — MARCO (protagonist, Act 1 and Act 3)

> A 52-year-old Italian man, solid working build with broad shoulders and a slight paunch, square face with a heavy jaw and deep nasolabial lines, olive-tan weathered skin, close-cropped salt-and-pepper hair receding at the temples, thick greying eyebrows, deep-set dark brown eyes with pronounced crow's feet, three-day grey stubble, a short vertical scar through his left eyebrow, and thick calloused hands with short square nails.

Repeat this block **verbatim** at the start of every text-to-image prompt he appears in. Never write "the same man", "our protagonist", or "Marco" alone.

**Short identity anchor** for image-to-video prompts (repeat verbatim):
> the 52-year-old Italian man with close-cropped salt-and-pepper hair, grey stubble and a short scar through his left eyebrow

**Wardrobe by era** — the only identity-adjacent thing allowed to change, because the script spans five years. Physical descriptor stays complete and identical regardless.

| Era | Clips | Wardrobe |
|---|---|---|
| Year 1 | 03–05 | navy-blue work polo with a small embroidered chest logo, sleeves pushed to the elbows |
| Year 3 | 07–09 | heather-grey long-sleeve henley, top button open |
| Year 5 | 11–15, 29 | plain white cotton undershirt |
| Clinical / product | 01, 25 | bare-chested or bare right shoulder |

### Canonical subject — THE ANATOMICAL SHOULDER (Act 2 and the absorption inserts)

> A right human shoulder rendered as a semi-transparent anatomical model — deltoid, trapezius and rotator-cuff muscles in translucent warm grey, the humeral head and scapula visible as pale bone beneath, and the brachial plexus branching from the base of the neck across the joint and down the upper arm as fine luminous filaments.

**Short identity anchor:**
> the semi-transparent anatomical right shoulder with its luminous brachial-plexus nerve tree

### Canonical subject — THE PRODUCT

> The Rejuvir Magnesio Reset jar: a short wide white cylindrical tub with a smooth white screw-on lid, a deep navy-blue band across the upper body carrying the lowercase wordmark "rejuvir" in white, below it "TECNOLOGIA A TRIPLA AZIONE" in small caps on a grey bar, "Magnesio Reset" in large black type, a navy square "12" badge with three lines of small text beside it, two lines of red subtitle text, and a navy "4oz/120 ml" block at the lower right.

> **Product reference:** I will directly attach my product photo reference — use the attached Rejuvir Magnesio Reset jar image as the packaging reference for this clip. Do not redraw, re-letter, or reinterpret the label.

Paste that note into every product clip's prompt (clips 24, 25, 30). Label text generated from words alone will come back wrong.

### Canonical subject — THE ANNO CARD

> A plain white index card with one corner slightly curled, hand-lettered in thick marker in a rough uneven adult hand, photographed close with shallow depth of field.

Per-card variation, copied from the reference's three cards:

| Card | Clip | Marker | Surface and light |
|---|---|---|---|
| ANNO 1 | 02 | black | dark wooden table, blurred green plant leaves crossing the top of frame, soft morning light |
| ANNO 3 | 06 | navy blue | pale beige shelf, card standing upright against a wall, warm afternoon light |
| ANNO 5 | 10 | black | off-white tabletop, hard diagonal window-blind shadows falling across the card |

### Canonical style descriptor — LIVE ACTION (Act 1, Act 3)

> Photorealistic amateur UGC video still, shot handheld on a modern smartphone, natural available light with visible window falloff, slight lens softness and mild motion blur, true-to-life unretouched skin texture with visible pores and blemishes, neutral warm domestic colour grade, 9:16 vertical framing.

### Canonical style descriptor — MEDICAL CGI (Act 2, absorption inserts)

> Photorealistic 3D medical animation still, semi-transparent anatomical render floating on a deep teal-navy background, glowing volumetric light, fine particle haze and drifting motes, red-orange emissive glow for inflammation and electric-blue filaments for nerve signalling, high-contrast clinical sci-fi look, 9:16 vertical framing.

End every text-to-image prompt with whichever of the two applies. Never mix them inside one clip.

### Canonical voice descriptor — NARRATOR

The client's VO track already exists. This descriptor is the reference for any pickup, re-record or ElevenLabs regeneration, so the patch matches the master:

> Native Italian male voice, mid-forties, warm low-mid baritone with a dry grainy edge, neutral standard Italian with no strong regional accent, measured documentary pace around 140 words per minute, calm and serious without melodrama, the tone of someone explaining something they have watched happen many times, tightening and slowing on the year markers, flattening to plain reassurance on "Questa non è una storia per spaventarti", and opening warmer and lighter from "La soluzione?" onward.

### Speaker map

| Clips | Delivery mode | Speaker |
|---|---|---|
| 01–30 | Narrator voiceover, off-screen | Narrator |

**No on-camera dialogue anywhere in this ad.** Every visible person — Marco, the orthopaedist, the hands applying the cream — stays silent and never lip-syncs. State this explicitly in every image-to-video prompt; models will invent mouth movement otherwise.

### Global sound lock

Matched to the reference's measured profile.

- **Music bed** — continuous, wall-to-wall, never drops out until the last beat. Minor-key cinematic tension bed: sparse piano single notes over a low sub pulse for Act 1; add a sustained low synth drone under Act 2 (clips 16–23); lift to a warmer, brighter, major-leaning version from clip 24 to the end. Ducked **12–14 dB** under the VO.
- **Ambience** — light, diegetic, mixed low: workshop hum, morning room tone, kitchen, clinic air, outdoor birds. Never competes with the bed.
- **Sound effects** — sparse and purposeful only. Permitted: a soft marker-on-paper scratch or paper settle on each ANNO card; a low sub "whoomph" on the hard cut into CGI at clip 16; a rising electric crackle as the nerves ignite (17); a dull muted thud when the arm stalls (11); a soft wet cream sound on application (25); a shimmering chime as the red glow goes out (27); a single UI tap on the CTA (30). Nothing else.
- **Transitions** — hard cuts only, everywhere. No whooshes, no risers, no dissolves.
- **Mix** — VO clearly dominant at all times. Target **−15.2 LUFS integrated, −3.0 dBFS true peak, LRA ≈ 4 LU**. Compress the master hard and flat like the reference; this runs in muted-autoplay feeds where captions carry the ad.

### Caption lock (burned in during the edit — do not ask the image model for text)

- All **lowercase**, no terminal periods. Bold italic grotesque (Montserrat ExtraBold Italic or Poppins Bold Italic).
- White fill, hard black outline ~3 px, soft drop shadow beneath.
- 1–2 lines, 3–6 words per line, centred, baseline at ~74 % frame height.
- Keyword fill: **red `#E11D1D` in clip 01 only**. **Yellow `#FFD400` from clip 02 to the end.** One or two keywords per card, never more.
- `ANNO 1 / ANNO 3 / ANNO 5` are *handwriting on the card*, not captions. Burn no caption over the card clips.

### Scene variables

Only these change between clips: setting, Marco's pose, action, expression, era wardrobe, time of day, and the CGI's glow state. Identity, facial structure, build, the product label, the two style descriptors and the 9:16 frame stay fixed.

---

## 3. Clips

### Clip 01 — hook

**Script section / voiceover text**

"Ecco che aspetto può avere una spalla dopo 5 anni passati a ignorare i segnali."

**Text-to-image prompt**

A 52-year-old Italian man, solid working build with broad shoulders and a slight paunch, square face with a heavy jaw and deep nasolabial lines, olive-tan weathered skin, close-cropped salt-and-pepper hair receding at the temples, thick greying eyebrows, deep-set dark brown eyes with pronounced crow's feet, three-day grey stubble, a short vertical scar through his left eyebrow, and thick calloused hands with short square nails. He sits bare-chested on a treatment table in a small physiotherapy room, seen from behind and slightly to the side so his bare right shoulder fills the lower two-thirds of the frame and his tense jaw is visible in soft focus beyond it; two blue-gloved hands press deep into the back of his deltoid, the skin blanching white under the fingertips, a rolled white towel and a bottle of gel on the paper-covered table beside him. Photorealistic amateur UGC video still, shot handheld on a modern smartphone, natural available light with visible window falloff, slight lens softness and mild motion blur, true-to-life unretouched skin texture with visible pores and blemishes, neutral warm domestic colour grade, 9:16 vertical framing.

**Image-to-video prompt**

Animate the 52-year-old Italian man with close-cropped salt-and-pepper hair, grey stubble and a short scar through his left eyebrow. The blue-gloved hands press and slowly drag down the back of his shoulder; his shoulder blade lifts and resists, his jaw tightens and his eyes squeeze shut for a moment as he breathes out through his nose. Keep his face, build, stubble and the treatment room exactly as they are. The camera holds almost still, drifting a few centimetres closer to the shoulder. He does not speak and his mouth stays closed — no lip-sync — while the off-screen narrator says: "Ecco che aspetto può avere una spalla dopo 5 anni passati a ignorare i segnali." Slow, heavy, clinical tempo.

**Sound / voiceover direction**

Off-screen narrator voiceover; the visible man is silent and does not lip-sync. Native Italian male voice, mid-forties, warm low-mid baritone with a dry grainy edge, neutral standard Italian with no strong regional accent, measured documentary pace around 140 words per minute, calm and serious without melodrama, the tone of someone explaining something they have watched happen many times. Music bed enters cold on frame one at full level — minor-key piano single notes over a low sub pulse — then ducks 12 dB as the VO starts. Ambience: quiet clinical room tone. No sound effects. VO dominant, −15.2 LUFS.

**Caption cards**

`ecco che aspetto può avere una spalla` → `dopo 5 anni passati a ignorare i segnali` — fill **`5 anni`** and **`ignorare i segnali`** in red `#E11D1D`. This is the only clip that uses red.

**Estimated length**

5.5 seconds

---

### Clip 02 — ANNO 1 card

**Script section / voiceover text**

"Anno 1."

**Text-to-image prompt**

A plain white index card with one corner slightly curled, hand-lettered "ANNO 1" in thick black marker in a rough uneven adult hand, lying flat on a dark wooden table with blurred green plant leaves crossing the top of the frame, soft morning light raking across the paper grain, photographed close with shallow depth of field. Photorealistic amateur UGC video still, shot handheld on a modern smartphone, natural available light with visible window falloff, slight lens softness and mild motion blur, neutral warm domestic colour grade, 9:16 vertical framing.

**Image-to-video prompt**

Animate the white hand-lettered "ANNO 1" card on the dark wooden table. Nothing in the scene moves except the blurred plant leaves drifting slightly at the top of the frame and the light shifting a fraction across the paper. Keep the handwriting, card and table exactly as they are. The camera makes one slow shallow push toward the card. No people are visible and no one speaks while the off-screen narrator says: "Anno 1." Still, quiet, matter-of-fact tempo.

**Sound / voiceover direction**

Off-screen narrator voiceover; no people on screen. Same locked narrator voice: native Italian male, mid-forties, warm low-mid baritone with a dry grainy edge, neutral standard Italian, measured documentary pace around 140 words per minute, calm and serious — tightening and slowing on the year marker. Music bed continues unbroken and steps up ~2 dB into the card. Ambience: faint morning room tone. One sound effect: a soft paper settle on the cut in. VO dominant.

**Caption cards**

None — the handwriting on the card is the title. Burn no caption.

**Estimated length**

1.5 seconds

---

### Clip 03

**Script section / voiceover text**

"Tensione alla spalla a fine turno."

**Text-to-image prompt**

A 52-year-old Italian man, solid working build with broad shoulders and a slight paunch, square face with a heavy jaw and deep nasolabial lines, olive-tan weathered skin, close-cropped salt-and-pepper hair receding at the temples, thick greying eyebrows, deep-set dark brown eyes with pronounced crow's feet, three-day grey stubble, a short vertical scar through his left eyebrow, and thick calloused hands with short square nails, wearing a navy-blue work polo with a small embroidered chest logo and sleeves pushed to the elbows. He stands at the end of a shift in a small workshop among metal shelving and stacked cardboard boxes, half-turned away from the camera, his left hand reaching across his chest to squeeze the top of his right trapezius, head tipped to the opposite side; low evening light comes through a high dusty window behind him. Photorealistic amateur UGC video still, shot handheld on a modern smartphone, natural available light with visible window falloff, slight lens softness and mild motion blur, true-to-life unretouched skin texture with visible pores and blemishes, neutral warm domestic colour grade, 9:16 vertical framing.

**Image-to-video prompt**

Animate the 52-year-old Italian man with close-cropped salt-and-pepper hair, grey stubble and a short scar through his left eyebrow. He kneads the top of his right shoulder twice with his left hand, then rolls the shoulder slowly backwards and lets it drop, exhaling, his eyes closing briefly. Keep his face, build, navy work polo and the workshop exactly as they are. The camera stays handheld and nearly static with a slight natural sway. He does not speak and his mouth stays closed — no lip-sync — while the off-screen narrator says: "Tensione alla spalla a fine turno." Tired, end-of-day tempo.

**Sound / voiceover direction**

Off-screen narrator voiceover; the visible man is silent and does not lip-sync. Same locked narrator voice: native Italian male, mid-forties, warm low-mid baritone with a dry grainy edge, neutral standard Italian, measured documentary pace around 140 words per minute, calm and serious without melodrama. Music bed continues under, ducked 12 dB. Ambience: low workshop hum, a distant metallic clink. No added sound effects. VO dominant.

**Caption cards**

`tensione alla spalla a fine turno` — fill **`tensione`** in yellow `#FFD400`.

**Estimated length**

2.5 seconds

---

### Clip 04

**Script section / voiceover text**

"Rigidità mattutina che non ti molla."

**Text-to-image prompt**

A 52-year-old Italian man, solid working build with broad shoulders and a slight paunch, square face with a heavy jaw and deep nasolabial lines, olive-tan weathered skin, close-cropped salt-and-pepper hair receding at the temples, thick greying eyebrows, deep-set dark brown eyes with pronounced crow's feet, three-day grey stubble, a short vertical scar through his left eyebrow, and thick calloused hands with short square nails, wearing a navy-blue work polo with a small embroidered chest logo and sleeves pushed to the elbows. He sits on the edge of an unmade bed in a plain bedroom at dawn, feet on the floor, shoulders hunched, his right arm lifted only slightly away from his body mid-circle as he tests the joint, face pinched; cold blue-grey early light falls through half-closed shutters behind him. Photorealistic amateur UGC video still, shot handheld on a modern smartphone, natural available light with visible window falloff, slight lens softness and mild motion blur, true-to-life unretouched skin texture with visible pores and blemishes, neutral warm domestic colour grade, 9:16 vertical framing.

**Image-to-video prompt**

Animate the 52-year-old Italian man with close-cropped salt-and-pepper hair, grey stubble and a short scar through his left eyebrow. He rotates his right shoulder in a small stiff circle, stops short with a wince, then presses his palm flat against the joint and holds it there. Keep his face, build, navy work polo and the dawn bedroom exactly as they are. The camera holds still at bed height. He does not speak and his mouth stays closed — no lip-sync — while the off-screen narrator says: "Rigidità mattutina che non ti molla." Slow, stiff, just-woken tempo.

**Sound / voiceover direction**

Off-screen narrator voiceover; the visible man is silent and does not lip-sync. Same locked narrator voice: native Italian male, mid-forties, warm low-mid baritone with a dry grainy edge, neutral standard Italian, measured documentary pace around 140 words per minute, calm and serious without melodrama. Music bed continues under, ducked 12 dB. Ambience: quiet early-morning room tone, a faint bird outside. No added sound effects. VO dominant.

**Caption cards**

`rigidità mattutina che non ti molla` — fill **`rigidità mattutina`** in yellow `#FFD400`.

**Estimated length**

2.5 seconds

---

### Clip 05

**Script section / voiceover text**

"Pensi che col riposo passerà."

**Text-to-image prompt**

A 52-year-old Italian man, solid working build with broad shoulders and a slight paunch, square face with a heavy jaw and deep nasolabial lines, olive-tan weathered skin, close-cropped salt-and-pepper hair receding at the temples, thick greying eyebrows, deep-set dark brown eyes with pronounced crow's feet, three-day grey stubble, a short vertical scar through his left eyebrow, and thick calloused hands with short square nails, wearing a navy-blue work polo with a small embroidered chest logo and sleeves pushed to the elbows. He is slumped back on a beige fabric sofa in a modest living room, a blue gel ice pack resting on his right shoulder held loosely in place by his left hand, his head tipped back against the cushion, eyes half closed, a switched-off television and a cluttered coffee table in the background; warm lamplight from the left. Photorealistic amateur UGC video still, shot handheld on a modern smartphone, natural available light with visible window falloff, slight lens softness and mild motion blur, true-to-life unretouched skin texture with visible pores and blemishes, neutral warm domestic colour grade, 9:16 vertical framing.

**Image-to-video prompt**

Animate the 52-year-old Italian man with close-cropped salt-and-pepper hair, grey stubble and a short scar through his left eyebrow. He shifts the ice pack a little higher on his shoulder, exhales, and gives a small dismissive shrug with his good shoulder as his eyes drift shut. Keep his face, build, navy work polo and the living room exactly as they are. The camera holds still with a faint handheld drift. He does not speak and his mouth stays closed — no lip-sync — while the off-screen narrator says: "Pensi che col riposo passerà." Settled, resigned, unhurried tempo.

**Sound / voiceover direction**

Off-screen narrator voiceover; the visible man is silent and does not lip-sync. Same locked narrator voice: native Italian male, mid-forties, warm low-mid baritone with a dry grainy edge, neutral standard Italian, measured documentary pace around 140 words per minute, calm and serious without melodrama. Music bed continues under, ducked 12 dB. Ambience: quiet living-room tone. No added sound effects. VO dominant.

**Caption cards**

`pensi che col riposo passerà` — fill **`col riposo`** in yellow `#FFD400`.

**Estimated length**

2.0 seconds

---

### Clip 06 — ANNO 3 card

**Script section / voiceover text**

"Anno 3."

**Text-to-image prompt**

A plain white index card with one corner slightly curled, hand-lettered "ANNO 3" in thick navy-blue marker in a rough uneven adult hand, standing upright propped against a wall on a pale beige shelf, warm afternoon light falling across it from the right with a soft shadow behind, photographed close with shallow depth of field and a blurred neutral background. Photorealistic amateur UGC video still, shot handheld on a modern smartphone, natural available light with visible window falloff, slight lens softness and mild motion blur, neutral warm domestic colour grade, 9:16 vertical framing.

**Image-to-video prompt**

Animate the white hand-lettered "ANNO 3" card standing on the pale beige shelf. Nothing moves except a slow shift of the warm afternoon light across the card face and a barely perceptible settle of the paper. Keep the handwriting, card and shelf exactly as they are. The camera makes one slow shallow push toward the card. No people are visible and no one speaks while the off-screen narrator says: "Anno 3." Still, quiet, matter-of-fact tempo.

**Sound / voiceover direction**

Off-screen narrator voiceover; no people on screen. Same locked narrator voice: native Italian male, mid-forties, warm low-mid baritone with a dry grainy edge, neutral standard Italian, measured documentary pace around 140 words per minute, calm and serious — tightening and slowing on the year marker, a shade lower than on "Anno 1". Music bed continues unbroken and steps up ~2 dB into the card. Ambience: faint indoor room tone. One sound effect: a soft paper settle on the cut in. VO dominant.

**Caption cards**

None — the handwriting on the card is the title.

**Estimated length**

1.5 seconds

---

### Clip 07

**Script section / voiceover text**

"Ora esiti prima di alzare il braccio."

**Text-to-image prompt**

A 52-year-old Italian man, solid working build with broad shoulders and a slight paunch, square face with a heavy jaw and deep nasolabial lines, olive-tan weathered skin, close-cropped salt-and-pepper hair receding at the temples, thick greying eyebrows, deep-set dark brown eyes with pronounced crow's feet, three-day grey stubble, a short vertical scar through his left eyebrow, and thick calloused hands with short square nails, wearing a heather-grey long-sleeve henley with the top button open. He stands at an open kitchen cupboard reaching for a stack of white plates on a high shelf, his right arm raised only to chest height and stalled there, fingers open but not yet committed, his head tilted up and his brow furrowed; daylight from a window to the left, tiled splashback and a kettle on the counter behind him. Photorealistic amateur UGC video still, shot handheld on a modern smartphone, natural available light with visible window falloff, slight lens softness and mild motion blur, true-to-life unretouched skin texture with visible pores and blemishes, neutral warm domestic colour grade, 9:16 vertical framing.

**Image-to-video prompt**

Animate the 52-year-old Italian man with close-cropped salt-and-pepper hair, grey stubble and a short scar through his left eyebrow. His right hand rises a few centimetres toward the plates, hesitates and hovers, then he drops it and reaches up with his left arm instead. Keep his face, build, grey henley and the kitchen exactly as they are. The camera holds still with a slight handheld sway. He does not speak and his mouth stays closed — no lip-sync — while the off-screen narrator says: "Ora esiti prima di alzare il braccio." Hesitant, stop-start tempo.

**Sound / voiceover direction**

Off-screen narrator voiceover; the visible man is silent and does not lip-sync. Same locked narrator voice: native Italian male, mid-forties, warm low-mid baritone with a dry grainy edge, neutral standard Italian, measured documentary pace around 140 words per minute, calm and serious without melodrama. Music bed continues under, ducked 12 dB. Ambience: quiet kitchen tone, a faint fridge hum. No added sound effects. VO dominant.

**Caption cards**

`ora esiti prima di alzare il braccio` — fill **`esiti`** in yellow `#FFD400`.

**Estimated length**

3.0 seconds

---

### Clip 08

**Script section / voiceover text**

"Quel fastidio “occasionale” è diventato costante."

**Text-to-image prompt**

A 52-year-old Italian man, solid working build with broad shoulders and a slight paunch, square face with a heavy jaw and deep nasolabial lines, olive-tan weathered skin, close-cropped salt-and-pepper hair receding at the temples, thick greying eyebrows, deep-set dark brown eyes with pronounced crow's feet, three-day grey stubble, a short vertical scar through his left eyebrow, and thick calloused hands with short square nails, wearing a heather-grey long-sleeve henley with the top button open. He sits at a small kitchen table with a espresso cup and an open newspaper in front of him, looking down at the page while his left hand has drifted up to knead his right shoulder without him noticing, his expression neutral and absent; flat overcast daylight from a window behind him. Photorealistic amateur UGC video still, shot handheld on a modern smartphone, natural available light with visible window falloff, slight lens softness and mild motion blur, true-to-life unretouched skin texture with visible pores and blemishes, neutral warm domestic colour grade, 9:16 vertical framing.

**Image-to-video prompt**

Animate the 52-year-old Italian man with close-cropped salt-and-pepper hair, grey stubble and a short scar through his left eyebrow. His left hand keeps kneading the right shoulder in a slow absent rhythm while he turns a page of the newspaper with his other hand, never once looking at the shoulder. Keep his face, build, grey henley and the kitchen table exactly as they are. The camera holds still. He does not speak and his mouth stays closed — no lip-sync — while the off-screen narrator says: "Quel fastidio “occasionale” è diventato costante." Flat, habitual, unremarkable tempo.

**Sound / voiceover direction**

Off-screen narrator voiceover; the visible man is silent and does not lip-sync. Same locked narrator voice: native Italian male, mid-forties, warm low-mid baritone with a dry grainy edge, neutral standard Italian, measured documentary pace around 140 words per minute, calm and serious without melodrama — a light ironic lean on the quoted word "occasionale". Music bed continues under, ducked 12 dB. Ambience: quiet kitchen tone, paper rustle. No added sound effects. VO dominant.

**Caption cards**

`quel fastidio "occasionale"` → `è diventato costante` — fill **`costante`** in yellow `#FFD400`.

**Estimated length**

2.5 seconds

---

### Clip 09

**Script section / voiceover text**

"Ma non lo dici a nessuno."

**Text-to-image prompt**

A 52-year-old Italian man, solid working build with broad shoulders and a slight paunch, square face with a heavy jaw and deep nasolabial lines, olive-tan weathered skin, close-cropped salt-and-pepper hair receding at the temples, thick greying eyebrows, deep-set dark brown eyes with pronounced crow's feet, three-day grey stubble, a short vertical scar through his left eyebrow, and thick calloused hands with short square nails, wearing a heather-grey long-sleeve henley with the top button open. He stands alone in a narrow domestic hallway gripping his right shoulder hard with his left hand, face screwed up in pain, while far behind him a warmly lit doorway shows the blurred silhouette of a seated family member at a dining table, unaware; dim hallway light, a framed photo on the wall beside him. Photorealistic amateur UGC video still, shot handheld on a modern smartphone, natural available light with visible window falloff, slight lens softness and mild motion blur, true-to-life unretouched skin texture with visible pores and blemishes, neutral warm domestic colour grade, 9:16 vertical framing.

**Image-to-video prompt**

Animate the 52-year-old Italian man with close-cropped salt-and-pepper hair, grey stubble and a short scar through his left eyebrow. He grips the shoulder and grimaces, then the blurred figure in the lit doorway behind him begins to turn — he immediately drops his hand, straightens up and smooths his face into a neutral expression. Keep his face, build, grey henley and the hallway exactly as they are. The camera holds still. He does not speak and his mouth stays closed — no lip-sync — and the blurred background figure does not speak either, while the off-screen narrator says: "Ma non lo dici a nessuno." Furtive, quickly-masked tempo.

**Sound / voiceover direction**

Off-screen narrator voiceover; every visible person is silent and no one lip-syncs. Same locked narrator voice: native Italian male, mid-forties, warm low-mid baritone with a dry grainy edge, neutral standard Italian, measured documentary pace around 140 words per minute, calm and serious without melodrama, dropping quieter and closer on this line. Music bed continues under, ducked 12 dB, thinning to just the sub pulse. Ambience: muffled indistinct family conversation from the far room, deliberately unintelligible. No added sound effects. VO dominant.

**Caption cards**

`ma non lo dici a nessuno` — fill **`a nessuno`** in yellow `#FFD400`.

**Estimated length**

2.5 seconds

---

### Clip 10 — ANNO 5 card

**Script section / voiceover text**

"Anno 5."

**Text-to-image prompt**

A plain white index card with one corner slightly curled, hand-lettered "ANNO 5" in thick black marker in a rough uneven adult hand, lying flat on an off-white tabletop with hard diagonal window-blind shadows falling in stripes across the card and the surface around it, photographed close with shallow depth of field. Photorealistic amateur UGC video still, shot handheld on a modern smartphone, natural available light with visible window falloff, slight lens softness and mild motion blur, neutral warm domestic colour grade, 9:16 vertical framing.

**Image-to-video prompt**

Animate the white hand-lettered "ANNO 5" card on the off-white tabletop. Nothing moves except the hard blind shadows creeping a few millimetres across the card as the light shifts. Keep the handwriting, card and tabletop exactly as they are. The camera makes one slow shallow push toward the card. No people are visible and no one speaks while the off-screen narrator says: "Anno 5." Still, cold, final tempo.

**Sound / voiceover direction**

Off-screen narrator voiceover; no people on screen. Same locked narrator voice: native Italian male, mid-forties, warm low-mid baritone with a dry grainy edge, neutral standard Italian, measured documentary pace around 140 words per minute, calm and serious — the lowest and slowest of the three year markers. Music bed continues unbroken and steps up ~2 dB into the card; drop the piano so only the sub pulse remains. Ambience: near-silent room tone. One sound effect: a soft paper settle on the cut in. VO dominant.

**Caption cards**

None — the handwriting on the card is the title.

**Estimated length**

1.5 seconds

---

### Clip 11

**Script section / voiceover text**

"Non riesci più a sollevare il braccio sopra la spalla."

**Text-to-image prompt**

A 52-year-old Italian man, solid working build with broad shoulders and a slight paunch, square face with a heavy jaw and deep nasolabial lines, olive-tan weathered skin, close-cropped salt-and-pepper hair receding at the temples, thick greying eyebrows, deep-set dark brown eyes with pronounced crow's feet, three-day grey stubble, a short vertical scar through his left eyebrow, and thick calloused hands with short square nails, wearing a plain white cotton undershirt. He stands in a small utility room trying to hang a shirt on a hook set high on the wall, his right arm raised and stalled dead at shoulder height, elbow bent and trembling, the shirt still in his hand, his face contorted and turned away from the arm; a washing machine and a folded laundry basket behind him, flat white light from a small window. Photorealistic amateur UGC video still, shot handheld on a modern smartphone, natural available light with visible window falloff, slight lens softness and mild motion blur, true-to-life unretouched skin texture with visible pores and blemishes, neutral warm domestic colour grade, 9:16 vertical framing.

**Image-to-video prompt**

Animate the 52-year-old Italian man with close-cropped salt-and-pepper hair, grey stubble and a short scar through his left eyebrow. He pushes the right arm upward twice against the block, the arm shaking and refusing to rise past shoulder height, then he gives up, drops the arm heavily to his side and lets the shirt fall. Keep his face, build, white undershirt and the utility room exactly as they are. The camera holds still. He does not speak and his mouth stays closed — no lip-sync — while the off-screen narrator says: "Non riesci più a sollevare il braccio sopra la spalla." Straining then defeated tempo.

**Sound / voiceover direction**

Off-screen narrator voiceover; the visible man is silent and does not lip-sync. Same locked narrator voice: native Italian male, mid-forties, warm low-mid baritone with a dry grainy edge, neutral standard Italian, measured documentary pace around 140 words per minute, calm and serious without melodrama. Music bed continues under, ducked 12 dB. Ambience: small tiled-room reverb. One sound effect: a dull muted thud as the arm drops to his side, landing under the word "spalla". VO dominant.

**Caption cards**

`non riesci più a sollevare il braccio` → `sopra la spalla` — fill **`non riesci più`** in yellow `#FFD400`.

**Estimated length**

4.0 seconds

---

### Clip 12

**Script section / voiceover text**

"L'ortopedico parla di infiltrazioni e dolore cronico."

**Text-to-image prompt**

A 52-year-old Italian man, solid working build with broad shoulders and a slight paunch, square face with a heavy jaw and deep nasolabial lines, olive-tan weathered skin, close-cropped salt-and-pepper hair receding at the temples, thick greying eyebrows, deep-set dark brown eyes with pronounced crow's feet, three-day grey stubble, a short vertical scar through his left eyebrow, and thick calloused hands with short square nails, wearing a plain white cotton undershirt. He sits in the patient's chair seen from behind in the blurred foreground, the back of his head and his broad shoulders filling the lower left of frame, his face turned away toward a consulting-room desk. Beyond him a male orthopaedic specialist in his late fifties, wearing a white coat over a blue shirt, silver-rimmed glasses and neatly combed grey hair, sits turned toward a wall-mounted monitor displaying a greyscale shoulder X-ray with his pen raised to the joint on the screen. A plastic shoulder-joint model and a prescription pad sit on the desk, cool clinical daylight from a window on the left. Photorealistic amateur UGC video still, shot handheld on a modern smartphone, natural available light with visible window falloff, slight lens softness and mild motion blur, true-to-life unretouched skin texture with visible pores and blemishes, neutral warm domestic colour grade, 9:16 vertical framing.

**Image-to-video prompt**

Animate the scene. The orthopaedic specialist in the white coat traces his pen around the shoulder joint on the X-ray and taps it twice, then turns his head toward the patient; the 52-year-old Italian man with close-cropped salt-and-pepper hair, seen from behind in the blurred foreground, lowers his head slightly. Keep both faces, the white coat, the undershirt and the consulting room exactly as they are. The camera holds still over the patient's shoulder. Neither man speaks and both keep their mouths closed — no lip-sync — while the off-screen narrator says: "L'ortopedico parla di infiltrazioni e dolore cronico." Measured, clinical, heavy tempo.

**Sound / voiceover direction**

Off-screen narrator voiceover; every visible person is silent and no one lip-syncs. Same locked narrator voice: native Italian male, mid-forties, warm low-mid baritone with a dry grainy edge, neutral standard Italian, measured documentary pace around 140 words per minute, calm and serious without melodrama. Music bed continues under, ducked 12 dB, low sub pulse only. Ambience: quiet clinic room tone, a faint keyboard tap from off-screen. No added sound effects. VO dominant.

**Caption cards**

`l'ortopedico parla di infiltrazioni` → `e dolore cronico` — fill **`infiltrazioni`** and **`dolore cronico`** in yellow `#FFD400`.

**Estimated length**

3.5 seconds

---

### Clip 13

**Script section / voiceover text**

"Sei a un passo dal tavolo operatorio."

**Text-to-image prompt**

An empty operating theatre seen from the foot of the table: a bare stainless-steel operating table with a folded white sheet, a large multi-arm surgical lamp angled down over it and just switched on, casting a hard pool of white light on the empty surface, a draped instrument tray and an anaesthesia monitor standing unused to one side, pale green tiled walls and polished floor reflecting the lamp, everything cold and still and unoccupied. Photorealistic amateur UGC video still, shot handheld on a modern smartphone, natural available light with visible window falloff, slight lens softness and mild motion blur, neutral warm domestic colour grade pushed cool, 9:16 vertical framing.

**Image-to-video prompt**

Animate the empty operating theatre. The surgical lamp brightens smoothly to full over the bare table and its reflection sharpens on the polished floor; nothing else in the room moves. Keep the table, lamp, instrument tray and tiled walls exactly as they are. The camera makes one slow push in along the length of the empty table. No people are visible and no one speaks while the off-screen narrator says: "Sei a un passo dal tavolo operatorio." Cold, still, ominous tempo.

**Sound / voiceover direction**

Off-screen narrator voiceover; no people on screen. Same locked narrator voice: native Italian male, mid-forties, warm low-mid baritone with a dry grainy edge, neutral standard Italian, measured documentary pace around 140 words per minute, calm and serious without melodrama — landing this line flat and final, no lift at the end. Music bed continues under, ducked 12 dB; hold a single sustained low note through the whole clip. Ambience: hollow tiled-room air, a faint electrical hum from the lamp. No added sound effects. VO dominant. This is the lowest emotional point of the ad — let the bed sit for a beat before the cut.

**Caption cards**

`sei a un passo` → `dal tavolo operatorio` — fill **`tavolo operatorio`** in yellow `#FFD400`.

**Estimated length**

3.5 seconds

---

### Clip 14

**Script section / voiceover text**

"Questa non è una storia per spaventarti."

**Text-to-image prompt**

A 52-year-old Italian man, solid working build with broad shoulders and a slight paunch, square face with a heavy jaw and deep nasolabial lines, olive-tan weathered skin, close-cropped salt-and-pepper hair receding at the temples, thick greying eyebrows, deep-set dark brown eyes with pronounced crow's feet, three-day grey stubble, a short vertical scar through his left eyebrow, and thick calloused hands with short square nails, wearing a plain white cotton undershirt. He sits calmly on a plastic chair on a small apartment balcony in full soft daylight, forearms resting on his thighs, hands loosely clasped, looking out and slightly down with a quiet unguarded expression, terracotta pots and a low railing beside him, blurred green trees and neighbouring buildings beyond. Photorealistic amateur UGC video still, shot handheld on a modern smartphone, natural available light with visible window falloff, slight lens softness and mild motion blur, true-to-life unretouched skin texture with visible pores and blemishes, neutral warm domestic colour grade, 9:16 vertical framing.

**Image-to-video prompt**

Animate the 52-year-old Italian man with close-cropped salt-and-pepper hair, grey stubble and a short scar through his left eyebrow. He breathes out slowly, blinks, and lifts his gaze from the floor to look out past the railing; his shoulders drop and settle. Keep his face, build, white undershirt and the balcony exactly as they are. The camera holds still at seated height with a gentle handheld sway. He does not speak and his mouth stays closed — no lip-sync — while the off-screen narrator says: "Questa non è una storia per spaventarti." Calm, settled, honest tempo.

**Sound / voiceover direction**

Off-screen narrator voiceover; the visible man is silent and does not lip-sync. Same locked narrator voice: native Italian male, mid-forties, warm low-mid baritone with a dry grainy edge, neutral standard Italian, measured documentary pace around 140 words per minute — this is the tone-reset line, so flatten it to plain reassurance with no persuasive lean at all. Music bed continues under, ducked 12 dB; drop the sub pulse and let the piano return alone. Ambience: outdoor air, distant traffic, birds. No added sound effects. VO dominant.

**Caption cards**

`questa non è una storia` → `per spaventarti` — fill **`per spaventarti`** in yellow `#FFD400`.

**Estimated length**

3.0 seconds

---

### Clip 15

**Script section / voiceover text**

"È quello che può accadere quando tensione e sovraccarico vengono ignorati per anni."

**Text-to-image prompt**

A 52-year-old Italian man, solid working build with broad shoulders and a slight paunch, square face with a heavy jaw and deep nasolabial lines, olive-tan weathered skin, close-cropped salt-and-pepper hair receding at the temples, thick greying eyebrows, deep-set dark brown eyes with pronounced crow's feet, three-day grey stubble, a short vertical scar through his left eyebrow, and thick calloused hands with short square nails, wearing a plain white cotton undershirt. He is lifting a heavy cardboard box from a trolley up onto a high metal shelf in a storage room, both arms extended above chest height, the box tipped against his right shoulder taking the weight, his neck corded and his face strained, rows of stacked boxes receding behind him under a bare fluorescent strip light. Photorealistic amateur UGC video still, shot handheld on a modern smartphone, natural available light with visible window falloff, slight lens softness and mild motion blur, true-to-life unretouched skin texture with visible pores and blemishes, neutral warm domestic colour grade, 9:16 vertical framing.

**Image-to-video prompt**

Animate the 52-year-old Italian man with close-cropped salt-and-pepper hair, grey stubble and a short scar through his left eyebrow. He pushes the heavy box the last few centimetres onto the high shelf, holding it braced against his right shoulder, then lowers his arms slowly and rolls the shoulder once as he steps back. Keep his face, build, white undershirt and the storage room exactly as they are. The camera holds still in a low three-quarter angle. He does not speak and his mouth stays closed — no lip-sync — while the off-screen narrator says: "È quello che può accadere quando tensione e sovraccarico vengono ignorati per anni." Effortful, repetitive, everyday tempo.

**Sound / voiceover direction**

Off-screen narrator voiceover; the visible man is silent and does not lip-sync. Same locked narrator voice: native Italian male, mid-forties, warm low-mid baritone with a dry grainy edge, neutral standard Italian, measured documentary pace around 140 words per minute, calm and serious without melodrama. Music bed continues under, ducked 12 dB, rebuilding slightly toward the act change. Ambience: storeroom air, fluorescent hum, cardboard scrape. No added sound effects. VO dominant.

**Caption cards**

`è quello che può accadere quando` → `tensione e sovraccarico vengono ignorati per anni` — fill **`tensione e sovraccarico`** in yellow `#FFD400`.

**Estimated length**

5.0 seconds

---

### Clip 16 — hard cut into Act 2 (CGI)

**Script section / voiceover text**

"Ecco cosa sta succedendo alla tua spalla."

**Text-to-image prompt**

A right human shoulder rendered as a semi-transparent anatomical model — deltoid, trapezius and rotator-cuff muscles in translucent warm grey, the humeral head and scapula visible as pale bone beneath, and the brachial plexus branching from the base of the neck across the joint and down the upper arm as fine luminous filaments. It floats centred and slightly rotated toward the viewer in empty space, the nerve tree still dim and cool, the whole joint calm and unlit, faint dust motes drifting around it. Photorealistic 3D medical animation still, semi-transparent anatomical render floating on a deep teal-navy background, glowing volumetric light, fine particle haze and drifting motes, red-orange emissive glow for inflammation and electric-blue filaments for nerve signalling, high-contrast clinical sci-fi look, 9:16 vertical framing.

**Image-to-video prompt**

Animate the semi-transparent anatomical right shoulder with its luminous brachial-plexus nerve tree. The whole model rotates slowly a few degrees toward the viewer while the nerve filaments begin to flicker faintly awake along their length. Keep the anatomy, materials, colours and rendering style exactly as they are. The camera makes one steady push in toward the joint. No people are visible and no one speaks while the off-screen narrator says: "Ecco cosa sta succedendo alla tua spalla." Deliberate, revealing, gathering tempo.

**Sound / voiceover direction**

Off-screen narrator voiceover; no people on screen. Same locked narrator voice: native Italian male, mid-forties, warm low-mid baritone with a dry grainy edge, neutral standard Italian, measured documentary pace around 140 words per minute, calm and serious without melodrama — leaning forward into explanation here. **Act change:** on the hard cut, add a sustained low synth drone beneath the existing bed and keep it under every clip to 23. Ambience: none — the CGI act runs on bed and drone only. One sound effect: a low sub "whoomph" exactly on the cut in. VO dominant.

**Caption cards**

`ecco cosa sta succedendo` → `alla tua spalla` — fill **`alla tua spalla`** in yellow `#FFD400`.

**Estimated length**

3.0 seconds

---

### Clip 17

**Script section / voiceover text**

"Ore di movimenti ripetuti, sforzi e posture scorrette mandano in allarme permanente i tuoi nervi."

**Text-to-image prompt**

A right human shoulder rendered as a semi-transparent anatomical model — deltoid, trapezius and rotator-cuff muscles in translucent warm grey, the humeral head and scapula visible as pale bone beneath, and the brachial plexus branching from the base of the neck across the joint and down the upper arm as fine luminous filaments. The nerve tree is now blazing hot red-orange along every branch, sparks and embers flaring off the filaments where they cross the joint, the surrounding translucent muscle lit from within by the glow. Photorealistic 3D medical animation still, semi-transparent anatomical render floating on a deep teal-navy background, glowing volumetric light, fine particle haze and drifting motes, red-orange emissive glow for inflammation and electric-blue filaments for nerve signalling, high-contrast clinical sci-fi look, 9:16 vertical framing.

**Image-to-video prompt**

Animate the semi-transparent anatomical right shoulder with its luminous brachial-plexus nerve tree. The nerve filaments ignite in a wave that races from the base of the neck outward along every branch until the whole tree is burning red-orange and pulsing at a fast steady rate, embers streaming off it. Keep the anatomy, materials, colours and rendering style exactly as they are. The camera drifts slowly along the arm following the ignition. No people are visible and no one speaks while the off-screen narrator says: "Ore di movimenti ripetuti, sforzi e posture scorrette mandano in allarme permanente i tuoi nervi." Escalating, urgent tempo.

**Sound / voiceover direction**

Off-screen narrator voiceover; no people on screen. Same locked narrator voice: native Italian male, mid-forties, warm low-mid baritone with a dry grainy edge, neutral standard Italian, measured documentary pace around 140 words per minute, calm and serious without melodrama, pressing harder through the list. Music bed plus the low synth drone, ducked 12 dB. Ambience: none. One sound effect: a rising electric crackle riding the ignition wave, peaking on "allarme permanente", then settling into a faint sustained sizzle. VO dominant — keep the crackle well under the voice.

**Caption cards**

`ore di movimenti ripetuti, sforzi` → `e posture scorrette` → `mandano in allarme permanente i tuoi nervi` — fill **`allarme permanente`** in yellow `#FFD400`.

**Estimated length**

6.0 seconds

---

### Clip 18

**Script section / voiceover text**

"Il sistema nervoso comanda ai muscoli di rimanere contratti."

**Text-to-image prompt**

A right human shoulder rendered as a semi-transparent anatomical model — deltoid, trapezius and rotator-cuff muscles in translucent warm grey, the humeral head and scapula visible as pale bone beneath, and the brachial plexus branching from the base of the neck across the joint and down the upper arm as fine luminous filaments. Framed close on the deltoid and trapezius, whose individual muscle fibres are drawn short, thick and rigid, bunched and knotted, with the burning red-orange nerve filaments threading between them and electric-blue command pulses travelling down into the fibres. Photorealistic 3D medical animation still, semi-transparent anatomical render floating on a deep teal-navy background, glowing volumetric light, fine particle haze and drifting motes, red-orange emissive glow for inflammation and electric-blue filaments for nerve signalling, high-contrast clinical sci-fi look, 9:16 vertical framing.

**Image-to-video prompt**

Animate the semi-transparent anatomical right shoulder with its luminous brachial-plexus nerve tree. Electric-blue pulses travel down the nerve filaments into the muscle, and as each pulse lands the fibres cinch shorter and thicker and then lock rigid, refusing to release. Keep the anatomy, materials, colours and rendering style exactly as they are. The camera holds close and still on the contracting fibres. No people are visible and no one speaks while the off-screen narrator says: "Il sistema nervoso comanda ai muscoli di rimanere contratti." Tightening, mechanical, relentless tempo.

**Sound / voiceover direction**

Off-screen narrator voiceover; no people on screen. Same locked narrator voice: native Italian male, mid-forties, warm low-mid baritone with a dry grainy edge, neutral standard Italian, measured documentary pace around 140 words per minute, calm and serious without melodrama. Music bed plus the low synth drone, ducked 12 dB. Ambience: none. Sound effects: faint low creaking tension rising with each fibre contraction, and the sustained sizzle continuing underneath. VO dominant.

**Caption cards**

`il sistema nervoso comanda ai muscoli` → `di rimanere contratti` — fill **`rimanere contratti`** in yellow `#FFD400`.

**Estimated length**

4.0 seconds

---

### Clip 19

**Script section / voiceover text**

"La circolazione cala e l’articolazione s’infiamma."

**Text-to-image prompt**

A right human shoulder rendered as a semi-transparent anatomical model — deltoid, trapezius and rotator-cuff muscles in translucent warm grey, the humeral head and scapula visible as pale bone beneath, and the brachial plexus branching from the base of the neck across the joint and down the upper arm as fine luminous filaments. Framed on the joint capsule, where fine blood vessels threading through the contracted muscle are pinched narrow and their flowing light dimmed to a trickle, while the capsule around the humeral head swells and glows an angry saturated red. Photorealistic 3D medical animation still, semi-transparent anatomical render floating on a deep teal-navy background, glowing volumetric light, fine particle haze and drifting motes, red-orange emissive glow for inflammation and electric-blue filaments for nerve signalling, high-contrast clinical sci-fi look, 9:16 vertical framing.

**Image-to-video prompt**

Animate the semi-transparent anatomical right shoulder with its luminous brachial-plexus nerve tree. The blood vessels squeeze narrower and the bright flow inside them slows and fades toward dark, and as it does the joint capsule swells outward and floods deeper red. Keep the anatomy, materials, colours and rendering style exactly as they are. The camera holds still on the joint. No people are visible and no one speaks while the off-screen narrator says: "La circolazione cala e l’articolazione s’infiamma." Slowing then swelling tempo.

**Sound / voiceover direction**

Off-screen narrator voiceover; no people on screen. Same locked narrator voice: native Italian male, mid-forties, warm low-mid baritone with a dry grainy edge, neutral standard Italian, measured documentary pace around 140 words per minute, calm and serious without melodrama. Music bed plus the low synth drone, ducked 12 dB. Ambience: none. Sound effects: a slowing low pulse like a heartbeat losing pressure, and a soft swelling low-frequency bloom as the capsule inflames. VO dominant.

**Caption cards**

`la circolazione cala` → `e l'articolazione s'infiamma` — fill **`s'infiamma`** in yellow `#FFD400`.

**Estimated length**

3.0 seconds

---

### Clip 20

**Script section / voiceover text**

"Aumentando ulteriormente la sensibilità dei nervi."

**Text-to-image prompt**

A right human shoulder rendered as a semi-transparent anatomical model — deltoid, trapezius and rotator-cuff muscles in translucent warm grey, the humeral head and scapula visible as pale bone beneath, and the brachial plexus branching from the base of the neck across the joint and down the upper arm as fine luminous filaments. Framed very close on the fine nerve endings fanning out through the inflamed red tissue, each ending flaring hotter and whiter than the branch behind it, hair-thin tips crackling with white-hot sparks. Photorealistic 3D medical animation still, semi-transparent anatomical render floating on a deep teal-navy background, glowing volumetric light, fine particle haze and drifting motes, red-orange emissive glow for inflammation and electric-blue filaments for nerve signalling, high-contrast clinical sci-fi look, 9:16 vertical framing.

**Image-to-video prompt**

Animate the semi-transparent anatomical right shoulder with its luminous brachial-plexus nerve tree. The fine nerve endings brighten step by step from red to orange to white-hot and their sparking rate accelerates sharply. Keep the anatomy, materials, colours and rendering style exactly as they are. The camera pushes in very slightly on the brightest endings. No people are visible and no one speaks while the off-screen narrator says: "Aumentando ulteriormente la sensibilità dei nervi." Accelerating, escalating tempo.

**Sound / voiceover direction**

Off-screen narrator voiceover; no people on screen. Same locked narrator voice: native Italian male, mid-forties, warm low-mid baritone with a dry grainy edge, neutral standard Italian, measured documentary pace around 140 words per minute, calm and serious without melodrama. Music bed plus the low synth drone, ducked 12 dB. Ambience: none. Sound effect: the electric crackle climbing in pitch and density through the clip. VO dominant.

**Caption cards**

`aumentando ulteriormente` → `la sensibilità dei nervi` — fill **`la sensibilità dei nervi`** in yellow `#FFD400`.

**Estimated length**

2.5 seconds

---

### Clip 21 — the loop

**Script section / voiceover text**

"Ogni giorno un pò di più. Senza che tu te ne accorga."

> Two short sentences merged into one clip, per the brief. They describe a single continuous visual event: the cycle repeating unnoticed.

**Text-to-image prompt**

A right human shoulder rendered as a semi-transparent anatomical model — deltoid, trapezius and rotator-cuff muscles in translucent warm grey, the humeral head and scapula visible as pale bone beneath, and the brachial plexus branching from the base of the neck across the joint and down the upper arm as fine luminous filaments. Seen wide again with the whole joint glowing red, and a faint circular arrow of light tracing a closed loop around it from nerve to muscle to vessel to joint and back to nerve, each station on the ring lit slightly brighter than the last. Photorealistic 3D medical animation still, semi-transparent anatomical render floating on a deep teal-navy background, glowing volumetric light, fine particle haze and drifting motes, red-orange emissive glow for inflammation and electric-blue filaments for nerve signalling, high-contrast clinical sci-fi look, 9:16 vertical framing.

**Image-to-video prompt**

Animate the semi-transparent anatomical right shoulder with its luminous brachial-plexus nerve tree. The circular arrow of light travels the closed loop around the joint several times, and with each full revolution the overall red glow of the shoulder deepens a little further. Keep the anatomy, materials, colours and rendering style exactly as they are. The camera slowly pulls back as the loop turns. No people are visible and no one speaks while the off-screen narrator says: "Ogni giorno un pò di più. Senza che tu te ne accorga." Cyclical, accumulating, inevitable tempo.

**Sound / voiceover direction**

Off-screen narrator voiceover; no people on screen. Same locked narrator voice: native Italian male, mid-forties, warm low-mid baritone with a dry grainy edge, neutral standard Italian, measured documentary pace around 140 words per minute, calm and serious without melodrama — drop quieter and closer on "Senza che tu te ne accorga". Music bed plus the low synth drone, ducked 12 dB, the drone rising a couple of dB per loop revolution. Ambience: none. Sound effect: one soft low pulse per revolution of the ring. VO dominant.

**Caption cards**

`ogni giorno un pò di più` → `senza che tu te ne accorga` — fill **`ogni giorno`** and **`te ne accorga`** in yellow `#FFD400`.

**Estimated length**

4.5 seconds

---

### Clip 22 — the failed intervention

**Script section / voiceover text**

"Ed è inutile intervenire su contrattura e infiammazione se prima non si è spento l’allarme."

**Text-to-image prompt**

A right human shoulder rendered as a semi-transparent anatomical model — deltoid, trapezius and rotator-cuff muscles in translucent warm grey, the humeral head and scapula visible as pale bone beneath, and the brachial plexus branching from the base of the neck across the joint and down the upper arm as fine luminous filaments. A cool blue wave of light is washing across the outer muscle and the joint capsule, cooling that tissue from red toward calm blue as it passes, while at the core of the joint the brachial-plexus nerve tree still burns fierce untouched red-orange behind the blue, visibly unaffected. Photorealistic 3D medical animation still, semi-transparent anatomical render floating on a deep teal-navy background, glowing volumetric light, fine particle haze and drifting motes, red-orange emissive glow for inflammation and electric-blue filaments for nerve signalling, high-contrast clinical sci-fi look, 9:16 vertical framing.

**Image-to-video prompt**

Animate the semi-transparent anatomical right shoulder with its luminous brachial-plexus nerve tree. The cool blue wave sweeps fully across the muscle and joint capsule and calms them to blue, but the burning nerve core at the centre stays exactly as hot and red as before, untouched by the wave. Keep the anatomy, materials, colours and rendering style exactly as they are. The camera holds still on the joint. No people are visible and no one speaks while the off-screen narrator says: "Ed è inutile intervenire su contrattura e infiammazione se prima non si è spento l’allarme." Hopeful sweep that resolves into stubborn, unchanged burn.

**Sound / voiceover direction**

Off-screen narrator voiceover; no people on screen. Same locked narrator voice: native Italian male, mid-forties, warm low-mid baritone with a dry grainy edge, neutral standard Italian, measured documentary pace around 140 words per minute, calm and serious without melodrama — this is the reframe line, so slow slightly and land "l'allarme" flat and hard. Music bed plus the low synth drone, ducked 12 dB. Ambience: none. Sound effects: a soft cooling wash riding the blue wave, and the nerve sizzle continuing unbroken underneath it — the sizzle must not duck when the wash passes. VO dominant.

**Caption cards**

`ed è inutile intervenire su` → `contrattura e infiammazione` → `se prima non si è spento l'allarme` — fill **`inutile`** and **`l'allarme`** in yellow `#FFD400`.

**Estimated length**

6.0 seconds

---

### Clip 23

**Script section / voiceover text**

"Ecco perché il fastidio torna sempre."

**Text-to-image prompt**

A right human shoulder rendered as a semi-transparent anatomical model — deltoid, trapezius and rotator-cuff muscles in translucent warm grey, the humeral head and scapula visible as pale bone beneath, and the brachial plexus branching from the base of the neck across the joint and down the upper arm as fine luminous filaments. The blue calm is receding and red is bleeding back outward from the burning nerve core, reclaiming the muscle and the joint capsule from the inside out, roughly half the shoulder already returned to angry red. Photorealistic 3D medical animation still, semi-transparent anatomical render floating on a deep teal-navy background, glowing volumetric light, fine particle haze and drifting motes, red-orange emissive glow for inflammation and electric-blue filaments for nerve signalling, high-contrast clinical sci-fi look, 9:16 vertical framing.

**Image-to-video prompt**

Animate the semi-transparent anatomical right shoulder with its luminous brachial-plexus nerve tree. The red glow spreads back outward from the nerve core and overtakes the last of the blue until the entire shoulder is burning red again exactly as it was before. Keep the anatomy, materials, colours and rendering style exactly as they are. The camera holds still. No people are visible and no one speaks while the off-screen narrator says: "Ecco perché il fastidio torna sempre." Creeping, inevitable, closing-loop tempo.

**Sound / voiceover direction**

Off-screen narrator voiceover; no people on screen. Same locked narrator voice: native Italian male, mid-forties, warm low-mid baritone with a dry grainy edge, neutral standard Italian, measured documentary pace around 140 words per minute, calm and serious without melodrama. Music bed plus the low synth drone, ducked 12 dB. Ambience: none. Sound effect: the electric sizzle swelling back to full as the red reclaims the tissue. **Cut the drone dead on the last frame** — the silence into clip 24 is the turn. VO dominant.

**Caption cards**

`ecco perché il fastidio` → `torna sempre` — fill **`torna sempre`** in yellow `#FFD400`.

**Estimated length**

2.5 seconds

---

### Clip 24 — product reveal

**Script section / voiceover text**

"La soluzione? Magnesio topico."

> **Product reference:** I will directly attach my product photo reference — use the attached Rejuvir Magnesio Reset jar image as the packaging reference for this clip. Do not redraw, re-letter, or reinterpret the label.

**Text-to-image prompt**

The Rejuvir Magnesio Reset jar: a short wide white cylindrical tub with a smooth white screw-on lid, a deep navy-blue band across the upper body carrying the lowercase wordmark "rejuvir" in white, below it "TECNOLOGIA A TRIPLA AZIONE" in small caps on a grey bar, "Magnesio Reset" in large black type, a navy square "12" badge with three lines of small text beside it, two lines of red subtitle text, and a navy "4oz/120 ml" block at the lower right. A man's thick calloused hand holds the jar up toward the camera at chest height, label square to the lens and fully legible, filling the upper half of the frame, against a softly blurred sunlit domestic background of a balcony railing and green plants. Photorealistic amateur UGC video still, shot handheld on a modern smartphone, natural available light with visible window falloff, slight lens softness and mild motion blur, true-to-life unretouched skin texture with visible pores and blemishes, neutral warm domestic colour grade, 9:16 vertical framing.

**Image-to-video prompt**

Animate the white Rejuvir Magnesio Reset jar with its navy band and lowercase "rejuvir" wordmark, held in a man's thick calloused hand. The hand turns the jar a few degrees so the light travels across the label and the navy band catches the sun, keeping the label facing the lens and readable throughout. Keep the jar's shape, proportions, colours and every element of the label exactly as they are — do not alter, re-letter or redesign the packaging. The camera holds still. No face is visible and no one speaks while the off-screen narrator says: "La soluzione? Magnesio topico." Bright, simple, declarative tempo.

**Sound / voiceover direction**

Off-screen narrator voiceover; no speaking person on screen. Same locked narrator voice: native Italian male, mid-forties, warm low-mid baritone with a dry grainy edge, neutral standard Italian, measured documentary pace around 140 words per minute — opening warmer and lighter from this line onward, a small lift on the question and a clean flat landing on "Magnesio topico". **Music turn:** the drone is gone; the bed re-enters here in a warmer, brighter, major-leaning version and carries to the end, ducked 12 dB. Ambience: outdoor air, faint birds. No added sound effects. VO dominant.

**Caption cards**

`la soluzione?` → `magnesio topico` — fill **`magnesio topico`** in yellow `#FFD400`.

**Estimated length**

2.0 seconds

---

### Clip 25 — application

**Script section / voiceover text**

"Applicato sulla spalla dolorante."

> **Product reference:** I will directly attach my product photo reference — use the attached Rejuvir Magnesio Reset jar image as the packaging reference for the open jar in this clip. Do not redraw, re-letter, or reinterpret the label.

**Text-to-image prompt**

A 52-year-old Italian man, solid working build with broad shoulders and a slight paunch, square face with a heavy jaw and deep nasolabial lines, olive-tan weathered skin, close-cropped salt-and-pepper hair receding at the temples, thick greying eyebrows, deep-set dark brown eyes with pronounced crow's feet, three-day grey stubble, a short vertical scar through his left eyebrow, and thick calloused hands with short square nails. He sits bare-shouldered on a stool in a bright bathroom seen from behind and to the side, his right shoulder filling the centre of frame with a white cream just smoothed across the deltoid; a woman's hands work the cream into the joint with flat circular strokes. The open Rejuvir Magnesio Reset jar — short wide white tub, navy-blue band with the lowercase "rejuvir" wordmark in white, "Magnesio Reset" in black type — stands on the counter beside him with its white lid off, label facing the camera. Photorealistic amateur UGC video still, shot handheld on a modern smartphone, natural available light with visible window falloff, slight lens softness and mild motion blur, true-to-life unretouched skin texture with visible pores and blemishes, neutral warm domestic colour grade, 9:16 vertical framing.

**Image-to-video prompt**

Animate the 52-year-old Italian man with close-cropped salt-and-pepper hair, grey stubble and a short scar through his left eyebrow, seen from behind. The woman's hands massage the white cream into his bare right shoulder in slow firm circles until it absorbs and the skin is left faintly sheened; his shoulders drop and he exhales. Keep his build, the shoulder, the bathroom and the Rejuvir jar on the counter exactly as they are — do not alter, re-letter or redesign the packaging. The camera holds still and close on the shoulder. Neither person speaks and both keep their mouths closed — no lip-sync — while the off-screen narrator says: "Applicato sulla spalla dolorante." Slow, careful, soothing tempo.

**Sound / voiceover direction**

Off-screen narrator voiceover; every visible person is silent and no one lip-syncs. Same locked narrator voice: native Italian male, mid-forties, warm low-mid baritone with a dry grainy edge, neutral standard Italian, measured documentary pace around 140 words per minute, calm and warm here. Warm major-leaning music bed continues, ducked 12 dB. Ambience: small bright bathroom room tone. One sound effect: a soft wet cream sound under the circular strokes, mixed low. VO dominant.

**Caption cards**

`applicato sulla spalla dolorante` — fill **`spalla dolorante`** in yellow `#FFD400`.

**Estimated length**

2.0 seconds

---

### Clip 26 — absorption (CGI insert)

**Script section / voiceover text**

"Il magnesio viene assorbito direttamente attraverso la pelle"

> This is the first half of the script's longest sentence. It is split across clips 26 and 27 — the only sentence in the ad that is split — because it describes two distinct mechanisms (absorption, then signal interruption) that cannot be shown as one visual event. Cut clips 26 and 27 back to back with no gap and the line reads as one continuous sentence over the picture.

**Text-to-image prompt**

A cross-section of human skin rendered as a semi-transparent anatomical model in translucent warm greys, layered epidermis and dermis with fine capillaries and hair follicles running through it, and a layer of white cream resting on the surface at the top of the frame. Bright cyan-white magnesium particles are descending out of the cream in a steady column, passing down between the skin layers toward the fine luminous nerve filaments running along the bottom of the frame, which still glow hot red-orange. Photorealistic 3D medical animation still, semi-transparent anatomical render floating on a deep teal-navy background, glowing volumetric light, fine particle haze and drifting motes, red-orange emissive glow for inflammation and electric-blue filaments for nerve signalling, high-contrast clinical sci-fi look, 9:16 vertical framing.

**Image-to-video prompt**

Animate the semi-transparent skin cross-section with the white cream layer on its surface. The bright cyan-white magnesium particles stream steadily downward out of the cream, threading between the skin layers and past the capillaries toward the glowing red nerve filaments below, leaving faint luminous trails behind them. Keep the skin layers, particle colour, cream layer and rendering style exactly as they are. The camera descends slowly alongside the falling particles. No people are visible and no one speaks while the off-screen narrator says: "Il magnesio viene assorbito direttamente attraverso la pelle" Steady, purposeful, downward tempo.

**Sound / voiceover direction**

Off-screen narrator voiceover; no people on screen. Same locked narrator voice: native Italian male, mid-forties, warm low-mid baritone with a dry grainy edge, neutral standard Italian, measured documentary pace around 140 words per minute, calm and explanatory — do not close the phrase, carry the inflection straight into clip 27. Warm major-leaning music bed continues, ducked 12 dB. Ambience: none. Sound effect: a fine shimmering granular texture following the descending particles. VO dominant.

**Caption cards**

`il magnesio viene assorbito` → `direttamente attraverso la pelle` — fill **`attraverso la pelle`** in yellow `#FFD400`.

**Estimated length**

3.5 seconds

---

### Clip 27 — the alarm goes out (CGI insert)

**Script section / voiceover text**

"per interrompere i segnali nervosi che alimentano dolore e rigidità."

**Text-to-image prompt**

A right human shoulder rendered as a semi-transparent anatomical model — deltoid, trapezius and rotator-cuff muscles in translucent warm grey, the humeral head and scapula visible as pale bone beneath, and the brachial plexus branching from the base of the neck across the joint and down the upper arm as fine luminous filaments. Bright cyan-white magnesium particles have gathered densely along the nerve tree, and the burning red-orange glow is going out along the filaments from the neck outward, the quenched sections left calm and cool blue while the far tips still glow faintly red. Photorealistic 3D medical animation still, semi-transparent anatomical render floating on a deep teal-navy background, glowing volumetric light, fine particle haze and drifting motes, red-orange emissive glow for inflammation and electric-blue filaments for nerve signalling, high-contrast clinical sci-fi look, 9:16 vertical framing.

**Image-to-video prompt**

Animate the semi-transparent anatomical right shoulder with its luminous brachial-plexus nerve tree. The cyan-white particles settle along the burning filaments and the red-orange glow goes out behind them in a wave travelling outward to the last nerve tip, leaving the whole tree calm and cool blue, and as the nerves quiet the contracted muscle fibres around them visibly lengthen and release. Keep the anatomy, materials, colours and rendering style exactly as they are. The camera pulls back slowly to take in the whole calmed shoulder. No people are visible and no one speaks while the off-screen narrator says: "per interrompere i segnali nervosi che alimentano dolore e rigidità." Calming, releasing, resolving tempo.

**Sound / voiceover direction**

Off-screen narrator voiceover; no people on screen. Same locked narrator voice: native Italian male, mid-forties, warm low-mid baritone with a dry grainy edge, neutral standard Italian, measured documentary pace around 140 words per minute, calm and explanatory, landing the end of the sentence with quiet finality. Warm major-leaning music bed continues and opens up here, ducked 12 dB. Ambience: none. Sound effects: the electric sizzle from Act 2 fading out to nothing as the glow quenches, and a soft shimmering chime on the final frame. This is the payoff beat — let the sizzle's disappearance be audible. VO dominant.

**Caption cards**

`per interrompere i segnali nervosi` → `che alimentano dolore e rigidità` — fill **`interrompere i segnali nervosi`** in yellow `#FFD400`.

**Estimated length**

4.0 seconds

---

### Clip 28

**Script section / voiceover text**

"Senza farmaci."

**Text-to-image prompt**

A kitchen table seen from directly above: a white prescription pill bottle lying on its side with its cap off and a scatter of white oval tablets spilled across the dark stone surface, a blister pack of pills and a half-full glass of water beside them, and a man's thick calloused hand entering from the bottom of frame pushing the bottle and tablets away toward the top of the frame. Flat overcast daylight, a folded newspaper at the edge of the table. Photorealistic amateur UGC video still, shot handheld on a modern smartphone, natural available light with visible window falloff, slight lens softness and mild motion blur, true-to-life unretouched skin texture with visible pores and blemishes, neutral warm domestic colour grade, 9:16 vertical framing.

**Image-to-video prompt**

Animate the overhead kitchen-table scene. The thick calloused hand slides the pill bottle and the scattered tablets firmly away across the stone surface and out of the top of the frame, then withdraws. Keep the table, the pills, the glass and the lighting exactly as they are. The camera holds still directly overhead. No face is visible and no one speaks while the off-screen narrator says: "Senza farmaci." Decisive, dismissive, single-gesture tempo.

**Sound / voiceover direction**

Off-screen narrator voiceover; no speaking person on screen. Same locked narrator voice: native Italian male, mid-forties, warm low-mid baritone with a dry grainy edge, neutral standard Italian, measured documentary pace around 140 words per minute — clipped and flat on this two-word line, no lift. Warm major-leaning music bed continues, ducked 12 dB. Ambience: quiet kitchen tone. One sound effect: the dry rattle and scrape of the bottle and tablets sliding across stone. VO dominant.

**Caption cards**

`senza farmaci` — fill **`senza farmaci`** in yellow `#FFD400`.

**Estimated length**

1.5 seconds

---

### Clip 29

**Script section / voiceover text**

"Non aspettare che sia troppo tardi."

**Text-to-image prompt**

A 52-year-old Italian man, solid working build with broad shoulders and a slight paunch, square face with a heavy jaw and deep nasolabial lines, olive-tan weathered skin, close-cropped salt-and-pepper hair receding at the temples, thick greying eyebrows, deep-set dark brown eyes with pronounced crow's feet, three-day grey stubble, a short vertical scar through his left eyebrow, and thick calloused hands with short square nails, wearing a plain white cotton undershirt. He sits on the edge of his bed in warm morning light with his left hand resting on his right shoulder, looking down and thinking, his smartphone face-up on the nightstand beside him within reach; rumpled sheets and half-open shutters behind him. Photorealistic amateur UGC video still, shot handheld on a modern smartphone, natural available light with visible window falloff, slight lens softness and mild motion blur, true-to-life unretouched skin texture with visible pores and blemishes, neutral warm domestic colour grade, 9:16 vertical framing.

**Image-to-video prompt**

Animate the 52-year-old Italian man with close-cropped salt-and-pepper hair, grey stubble and a short scar through his left eyebrow. He rests his hand on his shoulder a moment longer, then lifts his head, turns toward the nightstand and reaches out for the smartphone. Keep his face, build, white undershirt and the bedroom exactly as they are. The camera holds still at bed height. He does not speak and his mouth stays closed — no lip-sync — while the off-screen narrator says: "Non aspettare che sia troppo tardi." Deciding, turning-point tempo.

**Sound / voiceover direction**

Off-screen narrator voiceover; the visible man is silent and does not lip-sync. Same locked narrator voice: native Italian male, mid-forties, warm low-mid baritone with a dry grainy edge, neutral standard Italian, measured documentary pace around 140 words per minute, warm and direct — this is the only line in the ad delivered as an instruction to the viewer, so lean in slightly. Warm major-leaning music bed continues and builds toward the CTA, ducked 12 dB. Ambience: quiet morning room tone. No added sound effects. VO dominant.

**Caption cards**

`non aspettare` → `che sia troppo tardi` — fill **`troppo tardi`** in yellow `#FFD400`.

**Estimated length**

2.5 seconds

---

### Clip 30 — CTA end card

**Script section / voiceover text**

"Clicca sul link e scopri come funziona questa formula."

> **Product reference:** I will directly attach my product photo reference — use the attached Rejuvir Magnesio Reset jar image as the packaging reference for this end card. Do not redraw, re-letter, or reinterpret the label.

**Text-to-image prompt**

The Rejuvir Magnesio Reset jar: a short wide white cylindrical tub with a smooth white screw-on lid, a deep navy-blue band across the upper body carrying the lowercase wordmark "rejuvir" in white, below it "TECNOLOGIA A TRIPLA AZIONE" in small caps on a grey bar, "Magnesio Reset" in large black type, a navy square "12" badge with three lines of small text beside it, two lines of red subtitle text, and a navy "4oz/120 ml" block at the lower right. The jar stands upright and perfectly centred, lid on, label square to the camera, lit with soft even studio light on a plain warm sand-beige backdrop with a soft contact shadow beneath it, generous empty space above and below the jar for text to be added in the edit. Clean commercial product photography, sharp focus, no props, 9:16 vertical framing.

**Image-to-video prompt**

Animate the white Rejuvir Magnesio Reset jar with its navy band and lowercase "rejuvir" wordmark, standing centred on the warm beige backdrop. The jar holds completely still and only the soft key light drifts very slightly across the label and the contact shadow. Keep the jar's shape, proportions, colours and every element of the label exactly as they are — do not alter, re-letter or redesign the packaging. The camera makes one extremely slow push in, no more than a few percent. No people are visible and no one speaks while the off-screen narrator says: "Clicca sul link e scopri come funziona questa formula." Still, confident, resolved tempo.

**Sound / voiceover direction**

Off-screen narrator voiceover; no people on screen. Same locked narrator voice: native Italian male, mid-forties, warm low-mid baritone with a dry grainy edge, neutral standard Italian, measured documentary pace around 140 words per minute, warm and open, closing the ad without hard-sell pressure. Warm major-leaning music bed resolves to its final chord and is allowed to ring out for the last ~0.8 s after the VO ends — the only moment in the ad where the bed is exposed. Ambience: none. One sound effect: a single soft UI tap under the word "link". VO dominant, then bed alone to the last frame.

**End-card graphics (built in the edit, not generated)**

Headline above the jar, dark navy on the beige, two lines:
`Spegni l'allarme.` / `Poi libera la spalla.`

Three benefit lines below the jar, each with a thin line icon, in dark grey — all drawn from the script, no added claims:
- `Magnesio topico, assorbito attraverso la pelle`
- `Agisce sui segnali nervosi di dolore e rigidità`
- `Senza farmaci`

CTA button at the bottom: rounded navy pill, white bold text `SCOPRI COME FUNZIONA`.

**Caption cards**

`clicca sul link` → `e scopri come funziona questa formula` — fill **`clicca sul link`** in yellow `#FFD400`. Overlay these on the end card as normal captions, above the CTA button.

**Estimated length**

4.0 seconds

---

## 4. Totals

| | |
|---|---|
| Clips | 30 |
| **Total runtime** | **95.0 seconds** |
| Mean clip length | 3.17 s |
| Cuts per minute | ~18.3 |
| Script words | 222 |
| Effective VO pace | ~140 wpm |

### Runtime map

| Act | Clips | Range | Medium |
|---|---|---|---|
| Hook | 01 | 0.0 – 5.5 s | live action |
| Anno 1 | 02–05 | 5.5 – 14.0 s | card + live action |
| Anno 3 | 06–09 | 14.0 – 23.5 s | card + live action |
| Anno 5 | 10–13 | 23.5 – 36.0 s | card + live action |
| Tone reset | 14–15 | 36.0 – 44.0 s | live action |
| Mechanism | 16–23 | 44.0 – 75.5 s | medical CGI |
| Solution | 24–28 | 75.5 – 88.5 s | live action + CGI inserts |
| CTA | 29–30 | 88.5 – 95.0 s | live action + end card |

### Notes on pacing versus the reference

The reference runs at ~29.5 cuts/min against a 2.03 s mean shot. This storyboard sits slower at ~18.3 cuts/min, because the brief is one clip per sentence and this script's sentences are longer than the reference's. To close the gap without regenerating anything, cut **within** the longer clips in the edit: clips 17, 22 and 15 are each 5–6 s and hold a single continuous action, so a mid-clip push-in or a reframed punch-in gives a second beat for free. Doing that on the six longest clips brings the effective cut rate to roughly 26/min, inside the reference's band.

### Production notes

- **Generate in two batches** so the look stays consistent: all live-action clips together (01–15, 24, 25, 28, 29), then all CGI clips together (16–23, 26, 27). Fix the seed within each batch.
- **Marco appears in 15 clips.** Generate his Year 1 look first, keep the best frame, and use it as a character reference image for every later clip if your platform supports one. The written descriptor is still repeated in full in each prompt so the prompts stay self-contained.
- **The three ANNO cards** are cheaper and more convincing shot on a real phone than generated — write them with a real marker and film them. The reference's cards are clearly real.
- **Clips 26 and 27** must be cut with no gap; they carry one sentence.
- **Captions carry this ad.** It plays muted by default. Burn them in before you judge any cut.
