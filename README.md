## CHITRANAGARI : SMART CITY DESIGN 

### Business Cases identified by Aditi Choudhary (01FE23BCS128)

**1. Industrial Expansion 🏭**  
As Chitranagari grows, it aims to establish itself as a hub for industrial development. The business case for industrial expansion involves the creation of dedicated industrial zones to boost economic growth and job opportunities. These zones will include small-scale, medium-scale, and large-scale industries with adequate infrastructure, such as efficient road networks, power supply, and waste management systems. The motive is twofold: 1. Attract investments from domestic and international companies, and 2. Utilize the revenue generated for further development of the city. Sustainable practices, such as green manufacturing units and carbon-neutral goals, will be incorporated to ensure environmental responsibility.

**2. Healthcare Infrastructure 🏥**  
A smart city must prioritize the well-being of its citizens. This business case focuses on building a robust healthcare ecosystem, including multi-specialty hospitals, community health centers, and digital health facilities for remote consultations. With advanced healthcare systems integrated with AI and IoT, Chitranagari aims to provide efficient and accessible services to its citizens. Preventive healthcare initiatives, like fitness zones, parks, and awareness programs, will also be introduced. Additionally, the plan includes public health monitoring systems and a centralized emergency response mechanism to enhance healthcare delivery.

**3. Education Hub 🎓**  
Chitranagari envisions becoming an educational powerhouse by establishing a network of schools, colleges, and research institutions. This business case focuses on creating a smart education system integrated with cutting-edge technology, including e-learning platforms, virtual labs, and interactive classrooms. Special emphasis will be placed on skill development and vocational training centers to prepare students for future industries. Partnerships with global universities and organizations will be encouraged to foster innovation and knowledge exchange. Scholarships and affordable education programs will be introduced to ensure inclusivity and accessibility for all citizens.


##COURSE LEARNING REFLECTIONS 

 ### 1. Iteration, Recursion, and Backtracking  
In nature , we come across many kinds of problems that could be solved using algorithm techniques that includes iteration , recursion , backtracking  

#### **Iteration**  
Iteration involves repeating a task multiple times in a process. 
For example, spiral arrangements of petals in flower or arranging Matryoshka dolls involves repeating the same action—forming a flower or nesting the dolls—until there isno more space left or dolls to handle.

#### **Recursion**  
Recursion involves solving a problem by breaking it down into smaller groups of the same problem.  
For instance, cell division process and food chain also involves recurssion 

#### **Backtracking**  
Backtracking explores multiple possibilities, retracing steps when a chosen path doesnt leads to a desired result.  
Examples include solving Sudoku puzzles or tackling the N-Queens problem. In these situations, the process involves trial and error, testing one path at a time and reverting to earlier steps when necessary.

---

### 2. Space and Time Efficiency & Orders of Growth  

#### **Space Efficiency**  
This refers to the additional memory required by an algorithm during execution.  

#### **Time Efficiency**  
This measures how long an algorithm takes to complete a task. Both metrics help evaluate how practical and efficient an algorithm is for a specific problem.  

#### **Orders of Growth**  
This describes how an algorithm’s execution time scales with input size.  
The growth can be constant, logarithmic, linear, quadratic, or cubic, depending on how input size impacts performance.

---

### 3. Design Principles  

Different design principles are developed to optimize problems, and selecting the right principle for a given problem is essential for efficiency.  
For example:  
- **Pruning** is ideal for solving the N-Queens problem, but **Parental Dominance** would not be suitable.  
- **Bit Manipulation** is used in Fenwick Trees, whereas **Edge Relaxation** is applied in spanning trees.  

Applying the wrong principle complicates the problem rather than simplifying it, underscoring the importance of matching the design principle to the problem.

---

### 4. Tree Data Structures  

Tree structures are designed for hierarchical data organization. Where elements (nodes) are connected by edges. A tree starts from a root node and branches out into child nodes, with no cycles. 
- **Balanced Trees** (AVL, Red-Black, 2-3 trees): Useful for maintaining balance through rotations, enabling faster search, insertion, and deletion operations with a time complexity of \( O(\log n) \).  
- **Trie**: Ideal for managing character data like dictionaries or prefixes.  
- **Heap**: Must satisfy the tree shape and parental dominance properties.

---

### 5. Array Query Algorithms  

Array query algorithms are effective for small and static datasets, such as finding the sum, minimum, maximum, or other properties over a range of indices.
These algorithms leverage **pre-computation** by storing previously calculated results to avoid redundant calculations.  
Structures like Segment Trees,Sparse Tables and Fenwick Trees use this principle, making them efficient for array queries.

---
### 6. Difference between trees and graphs 
Trees are hierarchical data structures with n nodes and n−1 edges, where each node has a single root to node path, making them acyclic. Traversals include Inorder, Preorder, and Postorder.
DFS and BFS are also used in tree traversals.
Graphs on the other hand, are generalized structures where nodes(vertices) connect through edges, which can form cycles and can be directed or undirected.
Its applications include navigation systems and other network purposes.

### 7. Sorting and Searching algorithms 
Sorting algorithms organize data for efficient access and manipulation.
They include sorting techniques like quick sort, merge sort, Bubble Sort
Searching algorithms locate data within structures
They include searching techniques binary search and linear search.

### 8. Graph algorithms
Graph algorithms solve essential problems in connectivity and optimization.
These algorithms include 
