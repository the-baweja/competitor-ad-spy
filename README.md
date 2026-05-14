# Competitor Ad Spy — Meta Ads Intelligence Skill

**Analyze competitor Facebook/Meta ads. Find patterns. Identify gaps. Generate winning ad angles.**

Give Claude your competitor names and it pulls every active ad from the Meta Ad Library, categorizes each one across 6 dimensions, runs cross-brand pattern analysis, finds the gaps nobody else sees, and generates original ad angle recommendations for your brand.

## Install

**Claude Desktop (Cowork):** download [`competitor-ad-spy.skill`](https://github.com/the-baweja/competitor-ad-spy/releases/latest) → Settings → Skills → drop it in.

**Claude Code:**
```
git clone https://github.com/the-baweja/competitor-ad-spy.git ~/.claude/skills/competitor-ad-spy
```

**Manual:** clone this repo into any skills directory your Claude setup reads from.

## What it does

You give it 4-6 competitor brand names. It:

1. **Pulls every active ad** from the Meta Ad Library (browser-based or paste-based)
2. **Categorizes each ad** across 6 dimensions:
   - Persuasion angle (social proof, pain point, education, UGC, authority, aspirational, founder story, contrarian, offer)
   - Funnel stage (cold / warm / hot)
   - Creative format (static, video 15s/30s/60s, carousel, collection)
   - Run duration (days active — 30+ days = likely performer)
   - Hook type (bold claim, question, demonstration, before/after, curiosity gap, social proof lead)
   - CTA style (Shop Now, Learn More, Sign Up, etc.)
3. **Runs 7 cross-brand analyses:**
   - Dominant angles (what everyone does — table stakes)
   - Angle gaps (what nobody does — opportunities)
   - Funnel imbalance (over-served vs under-served stages)
   - Format distribution
   - Longevity signals (what long-running ads have in common)
   - Video hook patterns
   - CTA patterns
4. **Generates 10+ original ad angles** that exploit the specific gaps found

## Output

Two deliverables:

- **Branded DOCX report** — executive summary, brand-by-brand breakdown, cross-brand pattern analysis, gap analysis, recommended ad angles
- **Excel workbook** (5 sheets) — executive summary, full brand analysis, pattern analysis matrices, recommended angles, raw data with filters

## Customize Your Branding

Edit `references/branding.md` with your own brand colors, typography, and document structure. The skill reads this file to generate reports that match your brand identity.

## Example

Prompt:
```
Run a competitive ad analysis for premium skincare.
Competitors: CeraVe, COSRX, La Roche-Posay, Paula's Choice, Medicube.
My brand is The Ordinary — we differentiate on radical ingredient transparency and clinical-grade formulas at drugstore prices.
```

Output: 54 ads analyzed, 5 competitive gaps identified, 12 ad angle recommendations — each traced to a specific gap.

## Who this is for

Media buyers, creative strategists, brand owners, and performance marketers who want data-driven ad strategy instead of guesswork.

This is skill 1 of 10 in the **AI Skills for Media Buyers** series by [Baweja Media](https://bawejamedia.com).

---

## Want Baweja Media to audit your ad account and explore opportunities to work together?

[→ Book a free strategy call](https://webinar.sannidhyabaweja.com/vsl-lp-ind)

---

Built by [Baweja Media](https://bawejamedia.com) · MIT License
