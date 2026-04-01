# Biodiversity in National Parks
*Analyzing conservation status and species observations across U.S. national parks*

**Presented by:** Maurice Lemoine  
**Date:** April 1, 2026

---

## Slide 2: Project Overview
This project analyzes biodiversity data from the National Parks Service to better understand how conservation status differs across species groups and parks.

The main goals were to:
- clean and explore the data
- identify patterns among protected species
- compare park-level observation trends
- communicate findings through tables and visualizations

---

## Slide 3: About the Data
Two datasets were used in this analysis:

- **`species_info.csv`**: includes each species’ category, scientific name, common name, and conservation status
- **`observations.csv`**: includes the number of observations for each species in four national parks

Together, these datasets make it possible to compare species categories, protection status, and park-level biodiversity patterns.

---

## Slide 4: Data Preparation
Before analysis, the data had to be cleaned and organized.

### Key preparation steps
- loaded and previewed both datasets
- checked data structure, missing values, and duplicates
- standardized the `conservation_status` column
- filled missing conservation values with `No Intervention`
- created an `is_protected` field
- merged species details with park observations using `scientific_name`

These steps helped ensure that the analysis was consistent and reliable.

---

## Slide 5: Species Distribution by Category
The data shows that **Vascular Plants** make up the largest category by far, with **4,262 species**.

Other categories are much smaller, including:
- **Birds**: 488
- **Nonvascular Plants**: 333
- **Mammals**: 176

This suggests that the dataset is heavily weighted toward plant life, so percentage-based comparisons are more useful than raw counts alone.

---

## Slide 6: Protected Species Share by Category
Although vascular plants have the largest total number of species, they have a very low proportion of protected species.

In contrast:
- **Mammals** have the highest protected-species percentage (**17.05%**)
- **Birds** are next (**15.37%**)
- **Amphibians** and **Fish** also show notable protected shares

This suggests that animals, especially mammals and birds, are more likely than plants to fall into at-risk conservation categories.

---

## Slide 7: Conservation Status Overview
Most species in the dataset are listed as **`No Intervention`**, meaning they are not currently marked for protection.

Only a much smaller number fall into the following categories:
- `Species of Concern`
- `Endangered`
- `Threatened`
- `In Recovery`

This indicates that protected species make up only a small fraction of the overall dataset, but they remain important for conservation analysis.

---

## Slide 8: Observations by Park
Observation counts vary across the four parks:

- **Yellowstone National Park** — 1,443,562 observations
- **Yosemite National Park** — 863,332 observations
- **Bryce National Park** — 576,025 observations
- **Great Smoky Mountains National Park** — 431,820 observations

Yellowstone had the highest total observation count, followed by Yosemite. This may reflect differences in park size, biodiversity, or observation activity.

---

## Slide 9: Most-Spotted Species in Each Park
The most frequently observed species were different in each park:

- **Bryce National Park** — `Columba livia`
- **Great Smoky Mountains National Park** — `Streptopelia decaocto`
- **Yellowstone National Park** — `Holcus lanatus`
- **Yosemite National Park** — `Hypochaeris radicata`

These differences suggest that each park has its own unique observation patterns and local biodiversity profile.

---

## Slide 10: Key Insights
Several important patterns emerged from the analysis:

- vascular plants dominate the dataset in total count
- mammals and birds have the highest protected-species percentages
- most species are listed as `No Intervention`
- Yellowstone and Yosemite have the greatest number of observations
- observation patterns differ across parks and species groups

Overall, the results show that conservation risk is not evenly distributed across categories.

---

## Slide 11: Recommendation for Conservationists
Based on this analysis, conservationists may want to focus particular attention on **mammals** and **birds**, since these groups show the highest share of protected species.

Parks with especially high observation activity, such as **Yellowstone** and **Yosemite**, may also be valuable locations for continued monitoring and biodiversity tracking.

A practical recommendation would be to combine broad ecosystem monitoring with targeted protection strategies for the animal groups that appear most at risk.

---

## Slide 12: Conclusion
This project used data analysis to explore biodiversity and conservation patterns across U.S. national parks.

The findings show that while most species are not currently under intervention, protected species are more concentrated among **mammals** and **birds** than among plants.

The project also demonstrates a complete data analysis workflow, including:
- data cleaning
- exploration
- merging datasets
- summarizing results
- creating visualizations
- communicating findings clearly

---

## Slide 13: Limitations
This analysis has a few important limitations:

- observation counts do not measure true population size
- the data supports pattern recognition, not causal conclusions
- duplicate names and simplified status labels may reduce real-world complexity

These findings are best interpreted as descriptive insights that can guide future investigation.

---

## Slide 14: Thank You
**Thank you for listening.**

Questions?