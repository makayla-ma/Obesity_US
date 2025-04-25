# Obesity Data Repository
## Table of Contents
- [Repository Contents and Source](https://github.com/makayla-ma/Obesity_US/blob/main/README.md#contents-and-source)
- [Purpose and Potential Usage](https://github.com/makayla-ma/Obesity_US/blob/main/README.md#purpose-and-potential-usage)
- [Data Visualization](https://github.com/makayla-ma/Obesity_US/blob/main/README.md#data-visualization)
- [Contact](https://github.com/makayla-ma/Obesity_US/blob/main/README.md#contact)
## Repository Contents and Source
This data repository was created for Professor Gotzler's ENGL 105 course. It includes the following:
- **A subset** (`USA_Decade_YoungAdult_Obesity_subset.csv`) containing the obesity rates for young adults (ages 18-24) in the United States in 2013 and 2023.
- **Two split files of the original public dataset**, the [Nutrition, Physical Activity, and Obesity - Behavioral Risk Factor Surveillance System](https://catalog.data.gov/dataset/nutrition-physical-activity-and-obesity-behavioral-risk-factor-surveillance-system) by the U.S. Department of Health & Human Services (because GitHub does not allow uploads of files larger than 25 MB):
    - `Nutrition_Physical_Activity_and_Obesity_Part_1.csv` contains data for 2011-2015, 2020-2023
    - `Nutrition_Physical_Activity_and_Obesity_Part_2.csv` contains data for 2016-2019
    - The original source for the public dataset (which is 34 MB) is hyperlinked above and throughout this repository for your convenience.
- **A Colab Notebook** (`Obesity_Subset_Tutorial.ipynb`) **containing instructions** for how to create the obesity subset from the public dataset using Python.
- **Two visual maps** comparing obesity rates across the United States in 2013 vs. 2023, created with [Tableau](https://www.tableau.com/).
## Purpose and Potential Usage
The obesity subset data waas used to compare obesity rates across the U.S. a decade apart, in 2013 and 2023. Although an in-depth analysis of the subet data has not yet been conducted, the visuals seem to display an unfavorable trend, with many states reporting higher obesity rates in 2023 than in 2013. 

This data could be used by nutritionists, health professionals, and policy makers to promote efforts to improve the diets of Americans.

Additionally, the [Nutrition, Physical Activity, and Obesity public dataset](https://catalog.data.gov/dataset/nutrition-physical-activity-and-obesity-behavioral-risk-factor-surveillance-system) is intended for public use and contains much potential for exploration and analysis. Subsets could be created for **other decades or timeframes**, for **individual states**, or for **nutrition** or **amount of daily exercise**. All of these would contribute to a better understanding of the physical health of Americans in recent years, and could provide valuable insights for the future.
### Getting Started
To recreate the obesity subset or use the data to create your own, open the Colab Notebook and follow the instructions as described.
> **Note:** If you choose not to download the full 34 MB dataset from [Data.gov](https://catalog.data.gov/dataset/nutrition-physical-activity-and-obesity-behavioral-risk-factor-surveillance-system), make sure to replace references to `Nutrition__Physical_Activity__and_Obesity_-_Behaavioral_Risk_Factor_Surveillance_System.csv` with `Nutrition_Physical_Activity_and_Obesity_Part_1.csv` (included in this repo).
## Data Visualization
The visual maps below were created with the obesity subset in [Tableau](https://www.tableau.com/).
The greener shades indicate percentages of obese adults closer to 5%, while redder shades indicate percentages closer to 30%.

![Map of young adult obesity rates in 2013](https://github.com/makayla-ma/Obesity_US/blob/main/Visuals/2013.png "2013 Visual")
![Map of young adult obesity rates in 2023](https://github.com/makayla-ma/Obesity_US/blob/main/Visuals/2023.png "2023 Visual")

**Note:** Obesity percentages for young adults in 2023 were not reported for Pennsylvania or Kentucky in 2023, so their data values have been excluded from the 2023 visual.
## Contact
- For questions about Python, please consult the web.
- For questions or suggestions about this data repository, please contact the maintainer at [mzm@unc.edu](mzm@unc.edu).
- Future contributors are welcome--feel free to suggest improvements!
