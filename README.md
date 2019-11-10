## An Analysis of Walkability in Mumbai

#### Introduction
Walkability is the ability of a citizen to walk around to amenities like schools and restaurants without taking a car. Walkability is a very important element in good urban design. It has especially become relevant today in countries like India. Roads in our cities have reached their limits in terms of the volume of traffic they can handle. The only way to inhabit more people into our cities while keeping them livable is to make them more walkable.

#### Why Mumbai?
The commercial capital of India, Mumbai has seen a massive growth in the recent decades. The subsequent rise in population has led to extremely overcrowded suburban railways and jam packed roads. This has adversely affected the livability of the city and the overall quality of lives of its citizens. It becomes very important in such a scenario to have the ability to bypass these burgeoning modes of transport and simply access day to day amenities by walking to them.
In this project, we visualize the walkability in Mumbai for 3 common amenities, restaurants, schools and bars. We believe that accessibility to these amenities is important for families, kids and bachelors in that order, this narrowly covers walkability for major categories of citizens.

#### Data Sources and tools used
This project was originally developed at Berkeley to visualize walkability in the Bay Area. We have adapted their work for Mumbai. Also we have updated the code to use python3 and pandana 0.4
The data for this work is obtained from open street maps. It is an open source, community curated map. We use the pandana library to access this data. Also the pandana library internally uses the osm overpass API.

#### Running this project
You can clone the entire project or just the jupyter notebook 'Visualizing Walkability in Mumbai.ipynb'. Rest of the files can be generated as you run the code in the notebook.

#### Our Findings
We start by visualizing overall walkability i.e. the combined walkability to all the 3 selected amenities, schools, bars and restaurants.
<p float="left" align="center">
  <img src="https://raw.githubusercontent.com/SusmeetJain/walkable_Mumbai/master/images/accessibility-all-Mumbai.png" width="300" />
  <img src="https://raw.githubusercontent.com/SusmeetJain/walkable_Mumbai/master/images/accessibility-all-5th-Mumbai.png" width="300" /> 
</p>
The first figure on the left visualizes your ability to walk to the nearest amenity. While the second figure on the right represents accessibility to the 5th nearest amenity, which is a more useful visualization, you should have accessibility to more than one amenity to be able to not have a car and just walk around. And clearly such areas are limited. You can see areas that are shining green, this is where you would want to be in Mumbai if you are not fond of long hours spent in traffic jams on roads.
