# The Shotz: Part 1 (Movies)

## Requirements

- As a user, I want to keep track of all the movies I am working on.
- Upon arriving at the homepage, I should see a section with information on each movie that is in progress - bootstrap cards would be good here.
- Each movie object should look something like this:
```
{
  "id": "movie1",
  "name": "Super Secret Movie",
  "genre": "Thriller",
  "releaseDate": "10/15/2020",
  "description": "super exclusive can't tell you",
  "locations": [
    "location1",
    "location3",
    "location9"
  ]
}
```
You will find a sample movies.json file [HERE](./sampleData/movies.json)

## Technical Requirements
- You should be using Bootstrap.
- You should be using ES6 Modules.
- You should be using Axios for all data requests
- Your code should be clean and readable
- Your functions should follow the single responsibility principle.