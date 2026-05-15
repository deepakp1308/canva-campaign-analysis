# Canva · Campaign Creation Workflow Analysis

Workflow × value-dimension analysis of Canva's marketing campaign creation product across **Email, SMS, and WhatsApp** channels.

**Live dashboard:** https://deepakp1308.github.io/canva-campaign-analysis/

## What's inside

Three tabs (Email · SMS · WhatsApp), each containing:

- **7 critical workflow steps** for creating and launching a campaign in that channel
- Per step, the **Canva features and functionalities** that ship today (sourced from official help docs, product pages, partner ESP docs, and reviews — no inferred or invented features)
- Per step × feature, an executive-readable assessment across **five value dimensions**:
  - **Eliminates friction** — how does Canva remove a barrier?
  - **Saves time** — what is the concrete time saving?
  - **Drives revenue** — how does this lift campaign revenue?
  - **Hyper-personalization** — how does this enable per-recipient or per-segment relevance?
  - **Builds trust & confidence in Canva** — what signals reliability to the user?
- Channel-level summary cards rolling up each value dimension

## Personas covered

- Small-business marketers (primary)
- In-house designers (primary)
- Mid-market marketing teams with developer involvement (Apps SDK pathway)

## Method

1. Researched Canva's actual shipping product surface across help docs, product pages, partner ESP/BSP documentation, and third-party reviews
2. Distilled findings into seven workflow steps per channel, collapsing related stages where it served clarity
3. Mapped each step to the documented micro-features that operate at that stage
4. Wrote per-feature commentary against each of the five value dimensions, executive-read
5. Explicitly flagged gaps (e.g. no native SMS send, no Meta WABA template authoring) rather than papering over them

## Sources

All sources are cited in the page footer. Primary references include the Canva Help Center, `canva.com/emails`, `canva.com/sheets`, the Canva Apps SDK docs, plus the Klaviyo / Mailchimp / Constant Contact / Flodesk / Textellent integration documentation.

## Deploying

This is a single-file static site. To deploy:

```bash
git init
git add .
git commit -m "Canva campaign workflow analysis"
git branch -M main
git remote add origin git@github.com:deepakp1308/canva-campaign-analysis.git
git push -u origin main
# Enable GitHub Pages: Settings → Pages → Deploy from branch → main / root
```

## Author

Deepak Prabhakaran · 2026.
