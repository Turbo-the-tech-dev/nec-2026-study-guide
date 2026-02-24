# NEC 2026 – Article 220: Load Calculations

**Critical for Examination: Branch-Circuit, Feeder, and Service Load Calculations**

---

## Part I – General

### 220.5 – Calculations

**220.5(A) – Voltages**
- Calculations based on nominal system voltages: 120V, 120/240V, 208Y/120V, 240V, 347V, 480Y/277V, 480V, 600Y/277V, 600V

**220.5(B) – Fractions of an Ampere**
- Fractions less than 0.5A may be dropped

**220.5(C) – Rounding**
- Calculations rounded to nearest whole ampere

---

## Part II – Branch-Circuit Load Calculations

### 220.10 – General

Branch-circuit loads calculated as follows:

**220.12 – General Lighting and General-Use Receptacles**

| Occupancy | Unit Load (VA/sq ft) |
|-----------|---------------------|
| Dwelling units | 3 VA |
| Hospitals | 2 VA |
| Hotels and motels | 2 VA |
| Office buildings | 3.5 VA |
| Schools | 3 VA |
| Stores | 3 VA |
| Warehouses | 0.25 VA |

**220.14 – Other Outlets – Loads**

| Outlet Type | Load |
|-------------|------|
| Receptacle outlets (general) | 180 VA per strap |
| Show windows | 200 VA per linear foot |
| Track lighting | 150 VA per 2 ft |
| Heavy-duty lampholders | 600 VA |

**220.14(I) – Dwelling Unit Receptacle Loads**
- General receptacle outlets included in general lighting load (3 VA/sq ft)
- No additional load required

---

## Part III – Feeder and Service Load Calculations

### 220.40 – General

Feeder and service loads calculated using:
- General lighting load from 220.12
- Other loads from 220.14
- Demand factors from 220.42 through 220.84

### 220.42 – General Lighting

**Demand Factors for Dwelling Units:**

| Portion of Load (VA) | Demand Factor |
|----------------------|---------------|
| First 3,000 VA | 100% |
| 3,001 to 120,000 VA | 35% |
| Remainder over 120,000 VA | 25% |

### 220.44 – Receptacle Loads – Nondwelling Units

**Demand Factors:**

| Portion of Load (VA) | Demand Factor |
|----------------------|---------------|
| First 10,000 VA | 100% |
| Remainder over 10,000 VA | 50% |

### 220.50 – Motors

Motor loads calculated per Article 430:
- Largest motor × 125%
- All other motors × 100%

### 220.51 – Fixed Electric Space Heating

Fixed electric space heating calculated at **100%** of connected load.

### 220.52 – Small-Appliance and Laundry Loads – Dwelling Unit

**220.52(A) – Small-Appliance Branch Circuits**
- 1,500 VA for each 2-wire small-appliance branch circuit
- Minimum 2 circuits required

**220.52(B) – Laundry Circuit**
- 1,500 VA for each laundry branch circuit
- Minimum 1 circuit required

**220.52(C) – Demand Factors**
- First 3,000 VA at 100%
- Remainder at 35% (combined with general lighting)

### 220.53 – Appliance Load – Dwelling Unit

**Demand Factor:** 75% for 4 or more fastened-in-place appliances

**Appliances Included:**
- Water heaters
- Dishwashers
- Garbage disposals
- Trash compactors
- Attic fans
- Garage door openers

**Appliances NOT Included:**
- Electric ranges
- Wall-mounted ovens
- Counter-mounted cooking units
- Clothes dryers
- Space heating equipment

### 220.54 – Electric Clothes Dryers – Dwelling Unit

**Dryer Load:** 5,000 VA or nameplate, whichever is larger

**Demand Factors for Multiple Dryers:**

| Number of Dryers | Demand Factor |
|------------------|---------------|
| 1-4 | 100% |
| 5 | 85% |
| 10 | 50% |
| 24+ | 35% |

### 220.55 – Electric Ranges and Other Cooking Appliances – Dwelling Unit

**Table 220.55 – Demand Factors for Household Electric Ranges**

| Number of Appliances | Demand Factor |
|----------------------|---------------|
| 1 | 100% (Column C) |
| 2 | 55% (Column C) |
| 3 | 55% (Column C) |
| 4 | 50% (Column C) |
| 5 | 45% (Column C) |
| 10 | 34% (Column C) |
| 24+ | 26% (Column C) |

**Column C – Maximum Demand (kW):**

| Number of Ranges | Maximum Demand (kW) |
|------------------|---------------------|
| 1 | 8 kW |
| 2 | 11 kW |
| 3 | 14 kW |
| 4 | 17 kW |
| 5 | 20 kW |

### 220.56 – Kitchen Equipment – Other Than Dwelling Unit

**Demand Factors:**

| Number of Units | Demand Factor |
|-----------------|---------------|
| 1 | 100% |
| 2 | 100% |
| 3 | 90% |
| 4 | 80% |
| 5 | 70% |
| 6+ | 65% |

### 220.60 – Noncoincident Loads

Where unlikely to be in use simultaneously, only largest load included.

### 220.61 – Feeder or Service Neutral Load

**220.61(A) – Basic Calculation**
- Neutral load = Maximum unbalance of loads

**220.61(B) – Permitted Reductions**
- 70% for that portion of unbalanced load over 200A

**220.61(C) – Prohibited Reductions**
- No reduction for:
  - 4-wire, wye-connected, 3-phase systems
  - Electric-discharge lighting
  - Data processing equipment
  - Nonlinear loads

---

## Part IV – Optional Calculations

### 220.82 – Optional Calculation – Dwelling Unit

**220.82(A) – Feeder and Service Load**
Applies when:
- One-family dwelling (or single dwelling unit in multifamily)
- Single set of 120/240V or 120/208V, 3-wire service conductors
- Service rating ≥ 100A

**220.82(B) – General Loads**

Sum of the following at 100%:

| Load Type | Calculation |
|-----------|-------------|
| General lighting & receptacles | Habitable sq ft × 3 VA |
| Small-appliance circuits | 1,500 VA × number of circuits (min 2) |
| Laundry circuit | 1,500 VA × number of circuits (min 1) |
| Fixed appliances | Nameplate VA (all permanently connected) |

**Demand Factor Applied:**
- First 10,000 VA at 100%
- Remainder at 40%

**220.82(C) – Heating or Air-Conditioning Load**

**Use LARGER of:**
- Total heating load at 100%
- Total air-conditioning load at 100%

**Do NOT add heating and cooling together.**

### 220.83 – Optional Calculations – Existing Dwelling Unit

For additional loads to existing dwellings:

| Existing Load | Additional Load | Calculation |
|---------------|-----------------|-------------|
| < 8 kVA | Any | First 8 kVA at 100%, remainder at 40% |
| ≥ 8 kVA | Any | First 8 kVA at 100%, remainder at 40% |

### 220.84 – Optional Calculations – Multifamily Dwelling Units

**Demand Factors for 3+ Units:**

| Number of Units | Demand Factor |
|-----------------|---------------|
| 3-5 | 45% |
| 6-7 | 44% |
| 8-10 | 43% |
| 11-13 | 42% |
| 14-15 | 41% |
| 16-17 | 40% |
| 18-20 | 38% |
| 21-23 | 37% |
| 24-25 | 36% |
| 26-27 | 35% |
| 28-30 | 34% |
| 31-33 | 33% |
| 34-36 | 32% |
| 37-38 | 31% |
| 39-42 | 30% |
| 43-45 | 29% |
| 46-50 | 28% |
| 51-55 | 27% |
| 56-61 | 26% |
| 62+ | 25% |

---

## Part V – Farm Loads

### 220.100 – General

Farm loads calculated per Part V requirements.

### 220.102 – Farm Loads – Buildings and Other Loads

**Demand Factors:**

| Load Portion | Demand Factor |
|--------------|---------------|
| First 60A at 240V | 100% |
| Next 60A at 240V | 50% |
| Remainder at 240V | 25% |

---

## Study Notes

### Critical for Examination:

| Topic | Key Points |
|-------|------------|
| **General Lighting (220.12)** | Dwelling = 3 VA/sq ft |
| **Small-Appliance Circuits (220.52)** | 1,500 VA each, min 2 circuits |
| **Laundry Circuit (220.52)** | 1,500 VA, min 1 circuit |
| **Dryer Load (220.54)** | 5,000 VA or nameplate |
| **Range Load (220.55)** | Table 220.55 Column C |
| **Optional Calc (220.82)** | 10k@100% + remainder@40%, HVAC = larger only |

### Common Exam Questions:

1. **What is the general lighting load for a 2,000 sq ft dwelling?**
   - Answer: 2,000 × 3 = 6,000 VA

2. **What is the minimum small-appliance branch circuit load?**
   - Answer: 2 × 1,500 = 3,000 VA

3. **What demand factor applies to the first 10,000 VA in optional calculation?**
   - Answer: 100% per 220.82(B)

4. **How is HVAC load calculated in optional method?**
   - Answer: Larger of heating or cooling at 100%, not both

5. **What is the dryer load for a dwelling unit?**
   - Answer: 5,000 VA or nameplate, whichever is larger

---

*Turbo Fleet Command | Electrical Training Division*

*For complete NEC 2026 Table of Contents, see: NEC-2026-TABLE-OF-CONTENTS.md*
