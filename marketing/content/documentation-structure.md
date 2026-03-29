# Marketing Documentation Structure

Defines the full inventory of marketing documents, their organization in GitBook, and the content migration plan.

## Document Inventory

28 documents across 8 functional areas:

### Brand & Identity (5 documents)
- Brand Guidelines — logo usage, color palette, typography, tone of voice
- Brand Positioning Statement — core differentiator, tagline, elevator pitch
- Target Audience Profiles — 4 segments with detailed personas
- Competitive Landscape — positioning vs Headspace, Calm, Insight Timer, Balance, Waking Up
- Messaging Framework — key messages per audience segment and channel

### Content Strategy (4 documents)
- Content Strategy Overview — pillars, goals, KPIs
- Blog Content Plan — topic backlog, SEO keyword targets, priority ranking
- Content Calendar — monthly posting schedule across all channels
- Editorial Guidelines — writing style, formatting standards, SEO checklist

### App Store Optimization (3 documents)
- ASO Playbook — keyword strategy, screenshot guidelines, description templates, localization
- App Store Listing Copy — current and versioned descriptions, what's new templates
- Rating & Review Strategy — in-app prompt timing, review response templates

### Social Media (4 documents)
- Social Media Playbook — platform-specific strategies
- Posting Cadence & Guidelines — frequency, best times, hashtag strategy per platform
- Social Media Templates — post templates, caption frameworks, visual specs
- Daily Quotes Library — quote database for automated X/Twitter posting

### Outreach & Partnerships (3 documents)
- Influencer Outreach Playbook — identification criteria, outreach templates, compensation models
- PR & Media Kit — press release template, media one-pager, founder bio, high-res assets
- Partnership Framework — wellness brands, tech integrations, co-marketing criteria

### Web & SEO (3 documents)
- SEO Playbook — technical SEO checklist, keyword research methodology, link-building strategy
- Domain Strategy — canonical URL decision, redirect rules
- Landing Page Guidelines — conversion best practices, A/B testing framework

### Email & Lifecycle (2 documents)
- Email Marketing Playbook — newsletter strategy, onboarding sequences, re-engagement campaigns
- Email Templates — welcome series, feature announcements, meditation challenges

### Operations & Reporting (4 documents)
- Marketing KPI Dashboard Guide — which metrics to track, reporting cadence
- Marketing Roadmap — quarterly initiatives and OKRs
- Campaign Retrospective Template — post-campaign analysis format
- Three-Tier Approval Workflow — governance for Tier 1/2/3 marketing work

## GitBook Folder Structure

```
marketing/
├── README.md                          # Marketing overview & quick links
├── brand-guidelines.md                # Brand identity, voice, visual system
├── content/
│   ├── content-strategy.md            # Strategy overview, blog plan, channels
│   ├── content-calendar.md            # Cross-channel posting calendar
│   ├── documentation-structure.md     # This document
│   └── editorial-guidelines.md        # Writing & formatting standards
├── social/
│   ├── social-media-strategy.md       # Platform strategies & templates
│   └── content-calendar.md            # 2-week draft calendar with copy
├── operations/
│   └── governance.md                  # Three-tier approval workflow
├── aso/
│   ├── README.md                      # ASO playbook
│   ├── listing-copy.md                # App Store listing versions
│   └── ratings-strategy.md            # Rating prompts & review responses
├── outreach/
│   ├── README.md                      # Outreach & partnerships overview
│   ├── influencer-playbook.md         # Influencer strategy & templates
│   └── media-kit.md                   # PR materials & press kit
├── web-seo/
│   ├── README.md                      # SEO playbook
│   └── domain-strategy.md             # Domain decisions & redirects
└── email/
    ├── README.md                      # Email marketing playbook
    └── templates.md                   # Email sequence templates
```

## Content Migration Status

### Seeded from MAS-6 Audit

| Source | Destination | Status |
|--------|-------------|--------|
| Brand Positioning (§2.1) | `brand-guidelines.md` | Done |
| Target Audiences (§2.1) | `brand-guidelines.md` | Done |
| Competitive Landscape (§2.7) | `brand-guidelines.md` | Done |
| Content Pillars (§2.2) | `content/content-strategy.md` | Done |
| Blog Content Plan (§2.3) | `content/content-strategy.md` | Done |
| Channel Strategy (§2.4) | `content/content-strategy.md` | Done |
| SEO Audit (§1.4) | `content/content-strategy.md` | Done |
| Quick Wins & Roadmap (§2.5–2.6) | `content/content-strategy.md` | Done |

### Seeded from MAS-8 Social Strategy

| Source | Destination | Status |
|--------|-------------|--------|
| Social media strategy | `social/social-media-strategy.md` | Done |
| 2-week content calendar | `social/content-calendar.md` | Done |

### Documents to Create Fresh

| Document | Priority | Notes |
|----------|----------|-------|
| Editorial guidelines | Medium | Define before blog writing begins |
| ASO playbook & listing copy | Medium | Build as ASO efforts ramp up |
| Influencer outreach playbook | Medium | Leverage existing admin infrastructure |
| PR & media kit | Medium | Requires brand assets from design |
| Email marketing playbook | Low | P2 channel per strategy |
| Campaign retrospective template | Low | Needed once campaigns are running |
