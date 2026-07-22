# claude-skills-demo

A small plugin marketplace for a Claude enablement workshop. It bundles five
synthetic skills built for the fictional training company Meridian Gold & Copper
Ltd. All content is synthetic.

## Skills

- `meridian-release-checker`: verify a release's numbers against a source table and flag hedged language.
- `sow-deviation-screener`: review a contract or SOW against a house standard and return a risk table.
- `board-brief-formatter`: turn a thread or notes into decisions, owners, dates, open questions, and needs-attention.
- `mining-news-recency-scan`: flag claims that rely on data older than six months and list what to re-verify.
- `my-voice`: draft in your own voice from a pasted writing sample.

## Add it in Claude Code

```
/plugin marketplace add peopleforrester/claude-skills-demo
/plugin install meridian-skills@claude-skills-demo
```

Then invoke a skill by describing the task, or with its slash command.
