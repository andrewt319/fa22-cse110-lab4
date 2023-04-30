1. Line 12 will print out 3. I is the variable used in the for loop, and it increments by one each time up to prices.length. Prices.length is 3, so once it gets to 3, then it will no longer meet the i < prices.length condition. Therefore, i is done at 3.
2. Line 13 will print out 150. This is basically just math it will do the formula in the for loop for each of the values inside prices, and then assign it to discountedPrice. It will keep reassigning the variable discountedPrice, and then after i becomes out of bounds, 150 is the last value stored in there.
3. Line 14 will print out 150. FinalPrice likewise will just do the math in the for loop for each value inside prices. It first computes discountedPrice, and then uses that in another formula to compute finalPrice. 
4. The function will return [50, 100, 150]. Essentially, each item is discounted by half each time after cmoputing the math formula written in lines 7 through 9.
5. The code will error out at line 12. This is because i is in a block scope inside the for loop. Outside of that, it's undefined.
6. The code will error out at line 13. This is because discountedPrice is in a block scope inside the for loop and outside of that, it's undefined.
7. The code will print 150. Because finalPrice is defined in the outer scope, it is accessible inside the nested scopes as well (the for loop) so it can be changed. Thus, when it is printed, it is able to because it was originally declared in that scope.
8. The code will print out [50, 100, 150]. This is because discounted was declared in the outer block scope inside the function, so it is accessible inside the for loop as well. It will do the math, and push it into discounted with no issues. 
9. The code will error out because i is in a block scope inside the for loop. Outside of this for loop it is undefined. 
10. The code will print out 3 because length is defined in the outer block scope. Line 12 is in the same scope as it was declared, so it will just print out the length of prices which is 3.
11. The code wioll return [50, 100, 150]. The code applies the math and pushes it into a const array, which is still allowed. When it returns, it has access to the discounted array because it was declared in the same scope.
12. 
    a. student['name']
    b. student['Grad Year']
    c. student['greeting']()
    d. student['Favorite Teacher']['name']
    e. student['courseLoad'][0]
13.   
    a. 32
    b. 1
    c. 3
    d. 3null
    e. 4
    5. 0
    6. 3undefined
    7. NaN
14. 
    a. true
    b. false
    c. true
    d. false
    e. false
    5. true
15. '==' does type conversion before doing equality check. However, '===' does not do type conversion before doing equality check, meaning, that if the data types aren't the same, it will be counted as unequal.
16. check part2-question16.js
17. The result will be [2, 4, 6]. This is because we pass in two arguments to the modifyArray function -- an array with [1, 2, 3] and a function that basically takes in a number and multiplies it by 2. It applies this function to each number inside the [1, 2, 3] array and as a result, we get [2, 4, 6].
18. Check part2-question18.js
19. The output is 1 4 3 2. Line 2 is done instantaneously as soon as it reaches the line. Line 3 waits for 1 second first, and in the meantime, Line 4 runs because it has a 0 second timeout. Then, it reaches line 5 and runs that because it has no delay either. Finally, after the timeout in line 3 ends, 2 is printed.