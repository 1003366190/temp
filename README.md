# The questions that were played in Kahoot during class.

---

# Algorithms


## Analysis

+ For any value of $`n`$, an algorithm with the runtime $`100n^2`$ runs faster than an algorithm with runtime $`2^n`$ (true/false).

	> *Answer: false*

+ The function $`n^3/1000-100n^2-100n+3`$ is of:

	a) $`\Theta(n^3)`$

	b) $`\Theta(n^2)`$

	c) $`O(n^2)`$

	d) $`O(n)`$

	> *Answer: a*

+ Which one of the following methods improves the best-case running time of a sort algorithm?

	a) Check if the array is sorted, if so then do nothing.

	b) Check if only the first two elements are not in-place, if so then swap them.

	c) Check if only the last two elements are not in-place, if so then swap them.

	d) All of them.

	> *Answer: d*
	
+ For any real constants $`a`$ and $`b (b > 0)`$, $`(n+a)^b = \Theta(n^b)`$ (true/false).

	> *Answer: true*

Given that $`f(n)`$ and $`g(n)`$ are two asymptotically non-negative functions: $`max(f(n),g(n)) = \Theta(f(n)+g(n))`$. (true/false)

	> *Answer: true*

+ The statement following statement is

	> The running time of insertion sort is at least $`O(n^2)`$

	a) meaningless

	b) true only for some cases

	c) true for all cases

	d) false

	> *Answer: a*

## Design

+ Suppose an implementation of *insertion sort* with running time $`8n^2`$ and an implementation of *merge sort* with running time $`64nlgn`$. Then:

	a) The merge-sort implementation is faster than that of the inserstion sort

	b) The insertion-sort implementation is faster than that of the merge sort

	c) The insertion-sort implementation is faster only for $`n \le 43`$

	d) The merge-sort implementation is faster only for $`n \le 43`$

	> *Answer: c*

+ A divide-and-conquer algorithm has the complexity $`T(n) = 2T(n/4) + n^2`$. This algorithm is of:

	a) $`\Theta(n^2)`$

	b) $`\Theta(n^2lgn)`$

	c) $`\Theta(nlgn)`$

	d) $`\Theta(lgn)`$

	> *Answer: a (use the master theorem -- case 3)*

+ Finding the shortest path between two nodes in an undirected graph has the suboptimal substructure. (true/false)

	> *Answer: true*

+ Which greedy choice for the activity-selection problem gives us a correct solution:

	a) Selecting the last compatible activity that starts the latest

	b) Selecting the compatible activity of least duration

	c) Selecting the compatible activity that overlaps the fewest

	d) Selecting the compatible remaining activity with the earliest start

	> *Answer: a*
	
+ Why a dynamic programming approach does not speed up Merge Sort?

  a) Merge sort doesn't have subproblems
  
  b) Subproblems do not overlap
  
  c) Merge sort is already the fastest sorting algorithm
  
  d) Merge sort does not optimize anything
  
  > *Answer: b*

## Complexity

+ Which one is definitely true?

	a) $`P \cap NP = \emptyset`$

	b) $`P \not = NP`$

	c) $`P = NP`$

	d) $`P \cap NP \not = \emptyset`$

	> *Answer: d*

+ Which one is NP-complete?

	a) Finding the shortest path between two vertices in a graph

	b) The vertex-cover problem in a graph

	c) Finding the shortest path between all pairs of vertices in a graph

	d) Finding the Euler tour in a graph

	> *Answer: b*

+ Using the cloud-computing infrastructure such as Amazon AWS with seemingly boundless computational power, we can solve any decision problem. (true/false)

	> *Answer: false (example: halting problem)*

---

# OS

## Introduction

+ Which one is not the goal of having an operating system?

  a) Providing an abstraction layer for hardware
  
  b) Managing resources such as CPU and memory
  
  c) Providing application program interface for programmers
  
  d) Protecting hardware from unauthorized access
  
  > *Answer: c*
  
+ What is a batch system?

	a) A system specifically designed for numerical analysis
	
	b) A system that processes input and output
	
	c) A system that runs multiple programs as jobs
	
	d) A system that involves human intervention for input/output
	
	> *Answer: c*
	
+ Which one is not part of a pipeline?

	a) Fetching instructions
	
	b) Decoding instructions
	
	c) Reading values of the operands from the cache
	
	d) Executing instructions
	
	> *Answer: c*
	
+ Which one is the __main__ characteristic of a microkernel architecture?

	a) It is based on calling service procedures
	
	b) Only one module runs in the kernel mode
	
	c) Provides more layers of abstraction on top of the OS
	
	d) The memory management is in a separate layer
	
	> *Answer: b*
	
+ We only need to be in user mode to manage the virtual memory. (true/false)

	> *Answer: false*
		
## Concepts

+ Which one certainly involves at least one process?

	a) Firefox 69.0

	b) A tab in Firefox

	c) A windwo in Firefox

	d) An instance of Firefox running

	> *Answer: d*

+ Which one is NOT an element of the program context?

	a) The program counter
	
	b) The stack pointer
	
	c) The program status word
	
	d) The value from the first layer of the cache
	
	> *Answer: d*
	
+ Every process in Linux has a parent. (true/false)

	> *Answer: false (the init process does not have any parent)*

+ Which one does NOT necessarily happen during creating a process:

	a) Assigning a unique process identifier

	b) Allocating space for the process

	c) Initializing the process control block

	d) Creating a main thread

	> *Answer: d*

+ Which one is NOT necessarily a way that a process terminates?

	a) Executing `exit(0);`
	
	b) Unhandled reading from a non-existent file
	
	c) A segmentation fault
	
	d) Executing kill by the parent process
	
	> *Answer: d*
	
+ If a thread in a process blocks, the entire process also blocks. (true/false)

	> *Answer: false*

+ Using the virtual memory expands the address space of the main memory. (true/false)

	> *Answer: true*
	
+ An OS with good resource management:

	a) maximizes throughput
	
	b) responds differently to different processes
	
	c) minimizes response time
	
	d) all
	
	> *Answer: d*
	
---

# Propositional Logic

+ "If I run the 100 meter race faster than 10.0 seconds, I will be admitted to the Olympic
games. Since I am not running the 100 meter race faster than 10.0 seconds, I will not be admitted to the Olympic games." (true/false)

> *Answer: false ($`p \longrightarrow q`$ does not mean $`\neg p \longrightarrow \neg q`$)*

+ $`F \longrightarrow (\neg A \longrightarrow (A \longrightarrow B))`$ is:

	a) A tautalogy

	b) Satisfiable

	c) Valid

	d) All

	> *Answer: d*

+ According to the following blurb, what is the most simplified diet that the centenarian follows?

  > "What is the secret of your long life?" a centenarian was asked.
  "I strictly follow my diet. If I don't drink beer for dinner, then I always have fish. Any time I have both beer and fish for dinner, then I do without ice cream. If I have ice cream or don't have beer, then I never eat fish."

	a) Only drink beer!

	b) Drink beer and eat ice cream!

	c) Drink beer and do not eat fish!

	d) Drink beer, do not eat fish, and eat ice cream!

	> *Answer: d*

+ Which one of the following statements is true:

	1. If $`(F \longrightarrow G)`$ is valid and $`F`$ is valid, then $`G`$ is valid.
    2. If $`(F \longrightarrow G)`$ is satisfiable and $`F`$ is satisfiable, then $`G`$ is satisfiable.
    3. If $`(F \longrightarrow G)`$ is valid and $`F`$ is satisfiable, then $`G`$ is satisfiable.

	a) 1 and 2

	b) 2 and 3

	c) 1 and 3

	d) All

	> *Answer: c*

+ $`B`$ is equivalent to $`(A \longrightarrow B) \wedge (\neg A \longrightarrow B)`$ (true/false).

	> *Answer: true*

+ Which one is an element of a formal logic?

	a) Syntax

	b) Semantics

	c) Proof system

	d) All

	> *Answer: d*

+ Which one is a statement in propositional logic?

	a) There exists a positive integer x, where $`x^2 \le x`$

	b) For all real numbers x, $`\sqrt x > x`$

	c) $`p \wedge q`$ where $`p`$ and $`q`$ are Boolean variables

	d) All

	> *Answer: c*

+ Which one indicates two formulas that are equivalent (multi-select):

	a) Two formulas with similar truth tables

	b) All tautologies

	c) All unsatisfiable formulas

	d) All satisfiable formulas

	> *Answer: a, b, and c*

+ Which formula is in CNF (multi-select)?

	a) $`A \wedge B`$

	b) $`A \vee B`$

	c) $`\neg (A \wedge B)`$

	d) $`\neg A \vee \neg B`$

	> *Answer: a, b, and d*
	
+ There is a polynomial-time algorithm that converts any Boolean formula into a CNF equivalent. (true/false)

	> *Answer: true*

+ Which one is NP-complete:

	a) 2-CNF-SAT

	b) 3-CNF-SAT

	c) CNF-SAT

	d) Converting a CNF into a 3-CNF equivalent

	> *Answer: b and c*
	
+ $`F = (\neg (A \wedge B) \longrightarrow \neg A) \longrightarrow B`$ is

	a) a tautology
	
	b) satisfiable
	
	c) valid
	
	d) false
	
	> *Answer: b*
	
+ Which one is the consequent of $`F = {{\neg A, B}, {\neg B, C}, {A, \neg C}, {A,B,C}}`$:

	a) A
	
	b) A and B
	
	c) A and B and C
	
	d) None
	
	> *Answer: c*
	
---

# Multiprocess & Multithreaded

+ How many "Hello, world!" is printed after running the following program?
```cpp
int main() {
	fork();
	fork();
	fork();
	std::cout << "Hello, world!\n";
	return 0;
}
```
	a) 3

	b) 4

	c) 7

	d) 8

	> *Answer: d*

+ If a thread blocks, the entire process blocks. (true/false)

	> *Answer: false*

+ Which one a user-level thread does NOT have:

	a) Execution state

	b) Execution stack

	c) Static storage for global variables

	d) An ID assigned by the OS

	> *Answer: d*

+ Which one is NOT a benefit of using threads:

	a) Faster creation

	b) Faster termination

	c) Faster context switch between threads

	d) Better inter-thread protection

	> *Answer: d*

---

# ADT

+ Which one is NOT an ADT?

	a) Int in C++

	b) A class that implements a graph

	c) Boolean values in C++

	d) None

	> *Answer: d*
	
+ One key relation in Facebook database is "friendship" between two users. Which property holds for this relationship?

	a) Reflexivity
	
	b) Symmetry
	
	c) Transitivity
	
	d) Equivalence
	
	> *Answer: b*
	
+ Which dataset does NOT have linear orderings?

	a) Memory values
	
	b) Real numbers
	
	c) The alphabet
	
	d) Memory address
	
	> *Answer: a*
	
+ Any hierarchy ordering is transitive (true/false).

	> *Answer: true*
	
+ Which data relation is best to use to implement a proof system (for example a SAT-solver)?

	a) Linear ordering
	
	b) Hierarchy ordering
	
	c) Partial ordering
	
	d) Weak ordering
	
	> *Answer: c*
	
+ Which asymptotic relation can be used to define an equivalency class of functions?

	a) $`O`$
	
	b) $`\Omega`$
	
	c) $`\Theta`$
	
	d) All
	
	> *Answer: d*

+ The Big-O notation defines a "weak ordering" on the asymptotically non-negative functions (true/false).

	> *Answer: true*
	
+ Which property is necessary for the following relation between nodes in a graph: node B is reachable from node A.

+ Which property is necessary for the following relation betwee nodes in a graph: node B is reachable from node A:

	a) Reflexivity

	b) Transitivity

	c) Symmetry

	d) Equivalence

	> *Answer: b*

+ The relationship of student data to the class data is:

	a) Hierarchical

	b) Equivalence

	c) Weak ordering

	d) Adjacency

	> *Answer: d*

+ The data objects that represent intersections for a street grid (like in the assignments) are defined:

	a) Locally
	
	b) Globally
	
	c) Explicitly
	
	d) Based on a weak ordering
	
	>*Answer: a*
	
# Data Structures

+ Which data structure is ideal to store the coordinates of the intersections in city of Waterloo:

	a) An array

	b) A singly-linked list

	c) A doubly-linked list

	d) All

	> *Answer: a*

+ We can implement a stack ADT using an array. (true/false)

	> *Answer: true*

+ What is an ideal DS to implement process scheduling in an OS?

	a) A stack
	
	b) A queue
	
	c) A tree
	
	d) a hash table
	
	> *Answer: b*
	
+ Which data structure is ideal to implement the depth-first and breadth-first search, respectively, in a graph:

	a) An array and a linked list

	b) A linked list and an array

	c) A stack and a queue

	d) A queue and a stack

	> *Answer: c*

+ For which usage using a Tree is an ideal DS:

	a) Checking if a set of parantheses is balanced, for example, (())() is balanced.
	
	b) UNIX file system
	
	c) Function calls within a program
	
	d) List of symbols in a program
	
	> *Answer: b*
	
+ What is the time complexity of finding an element in a BST in average-case?

	a) $`O(lgn)`$

	b) $`O(n)`$
	
	c) $`\Theta(n)`$
	
	d) $`\Theta(lgn)`$
	
+ A good size for a hash table that stores 2000 strings, and handles the average of a collision-chain of length 3 is:

	a) [2000/3]

	b) 700

	c) 701

	d) [2000/3]-1

	> *Answer: c (closet prime to [2000/3]*
	
+ Which one is NOT a characteristic of a good hash function?

	a) Uniform hashing
	
	b) Minimizes number of collisions
	
	c) Reduces the search-time to $`O(1)`$
	
	d) Reduces the insertion-time to $`O(1)`$

	> *Answer: c*

---
