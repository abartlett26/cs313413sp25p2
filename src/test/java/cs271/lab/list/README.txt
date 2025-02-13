TestIterator Questions
1. array list is faster than linked list. array list finished in 280ms and the linked list
finished in 341ms. the linked list is slower because the pointer dereferencing is causing
it to take more time.
2. if you use list.remove(Integer.valueOf(77)), it will say that the test has failed. this
is because it is only removing the first 77, rather than all the integers in the list that
are equal to 77.


TestList Questions
1. linked list finished in 286ms and the array list finished in 291ms. the linked list is
better for finding insertion points and doing the actual insertions.
2. list.remove(5) removes 77. it is not deleting the integer 5, but rather the number at
index 5.
3. list.remove(Integer.valueOf(5)) is doing the opposite. it is deleting the number 5 at
whatever index it is.

TestPerformance Questions
1. a linked list is better for adding or removing elements when it is at the beginning, because
it is not shifting elements, just updating the pointers. on the other hand, an array list is
better when accessing elements in the middle of the list, because it allows for a smaller time
complexity.