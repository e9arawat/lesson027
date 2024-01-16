# Problem No. 1

A palindrome is a number or letter that remains the same even if the number and letters are inverted.

Write a function **if_palindrome(input_list: list)** in which will return a list of all the elements of **input_list** that are palindrome.

For example:
 
                    121, 11, 414, 1221, 74747 are the palindrome numbers.
                    MOM, DAD, MADAM, REFER are the palindrome letters.       
                    JAVATPOINT, PROGRAM, JAVA are not the palindrome letters.




# Problem No. 2

If the natural number is greater than 1 and having no positive divisors other than 1 and the number itself etc.

Write a function **prime_numbers(p, q)** in which will return a list of all the prime numbers between p and q inclusive.

For example: 

              3, 7, 11 etc are prime numbers.





# Problem No. 3

Flattening a list of lists is a process of transforming a two-Dimensional list into a One-Dimensional list by un-nesting every list element kept in the list of lists

Write a function **flatten(input_list: list)** (*where **input_list** is a nested list with random depth*)  in which will flatten the input_list and return the flattened list.

For example:
    
                i/p: [[9, 8, 7], [6, 5, 4], [3, 2, 1]] 
                o/p: [9, 8, 7, 6, 5, 4, 3, 2, 1]





# Problem No. 4

Write a function **add_list(input_list: list)**, *where **input_list** contains **n** numbers each having **m** digits in it*, in which will return the sum of all the numbers in the input_list.

Example:  

                    Input: [12, 15, 3, 10]
                    Output: 40
                
                    Input: [17, 5, 3, 5]
                    Output: 30




# Problem No. 5

Write a function **merge_list(list1: list, list2: list)**, in to merge given two sorted lists into single sorted list. 

Example:  

                    Input: nums1 = [1, 2, 3, 0, 0, 0], m = 3, nums2 = [2, 5, 6], n = 3 
                    Output: [1, 2, 2, 3, 5, 6]





# Problem No. 6

Write a function **remove_duplicates(input_list: list)**, in to remove all the duplicate elements in the given list. 

Example:  

                    Input: [1, 1, 2, 2, 3, 4, 4, 5] 
                    Output: [1, 2, 3, 4, 5]





# Problem No. 7

Write a function **union(list1: list, list2: list)**, in to find their union (all unique elements from both arrays). 

Example:  

                    Input: nums1 = [1, 2, 2, 1], nums2 = [2, 2] 
                    Output: [1, 2]





# Problem No. 8

Write a function **find_intersection(list1: list, list2: list)**, in to find their union (all unique elements from both arrays). 

Example:  

                    Input: nums1 = [1, 2, 2, 1], nums2 = [2, 2] 
                    Output: [2]





# Problem No. 9

Write a function **reverse_words(input_string: str)**, in to reverse the order of words in it. 

Example:  

                    Input: "Hello World!" 
                    Output: "World! Hello"





# Problem No. 10

The Fibonacci numbers are the numbers in the following integer sequence. 0, 1, 1, 2, 3, 5, 8, 13, 21, 34, 55, 89, 144, …….. 

In mathematical terms, the sequence Fn of Fibonacci numbers is defined by the recurrence relation.

                              Fn = Fn-1 + Fn-2
                              with seed values : F0 = 0 and F1 = 1.   
                              
Write a function **nth_fibonacii(n)**, in to find the nth number in the fibonacii sequence. 
