## Hacker News JQuery App

![Final App](/hackernews.gif)

## Project Details

This is a pure Javascript/Jquery project loosely based on the news aggregator Hacker News. The app allows users to create accounts, log in, create articles, mark articles as favorites, and remove articles!. 

## Design 

![Final App](/design.svg)

Front-end app consists of two parts:

1. Classes and methods for the big data ideas: a Story class for each story, a StoryList class for the list of stories, and a User class for the logged-in user (if any). These methods also handle interacting with the API.

2. Functions for the UI, handling things like reading form values from forms and manipulating the DOM.

There’s one JS file for the “data” layer of the app:

1. js/models.js
Contains classes to manage the data of the app and the connection to the API. 

2. js/main.js
contains code for starting the UI of the application, and other miscellaneous things.

3. js/user.js
contains code for UI about logging in/signing up/logging out, as well as code about remembering a user when they refresh the page and logging them in automatically.

4. js/stories.js
contains code for UI about listing stories.

5. js/nav.js
contains code to show/hide things in the navigation bar, and well as code for when a user clicks in that bar.

## Quick Start
```javascript

// Run server
python3 -m http.server

// You can then visit the site at http://localhost:8000/.
```
