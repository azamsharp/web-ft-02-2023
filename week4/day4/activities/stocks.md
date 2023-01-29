
# Activity 2 - Stock Quotes

Create a page which allows users to search for stock quotes. The page will consist of a TextBox where users can enter the symbol of the stock they are looking for. When the presses the **"Show Quotes"** button the app will call the **"getStockQuote"** function implemented below and get the stock quotes. You should update the quotes every 2 seconds by making a call to getStockQuote function. Your app should display the name of the stock and also the price of the stock. 

**Create a file called stockQuotes.js and paste the following code in that file. Make sure stockQuotes file is loaded before your js file. Inside your file you can call the getStockQuote function to get the latest stock quote for a provided symbol** 

```

// In order to get the quotes you can call the getStockQuote function as shown below:

// getStockQuote(pass in the symbol of the stock)

// available symbols are below:
// APLE
// AMAZ
// ALBAB
// GOOG
// FB

let quotes = {
  "APLE":{name : "Apple", price : 0},
  "AMAZ":{name : "Amazon", price :0},
  "ALBAB":{name : "Ali Baba", price :0},
  "GOOG":{name : "Google", price :0},
  "FB":{name : "Facebook", price :0}
}

function getStockQuote(symbol) {

  let stock = quotes[symbol]
  stock.price = getRandomInt(100,500)
  return quotes[symbol]
}


function getRandomInt(min, max) {
    return Math.floor(Math.random() * (max - min + 1)) + min
}

```
