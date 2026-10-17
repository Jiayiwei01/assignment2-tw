# assignment2-tw
This assignment will teach you how to use GitHub Desktop and GitHub to make your data analysis work reproducible and collaborative. You will go through the full workflow — creating a repository, tracking changes, branching, pull requests, and documenting your project.

# Penguins Data Analysis
## 1.The Dataset
This project uses the Penguins dataset, stored in `penguins.csv`. The dataset contains 344 observations and 8 variables, including species, island, bill measurements, flipper length, body mass, sex, and year.

## 2.Analysis Script
The analysis is conducted using `penguins_analysis.R`. The script first loads the dataset, generates summary statistics, counts penguins by species, and then calculates the percentage of each species, and compares average body mass across species. Here are some basic summary statistics about the dataset:
- Mean bill length: 43.92 mm
- Mean bill depth: 17.15 mm
- Mean flipper length: 200.9 mm
- Mean body mass: approximately 4,202 g
- Body mass range: 2,700–6,300 g

## 3.How to Reproduce the Analysis
The analysis uses base R functions and does not require additional packages.
1. Download or clone this repository to your local computer.
2. Open `penguins_analysis.R`(the R script containing the analysis) in RStudio by selecting *File → Open File* in the menu.
3. Make sure `penguins.csv`(the original dataset) is in the same folder as the script.
4. Set the working directory by using *setwd()* to the repository folder.
5. Run the script from beginning to end.
6. Check the output files:
- `species_counts.csv`: Counts and percentages by species.
- `average_body_mass.csv`: Average body mass by species.

