# The Shotz: Part 2 (Locations)

## Requirements
- Upon arriving at the homepage, I should see a list of ALL locations that ALL of my movies need, displayed as cards.
- Each location object should look something like this:
```
{
  "id": "location1",
  "imageUrl": "https://www.roadsideamerica.com/attract/images/ks/KSCAWtwine2.jpg",
  "name": "World's Largest Ball of Twine1",
  "address": "1 Wisconsin St, Cawker City, KS 67430",
  "shootTime": "Morning"
}
```
You will find a sample locations.json file [HERE](./sampleData/locations.json)

- As a user, I should be displayed a search bar. This search bar should filter the results of the locations cards. On keypress, the text I type in the search bar should be contained in the location name text, or the location address on all cards still displayed.
- As a user, I should be displayed 4 button options for "time of day." (Options: Morning, Afternoon, Evening, After Dark). These buttons should filter the results down to each location that has a "Time That shot should occur" corresponding to the button clicked.

## Technical Requirements
- You should be using Bootstrap.
- You should be using ES6 Modules.
- You should be using Axios for all data requests
- Your code should be clean and readable
- Your functions should follow the single responsibility principle.