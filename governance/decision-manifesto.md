# Simon-in-the-Loop: Decision Manifesto

Simon is the board. Agents operate autonomously on routine work but must surface decisions that are **irreversible, costly, external-facing, or strategic** for Simon's approval before acting. The same rules apply to every agent — no exceptions.

## Decision Framework

### Always Requires Simon's Approval

These items **must** use the Paperclip formal approval system and block until resolved.

| Category | Examples | Why |
|---|---|---|
| **Hiring / Agent creation** | New agent proposals, role changes | Adds ongoing cost and capability |
| **Financial commitments** | Any spending, subscriptions, paid services | Real money |
| **External communications** | Emails/messages sent as Simon, public posts | Reputation risk |
| **Strategy / direction changes** | New projects, goal changes, priority shifts | Sets company direction |
| **Access / permissions** | API keys, new service accounts, OAuth grants | Security boundary |
| **Irreversible actions** | Deleting data, cancelling subscriptions, unsubscribing | Can't undo |

### Requires Review Before Completion

These items set status to `in_review` and reassign to Simon with a summary comment.

| Category | Examples | Why |
|---|---|---|
| **High/critical priority tasks** | Any task marked high or critical | Important enough to verify |
| **Code deployments** | Before merge to main, deploy to production | Quality gate |
| **Process changes** | Updates to agent instructions, workflow changes | Affects how team operates |
| **First-time actions** | First email sent, first document published | Validate before establishing pattern |

### No Approval Needed

Agents can complete these autonomously.

| Category | Examples | Why |
|---|---|---|
| **Routine internal work** | Low/medium priority internal tasks | Low risk, high volume |
| **Research / analysis** | Gathering information, reading docs | No external effect |
| **Internal subtask coordination** | Delegating between agents, status updates | Operational efficiency |
| **Drafting** | Writing plans, drafts for later review | No commitment made |
| **Monitoring / reporting** | Status checks, inbox triage, summaries | Informational only |

## How It Works

### `in_review` Flow

1. Agent finishes work on a task
2. Sets `status: "in_review"`, reassigns to Simon
3. Leaves a summary comment explaining what was done and what to check
4. Simon reviews in the Paperclip UI
5. Simon either marks `done` or reassigns back with feedback

### Formal Approval Flow

1. Agent creates an approval request via the Paperclip API
2. Links the approval to the relevant issue
3. Sets issue status to `in_review`
4. Simon reviews in the board UI — approve, reject, or request revision
5. On resolution, the agent is auto-woken and acts accordingly

## When in Doubt

{% hint style="info" %}
Use `in_review` — it's lightweight and low friction. If the action is irreversible or costs money, always use formal approval. Never send external communications, commit spending, or create new agents without approval.
{% endhint %}
