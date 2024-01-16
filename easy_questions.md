# Problem No. 1

## Write a Python program to check if a string is a palindrome.

A palindrome is a number or letter that remains the same even if the number and letters are inverted.

 For example:
 
                    121, 11, 414, 1221, 74747 are the palindrome numbers.
                    MOM, DAD, MADAM, REFER are the palindrome letters.       
                    JAVATPOINT, PROGRAM, JAVA are not the palindrome letters.

Write a function **if_palindrome(input_list: list)** in solution.py which will return a list of all the elements of **input_list** that are palindrome.


# Problem No. 2

## Prime number.
If the natural number is greater than 1 and having no positive divisors other than 1 and the number itself etc.

For example: 

              3, 7, 11 etc are prime numbers.

Write a function **prime_numbers(p, q)** in solution.py which will return a list of all the prime numbers between p and q inclusive.



# Problem No. 3

## Flatten List.
Flattening a list of lists is a process of transforming a two-Dimensional list into a One-Dimensional list by un-nesting every list element kept in the list of lists

For example:
    
                i/p: [[9, 8, 7], [6, 5, 4], [3, 2, 1]] 
                o/p: [9, 8, 7, 6, 5, 4, 3, 2, 1]

Write a function **flatten(input_list: list)** (*where **input_list** is a nested list with random depth*)  in solution.py which will flatten the input_list and return the flattened list.



# Problem No. 4

## Number Addition.

Example:  

                    Input: [12, 15, 3, 10]
                    Output: 40
                
                    Input: [17, 5, 3, 5]
                    Output: 30

Write a function **add_list(input_list: list)**, *where **input_list** contains **n** numbers each having **m** digits in it*, in solution.py which will return the sum of all the numbers in the input_list.



# Problem No. 5

## Merge Two Sorted Arrays.

Example:  

                    Input: nums1 = [1, 2, 3, 0, 0, 0], m = 3, nums2 = [2, 5, 6], n = 3 
                    Output: [1, 2, 2, 3, 5, 6]

Write a function **merge_list(list1: list, list2: list)**, in solution.py to merge given two sorted lists into single sorted list. 



# Problem No. 6

## Remove Duplicates from a Sorted Array.

Example:  

                    Input: [1, 1, 2, 2, 3, 4, 4, 5] 
                    Output: [1, 2, 3, 4, 5]

Write a function **remove_duplicates(input_list: list)**, in solution.py to remove all the duplicate elements in the given list. 



# Problem No. 7

## Union of Two Arrays.

Example:  

                    Input: nums1 = [1, 2, 2, 1], nums2 = [2, 2] 
                    Output: [1, 2]

Write a function **union(list1: list, list2: list)**, in solution.py to find their union (all unique elements from both arrays). 



# Problem No. 8

## Intersection of Two Arrays.

Example:  

                    Input: nums1 = [1, 2, 2, 1], nums2 = [2, 2] 
                    Output: [2]

Write a function **find_intersection(list1: list, list2: list)**, in solution.py to find their union (all unique elements from both arrays). 



# Problem No. 9

## Reverse Words in a String

Example:  

                    Input: "Hello World!" 
                    Output: "World! Hello"

Write a function **reverse_words(input_string: str)**, in solution.py to reverse the order of words in it. 



# Problem No. 10

## nth fibonacii number

The Fibonacci numbers are the numbers in the following integer sequence. 0, 1, 1, 2, 3, 5, 8, 13, 21, 34, 55, 89, 144, …….. 

In mathematical terms, the sequence Fn of Fibonacci numbers is defined by the recurrence relation.

                              Fn = Fn-1 + Fn-2
                              with seed values : F0 = 0 and F1 = 1.   
                              
Write a function **nth_fibonacii(n)**, in solution.py to find the nth number in the fibonacii sequence. 
