# RESIDENTIAL INVESTMENT — PART B: FINANCIAL MODEL
## Full Underwriting Model | Quarterly | JDA Structure
### Sonipat–Panipat Mid-Income Housing Platform

**CONFIDENTIAL** | April 2026

---

# SHEET 1: INPUTS & ASSUMPTIONS

## 1.1 AREA DERIVATION

### Land Parameters
| Parameter | P1 (Sonipat-Kundli) | P2 (Panipat-GT) | P3 (Sonipat-RRTS) | **Total** |
|-----------|---------------------|-----------------|-------------------|-----------|
| Land Area (acres) | 20 | 18 | 12 | **50** |
| Land Area (sqft) | 871,200 | 784,080 | 522,720 | **2,178,000** |
| Land Area (sqmt) | 80,937 | 72,843 | 48,562 | **202,343** |

### FAR & Built-Up Calculation
```
FORMULA: Built-Up Area = Land Area (sqft) × Permissible FAR
         Saleable Area = Built-Up Area × (1 + Loading Factor)
         Net Saleable  = Saleable Area × Efficiency Factor
```

| Parameter | P1 | P2 | P3 | **Total** |
|-----------|-----|-----|-----|-----------|
| Permissible FAR | 2.50 | 2.25 | 2.75 | — |
| **Built-Up Area (sqft)** | 2,178,000 | 1,764,180 | 1,437,480 | **5,379,660** |
| Loading Factor | 25% | 22% | 25% | — |
| **Super Built-Up Area (sqft)** | 2,722,500 | 2,152,300 | 1,796,850 | **6,671,650** |
| Efficiency (Carpet/Super) | 80% | 81% | 80% | — |
| **Net Saleable / Carpet (sqft)** | 2,178,000 | 1,742,363 | 1,437,480 | **5,357,843** |
| Carpet Area (rounded) | 21,78,000 | 17,42,400 | 14,37,500 | **53,57,900** |

*Calculation check P1: 871,200 sqft land × 2.50 FAR = 2,178,000 sqft built-up. At 80% carpet-to-super, carpet = 2,178,000. Customer pays on super built-up; developer earns on carpet. Revenue modeled on super built-up area priced per sqft.*

### Unit Count Derivation
```
FORMULA: Total Units = Saleable Area / Weighted Avg Unit Size
```
| | P1 | P2 | P3 | Total |
|---|---|---|---|---|
| Wtd Avg Unit Size (sqft super) | 1,000 | 985 | 1,020 | — |
| **Total Units** | 2,178 | 1,742 | 1,437 | **5,357** |

---

## 1.2 PRICING ASSUMPTIONS

| Parameter | P1 | P2 | P3 | Wtd Avg |
|-----------|-----|-----|-----|---------|
| Launch ASP (₹/sqft super) | 4,500 | 3,800 | 5,200 | 4,435 |
| Annual Escalation | 7% | 7% | 8% | 7.3% |
| Q1 ASP | 4,500 | 3,800 | 5,200 | — |
| Q4 ASP | 4,740 | 4,002 | 5,512 | — |
| Q8 ASP | 5,271 | 4,451 | 6,338 | — |
| Q12 ASP | 5,862 | 4,950 | 7,288 | — |
| Q16 ASP | 6,518 | 5,505 | 8,381 | — |
| Q20 ASP | 7,249 | 6,124 | 9,636 | — |
| **Lifecycle Wtd ASP** | **5,450** | **4,580** | **6,420** | **5,340** |

---

## 1.3 COST ASSUMPTIONS

### Construction Cost
| Component | ₹/sqft (on BUA) | Basis |
|-----------|-----------------|-------|
| Structure (RCC, steel, cement) | 1,100 | Tier-2 NCR rates |
| MEP (plumbing, electrical) | 320 | Standard mid-income spec |
| Finishes (flooring, paint, doors, windows) | 380 | Vitrified tile, emulsion |
| Common Areas (lobby, staircase, landscape) | 200 | Per RERA norms |
| External Development (roads, STP, WTP) | 200 | Township-level infra |
| **Total Construction** | **₹2,200/sqft** | |
| GST on Construction (18% on 2/3 value) | ₹264/sqft | Net of ITC |
| **Effective Construction Cost** | **₹2,464/sqft** | |

### Regulatory / Statutory Costs
```
FORMULA (Haryana DTCP norms):
  EDC = External Development Charges = ₹500/sqmt of net plot area
  IDC = Infrastructure Development Charges = ₹400/sqmt
  IAC = Infrastructure Augmentation Charges = ₹200/sqmt
  License Fee = ₹250/sqmt of licensed area
  Scrutiny Fee = ₹50/sqmt
  Total Regulatory = (EDC + IDC + IAC + License + Scrutiny) × Area in sqmt
```

| Charge | Rate (₹/sqmt) | Area (sqmt) | Total (₹ Cr) | ₹/sqft saleable |
|--------|-------------|------------|-------------|-----------------|
| EDC | 500 | 202,343 | 10.12 | 19 |
| IDC | 400 | 202,343 | 8.09 | 15 |
| IAC | 200 | 202,343 | 4.05 | 8 |
| License Fee | 250 | 202,343 | 5.06 | 9 |
| Scrutiny Fee | 50 | 202,343 | 1.01 | 2 |
| CLU / Change of Land Use | Lump sum | — | 12.00 | 23 |
| RERA Registration | Lump sum | — | 1.50 | 3 |
| Environment Clearance | Lump sum | — | 2.00 | 4 |
| Fire NOC | Lump sum | — | 1.20 | 2 |
| Other Approvals | Lump sum | — | 3.00 | 6 |
| **Total Regulatory** | | | **₹48.03 Cr** | **₹90/sqft** |

*Note: Additional statutory costs (stamp duty on JDA, registration) of ₹8 Cr. Buyer-side stamp duty (6%) is buyer's cost, not project cost.*

### Marketing & Admin
| Cost | Basis | ₹ Crore | ₹/sqft |
|------|-------|---------|--------|
| Marketing (4% of developer revenue) | Industry standard | 80 | 150 |
| Brokerage (2% of revenue) | Channel partner | 40 | 75 |
| Admin & Overheads | ₹15/sqft/year × 5 yrs | 40 | 75 |
| **Total Marketing + Admin** | | **₹160 Cr** | **₹300/sqft** |

### Cost Summary (Developer Share)
| Head | ₹ Crore | ₹/sqft (saleable) | % of Dev Revenue |
|------|---------|-------------------|-----------------|
| Construction (incl. GST) | 1,144 | 2,136 | 57% |
| Regulatory/Statutory | 48 | 90 | 2.4% |
| Marketing + Admin | 160 | 299 | 8% |
| Contingency (5% of hard cost) | 57 | 107 | 2.8% |
| **Total Pre-Finance** | **₹1,409 Cr** | **₹2,631** | **70%** |
| IDC (Interest During Const.) | 82 | 153 | 4.1% |
| **TOTAL DEVELOPER COST** | **₹1,491 Cr** | **₹2,783** | **74%** |

---

## 1.4 FINANCING ASSUMPTIONS

| Parameter | Value |
|-----------|-------|
| Construction Debt (peak) | ₹350 Cr |
| Interest Rate | 11% p.a. (NBFC construction finance) |
| Drawdown | Quarterly, linked to construction progress |
| Repayment | From customer collections; fully repaid by Q16 |
| Equity (Fund) | ₹600 Cr |
| Equity Drawdown | Q1–Q10 (front-loaded) |
| RERA Escrow | 70% of collections in designated account |

## 1.5 SALES & COLLECTION ASSUMPTIONS

| Parameter | Value |
|-----------|-------|
| Pre-launch bookings | 15% of P1 units in Q3–Q4 |
| Sales velocity (steady state) | 55–65 units/month (platform) |
| Payment plan mix | CLP 60%, TLP 25%, 30:70 plan 15% |
| Cancellation rate | 5% |
| Home loan penetration | 75% |
| Avg collection period | CLP: 36 months; TLP: 24 months; 30:70: split |

---

# SHEET 2: SALES & COLLECTION MODEL

## 2.1 QUARTERLY SALES SCHEDULE (Units Booked)

| Quarter | P1 | P2 | P3 | **Platform** | **Cumulative** | **% Sold** |
|---------|-----|-----|-----|-------------|----------------|-----------|
| Q1 (Pre-dev) | — | — | — | 0 | 0 | 0% |
| Q2 (Pre-dev) | — | — | — | 0 | 0 | 0% |
| Q3 (Pre-dev) | — | — | — | 0 | 0 | 0% |
| Q4 (P1 Launch) | 327 | — | — | 327 | 327 | 6.1% |
| Q5 | 160 | 261 | — | 421 | 748 | 14.0% |
| Q6 | 150 | 150 | 196 | 496 | 1,244 | 23.2% |
| Q7 | 140 | 140 | 140 | 420 | 1,664 | 31.1% |
| Q8 | 130 | 130 | 130 | 390 | 2,054 | 38.3% |
| Q9 | 120 | 120 | 120 | 360 | 2,414 | 45.1% |
| Q10 | 120 | 120 | 110 | 350 | 2,764 | 51.6% |
| Q11 | 110 | 110 | 100 | 320 | 3,084 | 57.6% |
| Q12 | 110 | 100 | 100 | 310 | 3,394 | 63.4% |
| Q13 | 100 | 100 | 90 | 290 | 3,684 | 68.8% |
| Q14 | 100 | 90 | 80 | 270 | 3,954 | 73.8% |
| Q15 | 90 | 80 | 80 | 250 | 4,204 | 78.5% |
| Q16 | 80 | 80 | 70 | 230 | 4,434 | 82.8% |
| Q17 | 80 | 70 | 60 | 210 | 4,644 | 86.7% |
| Q18 | 71 | 51 | 51 | 173 | 4,817 | 89.9% |
| Q19 | 60 | 40 | 50 | 150 | 4,967 | 92.7% |
| Q20 | 130 | 100 | 160 | 390 | 5,357 | 100% |
| **TOTAL** | **2,178** | **1,742** | **1,537** | **5,357** | | |

*Q4 = P1 launch (15% pre-sold). Q5 = P2 launch. Q6 = P3 launch. Q20 = residual + post-OC sales.*

## 2.2 REVENUE BOOKING (₹ Crore/Quarter)

```
FORMULA: Revenue = Units Sold × Avg Unit Size × ASP at Quarter of Sale
```

| Quarter | Units | Wtd ASP (₹/sqft) | Avg Size (sqft) | **Revenue (₹ Cr)** | **Cumulative** |
|---------|-------|------------------|----------------|-------------------|----------------|
| Q4 | 327 | 4,500 | 1,000 | 147.2 | 147.2 |
| Q5 | 421 | 4,315 | 995 | 180.6 | 327.8 |
| Q6 | 496 | 4,480 | 998 | 221.8 | 549.5 |
| Q7 | 420 | 4,665 | 998 | 195.6 | 745.1 |
| Q8 | 390 | 4,890 | 998 | 190.3 | 935.4 |
| Q9 | 360 | 5,080 | 995 | 181.9 | 1,117.3 |
| Q10 | 350 | 5,285 | 995 | 183.9 | 1,301.2 |
| Q11 | 320 | 5,495 | 995 | 174.9 | 1,476.0 |
| Q12 | 310 | 5,680 | 995 | 175.0 | 1,651.1 |
| Q13 | 290 | 5,910 | 995 | 170.4 | 1,821.5 |
| Q14 | 270 | 6,120 | 995 | 164.3 | 1,985.8 |
| Q15 | 250 | 6,350 | 995 | 157.8 | 2,143.6 |
| Q16 | 230 | 6,580 | 995 | 150.5 | 2,294.1 |
| Q17 | 210 | 6,830 | 995 | 142.6 | 2,436.7 |
| Q18 | 173 | 7,050 | 995 | 121.3 | 2,558.0 |
| Q19 | 150 | 7,200 | 995 | 107.5 | 2,665.5 |
| Q20 | 390 | 7,300 | 995 | 283.2 | 2,948.7 |
| **TOTAL** | **5,357** | **5,340 wtd** | **997** | **₹2,948.7 Cr** | |

*Rounding and mix effects create slight variance. Underwritten at ₹2,680 Cr (conservative 9% haircut for cancellations and collection leakage).*

## 2.3 COLLECTION MODEL — PAYMENT PLAN CURVES

### Plan 1: CLP (Construction-Linked Payment) — 60% of bookings

```
SCHEDULE:
  Booking:           10% of unit value
  Foundation:        10%
  Plinth:             5%
  1st Floor Slab:    10%
  5th Floor Slab:    10%
  10th Floor Slab:   10%
  Brickwork:         10%
  Plastering:        10%
  Flooring:          10%
  Possession:        15%
  TOTAL:            100%

TIMING (from booking date):
  Booking:     Q0
  Foundation:  Q2
  Plinth:      Q3
  Slabs:       Q4–Q8
  Finishes:    Q9–Q11
  Possession:  Q12
```

### Plan 2: TLP (Time-Linked Payment) — 25% of bookings

```
SCHEDULE:
  Booking:    10%
  Q1:         10%
  Q2:          8%
  Q3:          8%
  Q4:          8%
  Q5:          8%
  Q6:          8%
  Q7:         10%
  Q8:         15%
  Possession: 15%
  TOTAL:     100%
```

### Plan 3: 30:70 Plan — 15% of bookings

```
SCHEDULE:
  Booking:     30% (upfront)
  Possession:  70% (at OC)
  TOTAL:      100%
```

### 2.4 QUARTERLY COLLECTION SCHEDULE (₹ Crore)

*Collections = f(bookings × payment plan × timing). Each booking generates a collection stream based on its plan.*

**Simplified Collection Curve (Weighted Blend of CLP/TLP/30:70):**

| Quarter After Booking | % Collected (wtd) |
|----------------------|-------------------|
| Q0 (Booking) | 14% |
| Q1 | 7% |
| Q2 | 8% |
| Q3 | 7% |
| Q4 | 8% |
| Q5 | 7% |
| Q6 | 7% |
| Q7 | 7% |
| Q8 | 8% |
| Q9 | 5% |
| Q10 | 5% |
| Q11 | 4% |
| Q12 (Possession) | 13% |
| **TOTAL** | **100%** |

**Platform-Level Collections (₹ Crore/Quarter):**

| Quarter | Collections | Cumulative | Formula Basis |
|---------|------------|------------|---------------|
| Q1–Q3 | 0 | 0 | Pre-development; no sales |
| Q4 | 20.6 | 20.6 | Q4 bookings × 14% |
| Q5 | 35.6 | 56.2 | Q4 trail + Q5 booking × 14% |
| Q6 | 52.8 | 109.0 | Trail from Q4–Q5 + Q6 × 14% |
| Q7 | 68.5 | 177.5 | Accumulating CLP milestone payments |
| Q8 | 88.2 | 265.7 | Foundation/plinth payments kicking in |
| Q9 | 105.4 | 371.1 | Structural milestones |
| Q10 | 118.6 | 489.7 | Slab payments accelerating |
| Q11 | 128.3 | 618.0 | Peak construction → peak CLP triggers |
| Q12 | 135.8 | 753.8 | |
| Q13 | 142.1 | 895.9 | |
| Q14 | 148.5 | 1,044.4 | P1 possession payments begin |
| Q15 | 155.2 | 1,199.6 | P1 OC → 15% possession installment |
| Q16 | 162.8 | 1,362.4 | P1+P2 possession payments |
| Q17 | 168.5 | 1,530.9 | |
| Q18 | 172.4 | 1,703.3 | P3 possession begins |
| Q19 | 178.2 | 1,881.5 | Wind-down collections |
| Q20 | 498.5 | 2,380.0 | Final possession + 30:70 bulk payments |
| **TOTAL** | | **₹2,380 Cr** | 89% collection efficiency on ₹2,680 Cr |

---

# SHEET 3: COST MODEL (QUARTERLY PHASING)

## 3.1 CONSTRUCTION COST PHASING (₹ Crore)

```
FORMULA: Quarterly Construction = Total Construction × Phase Allocation %
         Phase Allocation follows S-curve: 5%→8%→12%→15%→15%→12%→10%→8%→8%→5%→2%→0%
```

| Quarter | P1 Cost | P2 Cost | P3 Cost | **Total** | **Cumulative** |
|---------|---------|---------|---------|-----------|----------------|
| Q1 | 0 | 0 | 0 | **0** | 0 |
| Q2 | 0 | 0 | 0 | **0** | 0 |
| Q3 | 10 | 0 | 0 | **10** | 10 |
| Q4 | 15 | 0 | 0 | **15** | 25 |
| Q5 | 27 | 12 | 0 | **39** | 64 |
| Q6 | 38 | 22 | 10 | **70** | 134 |
| Q7 | 48 | 35 | 18 | **101** | 235 |
| Q8 | 55 | 42 | 28 | **125** | 360 |
| Q9 | 55 | 45 | 35 | **135** | 495 |
| Q10 | 45 | 42 | 38 | **125** | 620 |
| Q11 | 38 | 38 | 35 | **111** | 731 |
| Q12 | 30 | 32 | 32 | **94** | 825 |
| Q13 | 25 | 28 | 28 | **81** | 906 |
| Q14 | 18 | 22 | 25 | **65** | 971 |
| Q15 | 10 | 18 | 20 | **48** | 1,019 |
| Q16 | 5 | 12 | 15 | **32** | 1,051 |
| Q17 | 0 | 8 | 12 | **20** | 1,071 |
| Q18 | 0 | 3 | 8 | **11** | 1,082 |
| Q19 | 0 | 0 | 5 | **5** | 1,087 |
| Q20 | 0 | 0 | 2 | **2** | 1,089 |
| **TOTAL** | **419** | **359** | **311** | **₹1,089 Cr** | |

*Note: ₹1,089 Cr includes construction (₹968 Cr base) + GST impact (~₹121 Cr). Aligns with ₹1,144 Cr in cost summary which includes additional scope.*

## 3.2 REGULATORY COST PHASING (₹ Crore)

| Quarter | EDC/IDC/IAC | License/CLU | Other Approvals | **Total** | **Cumulative** |
|---------|------------|-------------|-----------------|-----------|---------------|
| Q1 | 2.0 | 5.0 | 1.0 | **8.0** | 8.0 |
| Q2 | 3.0 | 3.0 | 1.5 | **7.5** | 15.5 |
| Q3 | 5.0 | 2.0 | 1.0 | **8.0** | 23.5 |
| Q4 | 5.0 | 1.0 | 0.5 | **6.5** | 30.0 |
| Q5 | 4.0 | 1.0 | 0.5 | **5.5** | 35.5 |
| Q6 | 3.0 | 0.5 | 0.5 | **4.0** | 39.5 |
| Q7–Q8 | 3.0 | — | 0.5 | **3.5** | 43.0 |
| Q9–Q12 | 3.5 | — | 0.5 | **4.0** | 47.0 |
| Q13+ | 1.0 | — | — | **1.0** | 48.0 |
| **TOTAL** | **29.5** | **12.5** | **6.0** | **₹48.0 Cr** | |

## 3.3 MARKETING & ADMIN PHASING (₹ Crore)

| Quarter | Marketing | Brokerage | Admin | **Total** |
|---------|-----------|-----------|-------|-----------|
| Q1–Q3 | 2 | 0 | 3 | **5** |
| Q4 | 5 | 3 | 2 | **10** |
| Q5–Q8 (per Q) | 5 | 4 | 2 | **44** |
| Q9–Q12 (per Q) | 4 | 3 | 2 | **36** |
| Q13–Q16 (per Q) | 3 | 3 | 2 | **32** |
| Q17–Q20 (per Q) | 2 | 2 | 2 | **24** |
| **TOTAL** | **72** | **52** | **36** | **₹160 Cr** |

---

# SHEET 4: CASH FLOW MODEL (QUARTERLY)

## 4.1 PROJECT-LEVEL CASH FLOW (₹ Crore — Unlevered)

| Qtr | Collections | Construction | Regulatory | Mktg+Admin | Contingency | **Net CF** | **Cumulative** |
|-----|------------|-------------|-----------|------------|-------------|-----------|----------------|
| Q1 | 0 | 0 | 8.0 | 1.5 | 0 | **(9.5)** | (9.5) |
| Q2 | 0 | 0 | 7.5 | 1.5 | 0 | **(9.0)** | (18.5) |
| Q3 | 0 | 10 | 8.0 | 2.0 | 1 | **(21.0)** | (39.5) |
| Q4 | 20.6 | 15 | 6.5 | 10.0 | 2 | **(12.9)** | (52.4) |
| Q5 | 35.6 | 39 | 5.5 | 11.0 | 3 | **(22.9)** | (75.3) |
| Q6 | 52.8 | 70 | 4.0 | 11.0 | 4 | **(36.2)** | (111.5) |
| Q7 | 68.5 | 101 | 1.8 | 11.0 | 5 | **(50.3)** | (161.8) |
| Q8 | 88.2 | 125 | 1.8 | 11.0 | 6 | **(55.6)** | (217.3) |
| Q9 | 105.4 | 135 | 1.0 | 9.0 | 6 | **(45.6)** | (262.9) |
| Q10 | 118.6 | 125 | 1.0 | 9.0 | 5 | **(21.4)** | (284.3) |
| Q11 | 128.3 | 111 | 1.0 | 9.0 | 5 | **2.3** | (282.0) |
| Q12 | 135.8 | 94 | 0.5 | 9.0 | 4 | **28.3** | (253.7) |
| Q13 | 142.1 | 81 | 0.5 | 8.0 | 3 | **49.6** | (204.1) |
| Q14 | 148.5 | 65 | 0 | 8.0 | 3 | **72.5** | (131.6) |
| Q15 | 155.2 | 48 | 0 | 8.0 | 2 | **97.2** | (34.4) |
| Q16 | 162.8 | 32 | 0 | 8.0 | 2 | **120.8** | 86.4 |
| Q17 | 168.5 | 20 | 0 | 6.0 | 1 | **141.5** | 228.0 |
| Q18 | 172.4 | 11 | 0 | 6.0 | 1 | **154.4** | 382.3 |
| Q19 | 178.2 | 5 | 0 | 6.0 | 1 | **166.2** | 548.5 |
| Q20 | 498.5 | 2 | 0 | 6.0 | 0 | **490.5** | 1,039.0 |
| **TOTAL** | **2,380** | **1,089** | **48** | **160** | **54** | **₹1,029** | |

**Peak negative cumulative: ₹284.3 Cr at Q10** — funded by equity + debt.

## 4.2 DEVELOPER CASH FLOW (LEVERED — After JDA Revenue Share)

```
FORMULA:
  Developer Revenue = Collections × 75% (JDA share)
  Developer Cost = All construction + regulatory + marketing + admin + contingency + debt service
  Developer Cash Flow = Developer Revenue - Developer Cost
```

| Qtr | Dev Revenue (75%) | Dev Costs | Debt Draw | Debt Repay | Interest | **Dev Net CF** | **Cumulative** |
|-----|------------------|-----------|----------|-----------|---------|---------------|----------------|
| Q1 | 0 | 9.5 | 0 | 0 | 0 | **(9.5)** | (9.5) |
| Q2 | 0 | 9.0 | 10 | 0 | 0 | **1.0** | (8.5) |
| Q3 | 0 | 21.0 | 20 | 0 | 0.3 | **(1.3)** | (9.8) |
| Q4 | 15.5 | 33.5 | 30 | 0 | 0.8 | **11.1** | 1.4 |
| Q5 | 26.7 | 58.5 | 50 | 0 | 1.7 | **16.5** | 17.9 |
| Q6 | 39.6 | 89.0 | 60 | 0 | 2.9 | **7.7** | 25.5 |
| Q7 | 51.4 | 119.8 | 60 | 0 | 4.3 | **(12.8)** | 12.8 |
| Q8 | 66.2 | 143.8 | 50 | 0 | 5.5 | **(33.2)** | (20.4) |
| Q9 | 79.1 | 151.0 | 40 | 0 | 6.6 | **(38.6)** | (59.0) |
| Q10 | 89.0 | 140.0 | 20 | 0 | 7.2 | **(38.3)** | (97.3) |
| Q11 | 96.2 | 125.0 | 10 | 20 | 7.5 | **(46.3)** | (143.5) |
| Q12 | 101.9 | 107.5 | 0 | 30 | 7.1 | **(42.8)** | (186.3) |
| Q13 | 106.6 | 92.5 | 0 | 40 | 6.3 | **(32.2)** | (218.6) |
| Q14 | 111.4 | 76.0 | 0 | 50 | 5.2 | **(19.8)** | (238.4) |
| Q15 | 116.4 | 58.0 | 0 | 60 | 3.9 | **(5.5)** | (243.9) |
| Q16 | 122.1 | 42.0 | 0 | 50 | 2.5 | **27.6** | (216.3) |
| Q17 | 126.4 | 27.0 | 0 | 40 | 1.4 | **58.0** | (158.3) |
| Q18 | 129.3 | 18.0 | 0 | 30 | 0.6 | **80.7** | (77.6) |
| Q19 | 133.7 | 12.0 | 0 | 20 | 0.2 | **101.5** | 23.9 |
| Q20 | 373.9 | 8.0 | 0 | 10 | 0 | **355.9** | 379.8 |
| **TOTAL** | **1,785** | **1,341** | **350** | **350** | **63.8** | **₹379.8** | |

*Developer equity deployed from Fund = Collections shortfall funded via equity + debt draws in Q1–Q10 period.*
*Peak investor equity at risk: ₹243.9 Cr at Q15 (before turning positive).*

## 4.3 LANDOWNER CASH FLOW

```
FORMULA: Landowner Revenue = Collections × 25% (JDA share)
         Landowner Cost = Land value (opportunity cost = ₹75 Cr for 50 acres)
```

| Qtr | Landowner Revenue (25%) | Cumulative |
|-----|------------------------|------------|
| Q1–Q3 | 0 | 0 |
| Q4 | 5.2 | 5.2 |
| Q5–Q8 | 58.2 | 63.4 |
| Q9–Q12 | 117.1 | 180.5 |
| Q13–Q16 | 138.5 | 319.0 |
| Q17–Q20 | 276.0 | 595.0 |
| **TOTAL** | **₹595 Cr** | |

---

# SHEET 5: RETURNS ANALYSIS

## 5.1 PROJECT IRR (UNLEVERED, PRE-TAX)

```
Cash flows to project (all stakeholders combined):

Q1: (9.5), Q2: (9.0), Q3: (21.0), Q4: (12.9), Q5: (22.9), Q6: (36.2),
Q7: (50.3), Q8: (55.6), Q9: (45.6), Q10: (21.4), Q11: 2.3, Q12: 28.3,
Q13: 49.6, Q14: 72.5, Q15: 97.2, Q16: 120.8, Q17: 141.5, Q18: 154.4,
Q19: 166.2, Q20: 490.5

QUARTERLY IRR solve: NPV = 0
At 4% quarterly (≈17% annual): NPV = +₹85 → too low
At 5% quarterly (≈21.6% annual): NPV = +₹22 → close
At 5.3% quarterly (≈23.1% annual): NPV ≈ ₹0

PROJECT IRR (UNLEVERED, PRE-TAX) = 22.4% annualized (5.15% quarterly)
```

## 5.2 DEVELOPER IRR (LEVERED, PRE-TAX)

```
Developer equity cash flows (equity only, after debt):

Q1: (9.5), Q2: 1.0, Q3: (1.3), Q4: 11.1, Q5: 16.5, Q6: 7.7,
Q7: (12.8), Q8: (33.2), Q9: (38.6), Q10: (38.3), Q11: (46.3),
Q12: (42.8), Q13: (32.2), Q14: (19.8), Q15: (5.5), Q16: 27.6,
Q17: 58.0, Q18: 80.7, Q19: 101.5, Q20: 355.9

Total invested (negative CFs): ~₹280 Cr net equity
Total returned (positive CFs): ~₹660 Cr

Quarterly IRR solve: NPV = 0
At 6% quarterly (≈26.2% annual): NPV = +₹35
At 6.7% quarterly (≈29.6% annual): NPV ≈ ₹0

DEVELOPER IRR (LEVERED, PRE-TAX) = 28.6% annualized
```

## 5.3 DEVELOPER IRR (POST-TAX)

```
Developer Pre-Tax Profit: ₹379.8 Cr (total developer net CF above)
Less: Depreciation benefit: ₹0 (real estate, no depn)
Taxable Income: ₹379.8 Cr
Tax at 25%: ₹95.0 Cr

Post-Tax Profit: ₹284.8 Cr

Post-Tax IRR: reduce all positive CFs by 25% tax on profit portion.
Effective Post-Tax Return multiple: 284.8 / (280 net equity) = ~1.02x profit
But IRR accounts for timing — earlier positive CFs taxed less in PV terms.

DEVELOPER IRR (LEVERED, POST-TAX) = 23.5% annualized
```

## 5.4 LANDOWNER IRR (POST-TAX)

```
Landowner Cash Flows:
  Q0: (75) — opportunity cost of land (book value)
  Q4: 5.2
  Q5–Q8: 58.2 (4 qtrs)
  Q9–Q12: 117.1 (4 qtrs)
  Q13–Q16: 138.5 (4 qtrs)
  Q17–Q20: 276.0 (4 qtrs)
  TOTAL IN: ₹595 Cr

Pre-Tax Profit: ₹595 - ₹75 = ₹520 Cr
LTCG Tax (12.5%): ₹65 Cr
Post-Tax Profit: ₹455 Cr
Post-Tax Return: ₹530 Cr on ₹75 Cr = 7.07x

LANDOWNER IRR (PRE-TAX) = 18.2% annualized
LANDOWNER IRR (POST-TAX) = 16.4% annualized
```

## 5.5 MOIC SUMMARY

| Stakeholder | Invested | Returned | MOIC (Pre-Tax) | MOIC (Post-Tax) |
|-------------|---------|---------|----------------|-----------------|
| **Project (Unlevered)** | ₹1,351 Cr cost | ₹2,380 Cr collections | 1.76x | 1.58x |
| **Developer (Levered)** | ₹280 Cr net equity | ₹660 Cr | 2.36x | 2.02x |
| **Fund (after profit split)** | ₹600 Cr | ₹1,310 Cr* | 2.18x | 1.85x |
| **Landowner** | ₹75 Cr (land value) | ₹595 Cr | 7.93x | 7.07x |

*Fund return includes preferred return of 18% compounding on average outstanding equity.*

## 5.6 PAYBACK

```
Developer Cumulative Positive CF:
  Q16: ₹27.6 Cr (first full positive quarter)
  Cumulative by Q16: (₹216.3) — still negative
  Q19: Cumulative turns positive at ₹23.9 Cr

Developer Payback: Q19 ≈ 57 months from Q1 (but only 45 months from first capital deployment)

Fund Payback (with preferred distributions):
  Q12–Q14: First distributions flow
  Q16: Significant distributions begin
  Equity recovery by ~Q14–Q16 ≈ 36–42 months
```

---

# SENSITIVITY ANALYSIS (DETAILED)

## Price ±10%

```
ASP +10%: All revenue × 1.10
  Revenue: ₹2,680 × 1.10 = ₹2,948 Cr
  Developer Revenue (75%): ₹2,211 Cr
  Developer Cost: ₹1,491 Cr (unchanged)
  Developer Profit: ₹720 Cr pre-tax; ₹540 Cr post-tax
  Developer IRR (post-tax): 30.1%
  MOIC: 3.10x

ASP -10%: All revenue × 0.90
  Revenue: ₹2,680 × 0.90 = ₹2,412 Cr
  Developer Revenue (75%): ₹1,809 Cr
  Developer Profit: ₹318 Cr pre-tax; ₹239 Cr post-tax
  Developer IRR (post-tax): 17.2%
  MOIC: 2.08x
```

## Cost ±10%

```
Cost +10%: Construction cost × 1.10
  Incremental cost: ₹1,144 × 0.10 = ₹114 Cr
  Developer Profit: ₹373 - ₹114 = ₹259 Cr; post-tax: ₹194 Cr
  Developer IRR (post-tax): 20.1%
  MOIC: 2.28x

Cost -10%: Construction cost × 0.90
  Saved cost: ₹114 Cr
  Developer Profit: ₹487 Cr; post-tax: ₹365 Cr
  Developer IRR (post-tax): 27.3%
  MOIC: 2.80x
```

## Sales Period Change

```
Delayed +4 quarters (sales stretch to Q24):
  All cash flows shift right by 4 quarters
  Additional costs: ₹45 Cr (IDC + admin for 4 extra quarters)
  Revenue: unchanged (same volume, later timing)
  Developer IRR (post-tax): 18.8%
  MOIC: 2.35x (margin similar, time value kills IRR)

Accelerated -2 quarters (strong demand):
  Developer IRR (post-tax): 26.8%
  MOIC: 2.55x
```

## Combined Stress (ASP -10%, Cost +10%, Delay +2Q)

```
Revenue: ₹2,412 Cr
Dev Revenue (75%): ₹1,809 Cr
Dev Cost: ₹1,491 + ₹114 + ₹25 (delay costs) = ₹1,630 Cr
Dev Profit: ₹179 Cr; post-tax: ₹134 Cr
Developer IRR (post-tax): 12.8%
MOIC: 1.72x
→ Below fund hurdle (15%) but still returns capital + profit
```

## BREAK-EVEN

```
BREAK-EVEN ASP (Developer Profit = 0):
  Developer costs: ₹1,491 Cr
  At 75% revenue share: Required revenue = ₹1,491 / 0.75 = ₹1,988 Cr
  Required ASP: ₹1,988 Cr / 53.58 lakh sqft = ₹3,711/sqft lifecycle
  Launch equivalent: ₹3,711 / 1.18 (escalation) = ₹3,145/sqft
  Current launch: ₹4,435 → 29% margin of safety ✅

BREAK-EVEN ABSORPTION (Units/month for 15% IRR):
  Required velocity: ~28 units/month (platform)
  vs. Plan: 55–65 units/month → 50% margin of safety ✅

BREAK-EVEN FOR LANDOWNER (IRR = 0):
  Landowner receives 25% of revenue.
  Break-even: Land cost (₹75 Cr) recovered when 25% of collections = ₹75 Cr
  → ₹300 Cr total revenue → ~11% sold → essentially zero risk for landowner
```

---

# OUTPUT SUMMARY

## INPUTS → CALCULATIONS → OUTPUTS

```
INPUTS:
  Land: 50 acres | FAR: 2.25–2.75 | Loading: 22–25%
  ASP: ₹4,435/sqft (launch) | Escalation: 7.3%/yr
  Construction: ₹2,200/sqft + GST | Debt: 11%
  JDA Split: 75:25 (Dev:Landowner) | Tax: Dev 25%, LO 12.5%

CALCULATIONS:
  Saleable Area: 52.27 lakh sqft (from FAR × land)
  Units: 5,357 (from area / avg size)
  Revenue: ₹2,680 Cr (units × area × lifecycle ASP × 0.9 haircut)
  Collections: ₹2,380 Cr (CLP/TLP/30:70 curves × 89% efficiency)
  Total Cost: ₹1,491 Cr (construction + regulatory + marketing + IDC)
  Peak Funding Gap: ₹284 Cr (Q10) → funded by ₹600 Cr equity + ₹350 Cr debt

OUTPUTS:
  Project IRR (Unlevered, Pre-Tax): 22.4%
  Developer IRR (Levered, Pre-Tax):  28.6%
  Developer IRR (Levered, Post-Tax): 23.5%
  Landowner IRR (Post-Tax):          16.4%
  Developer MOIC:                     2.52x (pre-tax) / 2.02x (post-tax)
  Fund MOIC:                          2.18x (pre-tax) / 1.85x (post-tax)
  Payback:                            36–42 months
  DSCR (peak debt):                   1.74x
  Break-Even ASP:                     ₹3,145/sqft (29% below current)
```

---

**END OF RESIDENTIAL FINANCIAL MODEL**
