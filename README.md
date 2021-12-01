

# Api Made Easy 

Api Made Easy is a web application that makes one of the tasks of programming easier by providing the source of information on how to configure the API based on their need, by showing source, artitle and url, this removes the the guess work from the process.


# Motivation 

One of the pain points of using an API is going through the documentation. API provide a tool that showcases API from source code, url links and real components to create a usable application that simplifies the process for programmers.


# Api Made Easy Team 

Michael Francois Kenneth King 

# Features

Features source code, url links real components

Mvp functionality avaliblity of serveral search options sections for display code

# MVP List

# Hosting on Heroku 

All user available see the displayed the index of the page.

Each user show page will have a 
     source
     description
     name of url
     articles.

Each user will have a section of code that is shown

Each  user will have a show page that also displays the number of times this api has been viewed.




## Color Reference

| Color             | Hex                                                                |
| ----------------- | ------------------------------------------------------------------ |
| Example Color | ![#3d5a80](https://via.placeholder.com/10/0a192f?text=+) #3d5a80 |
| Example Color | ![#98c1d9](https://via.placeholder.com/10/f8f8f8?text=+) #98c1d9 |
| Example Color | ![#e0fbfc](https://via.placeholder.com/10/00b48a?text=+) #e0fbfc |
| Example Color | ![#ee6c4d](https://via.placeholder.com/10/00b48a?text=+) #ee6c4d |


# WireFrame 
https://xd.adobe.com/view/276ed8fb-f923-4215-a142-aab359af54bc-723d/

# Code

## Usage/Examples for using axios for github

we will use the github api and and  custumfeedapi to with axios to call the json to show for the user to see
this is how it would look like. 


```javascript
import axios from "axios";

const axios = require('axios');

axios.get('user_url": "https://api.github.com/users/{user}')
      .then(resp => {

    console.log(resp.data);
});
```
## Usage/Examples for using axios for rapidapi
```javascript


const options = {
  method: 'GET',
  url: 'https://custom-search.p.rapidapi.com/api/search/CustomFeedAPIV2',
  params: {searchEngineId: '<REQUIRED>', pageNumber: '10'},
  headers: {
    'x-rapidapi-host': 'custom-search.p.rapidapi.com',
    'x-rapidapi-key': Api_kEY
  }
};

axios.request(options).then(function (response) {
	console.log(response.data);
}).catch(function (error) {
	console.error(error);
});
```

# Post-MVP: 

Add mutiple library to display api code ex React

display API code such as React to import API call for axios 


Installation npm axios npm --

# dependencies: 
axios


axios html / css

Testing:

Jest



