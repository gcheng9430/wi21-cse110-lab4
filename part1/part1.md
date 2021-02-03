1. The console will print whatever prices.length is becuase the variable i is declared in the for loop, which is not inside a function, and because var has no block scope so it is function-scoped 

2. The console will print the last discountedPrice calculated using the last element in prices in the for loop because the discountedPrice is declared in the for loop and is thus function-scoped. And because var tolerates redeclarations, there won't be any error.

3. The console will print the last finalPrice calculated in the for loop becaue the finalPrice variable is declared within the function and is thus function-scoped. 

4. The function will return [50,100,150] becuase the for loop uses the input for discount to caculate discounted price for each price from prices input and adds that to the array variable discounted. Since descounted is declared and modified inside the function, the function is able to return it. 

5. There will be an error becuase i is declared using let in the for loop and thus has a block scope.

6. There will be an error because discountedPrice is declared using let in the for loop and thus has a block scope.

7. The console will print the last finalPrice calculated using the last element of prices because finalPrice is declared inside the function outside the forloop and has a function scope.

8. The function will return [50,100,150] because discounted is declared outsdie the for loop inside the funtion and has a function scope. 

9. There will be an error because i is delcred using let inside the for loop and has a blockscope.

10. The console will print the last discounted price calculated because in each iteration a new const variable discountedPrice is created because const has block scope. 

11. The console will print 0 because finalPrice is a const declared insdie the function and thus has a function scope but can not be modified.

12. The function will return [] because discounted is a const variable that could not be changed. 

13.A student.name

   B student['Grad Year']
   
   C student.greeting
   
   D student['Favorite Teacher'].name
   
   E student.courseLoad[0]

14. A '32' because a number is concatenated with a string using plus sign 

    B 1 because string is converted to number in math operations
    
    C 3 because null is converted to 0 in math operations
    
    D '3null' because null is converted to string and concatenated to the previous one using plus sign
    
    E 4 because true is converted to 1 in math operationsfal
    
    F 0 because false and null are both converted to 0 in math operations
    
    G '3undefined' because undefined is converted to string in string concatenation
    
    H NaN because undefined is converted to NaN in math operations
 
 15. A true because 2 is converted to number in comparisons
 
     B false becasue both numbers are converted to numbers in comparisons 
     
     C true because string is converted to number in non strict equality check
     
     D false because they are different value, which is not equal in strict equality check
     
     E false becuase true is converted to 1 in euqality check
     
     F true because 2 is converted to boolean, which is true

16. == is equality check and can compare value of different types. === is strict equality check, which returns false if two values are of different type. Null and undefined are euqal using == but not ===.

17. 'How are you?' gets printed beacuse 2 == true will return false sincetrue is converted to 1 in equality checks. Thus we move to the second condition, and because 2 is converted to true in logical operations, we print 'How are you?' and ignore the third condition.









