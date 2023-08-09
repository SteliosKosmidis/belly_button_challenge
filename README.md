# belly_button_challenge

Module 14 Challenge - Build Interactive Dashboard using d3, plotly and leaflet libraries in javascript

Background:
In this assignment involved analysis of the Belly Button Biodiversity datasets in json, which catalogs the microbes that colonize human navels and then using those data to build interactive dashboard for each sample.
The dataset reveals that a small handful of microbial species (also called operational taxonomic units, or OTUs, in the study) were present in more than 70% of people, while the rest were relatively rare.
Deliverables involved:
app.js(javascript code for creating plots and charts and logic for populating dashboard)
sample.json
index.html(for interactive dashboard)
Analysis via dashboard
The habitat conditions of the belly button may explain why we generally find some microbial species to be more common than others in the navel, but we'll see in the interactive graphic below, there is an extraordinary amount of variation among individuals. Some people have belly buttons dominated by one or two species whereas others have more even representation by handfuls of species.

OTUs - a measure used in this analysis signify relative abundance of different microbial “species” , each having unique ids.

As you select each Test Subject ID/sample(volunteers who participated), the panel will display the correspondong demographic info, while the 3 differents charts display the divsersity results for the same sample.
Instructions
Complete the following steps:

Use the D3 library to read in samples.json from the URL https://2u-data-curriculum-team.s3.amazonaws.com/dataviz-classroom/v1.1/14-Interactive-Web-Visualizations/02-Homework/samples.json.

Create a horizontal bar chart with a dropdown menu to display the top 10 OTUs found in that individual.

Use sample_values as the values for the bar chart.

Use otu_ids as the labels for the bar chart.

Use otu_labels as the hovertext for the chart.


![newplot (1)](https://github.com/SteliosKosmidis/belly_button_challenge/assets/125541671/10dca5ea-dd41-4178-9023-17dd4ce4f332)
Create a bubble chart that displays each sample.

Use otu_ids for the x values.

Use sample_values for the y values.

Use sample_values for the marker size.

Use otu_ids for the marker colors.

Use otu_labels for the text values.
![newplot (2)](https://github.com/SteliosKosmidis/belly_button_challenge/assets/125541671/bb034576-cb39-4726-a28b-568587f97533)
![newplot (3)](https://github.com/SteliosKosmidis/belly_button_challenge/assets/125541671/fcdd37c1-841e-4a39-9a02-4caf25f2d575)
Display the sample metadata, i.e., an individual's demographic information.

Display each key-value pair from the metadata JSON object somewhere on the page.

hw

Update all the plots when a new sample is selected. Additionally, you are welcome to create any layout that you would like for your dashboard. An example dashboard is shown as follows:

hw

Deploy your app to a free static page hosting service, such as GitHub Pages. Submit the links to your deployment and your GitHub repo. Ensure that your repository has regular commits and a thorough README.md file

Advanced Challenge Assignment (Optional with no extra points earning)
The following task is advanced and therefore optional.

Adapt the Gauge Chart from https://plot.ly/javascript/gauge-charts/Links to an external site. to plot the weekly washing frequency of the individual.

You will need to modify the example gauge code to account for values ranging from 0 through 9.

Update the chart whenever a new sample is selected.


references:
https://www.tutorialsteacher.com/d3js/method-chaining-in-d3js
https://stackoverflow.com/questions/64994341/gauge-needle-for-plotly-indicator-graph
https://plotly.com/javascript/bubble-charts/
https://www.tutorialsteacher.com/d3js/dom-manipulation-using-d3js
Module 14 activities and class examples
