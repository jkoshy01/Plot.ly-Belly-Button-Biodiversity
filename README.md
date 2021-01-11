# Plot.ly-Belly-Button-Biodiversity


Plot.ly Homework - Belly Button Biodiversity

In this Homework assignment, you will need to build an interactive dashboard to explore the Belly Button Biodiversity dataset, which catalogs the microbes that colonize human navels.

In this dataset reveals that a small handful of microbial species (also called operational taxonomic units, or OTUs, in the study) were present in more than 70% of people, while the rest were relatively rare.




Step 1: Plotly


First Use the D3 library to read in samples.json.


Then you will create a horizontal bar chart with a dropdown menu to display the top 10 OTUs found in that individual.




Use the sample_values as the values for the bar chart.


Then Use otu_ids as the labels for the bar chart.


Use the otu_labels as the hovertext for the chart.




You will need to create a bubble chart that displays each sample.



Then you will use the otu_ids for the x values.


Use the sample_values for the y values.


Use the sample_values for the marker size.


Use the  otu_ids for the marker colors.


Use the otu_labels for the text values.








Then Display the sample metadata, i.e., an individual's demographic information.


Display each key-value pair from the metadata JSON object somewhere on the page.




Update all of the plots any time that a new sample is selected.




Additionally, you are welcome to create any layout that you would like for your dashboard. An example dashboard is shown below:












Advanced Challenge Assignment (Optional)

The following task is advanced and therefore optional.


Adapt the Gauge Chart from https://plot.ly/javascript/gauge-charts/ to plot the weekly washing frequency of the individual.



You will need to modify the example gauge code to account for values ranging from 0 through 9.




Update the chart whenever a new sample is set and change it.






