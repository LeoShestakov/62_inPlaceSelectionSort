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
will grow by 3x.
[Since every element will need to be analyzed and placed accordingly in the sorted ArrayList. The cost of construction is linear]

0. If the number of the elements in the input triples,
the number of times that the reigning champ algorithm
will be invoked will grow by 3x.
[Since champIndex is called once in the for loop per observed element index]

0. If the number of the elements in the input triples,
the time required for the selection sort will grow by 9x.
[The time required will grow by 3x, and champIndex will be invoked 3x more times per observed element index. This means that overall, the time required for the selection sort will grow by 3 * 3 = 9x]
