# Block-18-Workshops

Unit Tests

1. 
   a. expect (2,5) to be a number
   b. expect (2,5) to be 10
   c. expect ("c",5) to be an error

2. 
   a. expect concatOdds([1,3,4,5,7],[11,12,13]), to be an array of the odd 
   numbers [1,3,5,7,11,13]
   b. expect concatOdds(["words",golden,1,2,5],["hello",Jeff,1,5,9]) to be an error
   c. expect concatOdds([1,2,3,4,5],[1,2,3,4,5]) to be an array of the odd numbers [1,3,5]

Functional Test

3. 
   a. if the user adds/removes an item in the cart, the cart icon should update to reflect the total sum of items in the cart
   b. if the user adds/removes an item in the cart, the total price should update to reflect the total sum of items in the cart
   c. when the user clicks on the cart icon, it should display the checkout page
   d. when the user reaches checkout page, it should prompt the user to log in or sign up if they have no already done so
   e. when the user is logged in or continued as a guest, the shipping address will automatically populate or the user can input a new shipping address
