# UFOs
Javascript Project for Data Visualization

## Overview of the analysis:
For this project a webpage is created to display UFO sightings information that can be filtered according to the user's criteria.

### Objective
* Generate a dynamic table that takes multiple criteria at the same time to showcase UFO sightings information. 

## Results:

To filter the data a function was created to keep track of all the filters, in that way filters for each of the following elements could be used:

* Date: Enter the date in the following format mm/dd/yyyy to display the sightings from a specific day.
* City: Enter the name of a specific city to narrow the results further. The search is cap sensitive so the city name must be entered in lowercase. 
* State: Enter the state two letter abbreviation code to limit the search to a state.
* Country: Enter the state two letter abbreviation code to limit the search to a state.
* Shape: Enter a specific shape like sphere, fireball, or disk to reduce the search to a specific alien pattern.

Search Example:
1. Table without filters.

![1](https://github.com/Li11iana/UFOs/blob/main/resources/1.png)

2. Reducing the search by date. Showing results only for January 1st, 2010 (1/1/2010).

![2](https://github.com/Li11iana/UFOs/blob/main/resources/2.png)

3. Applying the filter only to sightings in California. The following image shows results for January 1st, 2010, in California only.

![3](https://github.com/Li11iana/UFOs/blob/main/resources/3.png)

## Summary:

The website displays information concisely that adapts to the users interests and that could be used with larger datasets.

### Drawbacks
*	Currently the data set used only contains a limited amount of information, thus some of the filters do not provide any visualization improvements such as the "country" filter, since all entries correspond to the US.
*	The cap sensitivity of the filters could make the user experience frustrating for users used to more flexibility.


### Recommendations
*	As mentioned above, it would be beneficial to increase the variety of the dataset used this could show more information about UFOs sightings.
*	Adding links to articles or more information about each sighting would add more valuable details and potentially more sources for research.

