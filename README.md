# in-place selection sort

Rearrange
an unordered `ArrayList<Integer>`
and use it as the data in an `OrderedList_inArraySlots`.

The re-use is probably contrary to Java's conventions
for its built-in classes. But as a pedagogical tool,
it has the advantage of allowing
the User program to check that the sort
is done in-place.

## count the cost

0. If the number of the elements in the input triples,
the time required to run the reigning champ algorithm
will grow by 2 times because three times as many elements will have to be processed and transferred.
[Justify, in about 2 sentences.]

0. If the number of the elements in the input triples,
the number of times that the reigning champ algorithm
will be invoked 
will grow by 2 times for the above reason.
[Justify, in about 2 sentences.]

0. If the number of the elements in the input triples,
the time required for the selection sort
will grow by about 1.5 times because although there are 3 times as many elements, each time an element 
	is processed, the equivalent of processing 2 elements is accomplished.
[Justify, in about 2 sentences.]
