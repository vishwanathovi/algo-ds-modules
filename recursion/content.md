## Recursion Study Material

1. [Recursion - khanacademy](https://www.khanacademy.org/computing/computer-science/algorithms/recursive-algorithms/a/recursion)
 - Finish the recursive factorial challenge


2. Write a recursive function to sum a list of numbers
 - Hint:--> Which is the simplest case where the answer can be solved directly
 - [Read after solving](https://interactivepython.org/courselib/static/pythonds/Recursion/pythondsCalculatingtheSumofaListofNumbers.html)


3. [Properties of recursive algorithms](https://www.khanacademy.org/computing/computer-science/algorithms/recursive-algorithms/a/properties-of-recursive-algorithms)

4. Practise Problems
  - (a) Write a program for checking if a string is a palindrome - [Solution](https://www.khanacademy.org/computing/computer-science/algorithms/recursive-algorithms/a/using-recursion-to-determine-whether-a-word-is-a-palindrome)

  - (b) Write a code for calculating the x^n where n can be any integer (negative also). Write a solution which is O(log(n)). - [Solution](https://www.khanacademy.org/computing/computer-science/algorithms/recursive-algorithms/a/computing-powers-of-a-number)

  - (c) Change the base of a number. Input parameters will be a number in base 10 and the base to convert it to. Output will be string containing number in a different base.(assume base <= 10)

      `fun(8,2) → “1000”`

      [Solution reference](https://interactivepython.org/courselib/static/pythonds/Recursion/pythondsConvertinganIntegertoaStringinAnyBase.html)      

      Now solve the above problem using stack to store the result of each recursive call - [Solution reference](https://interactivepython.org/courselib/static/pythonds/Recursion/StackFramesImplementingRecursion.html)

  - (d) [Practise questions -](https://www.geeksforgeeks.org/recursion/) go through practise questions set 1 to 7


5. Recursive Problems with multiple recursive calls(Optional, Intermediate-Hard)
    - Tower Of Hanoi

      Implement a tower of Hanoi solution which lists the moves made.
      [Read this before starting](https://www.khanacademy.org/computing/computer-science/algorithms/towers-of-hanoi/a/towers-of-hanoi)

    E.g. moveTower(3,"A","B","C") should give

    ```
    moving disk 1 from A to B
    moving disk 2 from A to C
    moving disk 1 from B to C
    moving disk 3 from A to B
    moving disk 1 from C to A
    moving disk 2 from C to B
    moving disk 1 from A to B
    ```

    Bonus: Use a counter to count the number of the move being made. For e.g. the 3rd line of output for the earlier example will look like,
    3: moving disk 1 from B to C -
    [Solution](https://interactivepython.org/courselib/static/pythonds/Recursion/TowerofHanoi.html)

Maintaining State
Read Section Return types from the following article
https://www.byte-by-byte.com/recursion/#section4

#### Practise questions
 - Recursive selection sort:
 - Recursive insertion sort
 - Recursive Bubble sort (Hint: For selection sort at kth pass first k elements are sorted. Is there a similar structure for bubble sort?)
 - Write a code to combine two merged arrays (No need to use recursion)
 - Merge Sort


Backtracking
Divide and conquer Algorithms
Dynamic Programming
Maze Traversal
Tail Recursion
Memorization
