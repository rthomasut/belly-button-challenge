# Belly Button Biodiversity Dashboard

## View Data
The data for the project can be viewed at the following location.
https://rthomasut.github.io/belly-button-challenge/

## Background

In this assignment, you will build an interactive dashboard to explore the Belly Button Biodiversity dataset, which catalogs the microbes that colonize human navels. The dataset reveals that a small handful of microbial species (also called operational taxonomic units, or OTUs) were present in more than 70% of people, while the rest were relatively rare.

### Bar Chart

1. Use the D3 library to read in **samples.json** from the URL https://2u-data-curriculum-team.s3.amazonaws.com/dataviz-classroom/v1.1/14-Interactive-Web-Visualizations/02-Homework/samples.json.
2. Create a horizontal bar chart with a dropdown menu to display the top 10 OTUs found in that individual.
3. Use **sample_values** as the values for the bar chart.
4. Use **otu_ids** as the labels for the bar chart.
5. Use **otu_labels** as the hovertext for the chart.

### Bubble Chart

1. Create a bubble chart that displays each sample.
2. Use **otu_ids** for the x values.
3. Use **sample_values** for the y values.
4. Use **sample_values** for the marker size.
5. Use **otu_ids** for the marker colors.
6. Use **otu_labels** for the text values.

### Display Sample Metadata and Updates

1. Display the sample metadata, i.e., an individual's demographic information.
2. Display each key-value pair from the metadata JSON object somewhere on the page.
3. Update all the plots when a new sample is selected.

### Advanced Challenge Assignment (Optional)

Adapt the Gauge Chart from [Plotly Gauge Chart](https://plot.ly/javascript/gauge-charts/) to plot the weekly washing frequency of the individual.

- You will need to modify the example gauge code to account for values ranging from 0 through 9.
- Update the chart whenever a new sample is selected.
