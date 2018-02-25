# Online-Shopping-Lab

Practicing Object Oriented programming, arrays, conditionals, and loops by creating a shopping cart with various features
using Vanilla JS.

<strong> 1: addToCart() function </strong>

First off, I created an addToCart() function that accepts one argument, the name of an item. 
Then I used that passed-in string to create a new object representing the item. 

The object should consist of one key-value pair in which the key is the item's name and the value is a randomly-generated price: { itemName: itemPrice }. As more items are added, the cart should start to look something like this: [ { "bananas": 17 }, { "pancake batter": 5 }, { "eggs": 49 }].

The price of each item should be a randomly-generated integer between 1 and 100. 

Upon the successful addition of a new item to the cart, the function should print <itemName> has been added to your cart. to the console and then return the updated cart.
        
 <strong> 2: viewCart() function </strong>

The viewCart() function does not accept any arguments. It should loop over every item in the cart, printing out the contents as one long, coherent statement in this format: In your cart, you have bananas at $17, pancake batter at $5, and eggs at $49.

If the cart is empty, the function should instead print out Your shopping cart is empty.


<strong> 3: total() function </strong>

The total() function accepts no arguments, iterates through the cart array, and returns the current total value of the items in the cart.

<strong> 4: removeFromCart() function </strong>

The removeFromCart() function accepts one argument, the name of the item that should be removed. 

If the cart does not contain a matching item, the function should print out That item is not in your cart. and return the unchanged cart.

If the item is present in the cart, the function should remove the object from the cart and then return the updated cart.

<strong> 5: placeOrder() function </strong>

If no argument is received, the function should print out Sorry, we don't have a credit card on file for you..

If a card number is received, the function should print out Your total cost is $71, which will be charged to the card 83296759. (where 71 is the value returned by total() and 83296759 is the credit card number passed to placeOrder()). Then, it should empty the cart array.

