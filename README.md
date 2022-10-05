# ATM

## Directions 

<img src="http://atm_1.png" height="60" width="60" >

This mock ATM "machine" allows the user to either <i>deposit</i> money into their account by selecting <b>Diposit</b> on the drop down menu, or <i>withdraw</i> money from their account by selecting <b>Cash Back</b>.

The ATM will not allow the user to overdraft their account, meaning if they attempt to remove more money than exists in their account, the transaction will not submit.

A running account balance is updated every time the <b>Submit</b> button is clicked. 


## How It Works

This project runs off of three files; <u>atm.jsx</u>, <u>index.html</u>, and <u>styles.css</u>.

### atm.jsx

In the atm.jsx file, the functionality is brought to life by using React hook useState which tracks the changing account values as deposits and withdrawals are made.

<img src="http://atm.png" height="60" width="60" >

### index.html

The html file links the project to React, Babel, and Bootstrap which allows for a smoother user experience using the app.

### styles.css

The styles sheet is where additional beautification <i>will</i> happen, and is the <i>next</i> focus for this project!
