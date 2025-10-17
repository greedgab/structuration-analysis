# Structuration Analysis Project

## Overview
The Structuration Analysis project aims to analyze various financial strategies using R Markdown. The primary focus is on simulating and visualizing the performance of different investment strategies, including equity, OBPI (Optimal Bond Portfolio Insurance), and CPPI (Constant Proportion Portfolio Insurance).

You can see HTML doc (in french) with the Link 

## Purpose
This project provides insights into how different financial strategies perform under various market conditions. By utilizing simulations, we can better understand the risks and returns associated with each strategy.

## Structure
The project is organized into the following directories:

- **src/**: Contains the R Markdown code for the structuration analysis.
  - `structuration_code.Rmd`: This file includes setup code, simulations, and visualizations related to financial strategies.

- **data/**: Documentation for the datasets used in the project.
  - `README.md`: Explains the datasets, their sources, and how they are utilized in the analysis.

- **results/**: Documentation for the outputs generated from the analysis.
  - `README.md`: Details the results, how to interpret them, and any relevant findings.

- **.gitignore**: Specifies files and directories to be ignored by Git.

## Running the Analysis
To run the analysis, follow these steps:

1. Ensure you have R and RStudio installed on your machine.
2. Install the required R packages, including `tidyverse` and `scales`.
3. Open the `structuration_code.Rmd` file in RStudio.
4. Knit the document to generate the HTML output, which will include the results of the simulations and visualizations.

## Dependencies
- R (version 4.0 or higher)
- RStudio (recommended)
- Required R packages:
  - `tidyverse`
  - `scales`
  - `knitr`
  - `pander`

## Conclusion
This project serves as a comprehensive analysis of financial strategies through simulations. The results can provide valuable insights for investors and financial analysts looking to understand the dynamics of different investment approaches.