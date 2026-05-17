# Golem Grad Tortoise Population Analysis

## Overview
This project explores 16 years of capture–recapture data from a Hermann's tortoise 
population on Golem Grad, a small island in Lake Prespa, North Macedonia. The island 
is the subject of a published ecological study titled *"Sex Ratio Bias Triggers 
Demographic Suicide in a Dense Tortoise Population"* which was notable enough to be covered 
by The New York Times.

The island hosts an extreme male-to-female sex ratio. Constant mating harassment 
leaves females injured, exhausted, and in poor physical condition, sometimes driving 
them off cliff edges. This analysis uses data visualization to quantify those effects 
across recapture patterns, physical condition, and reproductive output.

## Datasets
| File | Rows | Description |
|---|---|---|
| `tortoise_body_condition.csv` | ~10,174 | Individual body measurements, season, sex, locality, body condition index |
| `clutch_size.csv` | ~59 | Egg clutch records for females that reproduced, with age and body mass |

## Questions Explored
1. Do tortoise recaptures occur more frequently in spring or summer?
2. Are male or female tortoises easier to recapture?
3. How do island and mainland tortoises compare in body mass and carapace length?
4. Which sex and locality group shows the poorest body condition?
5. Does the male dominance in recaptures hold across both seasons?
6. Has island tortoise body mass changed over the 16-year study window?
7. Do heavier females produce larger egg clutches?
8. Are older females more common on the island or mainland?

## Key Findings
- **Spring dominates recaptures** - tortoises are nearly 3× more catchable in spring, 
  when temperatures are optimal and mating activity peaks.
- **Males are recaptured far more often** - reflecting both the skewed sex ratio and 
  males' active roaming behavior during mating season.
- **Island tortoises are lighter and smaller** - lower body mass and shorter carapace 
  length compared to the mainland, consistent with chronic stress and reduced foraging.
- **Island females are in the worst condition of any group** - body condition index 
  confirms the harassment effect falls hardest on island females specifically.
- **Heavier females lay more eggs** - creating a compounding problem: lighter island 
  females produce fewer offspring, accelerating population decline.
- **Island body mass has risen over 16 years** - likely survivorship bias; as the 
  weakest individuals are lost, the survivors skew heavier, masking an increasingly 
  small and vulnerable population.
- **Mainland females reproduce later in life** - island females who reproduce tend to 
  be younger, suggesting older island females do not survive long enough to breed again.

## Tools & Libraries
- Python · pandas · plotnine · pyjanitor · NumPy

## Data Source
Golem Grad Hermann's Tortoise Capture–Recapture Study  
*"Sex Ratio Bias Triggers Demographic Suicide in a Dense Tortoise Population"*
