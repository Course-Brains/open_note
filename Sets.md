Sets are lists of elements which have no repeats and no particular order.
Lists are written with {} and comma separation between elements:
	{1, 2, 3}
# Set operations
### Union
Union is shown with $\cup$ (\cup) and outputs a set of elements which are in either of the sets given to it.
$$
\{1, 2, 3\} \cup \{3, 4, 5\} = \{1, 2, 3, 4, 5\}
$$
Notice how the 3 did not get duplicated.
### Intersection
Intersection is shown with $\cap$ (\cap) and outputs a set of elements which are in both sets given to it.
$$
\{1, 2, 3\} \cap \{3, 4, 5\} = \{3\}
$$
### Set difference
Set difference is show with $\setminus$ (\setminus) and outputs a set of elements which are in the first set and not in the second. Because of this, $x\setminus y \ne y \setminus x$
$$
\{1, 2, 3\} \setminus \{3, 4, 5\} = \{1, 2\}
$$
### Cartesian product
The cartesian product is shown with $\times$ (\times) and outputs a set of all possible combinations of the elements in the sets given to it with order within the pair mattering.
$$
\{1, 2, 3\} \times \{3, 4, 5\} = \{(1, 3), (1, 4), (1,5), (2,3), (2, 4), (2,5), (3, 3), (3,4), (3,5)\}
$$
As you can see, the order within the pair does matter, which is why $(1, 3)$ is a pair in the output, but $(3, 1)$ is not.
### Cardinality
Cardinality is shown with $| |$ (| |) and outputs the number of elements in the list.
$$
|\{1, 2, 3\}| = 3
$$
For a bit of a shortcut:
$$
|x \times y| = |x| \times |y|
$$
For finite sets $x$ and $y$
# Statements
Just like how normal math as the equal sign to say that two inputs are equivalent, sets also have statements.
### In
You state that an element is in a set with $\in$ (\in)
$$
2 \in \{1, 2, 3\}
$$
### Subset
You state that all elements of a set are within a different set using $\subset$ (\subset)
$$
\{1, 2\} \subset \{1, 2, 3\}
$$
Notably, this remains a valid statement if both are equal
$$
\{1, 2, 3\} \subset \{1, 2, 3\}
$$
### Proper subset
A proper subset is like a regular [[#Subset|subset]] except that it also states that the two sets are not equal. It is shown with $\subseteq$ (\subseteq)
$$
\{1, 2\} \subseteq \{1, 2, 3\} 
$$
Is valid, while
$$
\{1, 2, 3\} \subseteq \{1, 2, 3\}
$$
Would not be.
# Constants
### Natural numbers
It includes every positive non-zero integer. It is shown with $\mathbb N$ (\mathbb N)
$$
\mathbb N = \{1, 2, 3, 4, 5, \dots, \infty\}
$$
### Natural numbers including 0
It is a shortened notation of $\mathbb N \cup 0$ aka [[#Natural numbers]] including 0 and is shown as $\mathbb N_0$ (\mathbb N_0)
$$
\mathbb N_0 = \{0, 1, 2, 3, 4, \dots, \infty\}
$$
#### Integers
The set of all integers. It is shown with $\mathbb Z$ (\mathbb Z)
$$
\mathbb Z = \{-\infty, \dots, -3, -2, -1, 0, 1, 2, 3, \dots, \infty\}
$$
### Rational numbers
The set of all rational numbers. It is shown with $\mathbb Q$ (\mathbb Q) and is defined as:
$$
\mathbb Q = \{\frac nd | n \in \mathbb Z, d \in \mathbb N\}
$$
Meaning that any number is in the set of rational numbers if it can be represented as an [[#Integers|integer]] divided by a [[#Natural numbers|natural number]]
$$
\{1, -7, 43.5, -72.8\} \subseteq \mathbb Q
$$
### Real numbers
The set of all real numbers, it is shown as $\mathbb R$ (\mathbb R). It is defined as all numbers denoting distance and their negative counterparts[^1]. I personally do not know how that is different from the [[#Rational numbers]] but that is why this is shared.

[^1]: Thomas Jansen (Lecturer at Aberystwyth University)
