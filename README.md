# Evaluating-iNaturalist-Data
# Purpose
  iNaturalist is an application designed to log observations of plant and animal species around the world. The application was launched in 2008 by the California Academy of Sciences in collaboration with National Geographic. In its fifteen years of operation the application has logged over 129 million observations or data points and it is time to evaluate how we can use this data. This project was an evaluation of the collected iNaturalist data's ability to show major climate change related shifts in species' ranges, behaviors, and populations. The goal of this evaluation was to see how well the dataset shows trends from reports from the U.S. Geological Survey and Nature Conservancy and what changes could be made to the application to improve the quality of the data if needed.
 # Data
 The data was collected from the [research grade observation dataset](https://www.gbif.org/dataset/50c9509d-22c7-4a22-a47d-8c48425ef4a7) and filtered down using the following criteria:
 
 ![Screenshot_20230216_071328](https://user-images.githubusercontent.com/124311840/227793567-4078d37e-5342-467b-99fe-e740b491e1fa.png)
The phylum Chordata was selected to create a case study to show climate change related shifts in behaviors and populations of mammals, birds, reptiles, and amphibians. The Appalachian Mountain region was selected as a case study location due to its role as a major wildlife corridor.

All iNaturalist Data is voluntary which has huge implications for the data and the stories that it is able to tell. 
# Analysis
1. How does the application show range shifts for different species? 

As the climate changes in the Appalachian Mountain Region many species have shifted their range northward to be in habitat better suited to their needs. According to an [article from the Nature Conservancy](https://www.nature.org/en-us/what-we-do/our-priorities/protect-water-and-land/land-and-water-stories/climate-resilient-network), species have shifted their range an average of 11 miles north over the past 10 years. In order to evaluate the iNaturalist data to show this change I looked at minimum, maximum, and average latitude for different classes and specific species to see if there was any specific evidence in the data to show this real world trend. 


 2. How well does iNaturalist show behvior shifts for different species in the Appalachian Range?
 
  The American Black Bear served as a case study for this particular question. Similar to the snowshoe hare, the black bear is susceptible to changes in the length of     winter due to their hibernation patterns. Black bears are found throughout the Appalachian Range and their behavior changes can be analyzed using the number of        observations during the winter months when they would typically be hibernating.

3. How well does iNaturalist show Biodiversity in the Appalachian Region? 

According to [States of the Union: Ranking America's Biodiversity](https://www.natureserve.org/sites/default/files/publications/files/stateofunions.pdf), Alabama, Georgia, North Carolina, Virginia, and Tennessee are the top 5 most biodivserse states in the Appalachian Mountain Chain. To test this ranking on the dataset I used a count of species observed for each state. I additionally looked at the distrbution of observations by class. 

4. How well does iNaturalist data show declining amphibian populations in the Appalachian Mountain Region?

 According to the [U.S. Geological Survey](https://www.usgs.gov/faqs/why-are-amphibian-populations-declining), amphibians have been declining at a rate of 3.79% every year. To test this against the dataset I looked at total amphibian observations overtime. I also looked at three species, the wood frog, spotted salamander, and the mole salamander to see how amphibians who rely on vernal pools were impacted. 
 # Findings and Recommendations
 iNaturalist is a powerful application that has engaged thousands of people around the world in citizen science. The data shows great strength in tracking biodivserity and showing seasonal behavioral changes in species like black bears. 
The data lacks integrity when showing population changes and range shifts. This makes sense given the nature of the application. Individuals record observations on voluntary basis and it is by no means representative of the population size or total range distribution of a species. 

In order to collect more reliable data, I suggest making a few small changes to the application. Including a note if a species is spotted at an abnormal time of year or outside of its historical range helps educate the public about climate related changes and insentivises them to keep making observations. In addition, adding a note to encourage individuals to record all instances of a species that they see instead of just one observation could help the population data.
Larger scale resources could also support the reliability of iNaturalist data. Finding ways to partner with colleges, universities, conservation organizations, and Americorps to create data collection internships with an emphasis on amphibians, reptiles, insects, and other classes of underrepresented species in the data with consistent methods of surveying and collection across all 50 states could provide a more reliable database to be supplemented with everyday observations.
 
 
