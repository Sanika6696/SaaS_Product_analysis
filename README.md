# Senior Product Analytics — Synthetic Dataset

This repo contains a **synthetic freemium SaaS dataset** for senior-level product analytics portfolio work.

## Tables
- **users.csv** — user_id, signup_ts, country, platform, persona_segment
- **sessions.csv** — session_id, user_id, session_start_ts, platform, country
- **events.csv** — event_id, event_ts, session_id, user_id, event_name, sku, revenue_usd, query_length, duration_sec
- **subscriptions.csv** — subscription_id, user_id, plan, start_ts, end_ts, status
- **experiments.csv** — user_id, experiment_name, variant, assignment_ts
- **marketing_touches.csv** — user_id, touch_ts, channel, campaign_id, is_last_touch_pre_signup

Row counts from local generation:
```
users.csv: 8,000
sessions.csv: 38,258
events.csv: 219,722
subscriptions.csv: 4,523
experiments.csv: 10,860
marketing_touches.csv: 10,715

```
