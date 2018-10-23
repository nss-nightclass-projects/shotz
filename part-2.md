# The Shotz: Part 2

## Requirements

#### All Movies View
- As a user, I have successfully completed my first movie and am filming a lot more.  I need to update my app to track all of the various locations for all my movies.
- Upon arriving at the homepage, I should see a section of cards with information on my movies (it should display all of them).
- Each movie car should contain the name, genre, estimated release date, description, and the number of shooting locations
- Upon arriving at the homepage, I should see a list of ALL locations that ALL of my movies need, displayed as cards.
- Each location card should show the image, name, address, shoot time, and number of movies that use that location.
- As a user, I should be displayed a search bar. This search bar should filter the results of the cards. On keypress, the text I type in the search bar should be contained in the location title text, the location address, or one of the movie names of all cards still displayed.
- As a user, I should be displayed 4 button options for "time of day." (Options: Morning, Afternoon, Evening, After Dark). These buttons should filter the results down to each location that has a "Time That shot should occur" corresponding to the button clicked.

#### Single Location View
- As a user, when I click on one of the movie cards, the DOM is completely rewritten (as though I am on a new page). This new DOM should have the info for the single movie I clicked on, cards for the locations for the movie I am currently viewing, and a back button.
- If I click on the back button, I should then be viewing "All Locations/movies View"

### Data Structure
- You should have one movies.json, this will be an array of objects representing movies. Each movie will have one key of 'locations' that has a value of an array of location ids.
- You should have one locations.json, this will be an array of objects representing locations. Each location should have an id to relate it to the movie in the step above.
- Movies can have many locations and locations can be associated with many movies.
Sample Movie:

```
{
  "id": "movie1",
  "name": "Super Secret Movie",
  "genre": "Thriller",
  "releaseDate": "10/15/2020",
  "description": "super exclusive can't tell you"
  "locations": [location1, location3, location9]
}

```

Sample Location:
```
{
  "id": "location1",
  "imageUrl": "https://www.roadsideamerica.com/attract/images/ks/KSCAWtwine2.jpg",
  "name": "World's Largest Ball of Twine",
  "address": "719 Wisconsin St, Cawker City, KS 67430",
  "shootTime": "Afternoon"
}
```


## Technical Requirements

- You should be using promises.
- You should be using Bootstrap.
- You should be using jQuery for
  - DOM manipulation
    - Event listeners
    - Selecting elements from the DOM
    - Traversal
    - Filtering results
  - AJAX call to the json file of locations
- Your code should be clean and readable, with single responsibility principle.
