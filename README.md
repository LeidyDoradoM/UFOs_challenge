# UFO Sightings Website

During this week project, we have been working on developing an **Unidentified Flying Objects (UFOs)** sightings webpage.  The website shows a table listing several sighting events registered around the world. The table is dynamic such that the user is able to filter table output based on the date in which the sighting ocurred.

## Overview of the Project:

Now, we want to update our website adding multiple filters that allow the user to display only the sightings that meet the specific search citeria. This means that only events that meet the criteria are displayed in the table. The filtering criteria consider: *Date, City, State, Country* and *Shape*.

## Results:

The design and styling of the website was made by using JavaScript and HTML. JavaScript file `app.js` creates a table displaying all the information stored in `data.js`. HTML file `index.html` uses bootstrap as the template of the website, and uses five text boxes as the interface with the user to receive the information to filtering the table data. Figures 1 and 2 show a first view of the website, without any filter be applied to the data. Figure 2 show all recorded events in the table and the filtering input boxes that are empty. 

<img width="100%" src="https://raw.githubusercontent.com/LeidyDoradoM/UFOs_challenge/main/Images/UFOsightings1.png">
Figure1: General Overview of the UFO sightings Website.

<img width="100%" src="https://raw.githubusercontent.com/LeidyDoradoM/UFOs_challenge/main/Images/UFOsightingsFilters.png">
Figure 2: Website area where the five filters are display.

Once the user makes any entry in one of the filtering inputs, the information that is displayed in the table is updated by the function `updateFilters()` in  the *`app.js`* file.  Then, the table only shows the sighting events that meet the condition. Figure 3 shows the case for one filter. First the search criterion is put on the box, then the key Enter is hit and the table is updated.

<img width="100%" src="https://raw.githubusercontent.com/LeidyDoradoM/UFOs_challenge/main/Images/DateFilter.png">
Figure 3: Searching using only a specific date as filter.

The filtering process could be repeated as long as different criteria need to be used.  Each time a new criteria is added, the key Enter is hit and the table only shows the entries that meet the criteria. Below figures show this process at different stages where one at one, each filter is added.

<img width="80%" src="https://raw.githubusercontent.com/LeidyDoradoM/UFOs_challenge/main/Images/dateCountryFilter.png">

<img width="80%" src="https://raw.githubusercontent.com/LeidyDoradoM/UFOs_challenge/main/Images/dateStateCountryFilter.png">

<img width="80%" src="https://raw.githubusercontent.com/LeidyDoradoM/UFOs_challenge/main/Images/dateCountryStateShapeFilter.png">

## Summary:

Our UFOs sightings website is clean, tidy and dynamic. The multiple filtering allows to inspect the data in great detail in an organized way.  However, the searching filtering is limited because is case sensitive such that only lower-case spellings are acepted. 

The searching filtering could be upgraded if some features are added:

1. Allowing for upper and lowercase spelling such that the searching results are exactly a reflect of the presence/not presence of the event that meet the searching criteria.

2. In addition, the multiple filtering could include: a date range to filter sighting events ocurred in between a period of time rather than only one day. For filtering by shape, it could be considered a menu drop button that consider the seven kind of shapes described in the data.  In this way, the searching process could be less sensitive.
