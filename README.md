# Africa Affordable Housing Lab

**A Legesi.xyz public research project.** Based on Kenneth Legesi's March 2018 article *Thoughts on a Model for Affordable Housing in Africa* (reposted in 2021).

## Thesis
Design affordable housing backwards from household capacity to pay, not solely forwards from developer construction cost. Explore a time-limited option to purchase a completed rental home, accumulating contractually protected rent credits before entering a mortgage.

## Audience
First-time buyers and working households; housing developers; SACCOs, banks and mortgage lenders; institutional investors and DFIs; policymakers; valuers and legal professionals.

## Working MVP
Open `index.html` in a browser. Enter income, housing budget, property price, base rent, option term, option premium and illustrative mortgage terms. Outputs include savings credits, deposit coverage, indicative mortgage payment and CSV export. Calculations run locally; no backend, accounts or tracking.

Run tests: `node --test tests/*.test.js` (Node 20+).

## Assumptions and limitations
See [methodology](docs/methodology.md). Values are hypothetical, not verified Uganda market quotes. The model does not determine legal enforceability, valuation, loan eligibility, tax treatment or creditworthiness. A rent credit is not automatically equity or collateral. Contracts must specify refund rights and custody.

## Governance
Public methodology and calculators; no identifiable household or proprietary underwriting data in the repository. No claim of regulatory approval. Independent research by Legesi.xyz; Oakstone Capital is a **potential** commercial implementation partner, not a lender or guarantor under this tool.

## Roadmap
1. Household calculator and transparent mortgage mathematics (MVP)
2. Developer unit economics, land and infrastructure, blended-finance sensitivity
3. Country-specific legal/valuation checklists after local legal review
4. Aggregated opt-in demand intelligence with privacy safeguards

## Deployment
Static hosting compatible with GitHub Pages: deploy repository root from the default branch. Link from legesi.xyz only after verifying the live URL.

## Licensing
MIT for code (see LICENSE); written research and editorial content © Kenneth Legesi, all rights reserved unless expressly licensed otherwise.
