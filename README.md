# Caching Budgets (Budget Tracker)

## Description

This application allows a user to track deposits and withdrawals. The user can even track their transactions while offline and the app will keep track of these transactions and update the database once back online. It was created using Mongo database with a Mongoose schema it handles routes with Express and utilizes caching and indexDB for offline logging.

## URL to application on Heroku

https://lychee-cobbler-11074.herokuapp.com/


## Instructions

When the user loads the page, they are presented with a total dollar amount and an input box for the name of their transaction along with a corresponding input box for the amount associated with the transaction.

* Enter the name of the transaction in the transaction name input box then enter the amount of the transaction in the input box for transaction amount
* Click the "+ Add Funds" button to add the funds to your total
  * Funds will be added and your total will go up, the transaction and amount will display in a transaction history log and the increase will be visually represented in a chart below
* Click the "- Subtract Funds" button to subtract the funds from your total
  * Funds will be subtracted and your total will go down, the transaction and amount will display in a transaction history log and the decrease will be visually represented in a chart below

* For use offline you can either navigate to the network tab within the dev tools and simulate an offline status or you can actually disconnect from the internet
  * Once offline all of the functionality described above should continue to work and once you come back online any transactions performed offline will load from the cache and update the database

## Screenshots
![image](https://user-images.githubusercontent.com/54122844/78192705-e5759b00-7435-11ea-8504-f0212290e0ed.png)

![image](https://user-images.githubusercontent.com/54122844/78192762-0c33d180-7436-11ea-89f6-b25425332a1a.png)


## Built With

* mongoDB
* mongoose.js
* node.js
* express.js
* chart.js
* morgan
* compression
* fontawesome
* HTML/CSS/JavaScript

## License
This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details
