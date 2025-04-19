# belly-button-challenge

# MODULE 14: Belly Button Biodiversity Dashboard

### by Patricia Daher

## Overview
This project involves building an interactive dashboard to explore the Belly Button Biodiversity dataset, which catalogs the microbes that colonize human navels. The data reveals that only a few microbial species are common across individuals, while the rest are relatively rare.

## Features
- Interactive Bar Chart: Displays the top 10 OTUs found in a selected individual
- Bubble Chart: Visualizes all OTUs with customizable markers
- Demographic Information Panel: Shows metadata for the selected individual
- Dynamic Updates: All visualizations update when a new sample is selected

## Project Structure

belly-button-challenge/
├── index.html          # Main dashboard page
├── app.js              # Main JavaScript application
├── samples.json        # Sample data (for reference)
├── README.md  
└── LICENSE 

## Accessing the Visualization website:
Click the following link:
https://patriciadaher.github.io/belly-button-challenge/

## Major 3 components: 
### 1- Horizontal Bar Chart
1- Displays the top 10 OTUs (Operational Taxonomic Units) for the selected individual.
2- Uses sample_values for the bar length.
3- Uses otu_ids for the labels.
4- Uses otu_labels for hover text.

### Bubble Chart
1- Visualizes all OTUs in the sample.
2- X-axis: otu_ids
3- Y-axis: sample_values
4- Marker size: sample_values
5- Marker color: otu_ids
6- Hover text: otu_labels

### Metadata Panel
1- Displays demographic info (e.g., ethnicity, gender, age, location, etc.) of the selected individual.
2- Automatically updates with sample selection.

## Technologies Used
- JavaScript (ES6+)
- D3.js (for loading and manipulating JSON data)
- Plotly.js (for charting)
- HTML/CSS
- GitHub Pages (for deployment)
- Deep Seek
- Chat Gbt

## Acknowledgements / references
This project was completed as part of the Data Analytics Bootcamp curriculum. 
Starter codes and json file was provided by the instructional team.

## License
GNU General Public License.
This project is for educational purposes only.
