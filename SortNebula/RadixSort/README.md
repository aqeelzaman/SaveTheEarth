Radix Sort


CODE EXPLANATION:


Lines 1-5 is creating the dictionary for storing key-value pairs required for sorting.

Lines 23-26 is looking for the number with the maximum digits and saving it in the variable 'maxi'

Lines 28-32 creates the list 'm' containing only the keys to sort it. then with the help of maxi, all the numbers are made
to have maxi number of digits by adding trailing zeros to the beginning and converting it to strings.

Lines 9-21 is the sorting function. This takes the list m and sorts it by using Radix Method
Radix Method is the method of sorting list by taking the unit digit and placing all the 0 ending numbers in a queue, followed
by 1 ending numbers, then 2 ending and so on until it is done with 9 ending numbers.
Then the numbers are taken out of queue(Queue is FIFO-First In First Out). 
The second place digits are checked in same way, then third place and so on until all iterations are done.
After this the list would be sorted

Function has 3 for loops, first is for number of digits, second is for sorting into queues of 0-9 and third is to check the digits.
The list is then duplicated and cleared so as to start with fresh queue of partially sorted list and continued to next iterations.

Finally the sorted list of keys are printed
