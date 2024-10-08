# United States Geological Survey on Earthquake Data

![image](https://github.com/user-attachments/assets/c00e2c1b-aac3-4eb3-9e50-6aa7fd9eaca5)

# Background

The United States Geological Survey, or USGS for short, is responsible for providing scientific data about natural hazards, the health of our ecosystems and environment, and the impacts of climate and land-use change. Their scientists develop new methods and tools to supply timely, relevant, and useful information about the Earth and its processes.

The USGS is interested in building a new set of tools that will allow them to visualize their earthquake data. They collect a massive amount of data from all over the world each day, but they lack a meaningful way of displaying it. In this challenge, I have been tasked with developing a way to visualize USGS data that will allow them to better educate the public and other government organizations (and hopefully secure more funding) on issues facing our planet.

# What I Am Creating

The instructions for this activity are broken into two parts:

Part 1: Create the Earthquake Visualization

Part 2: Gather and Plot More Data

# Instructions
                                  Part 1: Create the Earthquake Visualization
![image](https://github.com/user-attachments/assets/7590d74a-eb6e-4ad0-9cd2-f27fadc5bf25)

My first task is to visualize an earthquake dataset. Complete the following steps:

1. Get my dataset. To do so, follow these steps:

  * The USGS provides earthquake data in a number of different formats, updated every 5 minutes. Visit the USGS GeoJSON Feed (https://earthquake.usgs.gov/earthquakes/feed/v1.0/geojson.php) page and choose a dataset to visualize. The following image is an example screenshot of what appears when you visit this link:

![image](https://github.com/user-attachments/assets/52a85fe7-2e11-4737-a636-12ecb3a99476)

  * When I click a dataset (such as "All Earthquakes from the Past 7 Days"), I will be given a JSON representation of that data. Use the URL of this JSON to pull in the data for the visualization. The following image is a sampling of earthquake data in JSON format:

![image](https://github.com/user-attachments/assets/0508c156-29c5-447a-99ab-d32360c0fd41)

2. Import and visualize the data by doing the following:

  * Using Leaflet, create a map that plots all the earthquakes from your dataset based on their longitude and latitude.

     * My data markers should reflect the magnitude of the earthquake by their size and the depth of the earthquake by color. Earthquakes with higher magnitudes should appear larger, and earthquakes with greater depth should appear darker in color.

     * Hint: The depth of the earth can be found as the third coordinate for each earthquake.


  * Include popups that provide additional information about the earthquake when its associated marker is clicked.

  * Creating a legend that will provide context for my map data.

  * My visualization should look something like the preceding map.

                                  Part 2: Gather and Plot More Data

Plot a second dataset on your map to illustrate the relationship between tectonic plates and seismic activity. I will need to pull in this dataset and visualize it alongside my original data. Data on tectonic plates can be found at https://github.com/fraxen/tectonicplates.

The following image is an example screenshot of what I should produce:

![image](https://github.com/user-attachments/assets/2fd9c93d-0e63-4b1e-8edb-cf04be0aabb1)

Perform the following tasks:

  * Plot the tectonic plates dataset on the map in addition to the earthquakes.

  * Add other base maps to choose from.

  * Put each dataset into separate overlays that can be turned on and off independently.

  * Add layer controls to your map.

# Resources

  * Dataset created by the United States Geological Survey (https://earthquake.usgs.gov/earthquakes/feed/v1.0/geojson.php)
  * JSON HTML (https://www.w3schools.com/Js/js_json_html.asp)
  * JavaScript Tutorial (https://www.w3schools.com/js/)
  * HTML and Javascript (https://www.programiz.com/html/html-and-javascript)
  * JavaScript JSON (https://www.w3schools.com/js/js_json.asp)
  * HTML JavaScript (https://www.w3schools.com/html/html_scripts.asp)
  * Difference between JavaScript and HTML (https://www.geeksforgeeks.org/difference-between-javascript-and-html/)
