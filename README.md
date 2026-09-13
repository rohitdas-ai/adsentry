# AdSentry 🛡️

Automated Ad Destination, UTM Continuity & Stockout Sentinel for Google Ads & Meta Ads.

Website: https://adsentry.online

## Overview

AdSentry is a continuous synthetic monitoring platform for paid ad campaigns (Google Ads & Meta Ads). It detects 404/500 destination errors, ValueTrack/UTM parameter loss across redirects, and out-of-stock SKUs before ad spend is wasted.

## Core Capabilities

- **ValueTrack Macro Simulation**: Synthetic expansion of Google & Meta click tokens (`{lpurl}`, `{gclid}`, `{campaignid}`, `{device}`).
- **Redirect Continuity Tracer**: Multi-hop parameter preservation analysis.
- **Stockout Sentinel**: Detects disabled cart/buy buttons and Schema.org `OutOfStock` microdata.
- **Hierarchical Alerts**: Multi-channel pings via Slack Webhooks and transactional email.

## Tech Stack

- **Framework**: Next.js 14 (App Router)
- **Language**: TypeScript
- **Database & Auth**: Supabase (PostgreSQL with RLS)
- **Billing**: Paddle (Merchant of Record)
- **Email Gateway**: Resend

## License

This project is licensed under the MIT License - see the [LICENSE](./LICENSE) file for details.
