COMP 313/413 Project 2 Report Template

TestList.java and TestIterator.java

	TODO also try with a LinkedList - does it make any difference?

	no difference, 

		

TestList.java

	testRemoveObject()

		list.remove(5); // what does this method do?

			Removes item at 5th position [1, 2, 3, 4, 5, (6) <--, 7]

		list.remove(Integer.valueOf(5)); // what does this one do?
			
			removes integer from list whos value is 5
			

TestIterator.java

	testRemove()

		i.remove(); // what happens if you use list.remove(77)?

			if i use list.remove(77) it will remove the 77th value of the list

TestPerformance.java

	State how many times the tests were executed for each SIZE (10, 100, 1000 and 10000)
	to get the running time in milliseconds and how the test running times were recorded.
	These are examples of SIZEs you might choose, you can choose others if you wish.

	SIZE 10  (1,000,000 reps)
								  #1   #2   #3   #4   #5   #6 	... (as many tests as you ran)
       	testArrayListAddRemove:   221 222 225 225 227 224
	testLinkedListAddRemove:   10  10  20  20  15  13
	testArrayListAccess:        0   4   5   6   4   9
	testLinkedListAccess:      10   8   8   5   8  10

	SIZE 100 (1,000,000 reps)
								  #1   #2   #3   #4   #5   #6 	... (as many tests as you ran)
       	testArrayListAddRemove:   322 344 319 299 365 366
	testLinkedListAddRemove:   20  22  29  25  22  24
	testArrayListAccess:        8   9  10   5  12  11
	testLinkedListAccess:      11  21  20   8   6  10

	SIZE 1000 (500,000) 
								  #1   #2   #3   #4   #5   #6 	... (as many tests as you ran)
       	testArrayListAddRemove:   172 156 186 190 192 198
	testLinkedListAddRemove:   23  20  25  24  23  23
	testArrayListAccess:        6   4   5  11   6   4
	testLinkedListAccess:      12  16  16  16  16  17

	SIZE 10000 (100,000)
								  #1   #2   #3   #4   #5   #6 	... (as many tests as you ran)
       	testArrayListAddRemove:    96 131 117 129 125 124
	testLinkedListAddRemove:   10  12   0  11  10   7
	testArrayListAccess:        0   0   0   0   0   0
	testLinkedListAccess:     292 287 284 298 317 275

	listAccess - which type of List is better to use, and why?

		Array list access is better to use as it has quicker access time.

	listAddRemove - which type of List is better to use, and why?

		LinkedList is much faster for removing and adding.
