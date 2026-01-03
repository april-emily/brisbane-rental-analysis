The Brisbane "Commuter Tax" Analysis

Author: April Williams
Date: December 2025
Status: Complete

Executive Summary

Renters in Brisbane pay a premium for proximity to the CBD, but does the cost of commuting outweigh the rent savings? This project analyses over 6,000 listings to quantify the relationship between Distance and Price.

Key Findings

The "Tax": Rental prices drop significantly as you move away from the CBD, confirming a negative correlation between distance and cost.

The Sweet Spot: Suburbs located 15-20km from the city offer a high-value trade-off between price and accessibility.

Market Anomaly: A cluster of high-priced rentals exists ~30km out (coastal areas), breaking the linear trend and suggesting "lifestyle" factors can override the commuter penalty.

Tools & Libraries

Python 3.10+

Pandas: For data manipulation and cleaning.

Seaborn / Matplotlib: For statistical visualisation and mapping.

NumPy: For mathematical calculations (Haversine formula).

Microsoft Excel: Used for initial data inspection and validation.

VS Code: Development environment.

Project Structure

Brisbane_Rental_Analysis.ipynb: The main Jupyter Notebook containing all code, analysis, and visualisations.

listings.csv: The raw dataset (sourced from Inside Airbnb).

images/: Folder containing exported charts (Heatmap and Regression Plot).

How to Run

Clone this repository.

Install required packages: pip install pandas seaborn matplotlib numpy

Open Brisbane_Rental_Analysis.ipynb in VS Code or Jupyter Lab.

Run all cells to reproduce the analysis.

This project was created as part of a professional portfolio demonstrating end-to-end data analysis skills.
