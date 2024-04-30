Question 1: It will print the value of prices.length as we use the var declaration that uses function scope. 
Question 2: It will print the discountedPrice value which will be prices[prices.length-1]*(1-discount). This is because the declaration is using var which can be accessed anywhere in teh function. 
Question 3: It will print the value of finalPrice from the last iteration of the for loop. This is because finalPrice is a var that allows function scope. 
Question 4: The function will return [50,100,150]. This is because we send the given values of 100,200,300 as the prices and 0.5 as the discount to the function that ultimately calculates the discounted price for each given price by applying the 0.5 discount. we return discounted which is what contains the discounted prices and since this variable is in the function we can access it and return it. 
Question 5: This would give an error saying i is not defined because on line 12 i is out of the block scope therefore outside the for loop, i is not defined and thus gives an error. This is because we use let to define discountedPrice.
Question 6: This would give an error saying discountedPrice is not defined because on line 13 discountedPrice is out of the block scope therefore outside the for loop, it is not defined and thus gives an error. This is because we use let to define discountedPrice.
Question 7: At line 14, it will print the value of finalPrice from the last iteration of teh for loop which is 150. since finalPrice is still within the scope of the function, printing it using console.log does not give an error. 
Question 8: It will return [50,100,150] as there are no errors since all variables are in scope. we send the given values of [100,200,300] as the prices and 0.5 as the discount to the function that ultimately calculates the discounted price for each given price by applying the 0.5 discount. we return discounted which is what contains the discounted prices and since this variable is within the block scope, we can access it and return it.
Question 9: Line 11 will give an error because i is not defined outside the scope of the for loop as it is declared using 'let'. 
Question 10: It will print the value of the constant variable length which is 3 which is the size of prices variable. 
Question 11: This will return [50,100,150] as there are no errors in this code. We send the given values [100,200,300] to the function along with the 0.5 discount and then we iterate through each price and calculate its discounted price. On every iteration, we create a new const variable discountedPrice therefore, we are able to push new values into the discounted variable. 

Question 12: 
A. student.name
B. student['Grad Year']
C. student.greeting()
D. student['Favourite Teacher'].name
E. student.courseload[0]

Question 13: 
A. '32' as 2 is converted to s string as it is mapped to its string value. 
B. 1 as 3 is mapped to its integer value and 3-2 is 1. 
C. 3 as null is mapped to its conversion of 0. 
D. '3null' as null was converted to a string since '3' is a a string. 
E. 4 as true is mapped to its inetger value of 1(1+3)
F. 0 as both are mapped to its integer value(0+0)
G. '3undefined' as undefined is converted to a string value as '3' is a string value. 
H. NaN as using the - operator forces the values to be integers and 3 - NaN is NaN

Question 14: 
A. true as '2' is converted to a number and 2>1
B. false as '2' an '12' are compared lexicographically and first letter 2 >1 so returns false.
C. true since '2' is converted to an integer
D. false since we are checking using strict equal sign so it does not convert the types. 
E. false since true when converted to integer is 1 which is not equal to 2. 
F. true since Boolean(2) is true and true===true is equal. 

Question 15: == is the equality checker for two types or same types that are given but === is a strict equality checker which means it does not allow for automatic type comversions where == automatically converts type when applicable. 

Question 17: The function returns [2,4,6]. Here, we call the function modifyArray amd send the values [1,2,3] to the variable array and doSomething to callback. Then we iterate in teh for loop till we reach the end of teh array and in each iteration, we call function doSomething which returns the value*2 and this value when returned is pushed into the newArr and thus at the end of the for loop, we have all values in the array*2. 

Question 19: 
1
4
3
2