# Lysimeter Comparison for Mississippi Delta Corn Irrigation Guideline

## Objective
Compare the daily irrigation depth recommended by the guideline with actual crop evapotranspiration (ETc) measured by a weigh lysimeter over a two‑week period during the mid‑season growth stage (V12–R3).

## Data Sources
- **Guideline recommendations**: Calculated using the check‑book method with local weather station ET₀ and the crop‑coefficient (Kc) table from `GUIDELINE.md`.
- **Lysimeter ETc**: Hypothetical daily ETc values from a weigh‑lysimeter installed in a corn field at the Mississippi State University Delta Research and Extension Center (Stoneville, MS). The lysimeter measures actual water loss from a vegetated monolith with a precision of ±0.1 mm.

## Comparison Period
**Days 183–196** (July 2 – July 15) of the 2024 growing season. This period corresponds to the mid‑season stage (Kc = 1.15) and typically has high evaporative demand.

## Daily Comparison Table
| Date (2024) | Growth Stage | Guideline Recommended Irrigation (mm) | Lysimeter ETc (mm) | Difference (Guideline – ETc) (mm) |
|-------------|--------------|---------------------------------------|--------------------|-----------------------------------|
| July 2      | V12          | 0.0 (rainfall credit)                 | 5.8                | -5.8                              |
| July 3      | V12          | 0.0                                   | 6.2                | -6.2                              |
| July 4      | V12          | 0.0                                   | 6.5                | -6.5                              |
| July 5      | V13          | 0.0                                   | 6.7                | -6.7                              |
| July 6      | V13          | 0.0                                   | 6.9                | -6.9                              |
| July 7      | V13          | 0.0                                   | 7.1                | -7.1                              |
| July 8      | V14          | 25.0 (irrigation triggered)           | 7.3                | +17.7                             |
| July 9      | V14          | 0.0                                   | 7.0                | -7.0                              |
| July 10     | V14          | 0.0                                   | 6.8                | -6.8                              |
| July 11     | VT           | 0.0                                   | 6.5                | -6.5                              |
| July 12     | VT           | 0.0                                   | 6.3                | -6.3                              |
| July 13     | VT           | 0.0                                   | 6.0                | -6.0                              |
| July 14     | R1           | 0.0                                   | 5.8                | -5.8                              |
| July 15     | R1           | 25.0 (irrigation triggered)           | 5.6                | +19.4                             |

**Notes**:
- “0.0” indicates no irrigation was recommended on that day (soil‑water deficit still below the allowable depletion threshold).
- Rainfall occurred on July 1 (12 mm) and July 10 (8 mm), which contributed to the soil‑water balance and delayed irrigation events.
- The guideline triggered irrigation on July 8 and July 15 when the cumulative deficit exceeded the 60% allowable depletion for the mid‑season stage.

## Summary Statistics
- **Total guideline‑recommended irrigation** over 14 days: 50 mm (two events of 25 mm each).
- **Total lysimeter ETc** over 14 days: 86.4 mm.
- **Net difference (guideline – ETc)**: ‑36.4 mm (guideline applied 36.4 mm less water than the crop used).
- **Average daily difference**: ‑2.6 mm.

## Interpretation
The guideline recommended irrigation only when the soil‑water deficit reached the stage‑specific threshold, resulting in two irrigation events during the two‑week period. The total water applied (50 mm) was substantially lower than the cumulative ETc (86.4 mm), indicating that the guideline relies heavily on soil‑water storage and rainfall credits to meet crop demand. This behavior is appropriate for a humid‑region scheduling rule that aims to avoid over‑irrigation; however, the large negative difference suggests that under high‑ET conditions the guideline may allow the crop to experience moderate stress before triggering irrigation. Further analysis should examine whether the allowable depletion threshold of 60% for mid‑season corn is optimal for maintaining yield in the Mississippi Delta.

## Conclusion
Based on this two‑week comparison, the guideline’s irrigation schedule appears **conservative**, applying about 58% of the crop’s actual water use as measured by the lysimeter. While this conservatism may reduce water waste and leaching, it could risk yield loss if soil‑water storage is insufficient or if rainfall is below normal. The guideline’s accuracy in matching daily ETc is low (large daily differences), but its objective is to maintain soil moisture within a safe depletion range, not to match ETc on a daily basis. Therefore, the guideline performs as designed, though fine‑tuning of the depletion thresholds may be warranted for seasons with exceptionally high evaporative demand.

---

*This analysis is a hypothetical example for demonstration purposes. Real lysimeter data should be used for actual guideline validation.*