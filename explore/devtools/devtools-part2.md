1. The bug is that the input numbers are being stored as string inputs so when we do num1+num2 it concatenates the strings rather than treating them as numbers. 

2. The code can be fixed by converting the data type of the input string by using parseInt("string"); in this case. Screenshot is added for the fix. 