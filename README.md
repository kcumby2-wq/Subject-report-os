# Subject-report-os

The dedicated operating-agent repo for SubjectReport — brand 01 of the Subject/Ecosystem (data · evaluation · placement, electric blue `#4DB8FF`).

This repo was split out of the `Subjectreport` website repo's `sr-operating-brain/` folder so the operating agent's runtime configuration lives in its own dedicated home, mirroring the pattern used for `Subject-medias-os` (Subject Media's equivalent repo).

```
Subject-report-os/
├── CLAUDE.md                  ← identity + business context (auto-loaded)
├── goals/
│   ├── goals.md                ← active goals with metrics
│   └── archive/                ← completed goals
├── data/
│   ├── orders/
│   │   └── open-orders.md      ← every open transcript with 48hr deadline
│   ├── transcripts/            ← completed Prospect Edge evaluations
│   ├── programs/                ← 6-week program enrollees
│   ├── athletes/                ← SR Active Profile candidates
│   └── interviews/              ← discovery call and placement session notes
├── skills/
│   ├── srvoice/
│   │   └── SKILL.md            ← how SubjectReport writes (incl. brand/visual identity)
│   ├── evaluation-processing/
│   │   └── SKILL.md            ← transcript → family-facing summary
│   └── reporting/
│       └── SKILL.md            ← weekly and monthly report formats
├── workflows/
│   ├── daily.md                 ← run every session
│   ├── weekly.md                ← Monday planning + Friday review
│   └── monthly.md               ← report generation + goal review
├── feedback/
│   ├── feedback-log.md          ← YOU write here
│   └── improvements.md          ← agent logs what changed and why
└── output/
    ├── content/                  ← social posts, course content
    ├── reports/                  ← transcripts, weekly reports, session logs
    └── sequences/                ← GHL email sequences, SM upsell flows
```

## Relationship to other repos

- **`Subjectreport`** — the actual website (index.html, admin.html, api/). No longer holds the operating-brain content; that has moved here.
- **`Subject-medias-os`** — the sister operating-agent repo for Subject Media (brand 02, coral, content/fulfillment/story).

Every session: read `CLAUDE.md` for context, then `workflows/daily.md` for the step-by-step. `feedback/feedback-log.md` is read FIRST, every session, before any other work begins.
