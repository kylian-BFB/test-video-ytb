# BiotyfullBox – Box Beauté Naturelle Été

## Film Direction

**Palette:** 60% canvas (cream `--brand-costume` over brand-color mesh, heavy veil — three atmospheric blobs in brand-primary turquoise, brand-secondary pink, brand-accent amber, always reading as restrained from distance) / 30% hairline rules + repeated canvas surface (no dedicated surface token — canvas bleeds through translucent cards at `--surface-card`) / 10% accent — brand-primary turquoise carries hero words and the CTA; brand-secondary pink carries product highlight labels; two-color-per-scene limit applies; ink stays `--ink` teal-dark throughout.

**Type:** display = hero claims, scene titles, brand names in hero moments; body = supporting copy, product descriptions, detail; mono = eyebrow metadata, chapter chips. Text stays sentence case — no uppercase elements per soft-editorial voice register.

**Motion:** entries `EASE.entry`; hero visuals heavy; idle ambient `EASE.drift`; exits none — scenes hold final frame. Budget: one root-level camera move per scene (slow dolly-in, gentle drift, or parallax) + at most one breathing hero or glow CTA; everything else rests after entry.

**Ambient:** brand-color mesh background (heavy veil, brand-primary + secondary + accent as three subtle atmospheric blobs) — consistent across all 9 scenes including the closing CTA. No mesh gradients, no scanlines, no halftone, no separate architectural grid. Sparse brand-color float particles may coexist with mesh.

**Never (film-wide):** no neon on dark, no purple-blue AI gradient, no drop shadows, no glow bloom halos, no bokeh balls, no z-stacked cards, no pure black/white, no inverted text on pastel cards (ink stays on every surface).

**Transitions:** `blur-crossfade` and `push-slide` only — two types across the full film for cohesion.

**Stillness-before-climax:** allocated to scenes 2 and 8 only — the box reveal payoff and the value proposition landing. No other scene uses this beat.

**Assets:** No `assetCandidates` were provided across all 9 scenes — all visuals are text and graphics compositions. No assets to place or drop.

---

## Scene 1: Accroche Estivale

**Effects:** [`sine-wave-loop`, `discrete-text-sequence`, `svg-path-draw`, `multi-phase-camera`]
**Duration:** 6.83s
**Blueprint:** composed
**Transition:** blur-crossfade

**SFX:**

- `chime.mp3` at 0.4s, volume 0.25 — brand name lands

Luminous summer hook, unhurried and warm — the opening breath of the film. Centered composition: a display-tier headline occupies ~55% of canvas width, centered with generous breathing room above and below. Two-line soft structure: a rhetorical question floats in first (body tier, italic `<em>` on "vacances"), then the brand name "BiotyfullBox" assembles as a separate hero word in brand-primary turquoise (display tier, tight tracking). SVG sun or hibiscus-petal ornament (simple path drawing) enters on a second beat after the brand name lands. Macro motion: multi-phase gentle camera pull-back (wide → settled rest) for the opening 2s, then slow dolly-in drift through the hold. Entry: rhetorical question rises with `EASE.entry` gentle, brand name enters heavy. Hero "BiotyfullBox" breathes as the one live element. Eye drifts right into the incoming box reveal.

---

## Scene 2: Révélation de la Box

**Effects:** [`center-outward-expansion`, `counting-dynamic-scale`, `sine-wave-loop`, `card-morph-anchor`]
**Duration:** 10.01s
**Blueprint:** composed
**Transition:** blur-crossfade
**PrimarySubjectTimeline:** 0-5.0s box hero card primary; 5.0-8.0s count stamp "7 produits" primary, box card demotes to supporting rail; 8.0-10.0s full composition holds, count breathes.
**Handoff:** Before the count stamp enters, the box hero card shifts to left-third supporting rail and reduces in visual weight. The count stamp owns the center safe zone.

Wonder and abundance — this is the film's first stillness-before-climax comma. Layered depth composition: a centered hero card representing the summer box (display-tier "Box Beauté Naturelle Été" on a brand-secondary pink card fill) occupies ~50% canvas height at center. From the hero card, 7 small product chip indicators expand outward (`center-outward-expansion`) over ~2.5s, staggered tight (total stagger ≤400ms). At ~5s, the count "7" rises into a stat-stamp block (counting-dynamic-scale from 0→7, font grows with count) entering the center safe zone — **stillness-before-climax 0.5s pause** before "produits" body copy appears beneath it. Macro motion: slow dolly-in on scene root throughout. The box card breathes gently as one live secondary element.

---

## Scene 3: Nettoyant Visage Hoolia

**Effects:** [`discrete-text-sequence`, `asr-keyword-glow`, `svg-icon-enrichment`, `viewport-change`]
**Duration:** 10.73s
**Blueprint:** composed
**Transition:** push-slide LEFT

Freshness and botanical trust — a confident left-to-right feature reveal. Asymmetric 60/40 composition: left 60% holds a large product feature card (brand-primary turquoise fill, display-tier "Nettoyant Visage" + body "Hoolia" eyebrow chip); right 40% holds supporting copy with the hibiscus ingredient keyword highlighted. An enriched SVG hibiscus icon (petals open progressively via `svg-icon-enrichment`) occupies the upper-right supporting zone. `asr-keyword-glow` syncs a glow emphasis to "hibiscus" and "purifie" as the narrator speaks. Entry: product card slides in from left with `EASE.entry` heavy; icon enters snappy on the right. Macro motion: `viewport-change` gentle rightward pan as if the camera tracks the feature. Product card holds steady; icon petal animation is the one secondary live element. Eye exits left toward the next product.

---

## Scene 4: Soin Solaire Capillaire Tîtl

**Effects:** [`split-tilt-cards`, `asr-keyword-glow`, `sine-wave-loop`, `svg-path-draw`]
**Duration:** 10.88s
**Blueprint:** based-on comparison-split-cards
**Transition:** push-slide RIGHT

Sun protection and protection ritual — a tactile dual-card reveal from opposite directions. Split screen composition: two feature cards enter from left and right with opposing Y-axis rotations (+12° / -12°), creating the signature soft editorial triptych tension. Left card (canvas fill, body tier): "Avant le soleil" protection claim; right card (brand-secondary pink fill, display tier): "Skin Restore Tîtl" + UV benefit chip in brand-primary. A dashed SVG sun-ray path draws in the background zone (ambient ornament, no competing focal weight). `asr-keyword-glow` highlights "soleil" and "UV". Macro motion: slow dolly-in on scene root; both cards breathe in antiphase (`Math.PI` phase offset) as the one live secondary element. Pill badge "Soin solaire" pops at each card's inner edge with `EASE.entry` snappy. Eye rests at center gap, then flows downward.

---

## Scene 5: Le Lait Capillaire Protecteur

**Effects:** [`discrete-text-sequence`, `svg-icon-enrichment`, `sine-wave-loop`, `viewport-change`]
**Duration:** 8.56s
**Blueprint:** composed
**Transition:** blur-crossfade

Security and sensory comfort — the quieter complement after two bold product reveals. Centered composition: a soft editorial card (canvas fill, `--surface-card` translucency) with display-tier headline "Bouclier invisible" and two body lines describing heat and humidity protection. An enriched SVG shield icon (interior fill pulses softly) sits above the headline as an ornamental signal. Text assembles sequentially: headline first (`discrete-text-sequence`), then two body lines stagger in. Macro motion: gentle upward `viewport-change` drift, slow and calm — reinforces the "protective wrap" mood. Shield icon pulse is the one secondary live element; everything else rests in the hold. Eye drifts upward and to the right, opening toward the "surprise" scene.

---

## Scene 6: Vernis et Déodorant – Petits Plaisirs

**Effects:** [`reactive-displacement`, `discrete-text-sequence`, `asr-keyword-glow`, `sine-wave-loop`]
**Duration:** 13.63s
**Blueprint:** composed
**Transition:** push-slide LEFT
**PrimarySubjectTimeline:** 0-5.0s vernis card primary; 5.0-10.0s déodorant card primary, vernis demotes to left rail; 10.0-13.6s both products in triptych with equal visual weight, brand logos as accents.
**Handoff:** Before the déodorant card enters, the vernis card compacts to a left-rail supporting tile. Déodorant card enters from the right and owns the center safe zone. At 10s both settle into a balanced two-column layout, neither primary.

Joyful discovery — the box's double surprise, playful rhythm. The scene runs the longest (13.6s) so it earns a multi-phase choreography. Phase 1 (0–5s): asymmetric right-anchored card for vernis — turquoise vernis tendance chip in brand-primary on brand-secondary pink card fill, headline "Beauty Nails" at display tier with `asr-keyword-glow` on "turquoise". Phase 2 (5–10s): déodorant card (`reactive-displacement` — incoming card pushes vernis left) in canvas fill, "Mymosa" eyebrow, "naturel et efficace" body with keyword glow. Phase 3 (10–13.6s): both cards rest side-by-side, slow dolly-in as macro motion throughout. One card breathes softly as the only secondary live element. Eye exits left.

---

## Scene 7: Sérum et Gloss – Éclat Parfait

**Effects:** [`asr-keyword-glow`, `svg-path-draw`, `sine-wave-loop`, `multi-phase-camera`]
**Duration:** 8.98s
**Blueprint:** composed
**Transition:** blur-crossfade

Luminous aspiration — the emotional apex of product beauty, soft and radiant. Rule-of-thirds composition: the primary block anchors left-upper third — a centered editorial soft card with display-tier "Éclat parfait" and two supporting lines ("sérum boosteur" / "gloss baume rose"). A hand-drawn SVG arc or botanical-petal path draws in the right-third zone as a supporting ornament (it does not compete for attention). `asr-keyword-glow` glows "éclat", "hydratation", and "brillantes" as the narrator speaks them. Macro motion: `multi-phase-camera` — subtle push in during the first half, micro-drift hold during the second. "Éclat parfait" display headline breathes as the sole secondary live element. Eye destination: calm center gaze, softening toward the value summary.

---

## Scene 8: La Valeur de l'Abonnement

**Effects:** [`counting-dynamic-scale`, `center-outward-expansion`, `asr-keyword-glow`, `sine-wave-loop`]
**Duration:** 8.02s
**Blueprint:** based-on hook-counter-burst
**Transition:** zoom-through
**SFX:**

- `impact-bass-2.mp3` at 2.8s, volume 0.28 — value stat lands

**PrimarySubjectTimeline:** 0-2.8s stat stamp "6–10 produits" primary; 2.8-5.5s stillness comma holds, stat primary, chips supporting; 5.5-8.0s body copy "valeur toujours supérieure" primary, stat demotes to upper supporting rail.
**Handoff:** Before the body copy enters, the stat stamp shifts upward and reduces scale to a supporting header. Body copy owns the center safe zone.

Rational satisfaction — the "good deal" beat, measured and warm, not boastful. Centered composition with three-layer depth: background mesh veil slightly lighter than default (brand-color saturation release moment — the film's one climax intensity shift), midground stat stamp, foreground body copy. Primary stat: "6–10 produits" assembled via `counting-dynamic-scale` (count grows, font weight increases). From that stat stamp, four supporting benefit chips expand outward (`center-outward-expansion`): livraison, naturalité, bio, valeur. **Stillness-before-climax 0.55s** — count lands at ~2.8s, chip expansion holds a comma before body copy "valeur toujours supérieure" appears. `asr-keyword-glow` highlights "valeur supérieure". Macro motion: slow dolly-in from slightly wider to settled rest. Stat block breathes as the sole live secondary element. Eye destination flows upward and forward, arriving at the CTA scene.

---

## Scene 9: Appel à l'Action

**Effects:** [`cta-morph-press`, `sine-wave-loop`, `svg-path-draw`, `center-outward-expansion`]
**Duration:** 10.28s
**Blueprint:** based-on cta-morph-press
**Transition:** blur-crossfade

**SFX:**

- `sparkle.mp3` at 3.2s, volume 0.3 — CTA pill appears
- `click-soft.mp3` at 6.0s, volume 0.25 — physics press lands

Belonging and warmth — the quiet resolution after the journey. Centered composition: "BiotyfullBox" wordmark in display tier breathes at center for the first ~2s (hero breathing as opening live element), then morphs into a brand-primary turquoise "Abonnez-vous" CTA pill via `scale-swap-transition` (wordmark shrinks and fades, pill springs out with `EASE.entry` snappy). A soft SVG botanical arc draws in around the pill (supporting ornament). `center-outward-expansion` brings in three small community chips ("beauté naturelle", "chaque mois", "coups de cœur") from behind the pill after it settles. Physics press (`physics-press-reaction`) compresses cursor + CTA pill together at ~6s. "biotyfullbox.fr" URL appears in mono eyebrow tier below the pill at ~7s. Macro motion: gentle slow dolly-in on scene root throughout. CTA pill glow pulse is the sole secondary live element during the hold. No exit eye destination — the film ends here.
