# warehouse-picker-kata
base kata data for warehouse picker assignment


You're working for a small e-commerce warehouse. Orders come in as list of items and each item lives at a specific shelf location in the warehouse. A picker walks through the warehouse with his cart, collects all items for an order, then returns to the packing station.

Write a function that takes an order and returns the sequence the picker should walk to gather everything in the most efficient way.

You'll be given a grid with coordinates and a shelf-to-item map.

assume the picker can move in 4 directions, one position at a time. Shelves are obstacles you walk around, not through.


desired output:
[ "0,0", "0,1", "pick apple", "0,0", "done"]

