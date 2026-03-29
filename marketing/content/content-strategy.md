# Content Strategy

Masterful's content strategy, built from a comprehensive marketing audit completed March 2026.

## Content Pillars

| Pillar | Purpose | Content Types |
|--------|---------|---------------|
| **Biometric Wellness** | Establish thought leadership on biometric-adaptive meditation | Blog posts, infographics, research roundups |
| **Meditation Education** | SEO capture for meditation-related queries | How-to guides, technique breakdowns, beginner content |
| **Product Differentiation** | Show why Masterful is different from Calm/Headspace | Comparison posts, feature deep-dives, user stories |
| **Mindfulness Lifestyle** | Broader wellness content for social engagement | Short-form tips, daily quotes, seasonal content |

## Blog Content Plan

Prioritized by SEO opportunity and brand alignment.

| # | Title | Pillar | Target Keywords | Priority |
|---|-------|--------|----------------|----------|
| 1 | How Biometric Meditation Works: Why Your Heart Rate Should Guide Your Practice | Biometric Wellness | biometric meditation, heart rate meditation | High |
| 2 | Meditation for Beginners: A Complete Guide to Starting Your Practice | Education | meditation for beginners, how to meditate | High (SEO volume) |
| 3 | Masterful vs Headspace vs Calm: What Makes AI-Adaptive Meditation Different | Differentiation | best meditation app, meditation app comparison | High |
| 4 | 5-Minute Stress Relief: Quick Meditations That Actually Work | Lifestyle | quick meditation, stress relief meditation | High |
| 5 | What Is NSDR (Non-Sleep Deep Rest) and How It Can Change Your Day | Education | NSDR, non-sleep deep rest, yoga nidra | Medium |
| 6 | How Apple Watch Integration Makes Meditation Smarter | Biometric Wellness | Apple Watch meditation, meditation watch app | Medium |
| 7 | The Science of Personalized Meditation: Why One Size Doesn't Fit All | Differentiation | personalized meditation, AI meditation | Medium |
| 8 | Morning Meditation Routines: How to Start Your Day Mindfully | Lifestyle | morning meditation, morning routine | Medium |
| 9 | Body Scan Meditation: A Step-by-Step Guide | Education | body scan meditation, guided body scan | Medium |
| 10 | How Spatial Audio Transforms Your Meditation Experience | Product | spatial audio meditation, Apple Music meditation | Low |
| 11 | Breathwork Techniques: 4-7-8, Box Breathing, and More | Education | breathwork techniques, breathing exercises | Low |
| 12 | Building a Meditation Streak: The Psychology of Daily Practice | Lifestyle | meditation habit, daily meditation | Low |

## Channel Strategy & Posting Cadence

| Channel | Cadence | Content Focus | Priority |
|---------|---------|---------------|----------|
| **Blog** (getmasterful.xyz/blog) | 2 posts/month | Long-form SEO content, guides, comparisons | **P0** |
| **X/Twitter** (@masterful_app) | 3–5x/week | Daily quotes, tips, product updates, engagement | **P0** |
| **Instagram** (@masterful) | 3–4x/week | Visual meditation tips, app screenshots, reels | **P1** |
| **TikTok** | 2–3x/week | Short meditation clips, biometric demos, wellness tips | **P1** |
| **App Store** | Monthly | Screenshot updates, keyword optimization, review responses | **P0** |
| **Email/Newsletter** | Bi-weekly | Curated content, new features, meditation challenges | **P2** |

## Current State (as of March 2026)

### Web Presence

| Channel | Status | Notes |
|---------|--------|-------|
| masterful.app | Not owned — parked domain for sale | Major branding gap |
| getmasterful.xyz | Active — official domain per App Store | .xyz TLD may affect trust |
| masterful-web.vercel.app | Active — functioning landing page | Unprofessional subdomain |
| share.getmasterful.xyz | Active — session sharing subdomain | Deep links and share cards |

### SEO Strengths

- Comprehensive OpenGraph tags on all pages
- Twitter card metadata configured
- PWA manifest with health/wellness categories
- Dynamic OG images for shared sessions
- Apple deep linking configured (AASA file)

### SEO Gaps

- No robots.txt
- No sitemap.xml
- No blog/content pages (zero organic SEO content)
- No JSON-LD structured data
- No Google Search Console

### App Store

- **App ID:** 6754541672
- **Developer:** Evie Digital
- **Ratings:** Zero — critical for discoverability
- **Pricing:** Free + IAP (Pro Monthly $12.99, Pro Annual $99.99, Flow Monthly $6.99, Flow Annual $49.99)
- **Listing copy:** Strong — mentions biometric adaptation, Apple Watch, spatial audio, AI personalization

### Existing Marketing Infrastructure

- Session sharing system (`/share/[sessionId]` with dynamic OG cards)
- Referral system (partially implemented)
- Influencer management (admin routes at `/admin/influencers`)
- X/Twitter scheduled posting (Cloud Functions for daily quotes)
- Push notifications (Firebase Cloud Messaging)
- Download tracking (`/download/[code]` routes)

## Roadmap

### Immediate (Quick Wins)

1. Add robots.txt — exclude /admin/\*, /api/\*, /login, /dashboard
2. Add dynamic sitemap.xml via Next.js
3. Add JSON-LD structured data (SoftwareApplication schema)
4. Fix privacy policy — remove "Dayconn" reference
5. Flesh out support page FAQs
6. Implement in-app rating prompt (coordinate with iOS team)
7. Activate @masterful_app on X — start daily quote posting
8. Set up Google Search Console
9. Consolidate domains — decide canonical URL

### Medium-Term (1–3 Months)

1. Build blog infrastructure (`/blog` route with MDX or CMS)
2. Write first 6 blog posts from the content plan
3. ASO optimization — keyword research, screenshot A/B testing, localization
4. Influencer outreach via existing admin infrastructure
5. PR push — pitch to wellness tech publications
6. Referral program activation
7. Email capture — newsletter signup on landing page and blog
