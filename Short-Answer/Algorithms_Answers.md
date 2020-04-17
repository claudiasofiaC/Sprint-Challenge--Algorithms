#### Please add your answers to the ***Analysis of  Algorithms*** exercises here.

## Exercise I

a)O(n)
Value of n determines how many operation are carried out.

b) O(n^2)
There is a loop of loops

c) O(n)
Its a single recursion     

## Exercise II

Use binary search to find highest floor that an egg can be dropped from where it won't break.
Divide number of floors in half, drop egg from middle floor to see if it breaks. If the egg breaks I know that all floors higher than the middle floor will not need to be tested, then take all floors below middle floor and divide in half to set a new middle. Drop egg from new middle floor to see if it breaks, and so on until I reach a floor where the egg will not break.
If the egg does break from the initial middle floor, divide all higher floors from middle and drop egg again. Repeat process to see where egg will survive drop.
With each iteration of dropping the egg I getting rid of half of the remaining floors until I can reach the highest floor an egg can be dropped from without breaking.
