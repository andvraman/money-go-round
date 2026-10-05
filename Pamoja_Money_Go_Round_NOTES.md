# Pamoja Money-Go-Round — working notes

- **Current version:** `Pamoja_Money_Go_Round_v3.html` (draft, 5 Oct 2026) · published at https://claude.ai/artifact/Kq183eTsVtFigqWZH89jRi
- **Earlier versions:** `archive/` (v1, v2)
- **Project:** PAMOJA Sub-Component 1.2 — capital for Community Microfinance Groups (CMGs) through FIs
- **Built from:** the "Funds Flow Process" note (5 Oct 2026) and the look of `CMG_Financing_Lifecycle_v9.html` in the `Pamoja-loan-flowchart` repo.

## v3: three simple flows (5 Oct 2026)

v2 was too detailed for the client. v3 splits it into three tabbed flows with clickable jumps between them. Arrows run account to account. Each flow has three party columns (PMO-RALG · FI · CMG).

- **Flow 1 · Money goes round:** PMO-RALG disbursal account → FI disbursal account (1 Fund) → CMG group bank account (2 Lend; max 2 loans, 2nd only if 1st repaid) → FI collection account (3 CMG Repays) → PMO-RALG collection account (4 FI Repays) → ↻ 5 Recycle to the PMO-RALG disbursal account, then to the same or another FI. FI's interest share: PMO-RALG collection account → FI own account. Jumps: "Not repaid? → Flow 2" under the CMG, and green "★ Reward → 3" chips on steps 3 and 4 (bottom jump buttons removed from flow 1, review comment). CMGs may withdraw in cash and repay in cash into the FI's collection account at its bank, with an FI reference number (review comment, 5 Oct 2026).
- **Flow 2 · When a CMG doesn't repay:** 1 Recovery (CMG → FI collection account; recovered money jumps to Flow 1 step 4) → 2 Write-down in the FI's books at agreed days past due (recovery stops) → 3 Loss share (PMO-RALG disbursal account → FI own account), claimed at an agreed periodicity.
- **Flow 3 · Rewards:** PMO-RALG grant pool → FI own account (recovery and quick recycling) and → CMG group bank account (on-time repayment + using the CMG app). First 2 years or until the pool runs out.
- Details, still-to-settle points and the glossary sit behind one "Notes and glossary" button.
- New in v3: an FI "own account" (income: interest share, loss share, rewards). Which accounts pay and receive loss share and rewards is still to confirm.

## What v2 showed

Money flows only, between PMO-RALG, the FIs and the CMGs. One page, no scrolling at 1280×720. Click a step for detail; Esc returns to the key.

Three lanes (PMO-RALG · FIs · CMGs). Each card sits in the lane of the party the money leaves.

**Main round (1–5)**
1. Fund the FI: PMO-RALG disbursal account → FI
2. Lend: FI → CMG (maximum two loan cycles per CMG; the second depends on full, on-time repayment of the first)
3. Repay: CMG → FI collection account (principal + interest)
4. Pay back: FI → PMO-RALG disbursal account (principal + interest, including recoveries). PMO-RALG returns the FI's agreed (majority) interest share at regular intervals. *Alternative:* each quarter (or agreed period) the FI pays only principal + PMO-RALG's interest share.
5. Recycle: PMO-RALG → the same FI, or another FI serving a different region or district. This is the only way an FI gets fresh capital.

**Recovery (6–8)**
6. Recovery: the FI recovers from the CMG; amounts recovered go to step 4
7. Write-down: at pre-agreed days past due, booked at an agreed periodicity. After a write-down the FI may not pursue recovery; the agreement can set penalties or suspension for confirmed cases.
8. Loss share: PMO-RALG pays its share to the FI, based on the write-downs

**Incentives (9)**: PMO-RALG pays FIs and CMGs from a grant pool, for the first two years or until the pool runs out, whichever is earlier. Shown as a banner across all three lanes.

## Decisions (agreed with Anand, 5 Oct 2026)

- Use **PMO-RALG** (not PO-RALG) in this chart.
- Principal and interest go back to PMO-RALG's disbursal account and are recycled from there.
- "If not repaid" is called **Recovery**.
- Maximum two loan cycles per CMG.

## Decisions (v2, Anand, 5 Oct 2026)

- FI gets back its agreed (majority) interest share at regular intervals; fresh capital only through recycling. Alternative kept in the side panel of step 4.
- Loss-share treatment (cash payment by PMO-RALG, based on write-downs) agreed.
- No recovery after write-down; penalties or suspension for confirmed cases.
- Second loan cycle depends on repaying the first.
- Incentives from a grant pool, first two years or until it runs out.

## Still to settle (shown in the side panel)

- One transfer or instalments; which FI account receives funds.
- What happens to a CMG after cycle 2.
- The exact interest split; pay-back frequency.
- Rules for choosing where recycled funds go.
- Definition of default.
- What earns an incentive, and how much; the size of the grant pool.
- What the FI incentive rewards (shown as recovery and quick recycling, from the funds-flow note; to confirm).
- Days-past-due threshold; write-down periodicity.
- Loss split (FI 70 : PMO-RALG 30 proposed).
- Which accounts pay and receive loss share and rewards.
- Cash repayments via Wakala: allowed? who bears fees? can the Wakala record the FI account and reference number?

## Glossary

| Term | Meaning |
|---|---|
| PMO-RALG | Prime Minister's Office – Regional Administration and Local Government |
| PAMOJA | The program that funds this scheme |
| FI | Financial institution: the partner bank that lends to CMGs |
| CMG | Community Microfinance Group |
| TZS | Tanzanian shilling |
| Disbursal account | PMO-RALG: funds FIs and receives pay-backs. FI: receives program funds and pays out loans |
| Collection account | FI account that receives CMG repayments and recoveries |
| Loan cycle | One loan to a CMG and its full repayment |
| Recycle | Lending returned money out again |
| Recovery | The FI's steps to collect an overdue loan |
| DPD | Days past due: how many days a payment is late |
| Write-down | Reducing a loan's value in the FI's books |
| Periodicity | How often something is done |
| Loss share | The agreed split of an unrecovered loss |
| Interest share | Agreed split of interest between the FI (majority) and PMO-RALG |
| Grant pool | Money set aside for incentives; not lent, does not come back |
| Incentive | A payment that rewards an FI or CMG for good results |
| Own account | FI account for its own income: interest share, loss share and rewards |
| CMG app | The app CMGs use to manage their group and loan records |
| Reference number | FI-issued number that matches a cash repayment to the right CMG loan |
| Wakala | Agent who takes cash deposits and payments for a bank or mobile money service |
| Set-off | Netting one amount owed against another |
| Reconciliation | Checking that balances match reported flows |
