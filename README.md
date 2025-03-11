# Belly Button Challenge

## Background 
In this challenge, an interactive dashboard was created to explore the 'Belly Button Biodiversity' dataset, which catalogs the microbes that colonize human navels. The study was taken from "A Jungle in There: Bacteria in Belly Buttons are Highly Diverse, but Predictable" (_Hulcr, 2012_). This study found that belly buttons were a jungle of microbial diversity, having detected over 2300 species in navels. This dataset revealed that a small handful of microbial species (also called operational taxonomic units or OTUs) were present in more than 70% of people. The rest were relatively rare, as the data shows. 

This challenge used skills learned with JavaScript, D3 library, JSON, HTML, and Plotly. 

## Challenge 
### Steps to Complete the Challenge 
1. **Initalize the Dashboard**
- Fetch the data from the provided URL using D3 library and read in _samples.json_. 
- Populate the dropdown menu with sample names. 
- Build the initial charts and metadata panels using the first sample. 

2. **Build the Metadata Panel**
- Filter the metadata for the selected sample. 
- Clear any existing metadata. 
- Append new tags for each key-value pair in the filtered metadata. 

3. **Build the Charts** 
**Bar Charts** 
- Use the top 10 sample values as values. 
- Use the `otu_ids` as the labels. 
- Use `otu_labels` as the tooltip.

**Bubble Chart**
- Use `otu_ids` for the x values.
- Use `otu_ids` for marker colors.
- Use `sample_values` for the y values.
- Use `sample_values` for the marker size.
- Use `otu_labels` for text values.

4. **Update the Dashboard**
- Create an event listener for the dropdown menu. 
- Update the charts and metadata panel when a new sample is selected. 

## Results
Below is a screenshot taken of the HTML created website of the Belly Button Biodversity, showing a random sample with the bar chart and the bubble chart. 

![alt text](https://github.com/maddieemihle/belly-button-challenge/blob/main/html_dashboard.png?raw=true) 

## Methods Used 
* JavaScript 
* Plotly 
* D3 
* HTML 
* JSON 


## Software Used 
* Visual Studio Code 

## References
- [D3.js Documentation](https://d3js.org/)
- [Plotly.js Documentation](https://plotly.com/javascript/)
- [Belly Button Biodiversity Dataset](https://static.bc-edx.com/data/dl-1-2/m14/lms/starter/samples.json)
- Hulcr, J. et al. (2012) A Jungle in There: Bacteria in Belly Buttons are Highly Diverse, but Predictable. Retrieved from: http://robdunnlab.com/projects/belly-button-biodiversity/results-and-data/ 