# DhakaFin — Master Plan v2 (Grounded, 2026 Reality)

> **Status:** Working strategy document. Companion scorecard in §12 is designed to grade the
> founder's original "Complete Master Product, SaaS & Technology Roadmap" PDF against this plan.
> All regulatory facts researched Sep 2026; verify exact circulars with Bangladesh Bank PSD before filing anything.

---

## 0. Executive Summary

DhakaFin should **NOT** launch as a consumer wallet. That door is closed: bKash holds ~80% of MFS,
the MFS license now requires a scheduled bank to own ≥51%, digital bank licensing has been frozen
since Aug 2024, and ecosystem funding is in a historic drought (US$6M across all of H1 2026).

The powerful path is the one the rails themselves just opened:

**Wedge (0–12mo):** B2B "money operations" SaaS — instant **collections + disbursements API &
dashboard** on the new interoperable rails (NPSB ⇄ bKash ⇄ Nagad ⇄ banks, Bangla QR), sold to
SMBs and mid-market businesses that today reconcile cash by hand. No mega-license required at
launch (ride licensed PSP rails / bank partner). Revenue from month 1–3, not year 3.

**Beachhead (12–30mo):** Become the **Merchant OS** — QR payments + sales ledger + inventory +
payroll/wage disbursement + working-capital data. Use the transaction data (with consent) to
originate **embedded credit through partner banks/NBFIs** under BB's 2027 digital-credit push.
File for our own **PSP license (BDT 20 cr)** once revenue justifies the capital.

**Platform (30mo+):** Embedded-finance rails for other businesses (wallet-as-a-service,
payout APIs, cross-border remittance partnerships). Digital bank only if/when licensing reopens
and unit economics demand it.

Sequencing logic: **SaaS cash flow pays for the license; the license deepens the moat; the data
moat enables credit; credit is where the real margin in Bangladeshi fintech lives.**

---

## 1. Market Snapshot (Sep 2026)

| Fact | Number | So what |
|---|---|---|
| Registered MFS accounts | 210M+ (FY25) | Multi-accounting; real actives far lower. Wallet acquisition is a red ocean |
| Mobile internet subscribers | ~121M | Digital-first distribution is viable without agents |
| Cash share of formal retail payments | ~35% (India 4%, Pakistan 10%) | Huge remaining digitization headroom = our revenue pool |
| Bangla QR ("One Country, One QR") | Mandatory from 1 Jul 2026; ~1.5M merchants | QR playing field leveled — differentiation moves to **software on top** |
| NPSB interoperability | Bank ⇄ wallet ⇄ PSP instant transfers since Nov 2025 | A third-party app can now move money across the whole system — the "UPI moment" |
| Binimoy (IDTP) | ~481K virtual IDs, tiny volumes | Public rails exist but under-consumed → integration/UX layer is an opportunity |
| Digital bank licensing | Frozen since 5 Aug 2024 (Nagad suspended; WB flagged favoritism) | Don't build the plan around a digital bank license |
| MFS license model | Bank-led; bank must own ≥51% | Independent consumer wallet: effectively unavailable |
| PSP license | BDT 20 cr paid-up capital (≈US$1.6–1.7M) | Achievable at Series A stage, not day 1 |
| PSO license | BDT 5 cr min | For gateway/switch infra play |
| Banglalink | PSP NOC Dec 2025; PISP debate opening | Telco entering payments → rails getting cheaper for everyone; PISP = future wedge |
| BB digital-credit roadmap 2027 | BNPL, nano-loans, CMSME credit via IIPS | Regulatory tailwind for our H2 credit phase |
| Startup Finance Master Circular (Jul 2025) | BDT 2–8 cr loans @ ≤4%, BB refinance, bank equity VC | **Local, non-dilutive-ish capital route — critical in the funding winter** |
| Startup funding | H1 2026: US$6M / 6 deals ecosystem-wide | Plan must be default-alive, not default-raise |

**Competitive set:** bKash (~80% MFS), Nagad (state-administered, distracted), Rocket, Upay,
Tap; PSP/gateways (SSLCOMMERZ, ShurjoPay, aamarPay, Portwallet…); commerce-embedded players
(Pathao, ShopUp/axon). **Nobody owns "money ops software for the 7.8M MSMEs."** That gap is the plan.

---

## 2. Brutal Truths (Design Constraints)

1. **Consumer wallet is a trap**: 80% incumbent share, bank-51% MFS rule, frozen digital-bank path, and interoperability (Nov 2025) just commoditized wallets — any app can now reach any wallet/bank, so *owning* a wallet no longer locks anyone in.
2. **Funding winter is real**: raise-less-by-default. Every phase must generate revenue or a clear license/data asset.
3. **Regulatory sequencing is survival**: the wrong license order burns 12–18 months and BDT crores. Partner-first, license-when-proven.
4. **Agent networks are incumbents' moat** — don't fight it with agents; fight it with software and SMB channels (distributors, associations, chambers, ecosystem apps).
5. **Trust is earned in cash-out**: any money product must guarantee same-day settlement and human-reachable support, or SMBs revert to cash in weeks.
6. **Politics is a risk factor**: Nagad shows a regime/regulator shift can suspend a giant. Keep the model regulator-aligned (formalization, AML, tax trail) — it's both moat and insurance.

---

## 3. Strategy — Three Horizons

### H1 · Wedge (Months 0–12): "Money Ops" SaaS
**One sentence:** *Every SMB that takes QR/wallet payments today still runs books in a notebook — DhakaFin is the instant-collections, instant-payout, auto-reconciling OS for them.*

**Product (lean):**
- **Collect:** Bangla-QR + payment links + checkout API (card/wallet/bank via licensed PSP partner rails)
- **Disburse:** bulk payouts to any wallet or bank account (salary, supplier, commission) — one CSV/API call, instant NPSB routing
- **Reconcile:** auto-matched ledger (who paid, which invoice, fees, refunds) — the killer feature nobody local does well
- **Day-1 rails:** partner with 1 licensed PSP + 1 scheduled bank (nodal/escrow account). We are the software layer, not the money handler.

**Beachhead verticals (pick 2, not 10):**
1. **Wholesale/distribution (FMCG/electronics parts):** thousands of retailers → collections + payout math is their daily pain; distributors are natural channel partners.
2. **Coaching centers / schools / clinics:** recurring fees, receipts, parent-facing links; high trust halo, zero agent network needed.

**Metrics:** 500 paying merchants by M9; take-rate + BDT 500–2,000/mo subscription; gross margin >70%; monthly churn <3%.

**Kill criteria:** if <200 merchants by M6 on 2 verticals with CAC < BDT 3,000 → pivot vertical, not pivot company.

### H2 · Beachhead (Months 12–30): Merchant OS + Embedded Credit
- Full Merchant OS: inventory-lite, invoicing, staff roles, wage disbursement (RMG SMEs, agencies), VAT-ready receipts.
- **Apply for PSP license (BDT 20 cr)** once ARR covers burn and the data case is strong — cheaper rails, own merchant onboarding, MDR independence. (Fallback: stay on partner rails; license is an upgrade, not a dependency.)
- **Embedded credit via partners:** under BB's 2027 digital-credit direction, originate nano/working-capital loans *on our ledger data* through a partner bank/NBFI. We take origination + servicing fees, keep credit risk on the lender. This is where bKash is weak: their credit is generic; ours is **contextual (invoice-level, cash-flow-based)**.
- Remittance corridor pilot (partner MTO + bank): USD→BDT direct-to-merchant-wallet for freelance/exporters — formal, cheap, instant.

**Metrics:** BDT 1 cr+ ARR run-rate; PSP application filed; 1 bank/NBFI credit partnership live; 10K merchants.

### H3 · Platform (Months 30+): Embedded-Finance Rails
- Wallet-as-a-service & payout APIs for other businesses (marketplaces, logistics, gig platforms) — the "Stripe/Modern Treasury of Bangladesh" layer.
- Cross-border payouts via international MTO partnerships.
- Credit underwriting as a product (score-as-a-service) once default data matures.
- Digital bank **only** if licensing reopens with sane rules AND credit book demands a balance sheet.

---

## 4. Regulatory Sequencing (Decision Map)

```
Day 1 ───► Company (RJSC), AML/KYC SOP, BFIU-aligned data policy
           Partner: licensed PSP (process payments) + bank (nodal/escrow)
           → NO new license needed to launch SaaS layer
M6–12 ───► BB Innovation Hub / sandbox touchpoint (relationship, not dependency)
           Review: stay partner-model vs apply PSP
M12–18 ─► PSP application (if revenue ✓): NOC → 1yr build (local DC, audits) → license
           Cost gate: BDT 20 cr capital + ~1.5–3 cr build/audit
M24+ ────► Agent-based services (via bank partner under MFS/agent-banking rules)
           Credit partnerships (bank/NBFI balance sheet)
M36+ ────► PSO (only if we run switch-grade infra for others)
           Digital bank (only if unfrozen + economics proven)
```

**License cheat-sheet (verify current circulars with BB PSD):**

| License | Capital | Use case | Needed for our plan? |
|---|---|---|---|
| PSP | BDT 20 cr | e-wallet-lite, merchant payments, QR | Yes, at H2 — via NOC → build → audit |
| PSO | BDT 5 cr | gateway/switch infra | Only if platformizing infra (H3) |
| MFS | bank ≥51%, ~BDT 45 cr (subsidiary) | agent-based wallet, cash-in/out | **No** — avoid; requires bank control |
| Digital bank | frozen | full banking | Watch only |
| NBFI/bank partnership | — | credit | Contract, not license |
| MTO/remittance | via bank partner | cross-border | Contract + BB approval via partner |

---

## 5. Product Roadmap & Kill Criteria

| Phase | Ship | Success gate | Kill/pivot trigger |
|---|---|---|---|
| P0 (M0–2) | Partner rails live; collect + payout MVP for 20 design partners | 80% weekly retention among partners | Redesign onboarding before scaling |
| P1 (M2–9) | Reconciliation engine, merchant dashboard (Bengali-first), subscription billing | 500 merchants, MRR BDT 8L+ | Vertical swap if CAC/LTV fails in chosen 2 |
| P2 (M9–18) | Merchant OS suite; wage disbursement; API v2; PSP NOC filed | 5K merchants, ARR BDT 1 cr | If credit partners won't bite, deepen SaaS pricing instead |
| P3 (M18–30) | Embedded credit live; remittance corridor pilot; PSP license granted | Credit origination BDT 5 cr/mo via partners | Credit NPL >5% → tighten underwriting, shrink |
| P4 (M30+) | Platform APIs for businesses; regional expansion thesis (Nepal/Pakistan analog rails) | 40% revenue from platform/API | — |

---

## 6. Tech Architecture (Built for Bangladesh Reality)

- **Ledger-first core**: double-entry, immutable, event-sourced. Every integration (PSP, bank, QR) posts to one canonical ledger → reconciliation is a query, not a nightmare. This is the moat that compounds.
- **Connector layer**: PSP APIs, bank nodal/escrow, NPSB routes, Bangla QR decode/encode, MFS wallet APIs — behind one internal `MoneyMovement` interface so rails can be swapped without product rewrites.
- **Resilience**: idempotent everything; outbox pattern; queues (Kafka/NATS) with replay; graceful degradation to payment links + SMS confirmations when apps degrade; multi-AZ hosting (local DC for regulated workloads later — PSP requires local data residency).
- **Client reality**: cheap Android, intermittent data, Bengali-first UX, offline-tolerant drafts, 3-tap core flows. USSD/SMS fallback via telco partner (not core, but a trust builder).
- **Security & compliance**: PCI-DSS-scope minimization (we never store PAN via partner rails), RBAC + maker-checker for payouts, full audit trail (BFIU-friendly), NID-based eKYC via licensed partner, data residency roadmap.
- **Team shape early**: 6–8 engineers (ledger/platform 3, integrations 2, product/app 2, SRE 1). No microservices circus at start — modular monolith + the ledger done right.

---

## 7. Go-To-Market — Distribution Arbitrage

- **Channel partners who already visit SMBs**: FMCG distributors, POS/hardware resellers, chamber & association networks, accounting-software resellers. Rev-share 15–20% on subscription. Zero agent-capex.
- **Ecosystem embeds**: inside marketplaces/logistics/gig apps via API (they get payouts + reconciliation free; we get distribution).
- **Content & trust**: Bengali "digital hisab" content, in-person onboarding clinics in 2 cities until playbooks are proven.
- **Pricing** (indicative): BDT 500–2,000/mo SaaS tiers; payments at partner-PSP MDR minus our margin (target +0.3–0.5% effective take or flat BDT 2–5/txn); payouts BDT 3–8/credit bulk-discounted; credit origination 1–3% of disbursed (partner-funded).

---

## 8. Unit Economics (Worked Example, per active merchant/mo)

| Line | Conservative | Good |
|---|---|---|
| Subscription | 800 | 1,500 |
| Payments take (BDT 3L volume × 0.35%) | 1,050 | 3,500 (10L × 0.35%) |
| Payout fees | 150 | 500 |
| **Revenue** | **2,000** | **5,500** |
| Infra + rail costs | (400) | (900) |
| Support allocation | (200) | (300) |
| **Contribution** | **1,400** | **4,300** |
| CAC (blended, channel-led) | 2,500 one-off | 2,000 |
| **CAC payback** | **~2 months** | **<1 month** |

Credit phase adds 1–3% origination on ledger-qualified volume with **zero balance-sheet risk** (partner-funded). Break-even plausible at ~3–4K merchants on SaaS+payments alone — deliberately achievable before any raise.

---

## 9. Funding Plan (Winter-Proof)

1. **Bootstrap + revenue** through P1 (founders + angels, ≤US$300K).
2. **BB Startup Finance Master Circular (Jul 2025)**: term loan up to BDT 2 cr (<2yr-old) at ≤4% via scheduled banks; up to 5 cr at 2–6 yrs. Cheap, non-dilutive, and builds bank relationships that later power credit partnerships. **This is the most underused fintech capital source in the country.**
3. **Startup Bangladesh + ICT Division** grants/equity; accredited startup-hunting programs ease bank approval.
4. **PSP-license gate raise** (BDT 20 cr) at P2 from regional fintech VCs / strategic banks — raised *with* revenue proof, not promises.
5. **Rule:** no phase may depend on a VC round clearing; every phase ends with a self-fundable asset (revenue, license, or data asset).

---

## 10. Team Sequence

M0: 2 founders (product/commercial + ledger/tech lead) + 3 eng + 1 designer + 1 ops/support.
M6: +2 eng (integrations), +2 SMB sales, +1 partnerships.
M12: +compliance officer (ex-bank, BB-literate — hires the PSP file), CFO-lite.
M18+: credit risk lead (ex-NBFI/MFI), data lead. Never scale sales ahead of support quality — churn in SMB software is a support artifact.

---

## 11. Risk Register

| Risk | Likelihood | Impact | Mitigation |
|---|---|---|---|
| PSP partner squeezes economics / drops us | Med | High | Dual-PSP from day 1; PSP license at H2 |
| Regulatory reversal on interoperability fees | Med | Med | Diversified revenue (SaaS > payments take) |
| bKash ships SMB OS | Med | High | Speed + vertical depth; they serve consumers first, always |
| Bank partner failure (politics, fraud) | Low–Med | High | Two nodal banks; BFIU-clean audits as insurance |
| Funding winter persists | High | Med | Default-alive design; BB refinance route |
| Fraud/social-engineering on merchants | High | Med | Maker-checker, velocity limits, human support line, merchant education |
| Talent drain abroad | High | Med | Remote-friendly, meaningful ledger/infra problems, ESOP from day 1 |
| Political/regime shift (Nagad precedent) | Med | High | Regulator-aligned positioning (formalization, tax trail); no political capital bets |

---

## 12. Scorecard — Grade Your PDF Against This (1–5 each)

1. **Sequence clarity:** does it say what to build FIRST and what to explicitly NOT build?
2. **Regulatory realism:** does it map products to licenses with the bank-51% MFS rule and frozen digital-bank reality?
3. **Revenue timing:** month-1 revenue path, or "monetize at scale" hand-waving?
4. **Distribution:** named channels beyond "agents + marketing"?
5. **Unit economics:** per-merchant P&L, CAC payback, break-even headcount?
6. **Rails leverage:** does it exploit Nov-2025 interoperability + Bangla QR as an unlock, or fight incumbents head-on?
7. **Data → credit flywheel:** consented ledger data → embedded credit via partner balance sheets?
8. **Tech spine:** ledger-first architecture, reconciliation as core, local residency roadmap?
9. **Funding realism:** survives US$6M/quarter market? BB refinance route named?
10. **Kill criteria:** explicit metrics that stop/pivot each phase?
11. **Risk register:** Nagad-style political risk acknowledged?
12. **Bengal reality:** cheap Android, offline, Bengali-first, cash-out trust?

**Scoring:** ≥50/60 → your PDF is strong, we merge notes. <36/60 → this plan is the replacement baseline.
Send me the PDF text (or a Google Docs viewer link) and I'll return the graded sheet with line-by-line fixes.

---

## 13. Sources (researched 19 Sep 2026)

- TBS: Nagad digital bank licence suspended; administrator appointed (Aug 2024) — tbsnews.net
- TBS: World Bank CPI diagnostic on digital-bank licensing favoritism; process on hold (May 2025) — tbsnews.net
- TBS: Banglalink PSP NOC (Dec 2025); PISP debate — tbsnews.net
- Lawzana legal Q&A: PSP/PSO/MFS categories, capital thresholds, NOC→build→audit process under Payment & Settlement Systems Act 2024 (Oct 2025) — lawzana.com *(verify figures with BB PSD)*
- NPSB/BB PSD Circular 12 (13 Oct 2025): wallet⇄bank⇄PSP interoperable transfers from Nov 2025 — via nsave.com explainer
- Prothom Alo: Bangla QR mandatory 1 Jul 2026; ~963K→1.5M merchants; settlement via NPSB — en.prothomalo.com
- ResearchGate: QR payments in Bangladesh — 210M+ MFS accounts FY25; cash 35% of formal retail — researchgate.net
- Financial Express: Binimoy/IDTP adoption ~481K VIDs (Jun 2024) — thefinancialexpress.com.bd
- Future Startup: BB Startup Finance Master Circular (Jul 2025) — BDT 2–8 cr, ≤4%, refinance, bank-equity VC — futurestartup.com
- Polygon Tech: BB Digital Finance Reforms by 2027 — sandbox, BNPL, nano-loans, CMSME via IIPS — polygontechnology.io
- Tracxn / ExitStack: BD fintech funding — US$6M in H1 2026; 340 startups, 26 funded — tracxn.com, blog.mean.ceo
