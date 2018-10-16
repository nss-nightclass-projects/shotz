# The Shotz: Part 1

## Requirements

- As a user, I want to keep track of all the shooting locations for my soon to be oscar winning movie.
- Upon arriving at the homepage, I should see a section with information on my movie (keep it to just one movie).
```
Name: xxx
Genre: xxx
Estimated Release Date: xxx
Description: xxx
```
- Upon arriving at the homepage, I should see a list of all locations that I plan to shoot, displayed as cards.
```
Location Image
Name: [Eg: Starbucks]
Location Address: [Eg: 1 Terminal Dr #325, Nashville, TN 37214]
Shoot Time: [Pick one of the following options: Morning, Afternoon, Evening, After Dark]
```
- As a user, I should be displayed a search bar. This search bar should filter the results of the cards. On keypress, the text I type in the search bar should be contained in either the location title text or the location address of all cards still displayed.
- As a user, I should be displayed 4 button options for "time of day." (Options: Morning, Afternoon, Evening, After Dark). These buttons should filter the results down to each location that has a "Shoot Time" corresponding to the button clicked.


## Technical Requirements

- You should be using Bootstrap.
- You should be using ES6 Modules.
- You should be using jQuery for
  - DOM manipulation
    - Event listeners
    - Selecting elements from the DOM
    - Traversal
    - Filtering results
  - AJAX call to the json file of locations
- Your code should be clean and readable, with single responsibility principle.