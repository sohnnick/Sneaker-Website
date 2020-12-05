# Sneaker Website
Link found here: https://viterbi-web.usc.edu/~nsohn/itp301/final_project/home.html

The topic of this website is a sneaker purchasing website. The website is called “Sneaker Trend Co.” The whole idea takes inspiration from both HypeBeast and StockX, where sneaker culture and sneaker trading have become a prominent aspect of today’s world. Hoping to merge my passion for streetwear and programming, I found this website a joy to make. The tag line is “the ultimate sneaker marketplace” which reflects the overall purpose of the website.

I utilized DOM Manipulation to generate my cart table. Users can add items to their cart through the browse page and remove and view their items on the cart page. There is also the option of clearing the cart table entirely.

I also used a JSON API for my search function in the browse page. The API I used is the sneaker database found on SwaggerHub (https://app.swaggerhub.com/apis-docs/tg4solutions/the-sneaker-database/1.0.0). Upon search, the API helps return a list of sneakers matching the search parameter.

Lastly, I utilized local storage to store JSON objects in the browser such that the items added in the browse section can be accessed in the cart section. Utilizing localStorage.clear(), localStorage.getItem(), localStorage.setItem(), I was able to generate and manage the shopping cart appropriately.
