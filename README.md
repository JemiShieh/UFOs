# UFOs Analysis

## UFOs Analysis Overview
Use JavaScript, HTML and CSS to create a custom webpage that showcases different UFO sightings around the world. Build a fully dynamic table to filter and organize UFO sightings data stored as a JavaScript array, using JavaScript as the primary coding language. Place the table into an HTML file for easy viewing, and customize the webpage using Bootstrap.

## UFOs Analysis Resources

* Data Source: data.js
* Software: Visual Studio Code 1.63.0, Chrome DevTools, Bootstrap 4.0.0
* Languages: JavaScript, HTML, CSS

## UFOs Analysis Results
This table is fully dynamic and reactive to user input, with several fully functional filters that allow users to interact with the visualization and filter data based on multiple search criteria simultaneously including Date, City, State, Country, and Shape. Users simply enter their filter search criteria by following the prompts in the input boxes in the Filter Search section, with the table updating after pressing “Enter”. The Filter Search is cleared and the full original table is restored upon clicking UFO Sightings in the Navigation Bar at the top of the webpage. Please refer to the images below for a step-by-step multi-criteria search for triangle-shaped UFO sightings in Massachusetts on 1/10/2010:

* Default View
![Screenshot (33)](https://user-images.githubusercontent.com/92612370/147378576-89cfba16-4e19-4230-ac50-b90592b5443d.png)

* Step 1: Enter Date: 1/10/2010
![Screenshot (34)](https://user-images.githubusercontent.com/92612370/147378582-07a9606c-e869-4b77-9125-e9116d187838.png)

* Step 2: Enter State: ma
![Screenshot (35)](https://user-images.githubusercontent.com/92612370/147378586-1c78eb74-2ec8-4566-967b-9903c6c8c8d6.png)

* Step 3: Enter Shape: triangle
![Screenshot (36)](https://user-images.githubusercontent.com/92612370/147378589-bbfb8299-a026-468f-a66c-8c6e9c1d06f5.png)

* Step 4: Click UFO Sightings in Navigation Bar to reset table
![Screenshot (33)](https://user-images.githubusercontent.com/92612370/147378599-48eeed88-ea09-47a4-9b8d-07cc23b4a215.png)

## UFOs Analysis Summary
Drawbacks of this webpage design:
* Because JavaScript is case-sensitive, and all of the data is stored in lowercase, any user input entered in uppercase letters, such as the city or state abbreviation, would not return any filter search results. 
* Lack of user input drop-down menus
* Inability to filter search by multiple values with the same ID, e.g. multiple cities or states
* Inability to sort filter search results
* Data set is limited to 13 dates

Additional recommendations for further development:
* Remove user input case-sensitivity
* Add drop-down menus for user input
* Ability to filter search by multiple values with the same ID, e.g. multiple cities or states
* Ability to sort filter search results in ascending/descending order by column
* Expand data set beyond 13 dates 

