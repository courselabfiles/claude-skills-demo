---
name: mining-news-recency-scan
description: Use when checking whether claims on a mining or market topic are current. Flags anything relying on data older than six months and lists what to re-verify from primary sources.
---

# Mining news recency scan

## Procedure
1. For the topic, identify each factual claim and the date of the data behind it.
2. Flag any claim that relies on data older than six months from today.
3. For each flagged claim, name the primary source to check (a regulator filing, a company release, exchange data) rather than a secondary summary.
4. Order the flags by how much their staleness would change a decision.

## Output format
Two lists. Current: claim, source, date. Re-verify: claim, why it is stale, the primary source to check. End with the single most decision-relevant item to confirm first.
