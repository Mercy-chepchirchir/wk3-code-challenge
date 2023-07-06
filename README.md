# FLATDANGO
This website allows buying of movie tickets online.

## Table of content
* Description 
* Installation requirement
* Technology used
* Licence
* Authors info

# DESCRIPTION
## index.html
Placed the name flatdango to be H1 that is the header.Use <ul> for the film list.Use span so that everything can be displayed in a line and <br> so as to have line breaks.
## Index.css
Used it to syle the film list, image and menu.

## Index.js 
First fetch this `"http://localhost:3000/films")`at then make the db.json file into an object which will return the films. We then used film.foreach so as to apply for each film .

Used the function getElementById to get the menu and added an event listener to the menu so as when clicked it should display the film list.Created the funtion displayfilmlist to diplay the movie detals.Created an li element. Add an event listener to the link.Displayed the runtime,showtime,number of available seats and image of the poster.Added an eventlistener to the buy ticket button.

# INSTALLATION PROCESS
## Frontend
* Create your folder using the command `git clone your ssh or https keys`
* Navigate to the code challenge directory using `cd wk3code challenge`
* copy the path to `index.html` and open it in the browser on a new tab


## Backend
* Install the json-server using the command `npm install -g json-server`
* To get backend started run this command `json-server --watch db.json`
* Test your server by visting this route in the browser `http://localhost:3000/films`

# TECHNOLOGY USED
Html
css
Javascript


# LICENSE
MIT license

# AUTHORS INFO
Mercy Chepchirchir

