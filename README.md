# Shotz

## Setup

**At minimum, your project should have the following file structure:**
```
|- db
    |- locations.json
    |- movie.json
|- src
    |- javascripts
        |- main.js [Entry point/start application]
        |- components
            |- locations
                |- locations.js [Writing to the dom for the locations component]
                |- locations.scss [styling for the locations component]
            |- movies
                |- movies.js [Writing to the dom for the movies component]
                |- movies.scss [styling for the movies component]
            |- singleMovie
                |- singleMovie.js [Writing to the dom for a single movie component]
                |- singleMovie.scss [styling for the single movie component]
        |- helpers
            |- util.js [contains printToDom function]
            |- data
                |- movieData.js [AJAX call for movie data]
                |- locationsData.js [AJAX call for locations data]
|- index.html
|- styles
    |- main.scss [main application styles]
```

This list is just a minimum list of files.  You can get more complex with the JavaScripts modules as needed and add more files if you need to.

**Install via npm:**
- all required webpack dev dependencies (see class notes)
- jQuery
- Bootstrap
- popper.js
- axios

## Part 1
Follow the instructions for [Part 1](./part-1.md).

## Part 2
Follow the instructions for [Part 2](./part-2.md).

## Part 3
Follow the instructions for [Part 3](./part-3.md).

