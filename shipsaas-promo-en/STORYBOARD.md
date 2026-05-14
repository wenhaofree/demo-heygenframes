# STORYBOARD

**Format:** 1920x1080  
**Audio:** English TTS voiceover + subtle electronic underscore + soft UI SFX  
**VO direction:** Confident, founder-facing, calm but decisive. Short phrases. Small pause after every sentence.  
**Style basis:** `DESIGN.md`

## Global Direction

- Push contrast between dark matte surfaces and luminous product proof.
- Use the captured `hero-stack.webp` aggressively. It is brand-recognition anchor.
- Keep one hard commercial idea per beat: launch fast, skip setup, trust stack, prove workflow, close on price.
- Every beat needs at least one bright color pull: pink CTA, cyan glow, green comparison, or amber proof.
- Motion language should feel intentional and premium: layered parallax, stat counters, logo drifts, marquee movement, terminal typing, and card reveals.

## Underscore Direction

Minimal electronic bed with low pulse and warm pad. Start under black. Add faint riser for beat changes. Single click or shimmer on CTA moments. No aggressive drums.

## Asset Audit

| Asset | Type | Assign to Beat | Role |
| --- | --- | --- | --- |
| `capture/assets/logo.webp` | Logo | 1, 5 | Open brand mark and close brand signature |
| `capture/assets/hero-stack.webp` | Hero art | 1, 2, 3 | Main full-bleed product proof |
| `capture/assets/og-image.png` | Brand image | 1 | Secondary glow texture / intro layer |
| `capture/assets/avatars/chen-wei.webp` | Avatar | 4, 5 | Founder proof |
| `capture/assets/avatars/sarah-j.webp` | Avatar | 4 | Developer proof |
| `capture/assets/avatars/kevin-zhang.webp` | Avatar | 4 | Indie hacker proof |
| `capture/assets/svgs/lucide-shield-check.svg` | Icon | 2 | Auth feature icon |
| `capture/assets/svgs/lucide-credit-card.svg` | Icon | 2 | Billing feature icon |
| `capture/assets/svgs/lucide-database.svg` | Icon | 2 | Database / type-safe feature icon |
| `capture/assets/svgs/lucide-globe.svg` | Icon | 2 | Global/i18n feature icon |
| `capture/assets/svgs/lucide-code.svg` | Icon | 3 | tRPC / developer velocity icon |
| `capture/assets/svgs/lucide-star.svg` | Icon | 4, 5 | Rating and proof |
| `capture/screenshots/scroll-000.png` | Website capture | 1 | Hero authenticity layer |
| `capture/screenshots/scroll-067.png` | Website capture | 3 | Stack + workflow context |
| `capture/screenshots/scroll-090.png` | Website capture | 5 | Pricing authenticity layer |

## Beat Plan

### BEAT 1 — HOOK (0.03-2.77s)

**VO cue:** “Ship your production SaaS before Monday.”

**Concept:** Open inside ShipSaaS brand world, already glowing. Viewer sees speed, polish, and a real product ecosystem before any feature explanation begins. This beat sells confidence, not detail.

**Visual description:** Dark matte canvas. Logo locks top-left. `hero-stack.webp` rises in with a cinematic crop while the glowing ring slowly drifts. Large headline punches in from the left with pink-to-sky gradient on key words. Floating proof chips show “4.9”, “1,000+ developers”, and “200+ hours saved”. A faint glass frame made from the real hero screenshot sits behind the product art for authenticity.

**Mood direction:** Premium SaaS launch trailer. Clean keynote energy with dev-tool credibility.

**Assets:**

- `capture/assets/logo.webp`
- `capture/assets/hero-stack.webp`
- `capture/assets/og-image.png`
- `capture/screenshots/scroll-000.png`

**Animation choreography:**

- Logo GLIDES in with soft scale rise.
- Headline SLAMS in line by line with gradient wipe.
- Hero art DRIFTS forward with slow zoom on child image.
- Rating chip DROPS in from upper right.
- Proof pills CASCADE in from left with stagger.

**Transition:** Cinematic zoom-through. Incoming Beat 2 enters from scale `0.86 -> 1`, blur `18px -> 0`, `0.55s`, `expo.out`.

**Depth layers:**

- BG: charcoal field + radial pink/sky glows
- MG: ghosted site screenshot frame
- FG: hero orb art, headline, proof chips

**SFX cues:**

- Low impact thump on headline arrival
- Soft sparkle on rating chip

### BEAT 2 — SKIP BOILERPLATE (2.45-11.65s)

**VO cue:** “ShipSaaS gives you auth, Stripe, multi-language support, and deployment ready out of the box, so you skip 200+ hours of setup.”

**Concept:** Translate boring setup work into an instantly visible stack of completed systems. Viewer should feel that tedious foundational work is already done.

**Visual description:** Four large glass feature cards sweep into a 2x2 grid over a blurred crop of the hero art. Each card carries one capability: auth, billing, i18n, deployment. A big side counter animates from `0` to `200+` while a pink “Hours Saved” label glows beneath it. Thin connector lines and icon rings animate between cards so it feels like a complete operating system, not disconnected features.

**Mood direction:** Structured, technical, no-nonsense. Dense enough to feel valuable.

**Assets:**

- `capture/assets/hero-stack.webp`
- `capture/assets/svgs/lucide-shield-check.svg`
- `capture/assets/svgs/lucide-credit-card.svg`
- `capture/assets/svgs/lucide-globe.svg`
- `capture/assets/svgs/lucide-code.svg`

**Animation choreography:**

- Background image FLOATS with slow pan.
- Feature cards CASCADE in from alternating diagonals.
- Icons DRAW on via stroke/fade combo.
- Counter COUNTS UP from `0` to `200+`.
- Connection lines TRACE between cards.

**Transition:** Velocity-matched upward. Outgoing visible. Incoming Beat 3 enters with `y: 120 -> 0`, blur `20px -> 0`, `0.9s`, `power2.out`.

**Depth layers:**

- BG: enlarged hero texture with blur and vignette
- MG: four glass cards and counter block
- FG: connector lines, spark particles, small labels

**SFX cues:**

- UI ticks for counter change
- Small electric pulse when all four cards settle

### BEAT 3 — STACK AND GLOBAL LAUNCH (11.33-20.45s)

**VO cue:** “Built on Next.js 16, React 19, Drizzle, Better Auth, and tRPC, it's ready for real products and global launch.”

**Concept:** Turn tech stack into momentum. This is not a boring logo wall. It should feel like the engine room of a product that can scale worldwide.

**Visual description:** Two sweeping marquee lanes of stack pills slide in opposite directions, inspired by the captured site. Center stage: terminal window types `git clone`, `pnpm install`, and `pnpm dev`. A world-grid glow appears behind it. Green latency pulses jump from left to right to imply edge deployment and global reach. Small labels like “Cloudflare Edge” and “Vercel Ready” orbit the terminal.

**Mood direction:** Technical precision, clean velocity, launch readiness.

**Assets:**

- `capture/screenshots/scroll-067.png`
- `capture/assets/logo.webp`
- `capture/assets/svgs/lucide-code.svg`
- `capture/assets/svgs/lucide-zap.svg`

**Animation choreography:**

- Stack pills SWAY in alternating marquee loops.
- Terminal TYPES commands in Roboto Mono.
- Green pulse lines SHOOT across a dotted grid.
- Small stack badges POP in with scale bounce.
- Background screenshot BREATHES with slow zoom.

**Transition:** Cross-warp morph feel recreated with layered scale and blur overlap. Beat 4 cards rise through from `y: 80`.

**Depth layers:**

- BG: dark grid and soft map glow
- MG: terminal window, marquee pills
- FG: latency lines, badges, cursor blink

**SFX cues:**

- Keyboard ticks during type
- Soft whoosh on global pulse sweep

### BEAT 4 — TRUST AND WORKFLOW (20.13-23.36s)

**VO cue:** “More than 1,000 developers already trust it.”

**Concept:** Move from technical proof to social proof. Show real people, real comments, and a believable fast path from repo to revenue.

**Visual description:** Three testimonial cards stack in perspective over a subtle dark gradient. Founder avatars appear in circular crops with star rows. Each quote card flips into place one after another while a large `1,000+` counter blooms in the background. Then the cards compress slightly to make room for a bright ribbon reading “Launch in hours, not months.”

**Mood direction:** Validation, momentum, founder reassurance.

**Assets:**

- `capture/assets/avatars/chen-wei.webp`
- `capture/assets/avatars/sarah-j.webp`
- `capture/assets/avatars/kevin-zhang.webp`
- `capture/assets/svgs/lucide-star.svg`

**Animation choreography:**

- Cards FAN IN with slight 3D tilt.
- Avatars POP with delayed scale.
- Stars SHIMMER across each card.
- Social-proof counter COUNTS to `1,000+`.
- Banner SWIPES across as closing proof.

**Transition:** Hard commercial snap into pricing. Use brief blur flash + light dip.

**Depth layers:**

- BG: proof counter and low-contrast gradient
- MG: testimonial cards
- FG: stars, avatars, proof banner

**SFX cues:**

- Soft camera clicks on each card arrival
- Quick shimmer on star pass

### BEAT 5 — PRICE AND CTA (23.05-29.40s)

**VO cue:** “Lifetime access is just $99. Buy once. Build forever. Start shipping today.”

**Concept:** Close like a direct-response ad without losing the brand’s premium tone. Price, value, and urgency must all be readable immediately.

**Visual description:** Massive split pricing panel recreates the site’s most convincing sales moment. Left side: large `$99`, crossed `Was $199`, pink CTA button, and green `2 Hours` versus red `200+ Hours` comparison. Right side: capability checklist ticks down into place. Final frame simplifies into bold title, logo, CTA line, and a long pink purchase bar.

**Mood direction:** Confident closer. Premium sales page, not hype circus.

**Assets:**

- `capture/screenshots/scroll-090.png`
- `capture/assets/logo.webp`
- `capture/assets/svgs/lucide-circle-check.svg`
- `capture/assets/svgs/lucide-arrow-right.svg`

**Animation choreography:**

- Pricing panel RISES up with glow behind it.
- Price DIGITS SCALE in one by one.
- Comparison numbers COUNT into red and green states.
- Checklist TICKS on in stagger.
- Final CTA BAR STRETCHES full width as logo settles.

**Transition:** Final scene only. Fade to dark over `0.8s` with logo and CTA holding longest.

**Depth layers:**

- BG: dark canvas + faint captured pricing texture
- MG: split pricing panel
- FG: CTA bar, logo, offer pulse ring

**SFX cues:**

- Soft click on each checklist item
- Low resolving hit on final CTA stretch

## Production Architecture

```text
shipsaas-promo-en/
├── index.html
├── DESIGN.md
├── SCRIPT.md
├── STORYBOARD.md
├── transcript.json
├── narration.wav
├── narration.txt
├── capture/
│   ├── screenshots/
│   ├── assets/
│   └── extracted/
└── compositions/
    ├── beat-1-hook.html
    ├── beat-2-boilerplate.html
    ├── beat-3-stack.html
    ├── beat-4-proof.html
    └── beat-5-cta.html
```
