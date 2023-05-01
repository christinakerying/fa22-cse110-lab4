1. It will print 3 because the value of i, the counter that goes up to the size of the array, is 3 at the end of the for loop.
2. It will print 150 because the during the last iteration of the foor loop, the variable discountedPrice got assigned 300*(1-0.5), which evaluates to 150.
3. It will print 150, because in the last iteration of the for loop, the value that finalPrice gets assigned is 150.
4. It will return discounted, which is an array holding all the discounted prices, because during the for loop, for each element in the prices array, we calculated the discounted price and pushed it onto the discounted array. So, by the time the for loop is done, it contains all the discounted prices. 
5. error, because due to being declared using let, i's scope is only in the for loop , so it cannot be printed outside of that scope. 
6. error, because discountedPrice's scope is only in the for loop, so it cannot be printed outside of that scope 
7. It will print 150 because finalPrice was declared in the same scope, so it is accessible. The final value of final price is 150, so it will print 150.
8. It will return discounted, which is an array holding all the discounted prices, because it was declared in the same scope and so is accessible. During the for loop, for each element in the prices array, we calculated the discounted price and pushed it onto the discounted array. So, by the time the for loop is done, it contains all the discounted prices. 
9. error, because due to being declared using let, i's scope is only in the for loop, so it cannot be printed outside of that scope. 
10. It will print 3,
11. It will return discounted, which is an array holding all the discounted prices, because it was declared in the same scope and so is accessible. During the for loop, for each element in the prices array, we calculated the discounted price and pushed it onto the discounted array. So, by the time the for loop is done, it contains all the discounted prices. 
12. a. student.name  
 b. student['Grad Year']  
 c. student.greeting()  
 d. student['Favorite Teacher'].name  
 e. student.courseLoad[0]  
13. a. "32" because string concatenation  
    b. 1 because the '3' gets turned into 3, then 3-2=1  
    c. 3 because the null converts to 0, and 3+0=3  
    d. "3null" because string concatenation  
    e. 4 because true evaluates to 1, then 1+3 = 4  
    f. 0 because false is 0 and null is 0  
    g. "3undefined" because string concatenation  
    h. NaN because undefined doesn't have a numerical value in numeric conversion
14. a. true because the string 2 gets type converted into int 2, which IS greater than 1   
    b. false because the strings are compared letter by letter, and 1 < 2  
    c. true because the string 2 gets type converted into int 2, which IS equal to 2  
    d. false because the int and string are different data types, so === does not convert them to a common type  
    e. false because true has a value of 1   
    f. true because 2 is nonzero, so it evaluates to true  
15. The == operator compares two values for equality after converting them to a common type, but the === does not convert them to a common type. It just compares them. The === returns false for different data types. 
16. in part2-question16.js
17. The result will be [2, 4, 6], because in modifyArray, the for loop iterates through every element of the array. It does callback on each element, which when we call it with doSomething, multiplies every element by 2, and then it pushes the doubled numer onto the new array. At the end, newArr has array, but all the elements are multiplied by 2.
18. in part2-question18.js
19. The output is 1 4 3 2.
