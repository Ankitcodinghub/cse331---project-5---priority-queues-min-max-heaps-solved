# cse331---project-5---priority-queues-min-max-heaps-solved
**TO GET THIS SOLUTION VISIT:** [CSE331 – Project 5 – Priority Queues, Min/Max Heaps Solved](https://www.ankitcodinghub.com/product/cse331-project-5-priority-queues-min-max-heaps-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;110623&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CSE331 - Project 5 - Priority Queues, Min\/Max Heaps Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (1 vote)    </div>
    </div>
This is not a team project. Do not copy someone else’s work.

Assignment Overview

Binary Min-Heap representation as an array.Â The root of the heap is the 0th-index in the array representation.Â In a zero-indexed heap, the parent of a node at index i is located at floor((i – 1) / 2).Â The left child and right child are located at 2 * i + 1 and 2 * i + 2, respectively.

In this project, you will be implementing a binary max heap and priority queue using a binary min heap.Â Heaps are data structures that are complete trees, with the parent of each node being smaller than its children in a min heap, and larger than its children in a max heap.Â A min heap always has the element with the smallest value as its root, while a max heap always has the element with the largest value as its root.Â

Because of heaps’ quick access to the largest or smallest element, they are generally the best choice to use as a priority queue.Â A priority queue is a data structure that has the element with the most significant priority in its top index.Â You can think of it as a regular queue, but instead of simply removing the first element that was stored, it removes the most important element.

You will be using your PriorityQueue class to store Nodes, a class that is provided for you.

Assignment Specifications

Node class is completed in the skeleton file. Do not modify this class.

Its definition includes a key and a value. The key denotes the entity determining the ordering within the heap. The value represents the content of interest and acts as the tie breaker if the comparator keys are the same.

The class has been provided with less than, greater than, equal to, and string representation methods.Â PriorityQueue class is partially completed in the skeleton file.

PriorityQueue Class

init(self)

self.data – built in list that stores nodes

str(self) repr(self) Complete and implement the following methods.Â Do not modify the method signatures.

len(self)

Returns the length of the PriorityQueue

Time Complexity: O(1)

Space Complexity: O(1) empty(self)

Checks if the priority queue is empty.

Return: type Bool

Time Complexity: O(1)

Space Complexity: O(1) top(self)

Gets the root node

Return: type Node

Time Complexity: O(1)

Space Complexity: O(1) get_left_child_index(self, index)

Given an index of a node, return the index of the left child.Â In the event that the index has no left child, return None.

Return: type int

Time Complexity: O(1)

Space Complexity: O(1) get_right_child_index(self, index)

Given an index of a node, return the index of the right child.Â In the event that the index has no left child, return None. Return: type int

Time Complexity: O(1)

Space Complexity: O(1) get_parent_index(self, index)

Given an index of a node, return the index of its parent.Â

In the event that the index is the top of the PriorityQueue, return None. Return: type int

Time Complexity: O(1)

Space Complexity: O(1) push(self, key, value)

Use the key and value parameters to add a Node to the heap. Return: type None

Time Complexity: O(log(N))

Space Complexity: O(1) pop(self)

Removes the smallest element from the priority queue.Â

Reminder: you cannot use self.data.pop(0).Â Â This has a runtime complexity of O(N), since after deletion, the function will shift all of the other elements down by one spot.Â You must write your own PriorityQueue pop function that runs in O(log(N)). If no elements exist, return None

Return: type Node

Time Complexity: O(log(N))

Space Complexity: O(1) get_min_child_index(self, index)

Given an index of a node, return the index of the smaller child.

In the event that the index is a leaf, return None.

Return: type int

Time Complexity: O(1)

Space Complexity: O(1) percolate_up(self, index)

Given the index of a node, move the node up to its valid spot in the heap. Return: type None

Time Complexity: O(log(N))

Space Complexity: O(1) percolate_down(self, index)

Given the index of a node, move the node down to its valid spot in the heap.

Return: type None

Time Complexity: O(log(N))

Space Complexity: O(1)

MaxHeap Class

init(self) self.data — PriorityQueue that contains the data in our MaxHeap

str(self)

repr(self) len(self) – returns the length of the data inside the heap

Complete and implement the following methods.Â Do not modify the method signatures.

empty(self)

Checks if the MaxHeap is empty.

Return: type Bool

Time Complexity: O(1)

Space Complexity: O(1) top(self)

If no root value, return None.

Gives the root value.

Return: type same as node.value

Time Complexity: O(1)

Space Complexity: O(1) push(self, value)

Adds the value to the heap

Return: type None

Time Complexity: O(log(N)) Space Complexity: O(1) pop(self)

If no elements exist, return None

Removes the largest element from the heap

Return: type Node

Time Complexity: O(log(N))

Space Complexity: O(1) Application Problems

heap_sort(array)

Sorts the given list in-place, in ascending order, using a MaxHeap

This means that you are not allowed to create a new list and append values onto it.Â You must modify the original array.

Return: type None; list should be sorted

Time Complexity: O(Nlog(N))

Space Complexity: O(N) for MaxHeap, not allowed to create other list.

CREATING A NEW LIST WILL RESULT IN ZERO POINTS ON THIS FUNCTION

find_ranking(rank, results)

Unfortunately, the NCAA has lost the information regarding the rankings of the teams at the end of the season.Â They could figure it out, but knowing you have created a PriorityQueue class, they have hired you to do it more quickly and efficiently.Â Given “results”, a list of tuples — with each tuple containing the amount of losses that team suffered and the team name – find the team that finished in the position “rank”.Â

Example: rank = 3, results = [(1, “Spartans”), (11, “Hoosiers”), (3, “Buckeyes”), (6, “Wolverines”), (5, “Golden Gophers”), (15, “Nittany Lions”), (7, “Badgers”), (12, “Scarlet Knights”)]

Return: “Golden Gophers”

Explanation: The Golden Gophers finished in 3^rd^ place, because they had the 3^rd^ least amount of losses (the Spartans (1) and the Buckeyes

(3) had less).Â

You must use the PriorityQueue class to solve this problem.

Time Complexity: O(Nlog(N)) Space Complexity: O(N)

Assignment Notes

No use of the module heapq allowed.

The Node class has built-in comparator functions, meaning you can check if one Node is less than or greater than another.

You must write docstrings for every completed function.

The only containers allowed are the built-in priority queue containers and lists to be used in the heap_sort function.

Guaranteed that no duplicate nodes will be pushed into the heap, meaning same key and value.

Keys and values for the PriorityQueue class can be ints, strings, or floats.

Values will only be ints for the MaxHeap class

String and print methods are provided for debugging purposes.

Some heaps start at an index at one. However, for this assignment, indexing will start at index zero, just like normal lists.

Submission

Deliverables

Project5.zip Â Â |— Project5/ Â Â Â Â |— README.mdÂ Â Â Â Â Â (for project feedback) Â Â Â Â |— init.pyÂ Â Â Â (for proper Mimir testcase loading) Â Â Â Â |— PriorityHeap.py (contains your solution source code) Grading

Mimir Tests (76]

Manual (24) ReadMe (2)Â

Time and Space Complexity length, top, empty, get_left_child_index, get_right_child_index, get_parent_index __ / 3 (0.5 pts each) get_min_child_index __ / 1

push, pop, percolate_up, percolate_down __ / 8Â (2 pts each) heap_sort __ / 5 find_ranking __ / 5

Project designed by Max Huang and Angelo Savich
