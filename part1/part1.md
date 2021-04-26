**Part 1a.**
1. values added:  20
2. final result:  20
3. values added:  20
4. error, because "let result" only declared inside the block. Since the second console.log is outside the block, it won't see the result.
5. error, the variables that declared by const cannot be reassigned.
6. error, the variables that declared by const cannot be reassigned.

**Part 1b.**
1. 3, because the i start from 0 and the length of list prices is three, so i will run plus 1 three times and equal to 3 after the loop. 
2. 150, in the last cycle of the for loop, prices[i]=300 and discount=0.5, so that discountedPrice = 300*(1-0.5) = 150.
3. 150, in the last cycle the discountedPrice = 150, so finalPrice = Math.round(150*100)/100 = 150.
4. [ 50, 100, 150 ], the function will return the value of discounted, which are (100*(1-0.5)*100/100=50, (200*(1-0.5)*100/100=100, and (300*(1-0.5)*100/100=150.
5. error, the console.log is outside the for loop and the variable i only declared inside the for loop. 
6. error, the console.log is outside the for loop and the variable discountedPrice only declared inside the for loop. 
7. 150, bothe the variable finalPrice and the console.log are outside the for loop, so finalPrice=Math.round(150*100)/100=150
8. [ 50, 100, 150 ], since both the variable discounted and the return are in the same block, the function will return the value of discounted, which are (100*(1-0.5)*100/100=50, (200*(1-0.5)*100/100=100, and (300*(1-0.5)*100/100=150.
9. error, the console.log is outside the for loop and the variable i only declared inside the for loop. 
10. 3, the length of the prices is three and it declared as a const variable in the function.
11. [
  [Function: discountPrices],
  [Function: discountPrices],
  [Function: discountPrices]
]
The variable discoutnredPrice = [Function: discountPrices], and the for loop push the value three times to the discounted. 
12. A. student.name
    B. student["Grad Year"]
    C. student.greeting()
    D. student["Favorite Teacher"].name
    E. student.courseLoad[0]
13. A. '32', because '3' is a string, so it simple made number 2 become a string and combine them together.
    B. 1, it made the string '3' become a integer so that 3-2=1.
    C. 3, 3 is a integer and null in integer means 0, so 3+0=3.
    D. '3null', '3' is a string, then make null become a string and combine together.
    E. 4, 3 is a integer and true in integer means 1, so 1+3=4.
    F. 0, false and null in integer are both mean 0.
    G. '3undefined', '3' is a string, then make undefined become a string and combine together.
    H. NaN, make string '3' become number 3, 3-undefined=NaN.
14. A. true, change string '2' to number 2, 2>1
    B. false, becasue first char '2' is greater than the first char '1'
    C. true, change string '2' to number 2, 2==2
    D. false, === won't do any conversion so number 2 is not eqaul to string '2'
    E. false, true is equal to number 1, and 1 is not eqaul to 2.
    F. true, Boolean(2) is true, and true equal to true.
15. Both == and === means the equality test, but == checks the equality with type conversion while === checks equality without it. In other words, === won't convert the type of the values.
16. part1b.question16.js
17. The newArr will be [ 2, 4, 6 ]. Because modifyArray passed an array[1,2,3] and a funtion doSomething, and it will multiply every element in the array by 2 and push into the newArr.
18. part1b.question18.js
19. because setTimeout only effect the single function, so the output is:
1
4
3
2