### Abstract

In this paper we describe an algorithm for extracting nearly every
relationship between every one column and every other column or
set of unique columns in a given dataset in a relatively easily
understandable manner.

Technically, we describe an algorithm which searches iterating
selections of one fixed column and another column or set of other
columns, whose number is defined by the user, for predefined
patterns when they’re taken as a collective in the frequencies of
unique row occurrences, and then output to the user, in relatively
easily read and understandable terms, conditional statements or
heuristic statements conveying those patterns observed like, “If X
is True and Y is True (where X and Y are constituent elements or
variables of the hypothesis), then Z is true (where Z is the
conclusion).”.

The motivation, behind the development of this algorithm, comes
from a background in machine learning where it’s seeming to
become crucial that the reasoning behind the output of an
estimator be relatively easily explainable to any person interacting
with it.

The methods developed for testing this algorithm were
rudimentary; we thought that if the algorithm was working
properly, then giving it a fixed dataset with prearranged
relationships between the features would cause it to pick up on the
patterns and output those relationships.
Thorough testing has not yet been done, for x vector of size 1
however in each demonstration the algorithm has worked
flawlessly.

In the future we intend to thoroughly test this algorithm and put
out a proper publication if it seems worthy of it.
The algorithm has at least partially theoretically and empirically
shown to be viable, further intensive testing will be required to
make anything of it.

<img width=500 align="center" alt="" src="https://github.com/user-attachments/assets/1bcd57bb-36e0-463f-820d-85960e7649a5"></img>
<img width=375 align="center" alt="" src="https://github.com/user-attachments/assets/e19c38ba-2270-4472-bd00-bc325d928c7d"></img>

