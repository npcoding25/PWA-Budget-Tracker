# PWA-Budget-Tracker

## Table of Contents

- [Objective](#Objective)
- [Installation](#installation)
- [Functionality](#Functionality)
- [Improvements](#Improvements)
- [Screenshots](#Screenshots)

## Objective 

Given a working application, create the logic so it can have offline features.

## Installation

Run 'npm install'

## Functionality

After running node server.js, and going on to the correct browser url, a budget tracker is shown. The user can add or delete funds and it will save it to the database and show a graph on the bottom logging the transactions. If the user switches to offline mode they can still make transactions but the data will be stored in indexedDB rather then the actual database. Once back in online mode, the transactions made while in offline mode will then be saved to the actual database in a 'bulk' file.

## Improvements

This app is fairly simple. It already shows dates in the graph for the logged transactions. The UI could use an upgrade from this boring look to something with a little more style. It could also have categories that the transaction belongs to so the user could see what ways they are spending their money.

## Screenshots
 
![image](https://user-images.githubusercontent.com/69565347/99154039-9cd7be80-2661-11eb-9da6-9c7e54d2064d.png)

Click [Here](https://limitless-thicket-35109.herokuapp.com/) to see deployed application.