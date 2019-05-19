Pigeonhole Sort


CODE EXPLANATION:


Lines 1-8 creates and prints a key-value pair as a dictionary as per the user given details.

Lines 24-28 creates a list 'm' with the keys of the dictionary. It also finds out the maximum, minimum values of keys and
get the value of range 'R' as 'max-min+1'

Line 29 calls the function

Lines 10-22 is the function which implements the Pigeonhole sort.
It first creates a list with the size of range R, filling it with zeros. Next, each element of m is subtracted the value of
mini and now that is its index position. it is added to that index position in lines 12-13. this will include a list of 0s and 1s.
The values are now known where to be placed so Lines 17-21 places the elements back in a new list 'a' with
length of m. it places in the correct sorted position with help of the list of 0s and 1s made earlier.

Finally the sorted list of keys are printed. 
