1. it will print '3,' since i has function scope and the loop stops when it equals the array length.

2. we'll print prices[2] * (1 - 0.5), which would mean 150.

3. we'll print math.round(150 * 100)/100, which is just 150

4. the function returns an array that's had all the various occuring values of final price pushed onto it during our four loop. [50, 100, 150]. Each loop we discount by half, assign it to final price, and push that value.

5. We'll have an error because 'i' doesn't exist outside the for loop.

6. We'll have an error because 'discountedPrice' doesn't exist outside the for loop.

7. We'll have the same '150' as before because final price has scope outside the for loop and had all the same operations done to it.

8. We'll return the same thing as before. [50, 100, 150].

9. We'll have an error because 'i' only exists inside the for loop.

10. We'll print 'length' just fine. In this case 3.

11. It'll print the same [50, 100, 150] as before. Pushing to a const array works fine, its just assignment that we can't do.

12. A) student.name B) student["Grad Year"], C) student.greeting(), D) student["Favorite Teacher"].name, E) student.courseLoad[0]

13. A) '32', B) 1, C) 3, D) '3null', E) 4, F) 0, G) '3undefined', H) NaN
14. A) true, B) false, C) true, D) false, E) false, F) True

15. '==' will ignore type differences, '===' will not

17. We'll return a modified array that has twice the values of the old array. In each pass of the for loop, we pass array[i] into callback which we've decided is "doSomething." doSomething just multiplies the input by two and returns it. So each pass of the for loop just multiplies array[i] by two and sticks it in newArr which is returned at the end.

19. prints 1, 3, 4, 2 in that order.