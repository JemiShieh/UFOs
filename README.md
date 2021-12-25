# UFOs Analysis

## UFOs Analysis Overview
Use JavaScript, HTML and CSS to create a custom webpage that showcases different UFO sightings around the world. Build a fully dynamic table to filter and organize UFO sightings data stored as a JavaScript array, using JavaScript as the primary coding language. Place the table into an HTML file for easy viewing, and customize the webpage using Bootstrap.

## UFOs Analysis Resources

* Data Source: data.js
* Software: Visual Studio Code 1.63.0, Chrome DevTools
* Languages: JavaScript, HTML, CSS

## UFOs Analysis Results
This table is fully dynamic and reactive to user input, with several fully functional filters that allow users to interact with the visualization and filter data based on multiple search criteria simultaneously including Date, City, State, Country, and Shape. Users simply enter their filter search criteria by following the prompts in the input boxes in the Filter Search section, with the table updating after pressing “Enter”. The Filter Search is cleared and the full original table is restored upon clicking UFO Sightings in the Navigation Bar at the top of the webpage. Please refer to the images below for a step-by-step multi-criteria search for triangle-shaped UFO sightings in Massachusetts on 1/10/2010:
* Default View	

* Step 1: Enter Date: 1/10/2010

* Step 2: Enter State: ma

* Step 3: Enter Shape: triangle

* Step 4: Click UFO Sightings in Navigation Bar to reset

## UFOs Analysis Summary
Drawbacks of this webpage design:
* Because JavaScript is case-sensitive, and all of the data is stored in lower case, any user input entered in capital letters, such as the city or state abbreviation, would not return any filter search results. 
* Lack of user input dropdown menu
* Inability to filter search by multiple values with the same ID, e.g. multiples cities or states
* Inability to sort filter search results
* Data set is limited to 13 dates

Additional recommendations for further development:
* Remove user input case-sensitivity
* Drop down menus for user input
* Ability to filter search by multiple values with the same ID, e.g. multiples cities or states
* Ability to sort filter search results in ascending/descending order by column
* Expand data set beyond 13 dates 

