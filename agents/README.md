# SubjectReport — Core Agent Stack
**Reference:** `SUBJECT-OS-MASTER.md` (`Groundfloorsports/trail-of-joy/`) for the strategic role of each agent.

These six roles are strategic lenses for every session, not separate AI instances. When working a session, ask which lens applies to the work at hand and let that frame the priority. As the repo matures (see `MATURITY.md`), some of these may graduate into tracked, semi-autonomous agents the way DEPLOYER/CAMPAIGNER/QA have in the Operating Charter.

## Chief of Staff
**Question:** What should Ky focus on today?
**Runs against:** `goals/goals.md` pulse (Step 4 of `workflows/daily.md`), the 48hr SLA guard (Step 2), and any blockers flagged in `feedback/feedback-log.md`.
**Current state:** Implicit — `workflows/daily.md` already performs this function each session. Not yet a separately named or logged role.

## Research
**Question:** What opportunities exist?
**Runs against:** Goal 6 (SEO Funnel Activation — collegefootballrecruiting.com), competitor recruiting-platform tracking, NIL regulation/news that affects the education curriculum.
**Current state:** Not yet started. This is the clearest Level 1 (Anticipation) gap identified in `MATURITY.md` — no documented trend-watch process exists for SubjectReport specifically.

## Content
**Question:** What content should be published?
**Runs against:** `skills/srvoice/SKILL.md` for voice, the course portal curriculum (Goal 3), and the weekly content-day production slot in `workflows/daily.md` Step 5.
**Current state:** Active — content production is already a named daily-workflow branch.

## Sales
**Question:** Who should we contact?
**Runs against:** Transcript order pipeline (`data/orders/open-orders.md`), Subject Media cross-sell triggers (Goal 5), Prospect Membership conversion (Goal 2).
**Current state:** Partially active via the SM upsell sequence trigger on delivery; no standalone outbound sales motion documented yet for SubjectReport itself (Subject Media's GHL pipeline handles outbound for that brand).

## Operations
**Question:** What is breaking?
**Runs against:** The 48-hour SLA guard (the single hardest operational commitment in the business), `feedback/feedback-log.md`, data intake quality (Step 3).
**Current state:** Active and well-instrumented — this is the most mature agent role in the repo, evidenced by the dedicated SLA-guard step at the top of every session.

## Analytics
**Question:** What numbers matter?
**Runs against:** All six goals in `goals/goals.md`, the Friday weekly report (`workflows/weekly.md`), `output/reports/`.
**Current state:** Active via the weekly report cadence; not yet broken out into its own dashboard or named agent.

## How this differs from the Operating Charter's agent registry

The Charter's agents (DEPLOYER, CAMPAIGNER, QA, etc.) execute specific technical tasks with tracked autonomy percentages. These six roles are strategic — they answer "what should get worked on and why," not "how do we ship it." A future SubjectReport-specific technical agent (e.g., a transcript-processing automation) would register in the Charter, not here.

## Revision History
- v1.0 — Initial stub, mapping the six Core Agent Stack roles to SubjectReport's existing goals and workflows.
