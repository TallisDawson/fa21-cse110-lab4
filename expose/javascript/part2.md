### Q1
i is printed to the console, since i is accessible throughout the funciton.
No errors

### Q2
discountedPrice is printed to the console, since discountedPrice is accessible throughout the funciton.
No errors

### Q3
finalPrice is also printed to the console, since finalPrice is accessible throughout the funciton.
No errors

### Q4
the function returns discounted, which is an array of new prices calculated by looping through the prices array, applying the specified discount to each price, and pushing the new value to the discounted array.
With the input given, the function returns [50, 100, 150]

### Q5
This code will return an error, since i is only locally defined in the for loop, and cannot be accessed at line 12.

### Q6
This code will return an error, since discountedPrice is only locally defined in the for loop, it cannot be accessed at line 13.

### Q7
finalPrice will be printed to the console since it was defined in the same block.

### Q8
This function will return the correctly computed array discounted as explained earlier. This time the variables are defined using let, however the variables inside the for loop are only used within the for loop, so the function still works normally.

### Q9
This code will return an error, since i is only locally defined in the for loop, and cannot be accessed at line 11.

### Q10
The length variable will be printed to the console

### Q11
This function will return the discounted array with updated discounted prices. They have not been rounded unlike earlier but other than that the function operates the same, since the const declerations are not violated.

### Q12
###### a:
    student.name;

###### b:
    student["Grad Year"];

###### c:
    student.greeting();

###### d:
    student['Favorite Teacher']name;

###### e:
    student.courseLoad[1];

### Q13
###### a:
output: '32'
2 was appended to the string '3'
###### b:
output: 1
3 was converted to an int and two was subtracted from 3 to make 1

###### c:
output: 3
The int 3 was returned since null is equivalent to 0 as a number

###### d:
output: '3null'
null was converted to a string and appended to the string '3'

###### e:
output: 4
Since true converted to a number is 1, 1+3 returns 4

###### f:
output: 0
Since false as a number is 0, and null as a number is a 0, their sum is 0

###### g:
output: '3undefined'
undefined is appended to the string '3'

###### h:
output: NaN
undefined does not convert to a number so the subtraction is impossible

### Q14
###### a:
output: true
'2' is read as a number greater than 1

###### b:
output: false
in the alphabet, 1 comes before 2

###### c:
output: true
the string is converted to the number 2, which is equal to lhs 2

###### d:
output: false
since '2' and 2 are not the same type

###### e:
output: false
true is converted to 1, which is not equal to 2

###### f:
output: true
typecasting any number over 0 to a bool will return true, which is equal to true

### Q15
== checks for equality after performing neccesary conversion, whereas === checks for the same type as well as that the values are equal

### Q17
newArr will contain all of the numbers in the initial array after the callbakc function is performed on them.
In this case the callback function doSomething multiplies the number by two. Therefore the newArr will contain [2, 4, 6].

### Q19
The output is:
1 3 4 2




