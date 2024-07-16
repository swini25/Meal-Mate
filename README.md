# Meal-Mate

## **Bot Description:**

DashBot is a discord online food ordering bot for users to order foods from different restaurants. It provides several functions such as ordering food, recommending dishes from restaurants, checking order status, checking history orders, and ordering together with other discord members.

**Features Involved:**
Embed, Button, Dropdown Selection, Multiple User Interaction

## **Commands:**

For Individual Ordering:
 - **`/neworder`**: start a new order
 - **`/order`**: add dishes into the shopping cart
 - **`/delete`**: delete dishes from current shopping cart
 - **`/deleteorder`:** delete current ongoing order
 - **`/checkout`**: check out the current order

For Group Ordering:
 - **`/grouporder`**: Start a group order which allows all members in the channel to add dishes in the shopping cart
 - **`/groupcheckout`**: Check out a group order

For Info Checking:

 - **`/restaurants`**: Show the list of all restaurants you can order at
 - **`/restaurants cuisine_type`**: Filter restaurants with the given cuisine type
 - **`/showcart`**: Show the items in the shopping cart
 - **`/orderstatus`**: Show the status of your orders (is preparing/being delivered, delivered)
 - **`/info`**: Show the info of the restaurant the user are ordering at
 - **`/info restaurant_name`**: Show the info of the given restaurant
 - **`/menu`**: Show the menu of the restaurant the user are ordering at
 - **`/menu restaurant_name`**: Show the menu of the given restaurant
 - **`/last num_k`**: Show last num_k numbers of history orders
 - **`/last num_k restaurant_name`**: Show last num_k numbers of history orders at the given restaurant

_____

**Build the Bot Locally:**

    ./gradlew spotlessApply build

**Run the Bot Locally:**
 - replace line 33 in Bot.java file with your bot token.

**Rule for Code Coverage:**
|line test | branch test |
|--|--|
| >= 80% | >= 80% |
_____