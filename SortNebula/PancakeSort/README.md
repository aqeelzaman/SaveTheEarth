Pancake Sort


CODE EXPLANATION:


Lines 1-8 creates the key-value pair according to the entry given by the user and prints the dictionary.

Lines 10-11 creates two lists, one containing the keys only called 'l' and one empty called 'm'. L is the unsorted list and it is printed.

Lines 27-34 sorts the list using two functions.
This sorting works in the way like stacking the pancakes according to the size.
The biggest element is found and the list from the beginning is flipped until the biggest number. Then the whole list is flipped. 
The last element will become the biggest number. so in the next iteration, the last element is ignored and then the rest undergoes 
the same procedure. this continues until all the elements are sorted

Lines 12-20 is the function that flips the list according to the arguments given

Lines 22-25 is a function which adds the biggest element at the end to the empty list m and then replaces the last biggest element in l
with 0 so that it doesnt interfere in next iterations. At the end, l becomes a list of 0s and m becomes the sorted list.

Finally the sorted list of keys are printed.
