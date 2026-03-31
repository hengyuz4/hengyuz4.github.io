---
layout: page
title: Bigfoot Sightings Visualization
permalink: /hw5/
---

# Bigfoot Sightings Visualization

This project uses the Bigfoot Sightings dataset to explore how reported sightings change over time and how they vary across states.

[The Data](https://raw.githubusercontent.com/UIUC-iSchool-DataViz/is445_data/main/bfro_reports_fall2022.csv){: .btn .btn-primary}
[The Analysis](https://github.com/hengyuz4/hengyuz4.github.io/blob/main/pages/hw5/Workbook.ipynb){: .btn .btn-primary}

## Visualization 1

<iframe src="/assets/hw5/plot1.html" width="100%" height="500" frameborder="0"></iframe>

My first visualization is a line chart showing the number of Bigfoot sighting reports by year. I encoded year on the x-axis as a quantitative variable and the number of sightings on the y-axis as a quantitative variable. I used a line chart with points so the viewer can see both the overall trend and individual yearly values. This plot also includes interactivity through a dropdown menu for classification, which allows the user to compare how different classes of reports change over time. In the notebook, I converted the date column to datetime format, extracted the year, cleaned missing values, and grouped the data by year for plotting.

## Visualization 2

<iframe src="/assets/hw5/plot2.html" width="100%" height="700" frameborder="0"></iframe>

My second visualization is a horizontal bar chart showing the top 20 states by number of Bigfoot sighting reports. I encoded state as a nominal variable on the y-axis and the number of sightings as a quantitative variable on the x-axis. I also used a sequential blue color scale to represent the counts, where darker shades indicate more sightings. This makes it easier to compare the states with the largest numbers of reports. In the notebook, I grouped the cleaned dataset by state, counted the number of reports, sorted the values in descending order, and kept only the top 20 states.

## Interactivity

The interactivity in this project appears in the first visualization. I added a dropdown menu that lets the user choose a report classification such as Class A, Class B, or Class C. This makes the visualization more useful because it allows the user to compare trends for different types of reports instead of only seeing the full dataset at once. It also makes the chart more interesting by showing that different classes of sightings may have different patterns over time.
