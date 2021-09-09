# Codecademy -- Len-s-Slice

# This code is to use the knowledge of Python list to organize sales data.

# Create a list that holds kinds of pizzas to be sell.
toppings = ["pepperoni", "pineapple", "cheese", "sausage", "olives", "anchovies", "mushrooms"]

# Create a list that holds the value of each kind of pizza slice costs.
prices = [2, 6, 1, 3, 2, 7, 2]

# Count the number of occurrences of 2 in the prices list and store in num_two_dollar_slices. Print output.
num_two_dollar_slices = prices.count(2)
print(num_two_dollar_slices)

# Find the length of the toppings list and store the value in num_pizzas.
num_pizzas = len(toppings)

# Print a string where num_pizzas represents the value of num_pizzas.
print("We sell " + str(num_pizzas) + " different kinds of pizza!")

# Convert toppings and prices lists to a two-dimensional list named pizza_and_prices.
pizza_and_prices = [[2, "pepperoni"], [6, "pineapple"], [1, "cheese"], [3, "sausage"], [2, "olives"], [7, "anchovies"], [2, "mushrooms"]]

# Print pizza_and_prices.
print(pizza_and_prices)

# Sort pizza_and_prices so pizzas are in the increasing price.
pizza_and_prices.sort()

# Store the first element of pizza_and_prices in a new variable, cheapest_pizza.
cheapest_pizza = pizza_and_prices[0]
print(cheapest_pizza)

# Store the expensive pizze price as priciest_pizza.
priciest_pizza = pizza_and_prices[-1]
print(priciest_pizza)

# Remove anchovies from the pizza_and_prices list since a customer bought it.
pizza_and_prices.pop()
print(pizza_and_prices)

# Add new toppings to the pizza_and_prices list.
pizza_and_prices.insert(4, [2.5, "peppers"])
print(pizza_and_prices)

# Store the 3 lowest cost pizzas to a new variable, three_cheapest.
three_cheapest = pizza_and_prices[:3]
print(three_cheapest)
