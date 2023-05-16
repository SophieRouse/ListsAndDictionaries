# This code is using dictionaries to calculate how much a cafe's total stock is worth.
# Menu items were put into a list, then dictionaries were used to determn Key-value pairs for stock numbers and prices of each menu item.
# An equation was then used to work out each item value and these were added together to get the total value.
# The total value was then printed.

menu = ["Chocolate Fudge Cake", "Victoria Sponge Cake", "Shortbread", "Lemon drizzle Cake", "New York Cheesecake"]

stock = {"Chocolate Fudge Cake":13, "Victoria Sponge Cake":15,"Shortbread":4, "Lemon drizzle Cake":17, "New York Cheesecake":26}

price = {"Chocolate Fudge Cake":3.50, "Victoria Sponge Cake":2.50,"Shortbread":1.50, "Lemon drizzle Cake":3.20, "New York Cheesecake":4.50}

total_value = 0
for item in menu:
    item_value = (stock[item] * price[item])
    total_value += item_value

print("The total value of stock is: £" + str(total_value))
