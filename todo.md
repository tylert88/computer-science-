## 01/24/2017

1. Consolidate exercises and curriculum from the gschool repo to:
  - https://github.com/gSchool/computer-science-curriculum
  - https://github.com/gSchool/computer-science-drills
1. Assess the current state of the curriculum, starting with the standards (what should be core vs. elective)
1. Add a few longer, practical exercises
1. Finalize the Python solutions at https://github.com/gSchool/computer_science_python_exercises
1. Possibly add in slides from https://github.com/gSchool/slides/tree/master/Programming
1. Possibly shorten the curriculum to just cover:
  - Memory and memory diagramming
  - OOP
  - Big O
  - Recursion
  - searching/sorting
  - linked lists as they are used in ...stacks & queues
  - tree traversal
  - graphs understand when to use breadth first/depth first searching

### Current Standards

1. [Explain the Big O of algorithms in O(1), O(n) and O(n^2)](https://github.com/gSchool/wdi-standards/blob/master/Programming/W0017%20-%20Big%20O%20Level%201.md)
1. [Determine the Big O of algorithms in the O(nm) space](https://github.com/gSchool/wdi-standards/blob/master/Programming/W0065%20-%20Big%20O%20Level%202.md)
1. [Explain the Big O of algorithms in the O(log n) and O(n log n) space](https://github.com/gSchool/wdi-standards/blob/master/Programming/W0062%20-%20Big%20O%20Level%203.md)
1. [Solve problems that require recursive iteration](https://github.com/gSchool/wdi-standards/blob/master/Programming/W0067%20-%20Recursive%20Iteration.md)
1. [Solve problems that require memory references](https://github.com/gSchool/wdi-standards/blob/master/Programming/W0068%20-%20Linked%20Lists.md)
1. [Solve problems that require swapping](https://github.com/gSchool/wdi-standards/blob/master/Programming/W0069%20-%20Swapping%20and%20Sorting.md)
1. [Solve problems that require tree traversal](https://github.com/gSchool/wdi-standards/blob/master/Programming/W0084%20-%20Tree%20Traversal.md)

---


* Include https://github.com/gSchool/graphs
* Include https://github.com/gSchool/graph-js/tree/master
* Add overview / description to readme
* Link files from outline
* Include reference links to http://www.csfieldguide.org.nz/ and https://github.com/open-source-society/computer-science and http://www.mattzeunert.com/2015/08/19/viewing-assembly-code-generated-by-v8.html, https://github.com/gSchool/google-cs-interview, http://jasonpark.me/AlgorithmVisualizer/#path=scratch/ef526a623afc44ab7d76f8cb5c9bc941

## Unit 0 - Fundamentals Part 1 (the concepts)
- Intro To Memory
- Memory Diagrams
- Memory Diagrams Exercises
- Binary
- **Add signed magnitude and two's complement**

## Unit 1 - Fundamentals Part 2 (the application)
- intro to Data Structures and Algorithms
- big O
- pointers
- recursion

## Unit 2 - DS + Algorithms Part 1
-  linked lists
-  doubly linked list
-  stacks and queues
-  bubble / insertion / selection sort / bogosort
-  binary search tree
-  hash tables
-  **Add Heap**

## Unit 3 - DS + Algorithms Part 2
- Trie
- Graphs (BFS / DFS)
- merge / quick sort
- **Add Skip List**
- **Add Heapsort / Radix Sort**

```
TECHNICAL
DOMAINS
Algorithm
Complexity:
It's
fairly critical that you understand big-O complexity analysis.
Again run some practice problems to get this down in
application.
Sorting:
Know
how to sort. Don't do bubble-sort. You should know the details of
at least one n*log(n) sorting algorithm, preferably two (say,
quicksort and merge sort). Merge sort can be highly useful in
situations where quicksort is impractical, so take a look at
it.
Hashtables:
Arguably
the single most important data structure known to mankind. You
absolutely should know how they work. Be able to implement one
using only arrays in your favorite language, in about the space of
one interview.
Trees:
Know
about trees; basic tree construction, traversal and manipulation
algorithms. Familiarize yourself with binary trees, n-ary trees,
and trie-trees. Be familiar with at least one type of balanced
binary tree, whether it's a red/black tree, a splay tree or an AVL
tree, and know how it's implemented. Understand tree traversal
algorithms: BFS and DFS, and know the difference between inorder,
postorder and preorder.
Graphs:
Graphs
are really important at Google. There are 3 basic ways to represent
a graph in memory (objects and pointers, matrix, and adjacency
list); familiarize yourself with each representation and its pros
& cons. You should know the basic graph traversal algorithms:
breadth-first search and depth-first search. Know their
computational complexity, their tradeoffs, and how to implement
them in real code.
If
you get a chance, try to study up on fancier algorithms, such as
Dijkstra and A*.
Other
data structures:
You
should study up on as many other data structures and algorithms as
possible. You should especially know about the most famous classes
of NP-complete problems, such as traveling salesman and the
knapsack problem, and be able to recognize them when an interviewer
asks you them in disguise. Find out what NP-complete
means.
Mathematics:
Some
interviewers ask basic discrete math questions.  This is more
prevalent at Google than at other companies because we are
surrounded by counting problems, probability problems, and other
Discrete Math 101 situations. Spend some time before the interview
refreshing your memory on (or teaching yourself) the essentials of
combinatorics and probability. You should be familiar with
n-choose-k problems and their ilk – the more the better.
Operating
Systems:
Know
about processes, threads and concurrency issues. Know about locks
and mutexes and semaphores and monitors and how they work. Know
about deadlock and livelock and how to avoid them. Know what
resources a processes needs, and a thread needs, and how context
switching works, and how it's initiated by the operating system and
underlying hardware. Know a little about scheduling. The world is
rapidly moving towards multi-core, so know the fundamentals of
"modern" concurrency constructs

SAMPLE
TOPICS

Coding
Sample
topics: construct / traverse data structures, implement system
routines, distill large data sets to single values, transform one
data set to another.
Algorithm
Design / Analysis
Sample
topics: big-O analysis, sorting and hashing, handling obscenely
large amounts of data. Also see topics listed under
'Coding'.
System
Design
Sample
topics: features sets, interfaces, class hierarchies, designing a
system under certain constraints, simplicity and robustness,
tradeoffs.
Open-Ended
Discussion
Sample
topics: biggest challenges faced, best/worst designs seen,
performance analysis and optimization, testing, ideas for improving
existing products.
```
