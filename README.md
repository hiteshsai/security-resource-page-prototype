# Security Resource Page

An AI-powered partner toolkit prototype. A single search box that turns a customer problem into ranked partner assets, sequenced next conversations, and the natural upsell.

**Live demo:** https://hiteshsai.github.io/security-resource-page-prototype/

## What it does

- **Ranked partner assets** with full preview drawers per asset type (slides, demo scripts, runbooks, pricing, battle cards, code, video chapters, industry crosswalks).
- **Recommended next customer conversations** sequenced as a play, not a wishlist.
- **Recommended upsell SKUs** tied to the customer's likely current position.
- Persona toggle (Pre-sales technical / Delivery specialist).
- Filtering by stage (Position, Decide, Sell, Deploy, Enable), industry, customer size, and existing SKU.
- Six themed quick-link chips: Defend with AI, Safely enable AI, Trust AI with your Data, Get Ready for AI, By Industry, Customer conversation.
- Curated scenario briefs for known prompts (frame, play, outcome, time).
- One-click drafting of customer emails and 5-minute demo flows.
- "My Toolkit" drawer to assemble a per-customer asset package.
- Dark / light theme toggle.

## Tech

Single self-contained HTML file. No build step, no dependencies, all data and logic inline. Hosted on GitHub Pages.

## Status

Concept prototype, not affiliated with any Microsoft product. Mocked retrieval logic stands in for the real Azure OpenAI + Azure AI Search RAG pipeline that the production build would use.
