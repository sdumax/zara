# Nelo: What's Actually Buildable (and When)
### A Realistic Scope for V1

**Prepared by:** Chizaram (Executive Assistant to Maxwell)
**Company:** Qodesquare
**Prepared for:** Chinedu Samuel
**Date:** 2026-03-13
**Status:** Draft, for alignment

---

## Why This Document Exists

After reviewing the Nelo PRD in full, this brief was put together to give an honest picture of what can be built right now, what needs more time, and what needs real users on the platform before it can exist at all.

The vision in the PRD is solid. The market opportunity is real. What this document addresses is **sequencing**: building the right things at the right time, so Nelo launches credibly and doesn't over-promise.

---

## 1. What the PRD Gets Right

- The gap in the market is real. Existing UGC and influencer platforms focus on follower counts and reach. Nelo's angle of matching based on cultural fit and community trust is a genuine differentiator.
- The core marketplace (brands, creators, campaigns, payments, content) is well thought out.
- The community activation layer (creator-led, offline events) is genuinely new and not something competitors are doing.
- The long-term AI vision is the right destination. The question is just: what comes first?

---

## 2. The One Thing That Changes Everything

A large part of the PRD describes features that **learn from data**. They get smarter the more the platform is used. Things like:

- Predicting which creator will perform best for a brand
- Forecasting trust scores over time
- Recommending the right price for a campaign
- Detecting when a creator is getting overused

These are powerful features. But they have one hard requirement: **they need real data from real users first.**

Think of it like training a new hire. On day one, you can give them a rulebook and they'll follow it. But they can't give you insights, spot patterns, or make smart predictions until they've seen enough real situations to learn from.

Before Nelo has real brands and creators transacting on the platform, there is no data. And without data, these features either:
- Don't work at all, or
- Produce results that look intelligent but are actually meaningless

Both are worse than being honest about what V1 can and can't do.

---

## 3. Three Types of Features in the PRD

### Type A: The Marketplace (buildable now, no AI needed)

This is the core product. It's regular software: user accounts, campaign workflows, payments, content management, notifications. No intelligence required, just solid engineering.

- Brand and creator profiles, onboarding, verification
- Campaign creation and management
- Marketplace browsing and filtering (search by category, location, budget)
- Contracts and usage rights
- Payments (escrow, creator payouts, invoices)
- Content upload, review, approval, and distribution
- Community activation request and coordination
- Dashboards, notifications, messaging

**This is what V1 is built on. It is the product.**

---

### Type B: "Intelligent" Features (buildable now, using smart rules)

Several features in the PRD are described as AI. In reality, they can be built using structured rules and scoring formulas. No machine learning required. That's not a downgrade. Rules-based intelligence is still intelligence, and it works well from day one.

| PRD Feature | What It Actually Is |
|---|---|
| Cultural fit score | A weighted formula comparing brand values to creator profile tags |
| Brand literacy score | A checklist-style scoring system against brand profile requirements |
| Trust score | A formula that tracks creator compliance, delivery, and platform history |
| Compliance checker | A rules database that checks for disclosure requirements, tone, and platform policies |
| Fair pricing detection | A comparison against pricing brackets by category, tier, and region |
| Creator tier ranking | Threshold rules: hit a score, move to the next tier |
| Leaderboard | Weighted ranking formula across trust, compliance, and reliability |
| Seasonal pricing | Calendar-based rules (Ramadan, Black Friday, back-to-school, etc.) |
| Location-based matching | Proximity filter by postcode/city for activations |

These features can be built in V1, presented accurately as intelligent features, and improved over time as the rules are tuned with real feedback.

**This is what makes V1 feel smart, without needing data that doesn't exist yet.**

---

### Type C: Predictive AI (needs real data first, V2)

These are the features that genuinely require machine learning. They can't be built on rules alone. They need to learn from patterns in real platform history. They are legitimate V2 features, not V1.

- Which creator will actually convert for a brand (conversion prediction)
- How a creator's trust score will trend over time (trust forecasting)
- When a creator is at risk of being overused or going stale (fatigue detection)
- What the right price is, dynamically, based on demand and performance history
- Whether a community will be receptive to a brand's campaign
- How competitors are positioning against Nelo (competitive intelligence)

**None of these can be built before Nelo has 6-12 months of real campaign data. Attempting to build them earlier would produce unreliable results that could damage the platform's credibility.**

---

## 4. The Build Plan

### Phase 1: Launch the Marketplace (V1)

**Goal:** Get a real, functional platform in front of brands and creators. Start collecting the data that powers everything that comes next.

**What gets built:**

- The full marketplace (Type A features above)
- The intelligent rules layer (Type B features above)
- A background data collection system. Every campaign outcome, pricing decision, creator-brand match, and compliance event gets recorded. This is invisible to users but essential for Phase 3.

**What gets deferred:**
- Any predictive or forecasting features
- Competitive intelligence
- Real-time trend tracking

**Rough timeline:** 4-6 months (subject to proper scoping)

---

### Phase 2: Tune and Expand (V1.5)

**Goal:** Use the first wave of real data to make the existing features more accurate, and ship the analytics dashboards that are now meaningful.

**What gets built:**
- Performance dashboards for brands and creators (now that there's real data to show)
- Pricing refinement using actual transaction history
- Creator benchmarking and trend tracking
- CRM, eCommerce, and affiliate integrations

**Timeline:** 2-3 months after V1 launch

---

### Phase 3: Real AI (V2)

**Goal:** Build the predictive models the PRD envisions, now backed by real platform data.

**What gets built:**
- Creator performance prediction
- Trust forecasting
- Dynamic pricing recommendations
- Creator fatigue and overexposure detection
- Conversion lift prediction
- Cultural misalignment risk scoring

**When this happens:** Once Nelo has completed at least 500 real campaigns with tracked outcomes. Before that, the models would be training on too little data to be reliable.

**Timeline:** 6-12 months post-launch

---

## 5. What V1 Nelo Competes On

The competitive advantage in V1 doesn't come from AI. It comes from the model:

1. **Cultural alignment as a filter.** No other platform makes this a first-class matching criterion. It's differentiated even as a rules-based feature.
2. **Community activation as a product category.** Creator-led offline activation is novel. No one else has productised this.
3. **Trust as a platform value.** Building trust scores into every interaction from day one creates compounding effects over time.
4. **Data collection from launch.** V1's biggest strategic job is to collect the right data cleanly, so V2's AI is built on something real.

The AI story Nelo wants to tell is achievable. It just needs to be earned through the marketplace first.

---

## 6. What Needs to Be Agreed Before Development Starts

1. **Sign off on this phase structure.** Phase 1, 2, and 3 boundaries need to be agreed before any scoping begins.
2. **Rewrite the PRD's AI section.** The current language sets expectations that V1 cannot meet. Updating it protects everyone.
3. **Define "done" for V1.** Clear acceptance criteria for every feature, no ambiguity.
4. **Confirm data infrastructure is in V1.** The background data collection system must be built from the start. It's non-negotiable for Phase 3.
5. **Full scoping session.** Once this brief is aligned on, a proper technical scoping session to estimate effort and timeline.

---

## Appendix: What Gets Built and When

| Phase | What Ships | When |
|---|---|---|
| V1 | The full marketplace and smart rules layer | Launch (4-6 months) |
| V1.5 | Analytics dashboards and deeper integrations | 2-3 months post-launch |
| V2 | Real predictive AI, dynamic pricing, forecasting | 6-12 months post-launch |
| V2+ | Competitive intelligence, external data integrations | After V2 models are proven |

---

*This document is intended to align scope expectations before development begins. It replaces any AI-related scope assumptions in the original PRD for planning purposes.*
