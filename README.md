# Belly Button Biodiversity

## Project Overview

The goal of this project was to use JavaScript and Plotly to create an interactive dashboard to explore the [Belly Button Biodiversity dataset](data/samples.json), which catalogs the microbes that colonize human navels.

## Technologies Used

- JavaScript
- HTML
- CSS
- Bootstrap
- D3.js
- Plotly.js

![](images/dashboard.png)

## Dashboard

### Dropdown Menu

An interactive dropdown menu which displays a complete list of test subject ID numbers and allows the user to choose which test subject data to view. 

### Horizontal Bar Chart

A horizontal bar chart with a dropdown menu to display the top 10 OTUs found in each individual.

Features:

- Used sample_values as the values for the bar chart.

- Used otu_ids as the labels for the bar chart.

- Used otu_labels as the hovertext for the chart.

### Bubble Chart

A bubble chart that displays each sample.

Features:

- Used otu_ids for the x values.

- Used sample_values for the y values.

- Use sample_values for the marker size.

- Use otu_ids for the marker colors.

- Use otu_labels for the text values.




