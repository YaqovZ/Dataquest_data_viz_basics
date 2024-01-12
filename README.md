# Traffic Analysis on I-94 Interstate Highway

## Introduction
This repository contains the Jupyter notebook for an analytical project focused on identifying heavy traffic indicators on the I-94 Interstate highway. The primary goal of this analysis is to uncover patterns and factors that contribute to increased traffic, particularly in the westbound direction.
It is a project completed with partial guidance of the coding platform Dataquest as part of my learning.
## Data Source
The dataset used in this project is available for download from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/492/metro+interstate+traffic+volume). It was made available by John Hogue and includes detailed traffic information on the I-94 Interstate highway.

## Analysis Objective
The analysis aims to identify indicators of heavy traffic on I-94. These indicators are categorized into:

- **Time indicators**: Variations in traffic volume based on months, days of the week, and specific times during a day.
- **Weather indicators**: The impact of different weather conditions on traffic volume, such as snow, rain, or thunderstorms.

## Technologies Used
The following technologies and libraries are utilized in this analysis:
- Python: For overall programming and data manipulation.
- Pandas: For handling and analyzing data.
- Matplotlib and Seaborn: For data visualization and creating informative charts.

## Key Findings
Through our analysis, we have identified several key indicators of heavy traffic on the I-94 highway:
- **Time Indicators**: Traffic tends to be heavier during warm months (March–October) and on business days, with rush hours peaking around 7 AM and 4 PM.
- **Weather Indicators**: Weather conditions like shower snow, light rain, and snow, as well as proximity thunderstorms with drizzle, are associated with increased traffic volumes.

## Usage
The notebook `Metro_Interstate_Traffic.ipynb` within this repository provides a comprehensive analysis workflow, demonstrating how to:
- Visualize time series data with line plots.
- Explore correlations using scatter plots.
- Analyze frequency distributions with bar plots and histograms.
- Enhance exploratory data visualization with the pandas library.
- Compare multiple graphs using grid charts.

## Note
It's important to note that the dataset and hence the analysis only cover the westbound traffic recorded at a station located between Minneapolis and Saint Paul. The findings are specific to this section of the I-94 Interstate highway and should not be generalized for the entire highway.
