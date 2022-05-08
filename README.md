# UFO Sightings
_Using dynamic tables to analyze data._


## Overview of the Project

An existing webpage created by a data journalist stores raw data on the web as a table and display information required by a user by accepting a date input and filtering the table to suit the input.
As part of enhancing the capabilites of this webpage, she wants to provide users with additional search criteria like city, state, country and shape that would filter the table at the same time and display the right information. 



## Results
The initial search form was expanded to now include fields for city, state, country and shape. Each field provide keys within the table for search.
A user can simply input his or her search item in the respective field and after pressing the Enter key the table on the page is filtered to display contents that match the search item.
The user can search by just one criteria or a combination to arrive at the desired results.


_Below is an example of the table filtered by state._

![hemisphere_images](https://github.com/emmanuelbrim/Mission-to-Mars/blob/main/Resources/Hemisphere%20images.PNG)


* **Updating Web App with Mars Hemisphere Images and Title**

The updated Mission_to_Mars.ipynb was converted to a python file and exported so that it could be read and cleaned using VSCode.
The original scrape script was then updated with the new code from Mission_to_Mars file so the process to extract hemisphere data would be automated.
To do this a new function was created after mars_facts function to hold the hemisphere code and a new dictionary (hemisphere) was also created in the data dictionary of the scrape_all function to hold the mages and tiles of Mars Hemisphere. 

_Example of the final scrape code_

![Scrape_code 1](https://github.com/emmanuelbrim/Mission-to-Mars/blob/main/Resources/scrape_code%201.PNG)


![Scrape_code 2](https://github.com/emmanuelbrim/Mission-to-Mars/blob/main/Resources/scrape_code%202.PNG)


The index.html file was also updated to reflect the change in the scraping file and retrieve the images and titles was to be displayed. 

![index.html](https://github.com/emmanuelbrim/Mission-to-Mars/blob/main/Resources/index.PNG)


* **Improve Responsiveness and Styling of the Webpage using Bootstrap3 Components.*

The responsiveness of the app was imporved with update to the grid system in the html so the page could be displayed on all platforms and devices.
Finally the appearance of the webpage was also improved by incorporating a background image into the header tag, changing the color of the scrape button and changing the shape of the featured_image to thumbnail.

_Example of the code to style page_

![style](https://github.com/emmanuelbrim/Mission-to-Mars/blob/main/Resources/Background.PNG)


_Example of the code to improve responsiveness_

![Responsive](https://github.com/emmanuelbrim/Mission-to-Mars/blob/main/Resources/Responsiveness.PNG)


## Final Webpage Display
![Web View]()
