<h1> Climate-change-impact-on-agriculture </h1>

This project explores the impact of climate change on agricultural productivity across multiple countries from 1991 to 2024. By leveraging data visualization techniques in R, we analyze key climate variables such as temperature, CO2 emissions and precipitation and their relationships with crop yields and adaptation strategies. This project provides valuable insights into the trends, correlations and adaptation efforts across different regions.

<h1> Project Overview </h1>

As climate change accelerates, understanding its effects on agriculture is critical for food security and sustainable development. This project visualizes the historical changes in climate variables and their potential effects on agricultural outcomes. The analysis aims to address the following questions:
    * How have mean temperature, CO2 emissions and precipitation changed over time by country?
    * What is the relationship between CO2 emissions and crop yield?
    * Which adaptation strategies have been used most frequently and how do they vary across countries?
    * Can we identify any correlations or trends that may inform future climate adaptation policies?

The dataset used includes climate and agricultural data spanning from 1991 to 2024 and can be obtained from kaggle.com. 

<h1> Visualization and Analyses </h1>

Ths project consists of the following visualizatiions:
    1. Mean temperature change over time by country: A line graph showing how the average temperature has changed in each country.
    2. CO2 emissions change over time by country: A line graph visualizing CO2 emissions trends by country over the years.
    3. Crop yield change over time by country: A line graph illustrating the change in crop yield in each country. 
    4. Mean precipitation over time by country: A graph showing how precipitation levels have fluctuated by country.
    5. CO2 emissions vs. crop yield correlation: A scatter plot with a regression line exploring the potential relationship between CO2 emission and crop            yield.
    6. Wordcloud of adaptation strategies: A wordcloud displaying the most commonly used adaptation strategies across the dataset.

<h1> Repository structure </h1>

This repository contains the following key files: 
    * climate_change_impact_on_agriculture_2024.csv: The dataset used for this project, containing climate and agricultural data. 
    * climate_change_visualizations.R: The R script used to generate the visualizations. 
    * README.md: The document you're currently reading, providing an overview of the project. 

<h1> How to run this project </h1>

1. Clone the repository:
    git clone https://github.com/AshyBB climate-change-agriculture-visualization.git
    cd climate-change-agriculture-visualization
2. Install the required R packages: You will need the following R libraries:
    install. packages(c("tidyverse", "dplyr", "wordcloud", "ggwordcloud", "tm", "RColorBrewer", "readr"))
3. Run the R Script: Open the climate_change_visualizations.R script in RStudio or any R environment, and run it to generate the visualizations. 

<h1>Key Findings</h1>

* Rising Temperatures and CO2 Emissions: Most countries show a steady increase in both temperature and CO2 emissions, signaling ongoing climate change.
* Crop Yield Trends: Crop yields vary significantly across countries, with some regions demonstrating resilience and others experiencing declines.
* Correlations: Preliminary analysis suggests a potential correlation between CO2 emissions and crop yields, though this varies by region and other local factors. 
* Adaptation Strategies: Commonly used adaptation strategies include crop diversification, water management, and the adoption of climate-resilient crop varieties. 

<h1> Future Work </h1>

Potential areas for future improvemnt or research:
    * Perform time-series forecasting to predict future climate impacts on crop yields.
    * Explore other climate variables such as soil quality and irrigation practices. 
    * Develop more advanced models (e.g., machine learning) to predict crop yield outcomes based on climate factors. 

<h1> Contributing </h1>

If you'd like to contribute to this project, feel free to fork the repository and submit a pull request with your proposed changes. All contributions are welcome! 

<h1> Licence </h1> 

This project is licensed under the MIT License - see the LICENSE file for details.
