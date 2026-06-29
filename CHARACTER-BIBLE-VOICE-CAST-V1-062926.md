# Character Bible & Master Portrait Guide — Voice Cast

Single source of truth for the 6 recurring voice-over characters: who they are, how to generate their master reference images, and how to keep them visually consistent across every question.

**Pairs with:** `Planning Text to Speech Experiment.docx` (voice casting) and the per-question scene prompts (e.g. `Q1-Image-Prompts-VoiceCast-V1-062926.md`).

---

## How the three pieces fit (read this first)

Each character has three text assets, used at different moments — they describe the same face on purpose, so each is self-contained and copy-pasteable:

| Asset | When you use it | Reference image attached? |
|---|---|---|
| **Master Portrait Prompt** | To **generate the master face**, once. | No — text only. |
| **Angle turnaround template** | To build the **reference bundle** (extra angles) from the master. | Yes — attach the master. |
| **Anchor block** | Inside **scene prompts**, as a text identity reminder. | Yes — attach the reference bundle. |

## Workflow

1. **Generate the master (Shot A):** paste a character's **Master Portrait Prompt** into Gemini 2.5 Flash Image (Nano Banana), text only. Generate a few, pick the best face. That's the canonical face — lock it.
2. **Build the angle bundle:** using the **Angle Turnaround Template**, generate the extra angles by *attaching Shot A* each time.
3. **Generate scenes:** attach the reference bundle (Shot A + two 3/4 angles + matching expression) + the scene prompt. The scene's **anchor block** is the text backup; the attached images are what actually lock identity.

**Style suffix (append to every prompt):**
> *Shot on [character's film stock]. Photorealistic, not illustration or cartoon. Real human subject. Warm film grain, natural skin tones. Documentary photography.*

**Film stock:** Tia / Joefe / Eva → **Kodak Portra 400** · Fortunate / Annakay / Leoni → **Fujifilm Pro 400H**.

**Intentional departures from standard art direction:** the platform-wide "rotate diversity per image" rule is suspended for the voice-cast questions — diversity lives across the 6-character cast, not within each image. All 6 are female diaspora healthcare workers, so the first-person speaker *is* the character; drop any scene detail that contradicts a locked identity.

---

## The Cast at a glance

| Character | Heritage | Age | Role | Visual quick-key | Film |
|---|---|---|---|---|---|
| **Tia Mirza** | Indian (North Indian) | 45 | Senior charge nurse | Sleek greying low bun, gold nose pin, navy scrubs, commanding | Portra 400 |
| **Fortunate** | Nigerian | 36 | ICU nurse | Tall, deep dark skin, box braids in high bun, royal-blue scrubs, bright | Pro 400H |
| **Joefe** | Filipino | 43 | Wellness nurse / educator | Heart-shaped face, low black ponytail, coral scrubs, warm host energy | Portra 400 |
| **Annakay** | Jamaican | 28 | Younger nurse / care worker | Honey-toned locs in high bun, gold nose stud, lavender scrubs, expressive | Pro 400H |
| **Eva Kintsugi** | Malay (Malaysian) | 54 | Hospice / palliative caregiver | Soft pastel hijab, round kind face, prayer-bead bracelet, serene | Portra 400 |
| **Leoni Vergara** | Spanish (Spain) | 48 | Nurse | Chestnut waves with silver temples, gold cross pendant, eloquent calm | Pro 400H |

Distinct age bands, skin tones, hair, and signature items are deliberate — they stop the model blending two characters.

---

## 1. TIA MIRZA — Indian · 45 · *crisp and commanding*

*📝 REFERENCE ONLY — describes her for you; never pasted into the generator.*
**Locked description.** A 45-year-old North Indian woman, senior charge nurse, medium-tall (5'7") with erect, commanding posture. Warm wheatish-brown skin. Angular face, defined jaw, strong dark brows, sharp composed dark-brown eyes, firm mouth. Sleek black hair with a few natural greys, center-parted in a neat low bun. Signature: small gold nose pin, fine gold chain (mangalsutra), thin gold bangles on her right wrist, small gold studs, occasionally a small maroon bindi. No-nonsense but not cold.
**Wardrobe:** crisp navy or charcoal scrubs on-shift; structured jewel-tone kurta off-shift.
**Expression range:** baseline composed/commanding; carries grief, resolve, weariness without losing stillness.

**Master Portrait Prompt (Shot A):** — *✅ PASTE THIS to generate the master. Text only, attach NO image. (Moment 1)*
> Front-facing studio portrait of a 45-year-old North Indian woman, senior nurse, warm wheatish-brown skin, angular face with a defined jaw, strong dark brows, sharp composed dark-brown eyes, sleek black hair with a few greys in a neat low center-parted bun. Small gold nose pin, fine gold chain, small gold studs, thin gold bangles on her right wrist, crisp navy scrubs. Neutral calm expression, looking straight at camera. Head-and-shoulders, soft even frontal light, plain soft-grey background. Shot on Kodak Portra 400 film. Photorealistic, natural skin tones.

**Anchor block (for scene prompts):** — *🔖 DON'T paste alone. It's already baked into the start of each Q1 scene prompt. (used in Moment 3)*
> *Tia Mirza — a 45-year-old North Indian woman, senior nurse, wheatish-brown skin, angular face with a defined jaw and sharp dark eyes, sleek greying black hair in a neat low center-parted bun, small gold nose pin, fine gold chain, thin gold bangles on her right wrist; composed and commanding; crisp navy scrubs —*

---

## 2. FORTUNATE — Nigerian · 36 · *bright and clear*

*📝 REFERENCE ONLY — describes her for you; never pasted into the generator.*
**Locked description.** A 36-year-old Nigerian woman, ICU nurse, tall (5'9"), upright confident posture. Deep rich dark-brown luminous skin. Oval-to-round face, high cheekbones, bright clear dark eyes, radiant wide smile. Natural hair in neat box braids gathered into a high bun. Signature: medium gold hoop earrings, a single strand of small colorful beads, a wooden bangle. Bright, clear, warm, direct gaze.
**Wardrobe:** royal-blue or emerald scrubs on-shift; subtle Ankara wax-print top off-shift.
**Expression range:** baseline bright/warm; carries determination, tenderness, sorrow while staying luminous and open.

**Master Portrait Prompt (Shot A):** — *✅ PASTE THIS to generate the master. Text only, attach NO image. (Moment 1)*
> Front-facing studio portrait of a 36-year-old Nigerian woman, ICU nurse, deep rich dark-brown luminous skin, oval face with high cheekbones, bright clear dark eyes, natural box braids gathered in a high bun. Medium gold hoop earrings, a wooden bangle, royal-blue scrubs. Neutral-bright expression, looking straight at camera. Head-and-shoulders, soft even frontal light, plain soft-grey background. Shot on Fujifilm Pro 400H film. Photorealistic, natural skin tones.

**Anchor block (for scene prompts):** — *🔖 DON'T paste alone. It's already baked into the start of each Q1 scene prompt. (used in Moment 3)*
> *Fortunate — a 36-year-old Nigerian woman, ICU nurse, tall with confident posture, deep rich dark-brown luminous skin, oval face with high cheekbones and bright clear dark eyes, natural box braids gathered in a high bun, medium gold hoop earrings, a wooden bangle; bright and warm; royal-blue scrubs —*

---

## 3. JOEFE — Filipino · 43 · *warm wellness host*

*📝 REFERENCE ONLY — describes her for you; never pasted into the generator.*
**Locked description.** A 43-year-old Filipino woman, wellness nurse and health educator, petite-to-medium (5'3"), soft grounded build. Warm tan-brown skin. Heart-shaped face, softly rounded features, expressive dark eyes, ready warm smile, small mole near the jaw. Straight mid-length black hair with subtle warm-brown highlights, low ponytail or loose. Signature: small gold studs, thin beaded bracelet, simple ring, often a lanyard ID badge. Warm, engaging, present.
**Wardrobe:** warm coral or soft-yellow scrubs on-shift; pastel cardigan off-shift.
**Expression range:** baseline warm/engaged; holds concern, fatigue, quiet emotion while staying approachable.

**Master Portrait Prompt (Shot A):** — *✅ PASTE THIS to generate the master. Text only, attach NO image. (Moment 1)*
> Front-facing studio portrait of a 43-year-old Filipino woman, wellness nurse, warm tan-brown skin, heart-shaped face with softly rounded features, expressive dark eyes, a small mole near the jaw, straight mid-length black hair with subtle warm-brown highlights in a low ponytail. Small gold studs, thin beaded bracelet, lanyard ID badge, warm coral scrubs. Calm warm expression, looking at camera. Head-and-shoulders, soft even frontal light, plain soft-grey background. Shot on Kodak Portra 400 film. Photorealistic, natural skin tones.

**Anchor block (for scene prompts):** — *🔖 DON'T paste alone. It's already baked into the start of each Q1 scene prompt. (used in Moment 3)*
> *Joefe — a 43-year-old Filipino woman, wellness nurse, warm tan-brown skin, heart-shaped face with softly rounded features, expressive dark eyes and a small mole near the jaw, straight mid-length black hair with warm-brown highlights in a low ponytail, small gold studs, thin beaded bracelet, lanyard ID badge; warm and engaging; coral scrubs —*

---

## 4. ANNAKAY — Jamaican · 28 · *expressive, young*

*📝 REFERENCE ONLY — describes her for you; never pasted into the generator.*
**Locked description.** A 28-year-old Jamaican woman, younger nurse / care worker, medium (5'5"), relaxed youthful energy. Warm medium brown-sugar dewy skin. Youthful round face, full lips, large expressive eyes, dimples. Medium-brown locs with honey-toned highlights, high bun with a few loose strands. Signature: small gold nose stud, layered thin gold necklaces, small gold hoops, a couple of beaded bracelets. Warm, emotionally open, expressive.
**Wardrobe:** soft lavender or mint scrubs on-shift; cozy-current off-shift (oversized hoodie / fitted knit).
**Expression range:** baseline open/expressive; moves easily into tears, joy, vulnerability — most emotionally readable of the cast.

**Master Portrait Prompt (Shot A):** — *✅ PASTE THIS to generate the master. Text only, attach NO image. (Moment 1)*
> Front-facing studio portrait of a 28-year-old Jamaican woman, young nurse, warm medium brown-sugar dewy skin, youthful round face with full lips, large expressive eyes, dimples, medium-brown locs with honey-toned highlights in a high bun with a few loose strands. Small gold nose stud, layered thin gold necklaces, small gold hoops, soft lavender scrubs. Calm open expression, looking at camera. Head-and-shoulders, soft even frontal light, plain soft-grey background. Shot on Fujifilm Pro 400H film. Photorealistic, natural skin tones.

**Anchor block (for scene prompts):** — *🔖 DON'T paste alone. It's already baked into the start of each Q1 scene prompt. (used in Moment 3)*
> *Annakay — a 28-year-old Jamaican woman, young nurse, warm medium brown-sugar dewy skin, youthful round face with full lips, large expressive eyes and dimples, medium-brown honey-toned locs in a high bun, small gold nose stud, layered thin gold necklaces, small gold hoops; warm and emotionally open; lavender scrubs —*

---

## 5. EVA KINTSUGI — Malay · 54 · *warm, soft, round*

*📝 REFERENCE ONLY — describes her for you; never pasted into the generator.*
**Locked description.** A 54-year-old Malay (Malaysian) woman, hospice / palliative caregiver, shorter (5'2"), soft round build. Warm golden-brown skin. Round face, full cheeks, kind dark eyes with gentle crinkle lines, soft warm smile. Softly draped pastel hijab (dusty rose or sage), loose and gentle, small pin. Signature: simple pearl studs, a worn wooden prayer-bead bracelet (tasbih). Serene, maternal, quietly brave.
**Wardrobe:** soft modest long-sleeved tunics in muted earth/pastel tones; or lavender long-sleeved scrubs on-shift.
**Expression range:** baseline serene/maternal; carries deep grief, comfort, steadiness without losing softness.

**Master Portrait Prompt (Shot A):** — *✅ PASTE THIS to generate the master. Text only, attach NO image. (Moment 1)*
> Front-facing studio portrait of a 54-year-old Malay woman, hospice caregiver, warm golden-brown skin, round face with full cheeks, kind dark eyes with gentle crinkle lines, a softly draped dusty-rose pastel hijab secured with a small pin. Pearl stud earrings, a worn wooden prayer-bead bracelet, a soft modest earth-toned tunic. Serene expression, looking at camera. Head-and-shoulders, soft even frontal light, plain soft-grey background. Shot on Kodak Portra 400 film. Photorealistic, natural skin tones.

**Anchor block (for scene prompts):** — *🔖 DON'T paste alone. It's already baked into the start of each Q1 scene prompt. (used in Moment 3)*
> *Eva Kintsugi — a 54-year-old Malay woman, hospice caregiver, warm golden-brown skin, round face with full cheeks and kind dark eyes with gentle crinkle lines, a softly draped dusty-rose pastel hijab, pearl stud earrings, a worn wooden prayer-bead bracelet; serene and maternal; soft modest earth-toned tunic —*

---

## 6. LEONI VERGARA — Spanish · 48 · *soothing and eloquent*

*📝 REFERENCE ONLY — describes her for you; never pasted into the generator.*
**Locked description.** A 48-year-old Spanish woman (from Spain), nurse, medium (5'6"), slender, elegant composed posture. Warm olive skin. Oval face, defined cheekbones, warm brown eyes, gentle smile lines, well-groomed brows. Dark chestnut-brown shoulder-length hair in soft waves, often half-pinned, a few silver strands at the temples. Signature: thin gold hoop earrings, a small gold cross pendant on a fine chain, reading glasses sometimes pushed into her hair. Composed, warm, eloquent, soft attentive gaze.
**Wardrobe:** muted teal scrubs on-shift; camel/cream knit with an earth-tone silk scarf off-shift.
**Expression range:** baseline composed/warm; carries reflection, sorrow, reassurance with unhurried elegance.

**Master Portrait Prompt (Shot A):** — *✅ PASTE THIS to generate the master. Text only, attach NO image. (Moment 1)*
> Front-facing studio portrait of a 48-year-old Spanish woman, nurse, warm olive skin, oval face with defined cheekbones, warm brown eyes, gentle smile lines, dark chestnut shoulder-length wavy hair half-pinned with a few silver strands at the temples. Thin gold hoop earrings, a small gold cross pendant, muted teal scrubs. Composed warm expression, looking at camera. Head-and-shoulders, soft even frontal light, plain soft-grey background. Shot on Fujifilm Pro 400H film. Photorealistic, natural skin tones.

**Anchor block (for scene prompts):** — *🔖 DON'T paste alone. It's already baked into the start of each Q1 scene prompt. (used in Moment 3)*
> *Leoni Vergara — a 48-year-old Spanish woman, nurse, warm olive skin, oval face with defined cheekbones, warm brown eyes and gentle smile lines, dark chestnut shoulder-length wavy hair half-pinned with silver at the temples, thin gold hoop earrings, a small gold cross pendant; composed and eloquent; muted teal scrubs —*

---

# ANGLE TURNAROUND (the reference bundle)

A wider turnaround locks identity far better than front-only — more facial geometry means she holds up no matter how a scene poses her. You only wrote **Shot A** per character above; every other angle is generated by **attaching Shot A** and changing one phrase. One template, applied to all six.

## Rules that make angles work (keep constant across all angles)
- **Same framing** (head-and-shoulders, same crop), **same lighting** ("soft even frontal light"), **same plain soft-grey background**, **same hair / wardrobe / signature items**.
- **Neutral expression** for the geometry angles (1–5). Do expressions *separately* (Set E) — never combine a new angle + new mood + new light in one shot.
- **Only the head/body rotation changes.**

## The 5-angle template
*✅ PASTE THIS (one per angle) WITH Shot A attached. (Moment 2)*
Attach **Shot A**, then: *"The same woman from the reference image, [angle]. Same hair, same [signature items], same [scrubs/tunic]. Head-and-shoulders, soft even frontal light, plain soft-grey background, neutral expression. Shot on [her film stock]. Photorealistic, natural skin tones."*

| # | Angle phrase |
|---|---|
| 1 | front view, facing camera directly *(this is Shot A — the anchor)* |
| 2 | turned three-quarters to her left (~45°), gaze slightly off-camera |
| 3 | turned three-quarters to her right (~45°), gaze slightly off-camera |
| 4 | left profile view (~90°), looking to the side |
| 5 | head tilted slightly downward, eyes lowered, as if looking at something in her hands |

Angle 5 matters because many scenes pose the character looking down (writing, holding a chart, a phone) — a down-tilt reference prevents face distortion in those poses.

## Set E — expressions (separate, all front-facing)
Attach Shot A, keep front view, change only the expression: **E1** warm smile · **E2** quiet sorrow / glassy eyes · **E3** tired / weary · **E4** resolved / steady.

## What to attach per scene
Attach **Shot A + the two 3/4 angles (2, 3) + the matching expression** (~4 references) — enough geometry and the right mood without overloading. Add the down-tilt (5) when the scene has her looking down.

## Faster alternative: one-shot character sheet
*"Character model sheet of the same woman: head-and-shoulders from front, 3/4 left, and left profile in one image; identical lighting, hairstyle, and clothing across all three; plain grey background."* Quicker but **less reliable** (views can drift into different people). Use only as a quick first pass; sequential anchoring off Shot A is the dependable method.

---

# Worked example (Tia, Q1 Checkpoint 2 Option 9)

**"How This Sounds":** *"Starting this means facing my own death... The finality lands differently when the name on the chart is mine."*

**Composed scene prompt (attach Tia's reference bundle + E2 sorrow):**
> *Tia Mirza — a 45-year-old North Indian woman, senior nurse, wheatish-brown skin, angular face with a defined jaw and sharp dark eyes, sleek greying black hair in a neat low center-parted bun, small gold nose pin, fine gold chain, thin gold bangles on her right wrist; composed and commanding; crisp navy scrubs —* sits alone in a dim hospital locker room after her shift, a patient chart resting in her lap with her own name where a patient's would be. Her commanding composure has gone still; she looks at the chart the way she has watched a thousand patients look at theirs. Low locker-room light, the quiet after the ward empties. *Shot on Kodak Portra 400 film. Photorealistic, documentary photography, warm film grain, natural skin tones.*

(Identity from the anchor block + attached references; scene + emotion from "How This Sounds"; style suffix unchanged.)
