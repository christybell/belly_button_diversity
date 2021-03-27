# Plotly & Belly Button Diversity
<img src="static/images/belly_button_readme_header.jpg" width="1000" height="300">

## Project Overview
The belly button is one of the habitats closest to us, and yet it remains relatively unexplored. That was until scientists at North Carolina State University launched the Belly Button Biodiversity (BBB) Project in 2011 to investigate the microbes inhabiting our navels. They collected samples from volunteers throughout the United States and extracted the DNA from microbes in each sample that eventually provided them with lists of species (and their relative abundances) for each belly button. They also explored factors thay may influence the microscropic life that call this often overlooked, moist patch of skin home. In this project, I've used the researcher's findings and the power of JavaScript to create data visualizations that are attractive, accessible, and interactive. I used Plotly, a JavaScript data visualization library, which offers interactivity and can help an audience understand the BBB data and draw the same conclusions as the scientists. Finally, I've deployed a polished and engaging dashboard to the web. I just may not be able to look at belly buttons the same every again!

## Resources
- **Data Sources**: `samples.json` file
- **Software and Tools**: JavaScript, HTML/CSS, Bootstrap, VS Code & Git Bash

## Challenge Deliverables and Results

### Deliverable 1: Create the `buildCharts` function and Bar Chart

<img src="static/images/Delv 1_buildCharts function.PNG">

<img src="static/images/Delv 1_bar chart js.PNG">

When the `charts.js` file runs, the bar chart is added to the dashboard:

<img src="static/images/Delv 1_bar chart.PNG">


### Deliverable 2: Create the Bubble Chart

<img src="static/images/Delv 2_bubble chart js.PNG">

When the `charts.js` file runs, the bubble chart is added to the dashboard:

<img src="static/images/Delv 2_bubble chart.PNG">


### Deliverable 3: Create the Gauge Chart

<img src="static/images/Delv 3_gauge chart js.PNG">

When the `charts.js` file runs, the gauge chart is added to the dashboard:

<img src="static/images/Delv 3_gauge chart.PNG">


### Deliverable 4: Customize the Dashboard
I made several customizations to the webpage:
- I added an image to the jumbotron.
- I added a background color to the dashboard and customized compatible colors for the charts.
- I made changes to the header font to make it more noticeable and visually appealing.
- I added more information about the project as a paragraph on the page.

When the dashboard is first opened in a browser, ID 940's data is displayed with all 3 charts. Then, when a user selects a sample, the dashboard displays the new data in the panel and all three charts are updated. 

The dashboard looks like this:

<img src="static/images/Delv 4_BBB Dashboard.PNG">
