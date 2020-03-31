### Online pizza order

Create an app for a pizza company where a user can choose one or more individual toppings (cheese, pepperoni, artichoke, broccoli, olives, shrimp, eggplant, steak, anchovy, shrimp) and any size pizza and see the final cost.

* Allow the user to enter the toppings and then the size (small, medium, or large) for the pizza they’d like to order.
* If the user selects the following special toppings, add .55 to each: eggplant, steak, lobster, anchovy, shrimp
* Create a pizza object constructor with properties for toppings and size.
* Create a user object constructor with properties that will eventually be added which will include: their name, the toppings they’ve selected and the pizza size they've selected.
* Create a prototype method for the cost of a pizza depending on the size selections chosen. A small pizza is 9.99, a medium is 12.99, and a large pizza is 19.99. Add a sales tax that is 6.25%.
* You will need to console log the final confirmation message that states:
    * the date and time of the order using the Date.Object, 
    * add a random order number by using Math.Object
    * list the user's pizza order and the toppings they've selected
    * the grand total cost which includes any special toppings.

**Bonus**

* Allow the user to order more than one pizza with different toppings.
* Offer a delivery option that then requires address information.