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

Puppy Bowl Feature Reqs

1. Main Page
   a. When the user clicks on the puppy bowl logo, it should redirect the user to the main page
   b. The main page should display the puppy bowl logo and a formatted list of puppies with "see details" and "remove" buttons
   c. Clicking the "see details" button will display the puppies name, breed, and team (unassiged, red, blue) along with an enlarged picture of the puppy and a return to main button
   d. Clicking the "remove" button will remove the puppy from the list of puppies on the main page's roster
2. Add Player
   e. Clicking the "add new player" button will redirect the user to the add player page, which should display a form with fields for the puppy's name and breed
   f. Clicking submit should automatically reload the main page with the updated roster
3. Stretch Goals
   g. The roster table's team input should be a dropdown menu with the options "unassigned", "red", and "blue" which will automatically update the team of the puppy when selected
   h. The "add new player" form should include a field for the user to provide an image url for the player's "details" page



