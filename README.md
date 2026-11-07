# Marketing OS — Interactive Product Showcase

**One connected operating workspace for marketing execution.**

[Explore the interactive demo](https://tdong1919-dev.github.io/Marketing-OS-Showcase/) · [Crystal Thuy Dong's portfolio](https://crystalthuydong.netlify.app)

Marketing work often breaks between the plan and the people doing the work: campaign briefs live apart from creative drafts, approvals disappear into messages, and customer questions never reach the content calendar. Marketing OS is designed around those handoffs.

This public repository is a **synthetic, standalone product demonstration** of that experience. It is not the production application, an SDK, or a source release of JIDOKA's private systems.

## Explore the product experience

The demo uses a minimal monochrome interface and two fictional brand workspaces. Navigate through the connected areas:

| Area | What the demonstration illustrates |
| --- | --- |
| **Core Command** | Campaign status, review queue, active conversations and decision ownership |
| **Inbox** | Synthetic conversations linked to campaigns; save a sample reply, resolve a thread or create a follow-up content task |
| **Clients** | Brand context, audience, voice and governance boundaries |
| **Paid Ad Campaigns** | Briefs, target dates, status and readiness derived from linked content |
| **Content** | Board, calendar and assets; approve drafts or request changes |
| **Market Intelligence** | Illustrative signals and ideas that inform the planning queue |
| **Analytics** | Fictional reporting views separated from real business metrics |
| **Add-ons** | Representative Performance Intelligence, Paid Ads Generator, Pipeline, Money and Settings screens |

### A five-minute guided walkthrough

1. Start in **Core Command** and note the pending review count.
2. Open **Content** and approve an item. Return to Core Command to see the review and approval totals update.
3. Visit **Paid Ad Campaigns** to see how linked content affects campaign readiness.
4. In **Inbox**, open a fictional conversation, save a sample reply and choose **Turn into content task**. The new task appears in Content and changes the review queue.
5. Switch the **Example workspace** selector to see a different fictional client context. Use **Reset demo** to restore sample state.

These actions model the relationship between records. They do **not** send communications, schedule real posts, spend money or contact external systems.

## Product and engineering perspective

The product's organizing idea is that **work should carry context across its lifecycle**. A conversation may reveal a content need; the resulting content should retain its campaign relationship; approval should affect whether a campaign is ready for its next step.

The public sandbox intentionally illustrates several product-design choices:

- **Connected records:** Campaigns, content and conversations refer to one another instead of appearing as isolated tools.
- **Explicit human decisions:** Approval, revision and resolution remain visible actions; automation is not presented as unlimited autonomy.
- **Traceable state changes:** An approval affects both the local item and relevant workspace summaries.
- **Multi-client context:** Switching a fictional brand changes the surrounding campaign and content dataset.
- **Safe public demonstration:** Deterministic sample records, temporary in-browser state and no production integrations.

This is **not a claim that the demo reproduces the production backend, security model, orchestration, or data architecture**. Those details are intentionally not published.

## My contribution

**Crystal Thuy Dong — Founder, product strategy and systems design**

My work centers on translating fragmented operational needs into coordinated products: defining workflows, user roles, decision boundaries, business requirements and how modules should work together. I work across product direction, technical prototyping, architecture discussions, and implementation coordination with developers and operators.

Marketing OS is an example of that founder/operator approach: begin with the operational handoff, then define the interface, data relationships and decisions needed to make it reliable.

## Public vs. private boundaries

| Public showcase | Private production work |
| --- | --- |
| Fictional brands, people, conversations and metrics | Real customers, leads and business data |
| Illustrative browser-only interactions | Live services, accounts and integrations |
| Demonstration-level state relationships | Production data models, access controls and orchestration |
| Generic campaign and content examples | Scout research, enrichment, scoring, prompts and proprietary methods |

The showcase ships as a static page with embedded synthetic examples. All changes are local to the browser session and reset on refresh. The public code contains no credentials or production API calls.

**Important:** A public UI can demonstrate product capability without disclosing the mechanisms that deliver it. Do not use this repository as a reference for private Scout implementation details.

## Repository purpose and rights

This repository exists to demonstrate product thinking, interface behavior and cross-functional workflow design to collaborators, prospective clients and employers.

© 2026 JIDOKA Group / Crystal Thuy Dong. All rights reserved. This repository does not grant permission to use private Marketing OS or Scout source, data, trademarks or proprietary methods. No open-source license is offered for this showcase.

---

[Interactive demo](https://tdong1919-dev.github.io/Marketing-OS-Showcase/) · [Portfolio](https://crystalthuydong.netlify.app) · [GitHub profile](https://github.com/tdong1919-dev)
