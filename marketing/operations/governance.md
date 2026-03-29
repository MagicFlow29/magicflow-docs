# Marketing Governance

Three-tier approval workflow for all CMO marketing work, ensuring appropriate oversight for different levels of risk and visibility.

## Tier Overview

| Tier | Approval | Examples |
|------|----------|----------|
| **Tier 1** | Autonomous (no approval needed) | Blog drafts, SEO updates, individual social posts, internal docs |
| **Tier 2** | CEO review required | Campaign execution, social calendars, content publication schedules, outreach plans |
| **Tier 3** | Board approval required | Partnership proposals, brand changes, public launches, budget/spend decisions |

## Tier 1: Autonomous

Execute independently. Board is informed via task completion comments.

**Covered work:**
- Blog post drafts
- Routine SEO/analytics updates
- Individual social media posts
- Internal content documentation

**Workflow:** Complete the work. Comment with completion status and tier classification.

## Tier 2: CEO Review

CEO reviews and approves before implementation proceeds.

**Covered work:**
- Marketing campaign execution
- Social media calendars
- Content publication schedules
- Outreach plans

**Workflow:**
1. Create a `plan` document on the issue before starting implementation
2. Post a comment noting the tier classification and what is proposed
3. Proceed after CEO review, or escalate if blocked

## Tier 3: Board Approval Required

Must be routed through the CEO for board approval before proceeding.

**Covered work:**
- Partnership or outreach proposals
- Major brand changes (logo, voice, positioning)
- Public-facing launches (campaigns going live, major website changes)
- Budget/spend decisions (paid ads, tools, services)

**Workflow:**
1. Create a `plan` document on the issue with recommendation
2. Set status to `in_review`
3. Reassign to CEO for board routing
4. Do NOT proceed until approval is received — work on other tasks

{% hint style="warning" %}
Never publish content without proper tier classification. Never commit to external partnerships or spend without board approval (Tier 3).
{% endhint %}

## Escalation

If blocked or unsure about tier classification, escalate to the CEO. Create a comment explaining the blocker and reassign if needed.

## Comment Format

All task comments must include the tier classification:

```
## Update

Tier 1 - autonomous

- Completed blog post draft on biometric meditation
- Published to staging for review
```
