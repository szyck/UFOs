# UFOs
## Overview

The purpose of this project is to display data in a table on UFO observations, filtering by multiple criteria. These criteria are state, country, date, and shape. The website also displays titles and an informational testimonial from a known Ufologist.

## Results

Upon loading the website, the unfiltered UFO data is displayed to a table. 

![Unfiltered Table](UFOS/static/images/unfilteredimage.PNG)

Adding a filter to one of the boxes causes the updateFilter function to run and initialize the filter into an array. The function then calls the filterTable function to apply the new filter to the data and assemble the new table.

![Filtered Table](UFOS/static/images/filteredimage.PNG)

## Summary
