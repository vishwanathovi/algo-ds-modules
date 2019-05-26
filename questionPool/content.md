Note: Still need to figure out a tool where the questions can be listed and
  * tagged with multiple tags(arrays, recursion etc)
  * rated according to difficulty
  * hints and parallel implementations explained
  * Time complexity and space complexity targets are set
  * prerequisite concepts to be known before attempting


## Array

  1. Implement an algorithm to determine if a string has all unique characters. What if you
  can not use additional data structures?
  ___________________________________

  2. Design an algorithm and write code to remove the duplicate characters in a string
without using any additional buffer. NOTE: One or two additional variables are fine.
An extra copy of the array is not.
FOLLOW UP
Write the test cases for this method

----------------------------------------

3. Write a method to decide if two strings are anagrams or not.

-----------------------------------------

4. Given an image represented by an NxN matrix, where each pixel in the image is 4
bytes, write a method to rotate the image by 90 degrees. Can you do this in place?

5. Write an algorithm such that if an element in an MxN matrix is 0, its entire row and
column is set to 0.

6. Assume you have a method isSubstring which checks if one word is a substring of
another. Given two strings, s1 and s2, write code to check if s2 is a rotation of s1 using
only one call to isSubstring (i.e., “waterbottle” is a rotation of “erbottlewat”).

## Linked List

1. Write code to remove duplicates from an unsorted linked list.
FOLLOW UP
How would you solve this problem if a temporary buffer is not allowed?

2. Implement an algorithm to find the nth to last element of a singly linked list.

3. Implement an algorithm to delete a node in the middle of a single linked list, given
only access to that node.

4. Given a circular linked list, implement an algorithm which returns node at the begin-
ning of the loop.
DEFINITION
Circular linked list: A (corrupt) linked list in which a node’s


# Stacks & Queues

1. Describe how you could use a single array to implement three stacks.

2. How would you design a stack which, in addition to push and pop, also has a function
min which returns the minimum element? Push, pop and min should all operate in
O(1) time.

3. Imagine a (literal) stack of plates. If the stack gets too high, it might topple. There-
fore, in real life, we would likely start a new stack when the previous stack exceeds
some threshold. Implement a data structure SetOfStacks that mimics this. SetOf-
Stacks should be composed of several stacks, and should create a new stack once
the previous one exceeds capacity. SetOfStacks.push() and SetOfStacks.pop() should
behave identically to a single stack (that is, pop() should return the same values as it
would if there were just a single stack).
FOLLOW UP
Implement a function popAt(int index) which performs a pop operation on a specific
sub-stack.

4. Implement a MyQueue class which implements a queue using two stacks.

5. In the classic problem of the Towers of Hanoi, you have 3 rods and N disks of different
sizes which can slide onto any tower. The puzzle starts with disks sorted in ascending
order of size from top to bottom (e.g., each disk sits on top of an even larger one). You
have the following constraints:
(A) Only one disk can be moved at a time.
(B) A disk is slid off the top of one rod onto the next rod.
(C) A disk can only be placed on top of a larger disk.
Write a program to move the disks from the first rod to the last using Stacks.

6. Write a program to sort a stack in ascending order. You should not make any assump-
tions about how the stack is implemented. The following are the only functions that
should be used to write this program: push | pop | peek | isEmpty.

## Puzzles & brain teasers

1. Add arithmetic operators (plus, minus, times, divide) to make the following expres-
sion true: 3 1 3 6 = 8. You can use any parentheses you’d like.

2. There is an 8x8 chess board in which two diagonally opposite corners have been cut
off. You are given 31 dominos, and a single domino can cover exactly two squares.
Can you use the 31 dominos to cover the entire board? Prove your answer (by provid-
ing an example, or showing why it’s impossible).

3. You have a five quart jug and a three quart jug, and an unlimited supply of water
(but no measuring cups). How would you come up with exactly four quarts of water?
NOTE: The jugs are oddly shaped, such that filling up exactly ‘half’ of the jug would
be impossible.

4. A bunch of men are on an island. A genie comes down and gathers everyone to-
gether and places a magical hat on some people’s heads (i.e., at least one person has
a hat). The hat is magical: it can be seen by other people, but not by the wearer of
the hat himself. To remove the hat, those (and only those who have a hat) must dunk
themselves underwater at exactly midnight. If there are n people and c hats, how
long does it take the men to remove the hats? The men cannot tell each other (in any
way) that they have a hat.
FOLLOW UP
Prove that your solution is correct.

5. There is a building of 100 floors. If an egg drops from the Nth floor or above it will
break. If it’s dropped from any floor below, it will not break. You’re given 2 eggs. Find
N, while minimizing the number of drops for the worst case.

6. There are one hundred closed lockers in a hallway. A man begins by opening all one
hundred lockers. Next, he closes every second locker. Then he goes to every third
locker and closes it if it is open or opens it if it is closed (e.g., he toggles every third
locker). After his one hundredth pass in the hallway, in which he toggles only locker
number one hundred, how many lockers are open?


## Question marked as moderate in the book - cracking the coding interview

19.1 Write a function to swap a number in place without temporary variables.
_ _ _______________________________________________________________pg 265
19.2 Design an algorithm to figure out if someone has won in a game of tic-tac-toe.
_ _ _______________________________________________________________pg 266
19.3 Write an algorithm which computes the number of trailing zeros in n factorial.
_ _ _______________________________________________________________pg 268
19.4 Write a method which finds the maximum of two numbers. You should not use if-
else or any other comparison operator.
EXAMPLE
Input: 5, 10
Output: 10
________________________________________________________________pg 269
19.5
The Game of Master Mind is played as follows:
The computer has four slots containing balls that are red (R), yellow (Y), green (G) or
blue (B). For example, the computer might have RGGB (e.g., Slot #1 is red, Slots #2 and
#3 are green, Slot #4 is blue).
You, the user, are trying to guess the solution. You might, for example, guess YRGB.
When you guess the correct color for the correct slot, you get a “hit”. If you guess
a color that exists but is in the wrong slot, you get a “pseudo-hit”. For example, the
guess YRGB has 2 hits and one pseudo hit.
For each guess, you are told the number of hits and pseudo-hits.
Write a method that, given a guess and a solution, returns the number of hits and
pseudo hits.
________________________________________________________________pg 270
19.6
Given an integer between 0 and 999,999, print an English phrase that describes the
integer (eg, “One Thousand, Two Hundred and Thirty Four”).
________________________________________________________________pg 271
19.7
You are given an array of integers (both positive and negative). Find the continuous
sequence with the largest sum. Return the sum.
EXAMPLE
Input: {2, -8, 3, -2, 4, -10}
Output: 5 (i.e., {3, -2, 4} )
________________________________________________________________pg 273
19.8
89
Design a method to find the frequency of occurrences of any given word in a book.


19.9
Since XML is very verbose, you are given a way of encoding it where each tag gets
mapped to a pre-defined integer value. The language/grammar is as follows:
Element --> Element Attr* END Element END [aka, encode the element

tag, then its attributes, then tack on an END character, then

encode its children, then another end tag]
Attr --> Tag Value [assume all values are strings]
END --> 01
Tag --> some predefined mapping to int
Value --> string value END
Write code to print the encoded version of an xml element (passed in as string).
FOLLOW UP
Is there anything else you could do to (in many cases) compress this even further?
________________________________________________________________pg 275
19.10 Write a method to generate a random number between 1 and 7, given a method
that generates a random number between 1 and 5 (i.e., implement rand7() using
rand5()).
________________________________________________________________pg 277
19.11 Design an algorithm to find all pairs of integers within an array which sum to a speci-
fied value.
__________


## Question marked as hard in the book - cracking the coding interview

20.1 Write a function that adds two numbers. You should not use + or any arithmetic op-
erators.
________________________________________________________________pg 279
20.2 Write a method to shuffle a deck of cards. It must be a perfect shuffle - in other words,
each 52! permutations of the deck has to be equally likely. Assume that you are given
a random number generator which is perfect.
________________________________________________________________pg 281
20.3 Write a method to randomly generate a set of m integers from an array of size n. Each
element must have equal probability of being chosen.
________________________________________________________________pg 282
20.4 Write a method to count the number of 2s between 0 and n.
_ _ _______________________________________________________________pg 283
20.5 You have a large text file containing words. Given any two words, find the shortest
distance (in terms of number of words) between them in the file. Can you make the
searching operation in O(1) time? What about the space complexity for your solu-
tion?
________________________________________________________________pg 285
20.6 Describe an algorithm to find the largest 1 million numbers in 1 billion numbers. As-
sume that the computer memory can hold all one billion numbers.
________________________________________________________________pg 286
20.7
Write a program to find the longest word made of other words in a list of words.
EXAMPLE
Input: test, tester, testertest, testing, testingtester
Output: testingtester
________________________________________________________________pg 287
20.8 Given a string s and an array of smaller strings T, design a method to search s for each
small string in T.
________________________________________________________________pg 288
20.9 Numbers are randomly generated and passed to a method. Write a program to find
and maintain the median value as new values are generated.
________________________________________________________________pg 290
20.10 Given two words of equal length that are in a dictionary, write a method to transform
one word into another word by changing only one letter at a time. The new word you
get in each step must be in the dictionary.
EXAMPLE
Input: DAMP, LIKE
Output: DAMP -> LAMP -> LIMP -> LIME -> LIKE
________________________________________________________________pg 291
20.11 Imagine you have a square matrix, where each cell is filled with either black or white.
Design an algorithm to find the maximum subsquare such that all four borders are
filled with black pixels.
________________________________________________________________pg 293
20.12 Given an NxN matrix of positive and negative integers, write code to find the sub-
matrix with the largest possible sum.
________________________________________________________________pg 295
20.13 Given a dictionary of millions of words, give an algorithm to find the largest possible
rectangle of letters such that every row forms a word (reading left to right) and every
column forms a word (reading top to bottom).
_________________________________________
