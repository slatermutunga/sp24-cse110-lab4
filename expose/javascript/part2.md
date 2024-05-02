1. It will print 3. This is because it prints i. i starts at 0 and runs in the for loop, increasing
   until i is equal to prices.length. Since prices.length = 3 this means that the loop will end when i = 3.
   So when console.log(i) is run it will print i which will equal 3.
2. It will print 150. This is because discountedPrice will be equal to the discounted price of the last index of the 
   prices array. Since the last value is 300, and the discount is .5, when you apply the discount it makes the discounted
   price 150. This is why when it prints it prints 150.
3. It will print 150. This is because it uses the final price which is used to round in case of the discounted price
   is a number with many decimal points. Since 150 is already rounded to a full integer, it doesn't change and prints 
   150 which is the finalPrice.
4. It will return an array of the discounted prices which will be equal to, [50, 100, 150]. This is because the for loop 
   applys the .5 discount to the original array cutting the prices in half, and puts them into the discounted array that we then
   return.
5. ReferenceError: i is not defined
   This causes an error because i is declared with the let keyword which only applys to the block that it is declared in which
   is the for loop. Since console.log(i) is called outside of that for loop it throws a reference error. 
6. ReferenceError: discountedPrice is not defined
   This causes an error because discountedPrice is declared with the let keyword which only applys to the block that it is declared in which is the for loop. Since console.log(discountedPrice) is called outside of that for loop it throws a reference error.  
7. It will print 150. This is because 150 is the last value that finalPrice is assigned to since 300 is the last value in the array
   and .5 is the discount. finalPrice is assigned with let but since it is declared within the same block that the console.log(finalPrice) is called it is fine.
8. It wil return the discounted array which is, [50, 100, 150]. This is because the discount of .5 is applied to the original array of [100,200,300].
9. ReferenceError: i is not defined
   This throws an error since i is declared with the let keyword. We try to print i outside of the for block that it was declared in which causes an error.
10. It will print 3. This is because length is equal to the length of the prices array which hold 3 values, 100, 200, and 300.
11. It will return the array discounted which holds the discounted prices, of [50, 100, 150]. This is because the discount of 50% is applied to the original array of [100,200,300].
12. A. student.name
    B. student['Grad Year']
    C. student.greeting()
    D. student['Favorite Teacher'].name
    E. student.courseLoad[0]
13. A. '32' This concates 2 to 3 since it does string concatenation if either are strings.
    B. 1 This does 3 - 2 since - is always used for arithmetic.
    C. 3 null = 0 during arithmetic so 3 + 0 = 3.
    D. '3null' This concates null to 3 since '3' starts as a string.
    E. 4 In addition true is set to 1 so 1 + 3 = 4.
    F. 0 False and null both equal 0 when used in addition so 0 + 0 = 0.
    G. '3undefined' Since 3 starts as a string we concate undefined to it.
    H. NaN Subtraction only allows arithmetic and undefined can't be made into a number so it results in Nan which stands for not a number.
14. A. true comparison makes 2 '2' into a number and 2 > 1 is equal to true.
    B. false since both are strings it compares them lexicographically and 2 is greater than twelve in that way
    C. true == makes them into numbers and 2 is = to 2
    D. false === compares type and value since 2 is a number and '2' is a string it is false
    E. false true becomes 1 and 1 != 2
    F. true boolean makes it a boolean value and 2 becomes true so it becomes true == true which is true
15. == compares equality after type coercion while === checks for both value and type equality
17. It will go through the original array, and run doSomething on all of the values. Do something multiplys the original value by 2
    so we by the end of modifyArray it will return the newArray of, [2,4,6].
19. 1
    4
    3
    2