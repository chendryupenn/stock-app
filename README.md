# stock-app
Simple Stock App

Welcome to the stock app, where users can retrieve financial information from a public company and create a watchlist of stocks they would like to follow. 

To start the application, please make sure that Node.js is installed (see this link: https://nodejs.org/en/download/). Run the following commands in the terminal from the parent directory of "src":

1. npm install
2. npm install react react-dom
3. npm i axios
4. npm i react-plotlyjs
5. npm start

Page Features:

Home Page
-Contains a search bar for searching for a company by its name or associated stock ticker symbol.
-Click on search result takes user to Finances page
-Should show the user’s watchlist of stocks they follow, displaying the company name, current stock price, and stock price percentage change.

Finance Page
-Contains a line graph displaying the stock price of the company over time, with the date on the x-axis and the stock price on the y-axis of the graph
-Contains a table with the company’s financial annual information 
-Contains an option to add the company to a stock price watchlist (only allows you to add it once)

The Watchlist page
-Displays all the companies and their associated stock prices that the user has added to their watchlist (stored in local storage, so data persists on refresh and closing and reopening the browser)
-Ability to delete entries from the watchlist
-Ability to sort the watchlist by stock price value either in ascending or descending order


