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
