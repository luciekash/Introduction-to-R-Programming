# Introduction-to-R-Programming
ShippingtoMali, a shipping company, provides shipping to Mali for items bought on Amazon at a
rate of $4 for the first item and $2 for each subsequent item with each of those items is also
subject to import 10% tax. During this time, they also have a $10 discount for orders worth
above $500.
Write an R program that prints out how much one would spend for both purchase and shipping
of the given items ('item 1', 'item 2', 'item 3', 'item 4', 'item 5', 'item 6', 'item 7') from the given
data that is stored in the vectors or lists.
We can write two functions that will help provide a solution to this problem.

● One function will iterate over the price list/vector (120, 32, 99, 49, 99, 75, 30) applying
the respective tax and appending the result to the total_cost list/vector.

● The other function will take the number of items in an order as its only parameter then
return the cost of shipping the function's result. This function would only display the
shipping charge.
