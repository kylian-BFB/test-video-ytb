# BiotyfullBox — Box Beauté Naturelle Été

## Film Direction

**Palette:** 60% cream canvas over brand-color mesh (heavy veil, three atmospheric blobs, reads as restrained base at distance) / 30% translucent card surfaces + hairline rules (`--surface-card` translucency; no separate surface token) / 10% accent — brand-primary turquoise carries heroes and the CTA; brand-secondary pink binds to product labels and feminine accents only. Two-color-per-scene limit; ink stays `--ink` on every surface — no inverted text.
**Type:** display (`--font-display` serif, italic `<em>` for one warm phrase per headline) for hero claims and brand names; body (`--font-body`) for supporting copy; mono for eyebrows, metadata, URL. Sentence case throughout.
**Motion:** entries `EASE.entry`; heroes heavy; idle `EASE.drift`; exits none — scenes hold final frame. Budget: one root-level camera move per scene + at most one breathing hero or one decorative cluster; everything else rests.
**Ambient:** brand-color mesh background (heavy veil, brand-primary + brand-secondary + brand-accent as three subtle atmospheric blobs) full-bleed every scene including closing CTA. No additional grid, scanline, or bokeh layer.
**Never (film-wide):** no dark ground, no neon-on-black, no purple-blue AI gradient, no bokeh spheres, no drop shadows or glow bloom halos, no z-stacked cards, no uppercase text, no three brand colors in one scene.
**Transitions:** `blur-crossfade` and `push-slide` only — two types across the full film.
**Stillness-before-climax:** scenes 1, 7, and 9 only.
**Assets:** No `assetCandidates` across all 9 scenes — all compositions are text and graphics only.

## Scene 1: Accroche Estivale

**Effects:** [`discrete-text-sequence`, `multi-phase-camera`, `svg-path-draw`, `sine-wave-loop`]
**Duration:** 6.83s
**Blueprint:** composed

Luminous opening hook — unhurried, warm, the film's first breath. Centered composition: display-tier headline fills ~55% canvas width with generous breathing room. `multi-phase-camera` gentle pull-back (wide → settled) for the first 2s, then slow dolly-in hold. `discrete-text-sequence` assembles the rhetorical question in two beats — question phrase first, then "BiotyfullBox" brand name in brand-primary turquoise (display tier, tight tracking); italic `<em>` on "airs de vacances". `svg-path-draw` traces a delicate botanical arc framing the headline after the brand name lands. **Stillness-before-climax 0.5s** — botanical arc complete, camera still — before "BiotyfullBox" stamp resolves. `sine-wave-loop` breathes the brand name as the sole live secondary element. Eye drifts forward into the box reveal.

## Scene 2: Révélation de la Box

**Effects:** [`center-outward-expansion`, `counting-dynamic-scale`, `card-morph-anchor`, `sine-wave-loop`]
**Duration:** 10.01s
**Blueprint:** composed
**Transition:** blur-crossfade

Wonder and abundance — expansive, slow-reveal. Layered-depth composition: a centered hero card (display-tier "Box Beauté Naturelle Été", brand-secondary pink card fill, ~50% canvas height) sits at center. From it, seven small product chips expand outward via `center-outward-expansion` (stagger ≤400ms total). At ~5s `card-morph-anchor` morphs the hero card and `counting-dynamic-scale` raises the count "7" in a stat block (font grows with count). Body copy "produits naturels et bio" supports beneath. Macro motion: slow dolly-in throughout. Hero card breathes as the sole secondary live element.

## Scene 3: Nettoyant Visage Hoolia

**Effects:** [`discrete-text-sequence`, `svg-icon-enrichment`, `asr-keyword-glow`, `viewport-change`]
**Duration:** 10.73s
**Blueprint:** composed
**Transition:** push-slide LEFT

Freshness and botanical trust — confident left-to-right feature reveal. Asymmetric 60/40 composition: left 60% primary column holds a feature card (brand-primary turquoise fill, display-tier "Nettoyant Visage", eyebrow chip "Hoolia"); right 40% supporting zone holds a hibiscus SVG icon panel. `svg-icon-enrichment` progressively opens hibiscus petals with a pulsing center dot. `discrete-text-sequence` introduces brand name then formula copy in two beats (~0.7s gap). `asr-keyword-glow` glows "hibiscus" and "purifie" as narrated. Macro motion: `viewport-change` gentle rightward pan. Hibiscus icon petal animation is the sole secondary live element. Eye exits left toward the next product.

## Scene 4: Soin Solaire Capillaire Tîtl

**Effects:** [`split-tilt-cards`, `svg-path-draw`, `asr-keyword-glow`, `sine-wave-loop`]
**Duration:** 10.88s
**Blueprint:** based-on comparison-split-cards
**Transition:** push-slide RIGHT

Sun protection — tactile dual-card reveal from opposite directions. Split-screen: left card (canvas fill) carries the UV protection claim (+12° rotateY); right card (brand-secondary pink fill) carries "Skin Restore Tîtl" benefit at display tier (−12° rotateY). Pill badge "UV protect" pops at the inner card edge with `EASE.entry` snappy. `svg-path-draw` traces a dashed sun-ray arc in the background zone (ambient ornament only). `asr-keyword-glow` highlights "soleil" and "UV". Macro motion: slow dolly-in; both cards breathe in antiphase (`Math.PI` phase offset) as the sole secondary live element. Eye rests at center gap then flows downward.

## Scene 5: Le Lait Capillaire Protecteur

**Effects:** [`discrete-text-sequence`, `svg-icon-enrichment`, `sine-wave-loop`, `viewport-change`]
**Duration:** 8.56s
**Blueprint:** composed
**Transition:** blur-crossfade

Security and sensory comfort — quiet complement after two bold reveals. Centered composition: a soft card (`--surface-card` translucency) holds display-tier "Bouclier invisible" and two body lines. An enriched SVG shield icon (interior fill pulses softly) sits above the headline as ornament. `discrete-text-sequence` assembles headline first, then two body lines stagger in. `svg-icon-enrichment` drives the shield pulse. Macro motion: `viewport-change` gentle upward drift — calm, protective. Shield pulse is the sole secondary live element; everything else rests in hold. Eye drifts upward and right toward the surprise scene.

## Scene 6: Vernis et Déodorant – Petits Plaisirs

**Effects:** [`reactive-displacement`, `discrete-text-sequence`, `asr-keyword-glow`, `sine-wave-loop`]
**Duration:** 13.63s
**Blueprint:** composed
**Transition:** push-slide LEFT

**Hierarchy:** multi-act

**PrimarySubjectTimeline:** 0–5.0s vernis card primary, right zone only; 5.0–10.0s déodorant card primary (center safe zone), vernis demotes to left supporting rail; 10.0–13.6s both cards in triptych, brand names headline primary.
**Handoff:** At 5.0s the vernis card compacts to a smaller left-rail supporting tile before the déodorant card enters from the right. At 10.0s both cards shift to equal supporting columns; the headline band owns the primary zone.

Joyful double discovery — playful multi-phase, brisk rhythm. Phase 1 (0–5s): asymmetric right-anchored card, "Beauty Nails" display, brand-secondary pink fill; `asr-keyword-glow` on "turquoise". Phase 2 (5–10s): `reactive-displacement` spring from incoming déodorant card pushes vernis to rail; "Mymosa" eyebrow on canvas fill card, `asr-keyword-glow` on "naturel". Phase 3 (10–13.6s): both cards side-by-side, `discrete-text-sequence` reveals full brand names in lower display band. Macro motion: slow dolly-in throughout. The active primary card breathes as sole secondary live element. Eye exits left.

## Scene 7: Sérum et Gloss – Éclat Parfait

**Effects:** [`asr-keyword-glow`, `svg-path-draw`, `multi-phase-camera`, `sine-wave-loop`]
**Duration:** 8.98s
**Blueprint:** composed
**Transition:** blur-crossfade

Luminous aspiration — emotional apex of product beauty, soft and radiant. Rule-of-thirds: primary editorial soft card anchors upper-left third (display-tier "Éclat parfait", italic `<em>` on "éclat", two supporting body lines); a decorative SVG botanical arc draws in the right-third zone as ornament. `asr-keyword-glow` glows "hydratation" (~3s) and "brillantes" (~6s) as narrated. **Stillness-before-climax 0.6s** after the second keyword glow peaks — camera micro-hold — before the final body phrase appears. Macro motion: `multi-phase-camera` slow push-in first half, micro-drift hold second half. Headline breathes as sole secondary live element. Eye softens toward center, transitioning to value summary.

## Scene 8: La Valeur de l'Abonnement

**Effects:** [`counting-dynamic-scale`, `center-outward-expansion`, `asr-keyword-glow`, `sine-wave-loop`]
**Duration:** 8.02s
**Blueprint:** based-on hook-counter-burst
**Transition:** zoom-through

**Hierarchy:** data-proof

**PrimarySubjectTimeline:** 0–3.5s stat stamp "6–10 produits" primary; 3.5–8.0s value body copy primary, stat demotes to upper supporting eyebrow.
**Handoff:** At 3.5s the stat stamp shifts upward and reduces scale to a supporting eyebrow label; body copy "valeur toujours supérieure" enters the center safe zone as the new primary.

**SFX:**

- `impact-bass-2.mp3` at 1.5s, volume 0.28 — stat stamp lands

Rational satisfaction — measured warmth, not boastful. Centered three-layer composition: `counting-dynamic-scale` counts 6 → 10 with font growing in the stat block. Four supporting benefit chips (`center-outward-expansion`) radiate from the stat block (livraison, bio, naturel, valeur). `asr-keyword-glow` highlights "valeur supérieure". Macro motion: slow dolly-in throughout. Stat block breathes as sole secondary live element during hold. Eye flows forward to the CTA scene.

## Scene 9: Appel à l'Action

**Effects:** [`scale-swap-transition`, `cursor-click-ripple`, `sine-wave-loop`, `svg-path-draw`]
**Duration:** 10.28s
**Blueprint:** based-on cta-morph-press
**Transition:** blur-crossfade

**Hierarchy:** action

**PrimarySubjectTimeline:** 0–3.5s brand wordmark "BiotyfullBox" primary; 3.5–10.3s CTA pill "Abonnez-vous" primary, wordmark demoted to top supporting badge.
**Handoff:** At 3.5s the wordmark shrinks and slides to a small top badge (supporting rail) before the CTA pill springs out to the center safe zone.

**SFX:**

- `sparkle.mp3` at 3.6s, volume 0.28 — CTA pill springs in
- `click-soft.mp3` at 6.5s, volume 0.25 — physics press

Belonging and warm resolution — the quiet close after the journey. **Stillness-before-climax 0.5s** after the pill fully settles, before the cursor enters. Centered composition: wordmark in display serif breathes at center for the opening ~2s, then `scale-swap-transition` morphs it into a brand-primary "Abonnez-vous" CTA pill. `svg-path-draw` traces a delicate botanical arc around the pill as supporting ornament. `cursor-click-ripple` tracks cursor to the pill with press and outward ripple at ~6.5s. "biotyfullbox.fr" in mono eyebrow tier appears below the pill at ~7.5s. Macro motion: slow dolly-in throughout. CTA pill breathes as sole live secondary element after click. No exit — film ends here.
