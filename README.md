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
will grow by __________________ (3 times).
[Justify, in about 2 sentences.]
The reigning champ algorithm goes through all elements once when comparing.
Increasing the number of elements by a factor increases the time by that factor.

0. If the number of the elements in the input triples,
the number of times that the reigning champ algorithm
will be invoked 
will grow by __________________ (3 times).
[Justify, in about 2 sentences.]
The reigning champ algorithm is invoked for each element in the list.
Increasing the number of elements by a factor increases the number of invocations by that factor.

0. If the number of the elements in the input triples,
the time required for the selection sort
will grow by __________________ (9 times.
[Justify, in about 2 sentences.]
The reigning champ algorithm is invoked 3x more, and it takes 3x more time.
This means that overall it takes 9x more time if the number of elements triple.
