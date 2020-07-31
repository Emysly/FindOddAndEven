# FindOddAndEven
A Program to find the frequency of odd &amp; even numbers in the given matrix

In this program, we need to find the frequencies of odd and even numbers present in the matrix.

Java Program to find the frequency of odd & even numbers in the given matrix
![](https://static.javatpoint.com/corebasic/programs/images/java-program-to-find-the-frequency-of-odd-and-even-numbers-in-the-given-matrix.png)


In the above example, all odd numbers are represented by the blue square and even numbers are represented by red circles. To find the frequencies of odd and even numbers, loop through the array and check if the element of the array is divisible by 2. If it is divisible by 2(even) then, increment the count of countEven by 1. Else, increment the countOdd by 1.

###Psuedocode

* STEP 1: START
* STEP 2: DEFINE rows, cols
* STEP 3: SET countOdd = 0, countEven =0
* STEP 4:INITIALIZE matrix a[][] ={{4,1,3},{3, 5, 7}, {8, 2, 6}}
* STEP 5: rows = a.length
* STEP 6: cols = a[0].length
* STEP 7: REPEAT STEP 8 to STEP 9 UNTIL i<rows for(i=0; i<rows; i++)
* STEP 8: REPEAT STEP 9 UNTIL j<cols
* STEP 9: if(a[i][j]%2 ==0)
        countEven++
        else
        countOdd++
* STEP 10: PRINT "Frequency of odd numbers " by assigning countOdd.
* STEP 11: PRINT "Frequency of even numbers " by assigning countEven
* STEP 12: END
