# 2027B run-rate forecast: Procore Datagrid AI, OpenSpace, Document Crunch

Prepared 2026-10-21 for Mike Santimaw. Proposed only; nothing is entered in Adaptive.

Revised 2026-10-21 (afternoon) on Mike's decisions: Document Crunch is dropped from 2027B, and Procore Datagrid AI is carried at $250,000.

Sources read: the 2027B working log and overview portal (OneDrive, `2027 Draft Files`), the 67375 Software Licenses audit of 10/21, the 10/06 preliminary deck, the OpenSpace order forms and proposal (Ken Luong's 9/02 forward and Cole Brewer's 9/22 email), the Procore Datagrid thread (David Ronson 7/24, Travis Niggemyer 8/04 recap), the Procore renewal thread of 12/2025, the Document Crunch mail and Teams history, and public pricing pages for Procore AI credits and Trimble.

The Obsidian vault itself was not reachable from this session (the EPG repo is empty and the vault is not synced there). The agent notes in Google Drive that reference "the TD vault" were read instead, and none of them carries a note on any of these three vendors.

## Where the three lines stand today

| Line | In Adaptive 2027 today | 2026 base in 910 | Quote or contract on file | Decision gate |
|---|---|---|---:|---|
| Procore Datagrid AI | No line (only a "Procore Datagrid" row in the Supporting Systems list) | None | Starter Pack $27,000 / 6 months (7/23). Enterprise credit model: no quote | Travis owes a credit consumption model once TD sends project count, GB and user volume (asked 8/04, not sent) |
| OpenSpace | No line | None in 910. 2026 spend is project-coded (PO-624815 journal in a project cost code; Multifamily contract P-30244 / P-39151) | Core 2-year order form $110,900 net (8/31, unsigned). Enterprise proposal P-42334 $275,990 / year (9/11, unsigned) | Executive meeting at Groundbreak, Thu 10/22 9:00 ET |
| Document Crunch | No line | None | No quote, no trial, no contract. Trimble acquired the company (announced 4/02, close expected Q3 2026); Trimble has not set pricing | Dropped from 2027B (Mike, 10/21) |

None of the three has a 2026 ancestor in 910, so the 12/7 annualization the planning app uses, and the 2026B straight-line the working log uses for 9100, do not apply. Each needs a contract-based build.

## How to build the run rate (method for all three)

1. Start from the contracted annual fee, not from actuals. For a new line the annual fee on the order form is the run rate. Where only a volume or credit rate exists, the run rate is rate x committed volume.
2. Phase from the contract start date. 2027 P&L = monthly rate x months of 2027 inside the term. An upfront prepaid is amortized evenly over the term (the audit flagged that the prepaid policy is not loaded; Controllership should confirm 67375 vs 67385 treatment).
3. Separate one-time from recurring. Onboarding, pilots and starter packs are one-time and should be labeled so they fall out of the 2028 base.
4. Decide gross or net of sales tax. OpenSpace's quotes carry 6.6 percent Texas sales tax on SaaS. If 2027B is gross, add it.
5. Pick the cost center once. Procore already sits in 9130 67375 at $1,500,000. All three fit 9130 unless the OpenSpace enterprise fee is to be recovered from the BUs; Technology told OpenSpace on 9/18 that it procures holistically, so plan on 910 carrying it.
6. Give each line an ID in the log (R-9130-67375-NNN) with the scenario chosen, the quote it rests on, and the date of the decision gate.
7. Budget to the decision, not to the hope. Carry the scenario that matches the decision you expect to make, and record the swing between scenarios as a disclosed risk on the variance slide.

## 1. OpenSpace

### What is on the table

Volume pricing (per million dollars of annual construction volume, ACV):

| Date | Offer | Annual | Notes |
|---|---|---:|---|
| 8/10 | $550 per $M on $150M committed, 2 years | $82,500 | Cole's recommendation off Ken's volume averages |
| 8/13 | 30 percent discount, 2 years prepaid | $83,684 (= $167,367 / 2) | vs about $240,000 list over 2 years |
| 8/17 | Traditional annual pricing | $496 to $625 per $M | Ken asked for $319 per $M; not approved |
| 8/31 | Order form v4 (unsigned), Core, 50-project cap | $82,500 per year | Term 7/31/2026 to 8/30/2028 (13 + 12 months), $165,000 list, $54,100 one-time discount, $110,900 net, $118,219 with tax, upfront, Net 60, auto-renews yearly. Supersedes P-30244 and P-39151 and voids INV00029214 |

Enterprise (unlimited):

| Date | Offer | Annual | Notes |
|---|---|---:|---|
| 9/11 | P-42334 Enterprise (Capture, Field, Air, BIM+, SSO, APIs), $1B ACV and 500-project placeholders | $275,990 | 9/30/2026 to 9/29/2027, upfront, Net 30, $294,205 with tax. Cole recommends a 3-year term for price protection |

Ken's volume projection for the projects that would use OpenSpace: $132M remaining 2026 (11 projects), $166M in 2027 (14 projects), $77M in 2028 (6 projects).

### The economics behind the choice

- At $550 per $M, the enterprise price of $275,990 breaks even at about $500M of annual volume on the platform. The Procore renewal priced TD's volume tiers at $850M of annual construction volume, so if OpenSpace goes enterprise-wide, volume pricing would run $420,000 to $530,000 a year and the unlimited deal is the cheaper structure.
- At the $166M Ken projects for 2027, volume pricing is $82,500 to $104,000. The enterprise deal is 2.7 to 3.3 times that.
- The enterprise price is therefore a bet on adoption beyond Multifamily and the QTS data center work. That is the question for Thursday.

### Scenarios for 2027B

| Scenario | 2027 P&L | Build |
|---|---:|---|
| Low: sign the Core 2-year order form as drafted | $53,232 | $110,900 prepaid amortized over 25 months = $4,436 a month x 12. (If treated as an annual fee rather than amortized: $82,500) |
| Base: Enterprise, 1-year, start 1/1/2027 | $275,990 | $22,999 a month x 12; $294,205 if 2027B is gross of tax |
| Base, if signed for a 11/1/2026 start | $275,990 in 2027, plus $46,000 in the 2026 reforecast | Two months of the first term land in 2026 |
| High: Enterprise 3-year | $275,990 a year, flat | Price protection; cash of $828,000 upfront if paid as one payment, so confirm annual invoicing before signing |

Recommendation: carry the Base, $276,000 in 9130 67375 phased evenly, as a new line, and note the $193,000 swing down to the Low scenario as a disclosed decision risk. Decide Thursday; if the answer is "Multifamily only," key the Low scenario instead.

Two things to settle regardless of scenario:
- The 2026 reforecast. OpenSpace spend to date sits in project cost codes, not 910. If 910 takes the enterprise fee, the BUs' 2027 project budgets should drop their OpenSpace lines, or the cost is counted twice across TD.
- The bridge. The short-term non-auto-renewing agreement agreed in September keeps QTS DFW2 DC4 live. Confirm its end date so it does not overlap the new term.

## 2. Procore Datagrid AI

### What is on the table

| Option | Price | Term | Scope |
|---|---:|---|---|
| Digital Coworker Starter Pack | $27,000 flat | 6 months, no renewal; must move to Pro or Enterprise to continue | 1 to 3 active projects, 5 pre-built agents, self-guided setup |
| Enterprise Proof of Value | Credit-based, no quote | 6 to 12 months | Portfolio-wide, 70+ agents, Agent Studio, 90+ connectors, dedicated architects |

Agreed with Travis on 8/04: TD's target is platform stabilization by end of 2026 and field-wide AI adoption from 1/1/2027; the commercial model is a pooled capacity-credit model driven by GB indexed; Datagrid would structure a 6-month pilot. TD owes the sample metrics (project count, GB per project, user volume) that drive the credit model. Procore's usage data in the 9/08 Risk and ROI guide gives the denominators: 634 projects and 892 users.

Procore's public credit policy (effective 7/22/2026) charges 3 credits per GB per day to keep project data indexed, plus per-task credits. The dollar value per credit and Enterprise bulk rates are only available from sales.

### The run-rate formula

Annual credits = (GB indexed x 3 x 365) + task credits. Example: 30 projects at 20 GB each = 600 GB, which is 657,000 indexing credits a year before any task usage. Multiply by the $ per credit Travis supplies to get the run rate. Until that number exists, every enterprise figure is a placeholder.

### Scenarios for 2027B

| Scenario | 2027 P&L | Build |
|---|---:|---|
| Low: Starter Pack only, decide later | $27,000 | One-time, H1 2027, label as pilot |
| Base (decided 10/21): Starter Pack H1, Enterprise ramp H2 | $250,000 | $27,000 pilot one-time + $223,000 recurring, about $37,167 a month Jul to Dec. The recurring figure is a planning placeholder until Travis quotes the credit pool |
| High: Enterprise from Q1 across the portfolio | $300,000 or more | Judgment placeholder; a Procore premium add-on for TD was priced at $210,094 a year in the 12/2025 renewal, which is the nearest comparable for an enterprise SKU |

Decision (Mike, 10/21): carry $250,000 in 9130 67375 as a new line separate from the $1,500,000 Procore line, with the $27,000 flagged one-time. Send Travis the project metrics this week so the placeholder can be replaced with a quoted credit pool before the 11/09 to 11/20 presentations. The 1/1/2027 field-wide adoption target in the 8/04 recap is not consistent with a Low scenario; if that target still stands, Base is the floor.

Note: the Datagrid General Management bundle includes a Contract Reviewer agent that scans prime contracts and subcontracts for unbudgeted risk. That covers the use case Document Crunch would have served, which is why Document Crunch is dropped below.

## 3. Document Crunch (dropped)

Dropped from 2027B on Mike's decision of 10/21. There was no quote, trial or contract on file; Trimble (which acquired Document Crunch in April 2026) has not set pricing; and the Datagrid Contract Reviewer agent covers the contract risk review use case. If a trial is wanted later in 2027, the BU Software Expansion roll-up ($240,000 in 9100) is the funding source. No named line is carried.

## Summary for Adaptive

| Line | CC / account | Recommended 2027B | Phasing | Status | Swing |
|---|---|---:|---|---|---:|
| OpenSpace Enterprise | 9130 67375 | $275,990 | $22,999 a month | Proposal P-42334 on file, unsigned; decide 10/22 | down to $53,232 |
| Procore Datagrid AI | 9130 67375 | $250,000 | $27,000 H1 one-time + $37,167 a month Jul to Dec | Starter Pack quoted; enterprise credit pool to be quoted | $27,000 to $300,000 |
| Document Crunch | none | $0 | n/a | Dropped 10/21 | none |
| Total | | $525,990 | | | |

Add $18,215 of sales tax on OpenSpace if 2027B is gross. All three belong under the "Increased partner usage (AI, Procore, Autodesk)" driver on slide 2 of the 10/06 deck.

## What is needed, by owner

- Mike: the OpenSpace structure decision on 10/22 (enterprise vs Multifamily-only).
- David Ronson: project count, GB per project and user volume to Travis Niggemyer for the credit model, so the $250,000 can be replaced with a quoted credit pool.
- Valerie Thomas: key the two new 9130 67375 lines once decided; confirm whether the 2026 reforecast needs an OpenSpace line for a November start; confirm with Controllership the prepaid treatment of any upfront payment.
- Ken Luong / Laura Gautreau: the bridge agreement end date and the list of 2027 projects that will carry OpenSpace, so project budgets stop double-funding it.
