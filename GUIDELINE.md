# Mississippi Delta Corn Irrigation Scheduling Guideline

## Overview
This guideline provides recommendations for scheduling irrigation events for corn (*Zea mays* L.) grown in the humid/sub‑humid climate of the Mississippi Delta. The objective is to maximize water‑use efficiency while maintaining yield potential by applying irrigation only when soil‑water depletion exceeds a crop‑specific threshold.

## Basic Principles
1. **Soil‑Water Balance Approach**: Irrigation is triggered when the available soil water in the root zone falls below a defined refill point.
2. **Crop Growth Stage Adjustments**: The refill point and irrigation depth are adjusted according to the crop’s phenological stage.
3. **Rainfall Credit**: Effective precipitation is subtracted from the soil‑water deficit before an irrigation event is scheduled.

## Recommended Soil‑Water Depletion Thresholds (Refill Points)
| Crop Growth Stage | Allowable Depletion (% of Available Water) | Corresponding Soil‑Water Potential (kPa) |
|-------------------|--------------------------------------------|------------------------------------------|
| Emergence – V6    | 40%                                        | ≈ -30                                    |
| V6 – VT           | 50%                                        | ≈ -50                                    |
| VT – R3           | 60%                                        | ≈ -70                                    |
| R3 – Physiological Maturity | 70%                                 | ≈ -100                                   |

*Note:* “Available Water” is defined as the water held between field capacity and permanent wilting point in the effective root zone (typically 0–60 cm for corn).

## Irrigation Depth per Event
- **Application Depth**: 20–25 mm (0.8–1.0 inch) per irrigation event.
- **Rationale**: This depth is sufficient to rewet the active root zone without causing excessive deep percolation or runoff in most Delta soils (silt loam to clay loam textures).

## Scheduling Triggers
### 1. **Soil‑Moisture Sensor‑Based Trigger**
   - Install capacitance or tensiometer sensors at 15 cm and 30 cm depths.
   - Initiate irrigation when the average soil‑water potential at 30 cm drops below the stage‑specific threshold listed above.

### 2. **Check‑Book Method (Simplified)**
   - Keep a daily water balance using:
     - **ETc** = Crop evapotranspiration (mm/day), estimated from reference ET (ET₀) × crop coefficient (Kc).
     - **Effective Rainfall** = Daily rainfall minus runoff and deep percolation losses (use a simple runoff coefficient of 0.2 for rainfall >10 mm/day).
   - Calculate cumulative soil‑water deficit:  
     `Deficit(t) = Deficit(t‑1) + ETc(t) – EffectiveRainfall(t)`
   - Schedule an irrigation event when the deficit exceeds the allowable depletion for the current growth stage.

### 3. **Remote‑Sensing辅助 Trigger (Optional)**
   - Use satellite‑derived vegetation indices (e.g., NDVI, NDWI) to detect crop water stress.
   - If the stress index exceeds a calibrated threshold for two consecutive clear‑sky days, consider scheduling an irrigation.

## Crop Coefficients (Kc) for Mississippi Delta Corn
| Growth Stage | Kc (FAO‑56) |
|--------------|-------------|
| Initial (planting – V4) | 0.30 |
| Development (V4 – V12)  | 0.30 → 1.15 |
| Mid‑Season (V12 – R3)   | 1.15 |
| Late Season (R3 – maturity) | 1.15 → 0.60 |

*Reference ET (ET₀)* can be obtained from the nearest Mississippi Agricultural Weather Station (MAWS) or calculated using the Penman‑Monteith equation.

## Special Considerations for Humid Regions
- **Rainfall Interception**: In high‑rainfall weeks, suspend irrigation for at least 3 days after a rainfall event >25 mm.
- **Disease Management**: Avoid frequent light irrigations that keep the canopy wet for prolonged periods; prefer fewer, deeper events.
- **Soil‑Type Adjustments**: For sandy soils, reduce the allowable depletion to 30–40% and apply smaller depths (15–20 mm) more frequently.

## Example Decision Table (Check‑Book Method)
| Day | Growth Stage | ETc (mm) | Effective Rain (mm) | Cumulative Deficit (mm) | Allowable Depletion (mm) | Irrigation Needed? |
|-----|--------------|----------|---------------------|-------------------------|--------------------------|--------------------|
| 1   | V6           | 4.5      | 0.0                 | 4.5                     | 30                       | No                 |
| 2   | V6           | 5.0      | 12.0                | -2.5                    | 30                       | No                 |
| 3   | V6           | 5.5      | 0.0                 | 3.0                     | 30                       | No                 |
| …   | …            | …        | …                   | …                       | …                        | …                  |
| 10  | V6           | 5.2      | 0.0                 | 32.1                    | 30                       | **Yes** (apply 25 mm) |

## Validation and Adaptation
This guideline should be validated with local weigh‑lysimeter data, soil‑moisture monitoring, and yield records. Farmers and researchers are encouraged to adjust thresholds based on field‑specific soil characteristics, cultivar response, and historical weather patterns.

## References
- FAO Irrigation and Drainage Paper 56: *Crop evapotranspiration*.
- Mississippi State University Extension Service publications on corn irrigation.
- Local soil survey data (NRCS Web Soil Survey).