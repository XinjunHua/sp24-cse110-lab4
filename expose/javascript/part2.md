1. line 12 prints "3", because prices.length=3.
2. line 13 prints 150. This is because it prints the very last discounted price, which is 300 * 0.5 = 150.
3. line 14 prints 150. This is because final price is the very last discounted price rounded, which is 150.
4. This function returns [ 50, 100, 150 ], because discounted is a list pushed with all the final prices.
5. line 12 throws the error "ReferenceError: i is not defined". This is because let is block scoped, and line 12 is out of the block i belongs to.
6. line 13 throws the error "ReferenceError: discountedPrice is not defined". This is because discountedPrice is let type, so it's block scoped. Line 13 is out of the block.
7. line 14 prints 150. line 14 is within the block of discounted, so it can successfully return the value. 
8. This function returns [ 50, 100, 150 ]. The return line is within the block of discounted, so it can successfully return the value of discounted. 
9. line 11 throws the error "ReferenceError: i is not defined". This is because i is a let, which is block scoped. i is only defined in the for block. Line 11 is not within the for block.
10. line 12 prints 3. This is because line 14 is within the block of length.
11. This functions returns [ 50, 100, 150 ]. The function can execute successfully, because the for loop didn't change any pre-defined const value. 
12. 
    A. student.name

    B. student['Grad Year']

    C. student.greeting()

    D. student['Favourite Teacher'].name

    E. student.courseLoad[0]

13. A. '32'. Because integer 2 maps to string '2'.
    B. 1. Because string '3' maps to interger 3.
    C. 3. Integer 3 plus null is 3.
    D. '3null'. Becuase integer 3 converts to string '3' then concatenates with 'null'.
    E. 4. Because true maps to 1.
    F. 0. Both false and null are treated as 0.
    G. '3undefined'. Because interger 3 converts to string '3' then concatenates with 'undefined'.
    H. NaN. NaN means not a number. Undefined can't be mapped into a value, so the result is NaN.

14. A. True. '2' maps to integer 2, which is > 1.
    B. False. '2' and '12' are both strings, so their comparision is character by character. ASCII of '2' is larger than ASCII of '1'.
    C. True. '2' maps to integer 2, which is = 2.
    D. False. === operator doesn't perform type conversion. ASCII of '2' is not equal to 2.
    E. False. True maps to integer 1, which is != 2.
    F. True. Boolean(2) is true. 

15.  The == operator compares the values of two variables after performing type conversion if necessary, while the === operator compares the values of two variables without performing type conversion.
16.  see part2-question16.js.
17.  The result is [2, 4, 6]. For each element in the array parsed, the callback function is performed(in this scenario it's doSomething). So, the result is [2,4,6].
18.  see part2-question18.js.
19.  It prints 1, 4, 3, and waits for a while and prints 2.