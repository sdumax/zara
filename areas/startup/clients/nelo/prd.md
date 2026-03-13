# Nelo: Product Requirements Document
### V1 — Prepared by Qodesquare

**Prepared by:** Chizaram (Executive Assistant to Maxwell)
**Company:** Qodesquare
**Prepared for:** Chinedu Samuel
**Date:** 2026-03-13
**Version:** 1.0 — Draft for review

---

## Product Overview

Nelo is a UGC and influencer marketplace built around cultural alignment and community trust. Where existing platforms match brands to creators based on follower count and reach, Nelo matches based on whether a creator genuinely understands a brand's culture, language, and community.

The platform also introduces community activation as a distinct service: creator-led, offline, real-world engagements (campus events, pop-ups, street activations) coordinated entirely through the platform. This is a category that no competitor has productised.

V1 launches as a web-based marketplace. It establishes the transactional foundation, the intelligent matching layer, and the data infrastructure that powers everything that follows.

---

## Users

Nelo has three user types:

**Brands**
Companies looking to run UGC or influencer campaigns. They create campaign briefs, browse and invite creators, review and approve content, and manage payments through the platform.

**Creators**
Individuals who produce content or lead community activations on behalf of brands. They build profiles, browse opportunities, submit work, and receive payment through the platform.

**Admins (Nelo/Qodesquare Ops)**
Internal team members who manage platform health: creator and brand approvals, dispute resolution, compliance oversight, and reporting.

---

## V1 Scope

### 1. Onboarding and Profiles

**Brands**
- Account creation and verification
- Brand profile: name, industry, values, cultural identity, tone of voice, target audience
- Brand risk and budget preferences
- Compliance rules setup: disclosures, product claims, regional requirements

**Creators**
- Account creation and identity verification
- Creator profile: bio, skills, content categories, location, community presence
- Portfolio: past work, platforms, audience overview
- Availability and preferred campaign types

**Admin**
- Admin accounts with role-based permissions
- Brand and creator approval queues
- Account management and moderation tools

---

### 2. Marketplace

**For Brands**
- Browse and search creator profiles
- Filter by: category, location, audience type, trust score, tier, budget fit
- View creator portfolio and platform history
- Send campaign invitations directly to creators

**For Creators**
- Browse open campaign opportunities
- Filter by: category, campaign type, brand, compensation
- Apply to campaigns or accept direct invitations

**Matching Intelligence (Rules-Based)**

The platform surfaces the most relevant creators for each brand using a structured scoring system. No guesswork, no black-box algorithm. The scores are calculated from clear signals:

- **Cultural fit score:** How well a creator's profile, categories, and content history align with the brand's stated values and identity
- **Brand literacy score:** Whether a creator has demonstrated understanding of brand language and guidelines in past work
- **Trust score:** A running score based on delivery history, compliance record, and platform behaviour
- **Community relevance:** Creator's location, niche presence, and audience overlap with the brand's target market
- **Budget fit:** Whether the creator's pricing range falls within the brand's campaign budget

These scores are visible to brands when browsing and are used to rank and sort results. They improve over time as more platform data accumulates.

---

### 3. Campaign Management

**Campaign Creation (Brands)**
- Campaign brief: objective, audience, platform mix, content format, timeline, budget
- Deliverable definition: video, UGC asset, testimonial, demo, activation
- Distribution strategy: paid, organic, or hybrid
- Usage rights and exclusivity settings
- Campaign scheduling and calendar

**Campaign Lifecycle**
- Draft, active, in-review, completed, archived states
- Creator invitation and acceptance workflow
- Campaign status tracking for brands and creators
- Revision request workflow
- Campaign cloning for repeat formats

**Community Activation Campaigns**
- Activation brief: format (campus, street, retail, pop-up, demo, meetup), location, dates, expected output
- Creator opt-in for activation opportunities
- Location-based creator matching (proximity to activation area)
- Post-activation UGC capture and submission
- Attendance and completion tracking

---

### 4. Content Management

- UGC asset upload (video, image, mixed formats)
- Content preview and review interface for brands
- Approval, rejection, and revision request workflows
- Version history and draft management
- Content archive and retrieval
- Usage rights documentation attached to each asset
- Distribution to social platforms (TikTok, Meta, YouTube) from within the platform

---

### 5. Compliance

The compliance layer checks submitted content and creator behaviour against a set of defined rules. It is not AI. It is a structured rules database that flags issues before they become problems.

**What it checks:**
- Sponsorship disclosure requirements (by platform and region)
- Brand tone alignment (does the content match the brand's stated voice?)
- Product claim accuracy (flags language that makes unsubstantiated claims)
- Platform-specific policy rules (TikTok, Meta, YouTube content policies)
- Regional sensitivity rules (language, imagery, or references that may be inappropriate in specific markets)

**How it works:**
- Content submitted by creators is run through the compliance checklist before it reaches brand review
- Issues are flagged with specific reasons, not just a pass/fail
- Creators can revise and resubmit
- Compliance history feeds into the creator's trust score

---

### 6. Pricing

V1 uses a structured pricing bracket system. Prices are not algorithmically generated. They are calculated from clear, explainable rules.

**Pricing factors:**
- Creator tier (Standard, Pro, Enterprise-Ready)
- Content category (fashion, fintech, beauty, hospitality, etc.)
- Deliverable type (short-form video, long-form, testimonial, activation, usage rights, exclusivity)
- Region (UK, US, and global markets carry different base rates)
- Campaign duration and platform scope
- Seasonal adjustments (calendar-based: key retail periods, cultural moments)

**Pricing intelligence:**
- Underpriced and overpriced creators are flagged against category benchmarks
- Brands see a "fair range" indicator when setting campaign budgets
- Creators see market-rate guidance when setting their rates

This system is transparent and auditable. It will be refined with real transaction data in V1.5.

---

### 7. Payments

- Stripe integration for all transactions
- Escrow: brand funds held until content is approved
- Creator payouts on approval
- Invoice generation and billing history
- Transaction records for brands and creators
- Admin payout management and dispute handling

---

### 8. Gamification and Creator Progression

Creators advance through tiers based on platform performance. The system is transparent: creators always know what is required to move up.

**Tiers:** Standard, Pro, Enterprise-Ready

**Points accumulate from:**
- Completed campaigns
- Compliance pass rate
- Brand ratings and repeat partnerships
- Delivery consistency (on-time submissions)
- Trust score maintenance

**Benefits by tier:**
- Higher visibility in brand searches
- Access to higher-budget campaigns
- Priority in direct brand invitations
- Leaderboard placement

---

### 9. Notifications and Messaging

- In-platform messaging between brands and creators
- Campaign invitation notifications
- Submission status updates (approved, rejected, revision requested)
- Payment notifications
- Compliance flag alerts
- Admin alerts for approvals, disputes, and platform events
- Email notification system for all key events

---

### 10. Dashboards and Reporting

**Brand Dashboard**
- Active campaign overview
- Creator shortlist and match recommendations
- Content in review
- Campaign spend and payout summary
- Basic performance metrics (once content is live): views, engagement, clicks

**Creator Dashboard**
- Active and available campaigns
- Submission status
- Earnings history and pending payouts
- Trust score and tier progress
- Leaderboard position

**Admin Dashboard**
- Platform health overview
- Pending approvals (brands and creators)
- Compliance incident log
- Transaction summary
- Creator and brand activity metrics

---

### 11. Integrations (V1)

- **Payments:** Stripe
- **Social platforms:** TikTok, Meta, YouTube (creator account connection for verification and content distribution)
- **Analytics:** Google Analytics 4, Facebook Pixel (for brand campaign tracking)
- **Media storage:** Cloudinary (UGC asset hosting)
- **Auth:** OAuth (Google, social login)

---

### 12. Data Infrastructure

This is invisible to users but critical to the product's future.

Every meaningful event on the platform is recorded: campaign outcomes, creator-brand pairings, pricing decisions, compliance events, content performance signals, match acceptance and rejection rates.

This data powers the analytics in V1.5 and the AI models in V2. Without it being built correctly from day one, the V2 roadmap is not possible regardless of how much time passes.

**What gets tracked from launch:**
- All campaign lifecycle events
- Creator-brand match decisions (accepted, rejected, no response)
- Pricing data (proposed, accepted, negotiated)
- Compliance events (flags raised, pass/fail rates by creator and category)
- Content performance (post-distribution engagement signals)
- Trust score changes and the events that caused them

---

## V1 Success Metrics

These are the signals that tell us V1 is working:

| Metric | Target (first 90 days post-launch) |
|---|---|
| Brands onboarded | 20+ |
| Creators onboarded | 200+ |
| Campaigns created | 30+ |
| Campaigns completed end-to-end | 15+ |
| Average time-to-match (brief to creator acceptance) | Under 72 hours |
| Content approval rate on first submission | 70%+ |
| Creator compliance pass rate | 80%+ |
| Payment disputes | Under 5% of transactions |

These targets are starting points. They will be refined after the first month of real usage.

---

## What Is Not in V1

The following features are explicitly out of scope for V1. They are not being deprioritised because they are unimportant. They are deferred because they require data or conditions that will not exist at launch.

- Predictive creator performance scoring
- Trust forecasting over time
- Dynamic AI-generated pricing
- Creator fatigue and overexposure detection
- Competitive benchmark intelligence
- Real-time trend and seasonality detection
- CRM integrations (HubSpot, Salesforce)
- eCommerce integrations (Shopify, WooCommerce)
- Affiliate network connectors (Awin, Partnerize)
- Advanced multi-touch attribution modelling
- Mobile app (web-first for V1)

---

## V1.5 Roadmap (2-3 Months Post-Launch)

Once the platform has real usage data, the following get built:

- Full analytics dashboards for brands and creators (campaign performance, creator benchmarks, pricing trends)
- Pricing refinement: brackets updated using real transaction history
- CRM integrations (HubSpot, Salesforce, Zoho)
- eCommerce integrations (Shopify, WooCommerce)
- Affiliate network connectors (Awin, Partnerize, Impact.com)
- Trust score tuning based on observed outcomes
- Compliance rule refinement based on real flag patterns

---

## V2 Roadmap (6-12 Months Post-Launch)

Once Nelo has completed a minimum of 500 campaigns with tracked outcomes, the real AI layer gets built:

- Creator performance prediction (trained on real campaign outcome data)
- Trust forecasting (trained on real trust signal history)
- Dynamic pricing engine (trained on real transaction and outcome data)
- Creator fatigue and overexposure detection
- Conversion lift prediction
- Cultural misalignment risk scoring
- Competitive benchmark intelligence (with external data integration)

---

## Technical Approach (High Level)

Qodesquare will propose the specific technology stack in a separate technical scoping document. At a high level, the architecture follows modern web application standards:

- Web application with separate brand, creator, and admin interfaces
- API-first backend to support future mobile and third-party integrations
- Event-driven data pipeline from day one (for V2 AI readiness)
- Stripe for all payment processing
- Cloud-hosted with scalability built in from the start
- Security and data privacy compliance for UK, US, and global markets (GDPR-aware)

Full technical specification to follow once this PRD is agreed.

---

## Open Questions for Chinedu

These need to be answered before development scoping can begin:

1. What is the target launch market? UK-first, US-first, or both simultaneously?
2. Are there specific brand categories or creator niches to prioritise for the launch cohort?
3. What is the go-to-market plan for V1? Invite-only beta, open launch, or curated cohort?
4. What does the team on Tiidelab's side look like? (Affects scoping, handoffs, and QA process)
5. Are there existing brand or creator partnerships lined up for launch?
6. What is the target budget range for V1 development?

---

*This PRD defines the scope of what Qodesquare will build. It is a living document and will be updated as decisions are made. It should be read alongside the accompanying technical brief.*
