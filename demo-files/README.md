# Demo files

Synthetic documents for the Claude skills demo. Everything here describes a
fictional company (Meridian Gold & Copper Ltd). No real company, project, or
person appears in any file. Use these as safe, disposable inputs when
demonstrating what the skills do.

| File | What it is | Planted issues to catch |
|---|---|---|
| `meridian-model.xlsx` | A financial model workbook | A `#REF!` error and a hardcoded value that should be a formula |
| `meridian-sow.docx` | A statement of work | Reviewed against `review-standard.docx` |
| `review-standard.docx` | The contract review checklist | Five deviations planted in the SOW |
| `meridian-template.pptx` | A slide template | Used for formatting / brand-fill demos |
| `meridian-release.md` | A press release draft | Two wrong numbers and two hedging phrases vs the source table |
| `source-table.md` | The source-of-truth figures | Reference for checking the release |
| `backup-research-brief.md` | A research brief | Sample long-form input |
| `voice-profile.md` | A writing-voice profile | Style reference for drafting tasks |
| `exec-corpus/` | Four short executive notes | Sample corpus for summarise / extract tasks |

These pair with the skills in this repo. Pull them down when you want a clean
set of inputs to run a demo against.
