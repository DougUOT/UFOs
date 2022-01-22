# UFOs
Use JavaScript, HTML, and CSS to create a custom webpage that showcases different UFO sightings around the world

## Overview of Project

This project will build a dynamic webpage by inserting JavaScript into an HTML page to display the data related to the UFO sighting information. The available database that we will work on in this project includes countries, cities, states, dates and other information related to UFO sightings. We will also draw on our knowledge of CSS and Bootstrap and explore some Chrome dev tools to test our code as we go. We will start by building a table to hold and neatly display the data we want to work with. Then we will add filters for that table which lets users refine their search on more than one level. Our table will be inserted into and styled the entire page. We will also include an attention-grabbing header an article summary. This assignment is related to the Bootcamp Data Analytics from the University of Toronto.

For data analysis, we will use the database file available called [data.js](https://github.com/DougUOT/UFOs/blob/main/static/js/data.js), 

Follow below the goals for this module:

1) Filter UFO sightings on multiple criteria
2) A written report on the UFO analysis

## Resources

* Data Source: [index.html](https://github.com/DougUOT/UFOs/blob/main/index.html), [app.js](https://github.com/DougUOT/UFOs/blob/main/static/js/app.js) and [style.css](https://github.com/DougUOT/UFOs/blob/main/static/css/style.css)
* Data Tools and Software: Visual Studio Code 1.63.2, Bootstrap 4, Jupyter Notebook 6.4.6, Javascript ES6, CSS, HTML and Chrome Browser Version 97.0.4692.71 (Official Build) (64-bit)

## Results

## Objetive 1: Filter UFO sightings on multiple criteria

### The list element that creates the button is removed, and there are five list elements for filtering in the index.html file

![](https://github.com/DougUOT/UFOs/blob/main/Resources/Images/Capture_UFO_1.PNG)
![](https://github.com/DougUOT/UFOs/blob/main/Resources/Images/Capture_UFO_1_2.PNG)

### The event listener is modified to detect changes to each filter in the app.js file

![](https://github.com/DougUOT/UFOs/blob/main/Resources/Images/Capture_UFO_1_3.PNG)

### The updateFilters() function saves the element, value, and the id of the filter that was changed

![](https://github.com/DougUOT/UFOs/blob/main/Resources/Images/Capture_UFO_1_3_1.PNG)

### The filterTable() function loops through all of the filters and keeps any data that matches the filter values

![](https://github.com/DougUOT/UFOs/blob/main/Resources/Images/Capture_UFO_1_4.PNG)

### The webpage filters the table correctly based on user input

![](https://github.com/DougUOT/UFOs/blob/main/Resources/Images/Capture_UFO_1_5.PNG)

## A written report on the UFO analysis

See below the UFO Sightings website, allowing the user to search for different types of field, with the result being displayed in the table in an organized way.

![](https://github.com/DougUOT/UFOs/blob/main/Resources/Images/Capture_UFO_2.PNG)

A filter feature has been added, allowing the user to get a more accurate result. Below is an example, selecting the UFO sightings related to bonita city. 

![](https://github.com/DougUOT/UFOs/blob/main/Resources/Images/Capture_UFO_2_1.PNG)

In addition to being able to filter for more accurate results, we added a field to clear the search, returning it to the original format with all the information being displayed from the website. 

![](https://github.com/DougUOT/UFOs/blob/main/Resources/Images/Capture_UFO_2_2.PNG)
![](https://github.com/DougUOT/UFOs/blob/main/Resources/Images/Capture_UFO_2_3.PNG)

## Summary

As a final result, we have a webpage connecting to the database with UFO sighting information, and displaying it in an orderly table by date, city, state, country, shape, duration and comments. In addition, we have added additional features to filter or clear table results.

In the future, as a recommendation to improve this project, new features may be added suc as a search field. 




