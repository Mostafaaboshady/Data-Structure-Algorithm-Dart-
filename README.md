# Data-Structure-Algorithm-Dart-  

☛ Data Structure & Algorithm (Dart) 🎲
==========================================

🤜 Bog O Notation
🤜 Analysis of (Objects & Arrays)
🤜 Solutions Of Problems
🤜 Problems Patterns
🤜 Recursion
🤜 Searching Algorithm
🤜 Sorting Algorithm
🤜 Data Structure
🤜 Primitive Data Structure
🤜 non-Premitive Data Structure     💨 Basic
                                    💨  Advance

🤜 How To understand The Problems (Analysis Problem)
-----------------------------------------------------------------------------------------------------------------------------------------------------------------------
☛ Big O 🚧
============   
⛔ لية بستخدمهاا ؟؟؟                         
✎ باختصار لو عندي مشكلة ليها اكتر من حل مثلا اتنين او تلاتة كل  الحلول صخ وتمشي بس فيه الحل الاصح دا بختارو علي حسب اللي يعملي  حل المشكلة بس ك وقت اقل بكتير 
من باقي الحلول

✉ هتفيد انها هتطلع معيار تقدر تقيس بيه الكود بتاعك حلو ولا ممكن يقضي وقت غرض ويقع منك (الفرق بين كودين)
✉ مهمة جدا جدا جدا في المشاريع الكبيرة مثلا 
  (Two Function) ==> نفس الغرض  ===>    
  هنفضل واحدة عن تانية ويكون معياري  هو ال Big O  ودا من خلال 
   1- Time Complexity  ✅
   2- Space Complexity ✅
   3- Simplify         ✅
   4- Evaluated        ✅

卐 وملحوظة بحسب دا من خلال عدد سطووور الكود بتاعي في كل فانكشن ودا عن طريق  ثوابت بيتم تقيم كل سطر من خلالها 卐 

لو حسبت الوقت ع كل جهاز غلط 
❄ لان ع  كل جهاز هتطلع قيمة مختلفة وع الجهاز الواحد  هتطلع قيم مختلفة ودا غلط لان انا عاوز قيم ثابتة عشان من خلالها اقدر احدد  الافضل بالنسبالي


🔥 Constant ➺ (1)
🔥 Logarithmic ➺ (log n)
🔥 linear ➺ (n) 
🔥 n-log-n ➺ (n log n)
🔥 quadratic ➺ (n^2) 
🔥 Cubic ➺ (n^3)
🔥 exponential ➺ (2^n)  
🔥 factorial ➺ (n!)

⬤ بص ي سيدي 
⦿ Time Complexity ==> دا الوقت اللي بياخدوا باختصار اثناء عملبة ال excution بتاعتك 
بمعني اصح وقت ال Run 
⦿ Space Complexity ==> دا برضو بنفس الاختصار المكان اللي بياخدوا في الميموري ناتج عملية الرن دي 


⌚ Example ==>  What is the Running Time ?

(One Loop)
for i  = 1 to n                   Big O  ➸ O(n)
if A[i] == T return true 
return false 

__________________________________________________

(Two Loop)
for i  = 1 to n                     
if A[i] == T return true 
return false 
for i  = 1 to n                             Big O  ➸ O(n)
if B[i] == T return true 
return false 
__________________________________________________

(Nested Loop)
for i = 1 to n    ===> O(n)
for j = 1 to n    ===> O(n)                              
                                                  Big O  ➸ O(n^2)
if A[i] == B[i] return true 
return false

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------
☛ Analysis List & Arrays 🚧
============================


var anyList = [1,2,3,'Ali']; //any List Contain Mix Data


it can 1 - Insertion ✍️
       2 - Removed   ✍️
       3 - Searching ✍️       
       4 - Access    ✍️

Big O ==>  O(1) ☝️ for Accessing  constant 
Big O ==>  O(1) ☝️ for Insertion when element in last  constant ===  When Put Value in first List or  center Big O ==> O(n)
Big O ==>  O(n) ☝️ for Remove any element without the lat element ===  When remove last element in List Big O ==> O(1)
Big O ==>  O(n) ☝️ for Searching

__________________________________________________

Var data = 
{
  'id': '1',
  'name': 'waled',
  'phone'" 123456789,
}

😊 ملحوظة سريعة بس بسرعة الفرق بين Map & List 
 🥲 List بيهتم بالترتيب
 🥲 Map دي ميفرقش فيها ترتيب الداتا بتستدعيها وبس مش شرط ترتيب عكس ال List

■ Big O ==> O(1) in any case for insertion , remove , Accessing
■ Big O ==> O(n) in Searching
-----------------------------------------------------------------------------------------------------------------------------------------------------------------------

☛ ALGo & Problem Analysis 🚧
=============================

⊗  ⫷ Input ⫸ Processing ⫷  Output ⫸

⊩ ALGo ==>  Collection Of Steps To Solve Problem && Divide Any Problem into Small Problems(many Sub Problems[tasks])

⋯ 🤷‍♂️ باختصاار كدااا اهمم حاجة لازم تفهمها او  تعملهاا لازم تفهم المشكلة وتحدد مدخلاتك وتحدد الناتج بتاعك انت عاوز ايههههه  ⋯


☛ Divide And Conquer Strategy 🚧
================================= فرق تسدد 

Ex -- Function ===> Sorted List ===> Search Number By Index ⚫
 
 By Divide & Conquer ... [1,3,5,6,9,15,18,20,21]   say searching num 20
                      .
                      .
                      .
                      هنقف في النص عند ال 9 ونقسم يمين ليست وشمال ليست 
                     [15,18,20,21] هل ال 20 شمال لا يمين يبقي الغي الشمال خالص ويكون تركيزي 
                     هيلاقي ال 20 هنا بعد لفتين 
                     كدا انا عملت اربع عمليات بسسس وجبت المطلوب 
-----------------------------------------------------------------------------------------------------------------------------------------------------------------------
☛ Greedy Method 🚧
===================

✱ Tha Aim of this Algorithm To get The Optimal Solutions
   for Example get min and max num

🔵Knapsack Problem With Greedy Method

The Greedy algorithm could be understood very well with a well-known problem referred to as Knapsack problem. Although the same problem could be solved by employing other algorithmic approaches,
 Greedy approach solves Fractional Knapsack problem reasonably in a good time. Let us discuss the Knapsack problem in detail.

Knapsack Problem
Given a set of items, each with a weight and a value, determine a subset of items to include in a collection so that the total weight is less than or equal to a given limit and the total value is as large as possible.

The knapsack problem is in combinatorial optimization problem. It appears as a subproblem in many, more complex mathematical models of real-world problems.
 One general approach to difficult problems is to identify the most restrictive constraint, ignore the others, solve a knapsack problem, and somehow adjust the solution to satisfy the ignored constraints.


🔴
        Algorithm: Greedy-Fractional-Knapsack (w[1..n], p[1..n], W) 
        for i = 1 to n 
          do x[i] = 0 
          weight = 0 
          for i = 1 to n 
         if weight + w[i] ≤ W then  
         x[i] = 1 
           weight = weight + w[i] 
         else 
           x[i] = (W - weight) / w[i] 
           weight = W 
           break 
        return x

🔴 time in O(n); Therefore, the total time including the sort is in O(n logn).

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------
☛ Dynamic Programming 🚧
=========================

⚪Dynamic Programming is mainly an optimization over plain recursion. Wherever we see a recursive solution that has repeated calls for same inputs, 
we can optimize it using Dynamic Programming. The idea is to simply store the results of subproblems, so that we do not have to re-compute them when needed later.
This simple optimization reduces time complexities from exponential to polynomial. For example, if we write simple recursive solution for Fibonacci Numbers, 
we get exponential time complexity and if we optimize it by storing solutions of subproblems, time complexity reduces to linear.



🔴Steps of Dynamic Programming Approach
Dynamic Programming algorithm is designed using the following four steps −
Characterize the structure of an optimal solution.
Recursively define the value of an optimal solution.
Compute the value of an optimal solution, typically in a bottom-up fashion.
Construct an optimal solution from the computed information.
Applications of Dynamic Programming Approach
Matrix Chain Multiplication
Longest Common Subsequence
Travelling Salesman Problem

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------
☛ Searching Algorithm 🚧
=========================

☛ Linear Search Algorithm 🚧
=============================

⚪Linear search is a very simple search algorithm. In this type of search, 
a sequential search is made over all items one by one. Every item is checked and if a match is found then that particular item is returned,
otherwise the search continues till the end of the data collection.
Big O(n)


🔴 Algo 
Linear Search ( Array A, Value x)

Step 1: Set i to 1
Step 2: if i > n then go to step 7
Step 3: if A[i] = x then go to step 6
Step 4: Set i to i + 1
Step 5: Go to Step 2
Step 6: Print Element x Found at index i and go to step 8
Step 7: Print element not found
Step 8: Exit


🔴 Pseudocode

for each item in the list
      if match item == value
         return the item's location
      end if
   end for

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------

☛ Binary Search Algorithm 🚧
=============================
⚪ Binary search is a fast search algorithm with run-time complexity of Ο(log n). This search algorithm works on the principle of divide and conquer.
For this algorithm to work properly, the data collection should be in the sorted form.

Binary search looks for a particular item by comparing the middle most item of the collection. If a match occurs, then the index of item is returned. 
If the middle item is greater than the item, then the item is searched in the sub-array to the left of the middle item. Otherwise, the item is searched for in the sub-array to the right of the middle item.
This process continues on the sub-array as well until the size of the subarray reduces to zero.

⚪ How Binary Search Works?
For a binary search to work, it is mandatory for the target array to be sorted. We shall learn the process of binary search with a pictorial example.
The following is our sorted array and let us assume that we need to search the location of value 31 using binary search.

🔴 Pseudocode

binary_search
   A ← sorted array
   n ← size of array
   x ← value to be searched

   Set lowerBound = 1
   Set upperBound = n 

   while x not found
      if upperBound < lowerBound 
         EXIT: x does not exists.
   
      set midPoint = lowerBound + ( upperBound - lowerBound ) / 2
      
      if A[midPoint] < x
         set lowerBound = midPoint + 1
         
      if A[midPoint] > x
         set upperBound = midPoint - 1 

      if A[midPoint] = x 
         EXIT: x found at location midPoint
   end while

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------
☛ Hash Table 🚧
================

⚪ Hash Table is a data structure which stores data in an associative manner. In a hash table, data is stored in an array format,
where each data value has its own unique index value. Access of data becomes very fast if we know the index of the desired data.

Thus, it becomes a data structure in which insertion and search operations are very fast irrespective of the size of the data.
 Hash Table uses an array as a storage medium and uses hash technique to generate an index where an element is to be inserted or is to be located from.

⚪ Hashing
Hashing is a technique to convert a range of key values into a range of indexes of an array. We're going to use modulo operator to get a range of key values.
Consider an example of hash table of size 20, and the following items are to be stored. Item are in the (key,value) format.

Basic Operations
Following are the basic primary operations of a hash table.

Search − Searches an element in a hash table.

Insert − inserts an element in a hash table.

delete − Deletes an element from a hash tabl

🔴 Like arrays, hash tables provide constant-time O(1) lookup on average, regardless of the number of items in the table. The (hopefully rare) worst-case lookup time in most hash table schemes is O(n)

🌵 Search Operation
Whenever an element is to be searched, compute the hash code of the key passed and locate the element using that hash code as index in the array. 
Use linear probing to get the element ahead if the element is not found at the computed hash code.
struct DataItem *search(int key) {
   //get the hash
   int hashIndex = hashCode(key);
	
   //move in array until an empty
   while(hashArray[hashIndex] != NULL) {
	
      if(hashArray[hashIndex]->key == key)
         return hashArray[hashIndex];
			
      //go to next cell
      ++hashIndex;
		
      //wrap around the table
      hashIndex %= SIZE;
   }

   return NULL;        
}
__________________________________________________

🌵 Insert Operation
Whenever an element is to be inserted, compute the hash code of the key passed and locate the index using that hash code as an index in the array.
Use linear probing for empty location, if an element is found at the computed hash code.

void insert(int key,int data) {
   struct DataItem *item = (struct DataItem*) malloc(sizeof(struct DataItem));
   item->data = data;  
   item->key = key;     

   //get the hash 
   int hashIndex = hashCode(key);

   //move in array until an empty or deleted cell
   while(hashArray[hashIndex] != NULL && hashArray[hashIndex]->key != -1) {
      //go to next cell
      ++hashIndex;
		
      //wrap around the table
      hashIndex %= SIZE;
   }
	
   hashArray[hashIndex] = item;        
}

__________________________________________________
🌵 Delete Operation
Whenever an element is to be deleted, compute the hash code of the key passed and locate the index using that hash code as an index in the array.
Use linear probing to get the element ahead if an element is not found at the computed hash code. When found,store a dummy item there to keep the performance of the hash table intact.

struct DataItem* delete(struct DataItem* item) {
   int key = item->key;

   //get the hash 
   int hashIndex = hashCode(key);

   //move in array until an empty 
   while(hashArray[hashIndex] !=NULL) {
	
      if(hashArray[hashIndex]->key == key) {
         struct DataItem* temp = hashArray[hashIndex]; 
			
         //assign a dummy item at deleted position
         hashArray[hashIndex] = dummyItem; 
         return temp;
      } 
		
      //go to next cell
      ++hashIndex;
		
      //wrap around the table
      hashIndex %= SIZE;
   }  
	
   return NULL;        
}

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------
☛ Sorting Algorithm 🚧
=======================
Sorting refers to arranging data in a particular format. Sorting algorithm specifies the way to arrange data in a particular order. Most common orders are in numerical or lexicographical order.

The importance of sorting lies in the fact that data searching can be optimized to a very high level, if data is stored in a sorted manner.
Sorting is also used to represent data in more readable formats. Following are some of the examples of sorting in real-life scenarios −
Telephone Directory − The telephone directory stores the telephone numbers of people sorted by their names, so that the names can be searched easily.

Dictionary − The dictionary stores words in an alphabetical order so that searching of any word becomes easy.

In-place Sorting and Not-in-place Sorting
Sorting algorithms may require some extra space for comparison and temporary storage of few data elements. These algorithms do not require any extra space and sorting is said to happen in-place, or for example,
within the array itself. This is called in-place sorting. Bubble sort is an example of in-place sorting.
However, in some sorting algorithms, the program requires space which is more than or equal to the elements being sorted. Sorting which uses equal or more space is called not-in-place sorting. Merge-sort is an example of not-in-place sorting.

Stable and Not Stable Sorting
If a sorting algorithm, after sorting the contents, does not change the sequence of similar content in which they appear, it is called stable sorting.


☛ Insertion Sort 🚧
=====================

This is an in-place comparison-based sorting algorithm. Here, a sub-list is maintained which is always sorted. For example, 
the lower part of an array is maintained to be sorted. An element which is to be 'insert'ed in this sorted sub-list,
has to find its appropriate place and then it has to be inserted there. Hence the name, insertion sort.
The array is searched sequentially and unsorted items are moved and inserted into the sorted sub-list (in the same array).
This algorithm is not suitable for large data sets as its average and worst case complexity are of Ο(n2), where n is the number of items.


🍄 Algorithm
Now we have a bigger picture of how this sorting technique works, so we can derive simple steps by which we can achieve insertion sort.

Step 1 − If it is the first element, it is already sorted. return 1;
Step 2 − Pick next element
Step 3 − Compare with all elements in the sorted sub-list
Step 4 − Shift all the elements in the sorted sub-list that is greater than the 
         value to be sorted
Step 5 − Insert the value
Step 6 − Repeat until list is sorted



🍄 Pseudocode

insertionSort( A : array of items )
   int holePosition
   int valueToInsert
	
   for i = 1 to length(A) inclusive do:
	
      /* select value to be inserted */
      valueToInsert = A[i]
      holePosition = i
      
      /*locate hole position for the element to be inserted */
		
      while holePosition > 0 and A[holePosition-1] > valueToInsert do:
         A[holePosition] = A[holePosition-1]
         holePosition = holePosition -1
      end while
		
      /* insert the number at hole position */
      A[holePosition] = valueToInsert
      
   end for
-----------------------------------------------------------------------------------------------------------------------------------------------------------------------
☛ Selection Sort 🚧
====================

Selection sort is a simple sorting algorithm. This sorting algorithm is an in-place comparison-based algorithm in which the list is divided into two parts, 
the sorted part at the left end and the unsorted part at the right end. Initially, the sorted part is empty and the unsorted part is the entire list.

The smallest element is selected from the unsorted array and swapped with the leftmost element, and that element becomes a part of the sorted array.
 his process continues moving unsorted array boundary by one element to the right.

This algorithm is not suitable for large data sets as its average and worst case complexities are of Ο(n2), where n is the number of items.

🍄 Algorithm
Step 1 − Set MIN to location 0
Step 2 − Search the minimum element in the list
Step 3 − Swap with value at location MIN
Step 4 − Increment MIN to point to next element
Step 5 − Repeat until list is sorted


🍄 Pseudocode

selection sort 
   list  : array of items
   n     : size of list

   for i = 1 to n - 1
   /* set current element as minimum*/
      min = i    
  
      /* check the element to be minimum */

      for j = i+1 to n 
         if list[j] < list[min] then
            min = j;
         end if
      end for

      /* swap the minimum element with the current element*/
      if indexMin != i  then
         swap list[min] and list[i]
      end if
   end for

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------
☛ Bubble Sort 🚧
=================

Bubble sort is a simple sorting algorithm. This sorting algorithm is comparison-based algorithm in which each pair of adjacent elements is compared and the elements are swapped if they are not in order. 
This algorithm is not suitable for large data sets as its average and worst case complexity are of Ο(n2) where n is the number of items


🍄 Algorithm
We assume list is an array of n elements. We further assume that swap function swaps the values of the given array elements.

begin BubbleSort(list)

   for all elements of list
      if list[i] > list[i+1]
         swap(list[i], list[i+1])
      end if
   end for
   
   return list
   
end BubbleSort


🍄 Pseudocode 

 bubbleSort( list : array of items )

   loop = list.count;
   
   for i = 0 to loop-1 do:
      swapped = false
		
      for j = 0 to loop-1 do:
      
         /* compare the adjacent elements */   
         if list[j] > list[j+1] then
            /* swap them */
            swap( list[j], list[j+1] )		 
            swapped = true
         end if
         
      end for
      
      /*if no number was swapped that means 
      array is sorted now, break the loop.*/
      
      if(not swapped) then
         break
      end if
      
   end for

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------
☛ Quick Sort 🚧
=================

Quick sort is a highly efficient sorting algorithm and is based on partitioning of array of data into smaller arrays. A large array is partitioned into two arrays one of which holds values smaller than the specified value, say pivot, based on which the partition is made and another array holds values greater than the pivot value.

Quicksort partitions an array and then calls itself recursively twice to sort the two resulting subarrays. This algorithm is quite efficient for large-sized data sets as its average and worst-case complexity are O(n2), respectively.

🍄 Quick Sort Pivot Algorithm

Based on our understanding of partitioning in quick sort, we will now try to write an algorithm for it, which is as follows.

Step 1 − Choose the highest index value has pivot
Step 2 − Take two variables to point left and right of the list excluding pivot
Step 3 − left points to the low index
Step 4 − right points to the high
Step 5 − while value at left is less than pivot move right
Step 6 − while value at right is greater than pivot move left
Step 7 − if both step 5 and step 6 does not match swap left and right
Step 8 − if left ≥ right, the point where they met is new pivot

🍄 Quick Sort Pivot Pseudocode

function partitionFunc(left, right, pivot)
   leftPointer = left
   rightPointer = right - 1

   while True do
      while A[++leftPointer] < pivot do
         //do-nothing            
      end while
		
      while rightPointer > 0 && A[--rightPointer] > pivot do
         //do-nothing         
      end while
		
      if leftPointer >= rightPointer
         break
      else                
         swap leftPointer,rightPointer
      end if
		
   end while 
	
   swap leftPointer,right
   return leftPointer
	
end function



🍄 Quick Sort Algorithm
Using pivot algorithm recursively, we end up with smaller possible partitions. Each partition is then processed for quick sort. We define recursive algorithm for quicksort as follows −

Step 1 − Make the right-most index value pivot
Step 2 − partition the array using pivot value
Step 3 − quicksort left partition recursively
Step 4 − quicksort right partition recursively

Quick Sort Pseudocode
To get more into it, let see the pseudocode for quick sort algorithm −

🍄 procedure quickSort(left, right)

   if right-left <= 0
      return
   else     
      pivot = A[right]
      partition = partitionFunc(left, right, pivot)
      quickSort(left,partition-1)
      quickSort(partition+1,right)    
   end if		
   
end procedure

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------
☛ Merge Sort 🚧
================

Merge sort is a sorting technique based on divide and conquer technique. With worst-case time complexity being Ο(n log n), 
it is one of the most respected algorithms.
Merge sort first divides the array into equal halves and then combines them in a sorted manner.

🍄  Algorithm
Merge sort keeps on dividing the list into equal halves until it can no more be divided. By definition, if it is only one element in the list, it is sorted. Then, merge sort combines the smaller sorted lists keeping the new list sorted too.

Step 1 − if it is only one element in the list it is already sorted, return.
Step 2 − divide the list recursively into two halves until it can no more be divided.
Step 3 − merge the smaller lists into new list in sorted order.


🍄 procedure
We shall now see the pseudocodes for merge sort functions. As our algorithms point out two main functions − divide & merge.
Merge sort works with recursion and we shall see our implementation in the same way.

mergesort( var a as array )
   if ( n == 1 ) return a

   var l1 as array = a[0] ... a[n/2]
   var l2 as array = a[n/2+1] ... a[n]

   l1 = mergesort( l1 )
   l2 = mergesort( l2 )

   return merge( l1, l2 )
end procedure

procedure merge( var a as array, var b as array )

   var c as array
   while ( a and b have elements )
      if ( a[0] > b[0] )
         add b[0] to the end of c
         remove b[0] from b
      else
         add a[0] to the end of c
         remove a[0] from a
      end if
   end while
   
   while ( a has elements )
      add a[0] to the end of c
      remove a[0] from a
   end while
   
   while ( b has elements )
      add b[0] to the end of c
      remove b[0] from b
   end while
   
   return c

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------
☛ Shell Sort 🚧
================
Shell sort is a highly efficient sorting algorithm and is based on insertion sort algorithm. This algorithm avoids large shifts as in case of insertion sort, if the smaller value is to the far right and has to be moved to the far left.

This algorithm uses insertion sort on a widely spread elements, first to sort them and then sorts the less widely spaced elements. This spacing is termed as interval. This interval is calculated based on Knuth's formula as −
⛔ Knuth's Formula
h = h * 3 + 1
where −
   h is interval with initial value 1

🍄 Algorithm
Following is the algorithm for shell sort.

Step 1 − Initialize the value of h
Step 2 − Divide the list into smaller sub-list of equal interval h
Step 3 − Sort these sub-lists using insertion sort
Step 3 − Repeat until complete list is sorted



🍄 Pseudocode

shellSort()
   A : array of items 
	
   /* calculate interval*/
   while interval < A.length /3 do:
      interval = interval * 3 + 1	    
   end while
   
   while interval > 0 do:

      for outer = interval; outer < A.length; outer ++ do:

      /* select value to be inserted */
      valueToInsert = A[outer]
      inner = outer;

         /*shift element towards right*/
         while inner > interval -1 && A[inner - interval] >= valueToInsert do:
            A[inner] = A[inner - interval]
            inner = inner - interval
         end while

      /* insert the number at hole position */
      A[inner] = valueToInsert

      end for

   /* calculate interval*/
   interval = (interval -1) /3;	  

   end while

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------
☛ Graph Data 🚧
================

A graph is a pictorial representation of a set of objects where some pairs of objects are connected by links. The interconnected objects are represented by points termed as vertices, and the links that connect the vertices are called edges.

Formally, a graph is a pair of sets (V, E), where V is the set of vertices and E is the set of edges, connecting the pairs of vertices. Take a look at the following graph −

In the above graph,

V = {a, b, c, d, e}

E = {ab, ac, bd, cd, de}

💫 Graph Data Structure
Mathematical graphs can be represented in data structure. We can represent a graph using an array of vertices and a two-dimensional array of edges. Before we proceed further, let's familiarize ourselves with some important terms −

Vertex − Each node of the graph is represented as a vertex. In the following example, the labeled circle represents vertices. Thus, A to G are vertices. We can represent them using an array as shown in the following image. Here A can be identified by index 0. B can be identified using index 1 and so on.

Edge − Edge represents a path between two vertices or a line between two vertices. In the following example, the lines from A to B, B to C, and so on represents edges. We can use a two-dimensional array to represent an array as shown in the following image. Here AB can be represented as 1 at row 0, column 1, BC as 1 at row 1, column 2 and so on, keeping other combinations as 0.

💫 Adjacency − Two node or vertices are adjacent if they are connected to each other through an edge. In the following example, B is adjacent to A, C is adjacent to B, and so on.

💫 Path − Path represents a sequence of edges between the two vertices. In the following example, ABCD represents a path from A to D.


Basic Operations
Following are basic primary operations of a Graph −

💫 Add Vertex − Adds a vertex to the graph.

💫 Add Edge − Adds an edge between the two vertices of the graph.

💫 Display Vertex − Displays a vertex of the graph.

To know more about Graph, please read Graph Theory Tutorial. We shall learn about traversing a graph in the coming chapters.



☛ Depth First Traversal 🚧
===========================
Depth First Search (DFS) algorithm traverses a graph in a depthward motion and uses a stack to remember to get the next vertex to start a search, when a dead end occurs in any iteration.
As in the example given above, DFS algorithm traverses from S to A to D to G to E to B first, then to F and lastly to C. It employs the following rules.

Rule 1 − Visit the adjacent unvisited vertex. Mark it as visited. Display it. Push it in a stack.

Rule 2 − If no adjacent vertex is found, pop up a vertex from the stack. (It will pop up all the vertices from the stack, which do not have adjacent vertices.)

Rule 3 − Repeat Rule 1 and Rule 2 until the stack is empty



☛ Breadth First Traversal 🚧
=============================

Breadth First Search (BFS) algorithm traverses a graph in a breadthward motion and uses a queue to remember to get the next vertex to start a search, when a dead end occurs in any iteration.

As in the example given above, BFS algorithm traverses from A to B to E to F first then to C and G lastly to D. It employs the following rules.

Rule 1 − Visit the adjacent unvisited vertex. Mark it as visited. Display it. Insert it in a queue.

Rule 2 − If no adjacent vertex is found, remove the first vertex from the queue.

Rule 3 − Repeat Rule 1 and Rule 2 until the queue is empty.


-----------------------------------------------------------------------------------------------------------------------------------------------------------------------
☛  Recursion Basics 🚧
========================

🔵 Some computer programming languages allow a module or function to call itself. This technique is known as recursion. In recursion, a function α either calls itself directly or calls a function β that in turn calls the original function α. The function α is called recursive function.

🔵 Example − a function calling itself.

int function(int value) {
   if(value < 1)
      return;
   function(value - 1);

   printf("%d ",value);   
}
🔵 Example − a function that calls another function which in turn calls it again.

int function1(int value1) {
   if(value1 < 1)
      return;
   function2(value1 - 1);
   printf("%d ",value1);   
}
int function2(int value2) {
   function1(value2);
}

🔴 Analysis of Recursion
One may argue why to use recursion, as the same task can be done with iteration. The first reason is, recursion makes a program more readable and because of latest enhanced CPU systems, recursion is more efficient than iterations.

🔴 Time Complexity
In case of iterations, we take number of iterations to count the time complexity. Likewise, in case of recursion, assuming everything is constant, we try to figure out the number of times a recursive call is being made. A call made to a function is Ο(1), hence the (n) number of times a recursive call is made makes the recursive function Ο(n).

🔴 Space Complexity
Space complexity is counted as what amount of extra space is required for a module to execute. In case of iterations, the compiler hardly requires any extra space. The compiler keeps updating the values of variables used in the iterations. But in case of recursion, the system needs to store activation record each time a recursive call is made. Hence, it is considered that space complexity of recursive function may go higher than that of a function with iteration.


☛  Fibonacci Series 🚧
========================

♻️ Fibonacci series generates the subsequent number by adding two previous numbers. Fibonacci series starts from two numbers − F0 & F1. 
The initial values of F0 & F1 can be taken 0, 1 or 1, 1 respectively.

Fibonacci series satisfies the following conditions −

Fn = Fn-1 + Fn-2



🌻 Fibonacci Iterative Algorithm
First we try to draft the iterative algorithm for Fibonacci series.

Procedure Fibonacci(n)
   declare f0, f1, fib, loop 
   
   set f0 to 0
   set f1 to 1
   
   display f0, f1
   
   for loop ← 1 to n
   
      fib ← f0 + f1   
      f0 ← f1
      f1 ← fib

      display fib
   end for
	
end procedure


🌻 Fibonacci Recursive Algorithm
Let us learn how to create a recursive algorithm Fibonacci series. The base criteria of recursion.

START
Procedure Fibonacci(n)
   declare f0, f1, fib, loop 
   
   set f0 to 0
   set f1 to 1
   
   display f0, f1
   
   for loop ← 1 to n
   
      fib ← f0 + f1   
      f0 ← f1
      f1 ← fib

      display fib
   end for

END
-----------------------------------------------------------------------------------------------------------------------------------------------------------------------
☛  Tree 🚧
============
Tree represents the nodes connected by edges. We will discuss binary tree or binary search tree specifically.

Binary Tree is a special datastructure used for data storage purposes. A binary tree has a special condition that each node can have a maximum of two children. A binary tree has the benefits of both an ordered array and a linked list as search is as quick as in a sorted array and insertion or deletion operation are as fast as in linked list.
Important Terms
Following are the important terms with respect to tree.

🌱 Path − Path refers to the sequence of nodes along the edges of a tree.

🌱 Root − The node at the top of the tree is called root. There is only one root per tree and one path from the root node to any node.

🌱 Parent − Any node except the root node has one edge upward to a node called parent.

🌱 Child − The node below a given node connected by its edge downward is called its child node.

🌱 Leaf − The node which does not have any child node is called the leaf node.

🌱 Subtree − Subtree represents the descendants of a node.

🌱 Visiting − Visiting refers to checking the value of a node when control is on the node.

🌱 Traversing − Traversing means passing through nodes in a specific order.

🌱 Levels − Level of a node represents the generation of a node. If the root node is at level 0, then its next child node is at level 1, its grandchild is at level 2, and so on.

🌱 keys − Key represents a value of a node based on which a search operation is to be carried out for a node.



⚪ Tree Node
The code to write a tree node would be similar to what is given below. It has a data part and references to its left and right child nodes.

struct node {
   int data;   
   struct node *leftChild;
   struct node *rightChild;
};


BST Basic Operations
The basic operations that can be performed on a binary search tree data structure, are the following −

Insert − Inserts an element in a tree/create a tree.

Search − Searches an element in a tree.

Preorder Traversal − Traverses a tree in a pre-order manner.

Inorder Traversal − Traverses a tree in an in-order manner.

Postorder Traversal − Traverses a tree in a post-order manner.


☛ Binary Search Tree 🚧
========================
💢 A Binary Search Tree (BST) is a tree in which all the nodes follow the below-mentioned properties −

The value of the key of the left sub-tree is less than the value of its parent (root) node's key.

The value of the key of the right sub-tree is greater than or equal to the value of its parent (root) node's key.

Thus, BST divides all its sub-trees into two segments; the left sub-tree and the right sub-tree and can be defined as −

left_subtree (keys) < node (key) ≤ right_subtree (keys)


💢 Basic Operations
Following are the basic operations of a tree −

☣️ Search − Searches an element in a tree.

☣️ Insert − Inserts an element in a tree.

☣️ Pre-order Traversal − Traverses a tree in a pre-order manner.

☣️ In-order Traversal − Traverses a tree in an in-order manner.

☣️ Post-order Traversal − Traverses a tree in a post-order manner.


💢 Node
Define a node having some data, references to its left and right child nodes.

struct node {
   int data;   
   struct node *leftChild;
   struct node *rightChild;
};
-----------------------------------------------------------------------------------------------------------------------------------------------------------------------

☛ AVL Trees 🚧
================
What if the input to binary search tree comes in a sorted (ascending or descending) manner? It will then look like this −

Unbalanced BST
It is observed that BST's worst-case performance is closest to linear search algorithms, that is Ο(n). In real-time data, we cannot predict data pattern and their frequencies. So, a need arises to balance out the existing BST.

Named after their inventor Adelson, Velski & Landis, AVL trees are height balancing binary search tree. AVL tree checks the height of the left and the right sub-trees and assures that the difference is not more than 1. This difference is called the Balance Factor.


If the difference in the height of left and right sub-trees is more than 1, the tree is balanced using some rotation techniques.

👉 AVL Rotations
To balance itself, an AVL tree may perform the following four kinds of rotations −

👉 Left rotation
👉 Right rotation
👉 Left-Right rotation
👉 Right-Left rotation
The first two rotations are single rotations and the next two rotations are double rotations. To have an unbalanced tree, we at least need a tree of height 2. With this simple tree, let's understand them one by one.

👉 Left Rotation
In our example, node A has become unbalanced as a node is inserted in the right subtree of A's right subtree. We perform the left rotation by making A the left-subtree of B.

👉 Right Rotation
AVL tree may become unbalanced, if a node is inserted in the left subtree of the left subtree. The tree then needs a right rotation.

👉 Left-Right Rotation
Double rotations are slightly complex version of already explained versions of rotations. To understand them better, we should take note of each action performed while rotation. Let's first check how to perform Left-Right rotation. A left-right rotation is a combination of left rotation followed by right rotation.

👉 Right-Left Rotation
The second type of double rotation is Right-Left Rotation. It is a combination of right rotation followed by left rotation.

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------

☛ Spanning Tree 🚧
===================
A spanning tree is a subset of Graph G, which has all the vertices covered with minimum possible number of edges. Hence, a spanning tree does not have cycles and it cannot be disconnected..
By this definition, we can draw a conclusion that every connected and undirected Graph G has at least one spanning tree. A disconnected graph does not have any spanning tree, as it cannot be spanned to all its vertices.
We found three spanning trees off one complete graph. A complete undirected graph can have maximum nn-2 number of spanning trees, where n is the number of nodes. In the above addressed example, n is 3, hence 33−2 = 3 spanning trees are possible.


🦈 General Properties of Spanning Tree
We now understand that one graph can have more than one spanning tree. Following are a few properties of the spanning tree connected to graph G −

A connected graph G can have more than one spanning tree.

All possible spanning trees of graph G, have the same number of edges and vertices.

The spanning tree does not have any cycle (loops).

Removing one edge from the spanning tree will make the graph disconnected, i.e. the spanning tree is minimally connected.

Adding one edge to the spanning tree will create a circuit or loop, i.e. the spanning tree is maximally acyclic

__________________________________________________

🦈 Mathematical Properties of Spanning Tree
Spanning tree has n-1 edges, where n is the number of nodes (vertices).

From a complete graph, by removing maximum e - n + 1 edges, we can construct a spanning tree.

A complete graph can have maximum nn-2 number of spanning trees.

Thus, we can conclude that spanning trees are a subset of connected Graph G and disconnected graphs do not have spanning tree.
__________________________________________________

🦈 Application of Spanning Tree
Spanning tree is basically used to find a minimum path to connect all nodes in a graph. Common application of spanning trees are −
Civil Network Planning
Computer Network Routing Protocol
Cluster Analysis
Let us understand this through a small example. Consider, city network as a huge graph and now plans to deploy telephone lines in such a way that in minimum lines we can connect to all city nodes. This is where the spanning tree comes into picture.

🦈Minimum Spanning Tree (MST)
In a weighted graph, a minimum spanning tree is a spanning tree that has minimum weight than all other spanning trees of the same graph. In real-world situations, this weight can be measured as distance, congestion, traffic load or any arbitrary value denoted to the edges.

Minimum Spanning-Tree Algorithm
We shall learn about two most important spanning tree algorithms here −
🦈Kruskal's Algorithm
🦈Prim's Algorithm
Both are greedy algorithms.



☛ Kruskal's Spanning Tree Algorithm 🚧
=======================================

Kruskal's algorithm to find the minimum cost spanning tree uses the greedy approach. This algorithm treats the graph as a forest and every node it has as an individual tree. A tree connects to another only and only if, it has the least cost among all available options and does not violate MST properties.


🦉Step 1 - Remove all loops and Parallel Edges
Remove all loops and parallel edges from the given graph.

🦉Step 2 - Arrange all edges in their increasing order of weight
The next step is to create a set of edges and weight, and arrange them in an ascending order of weightage (cost).

🦉Step 3 - Add the edge which has the least weightage
Now we start adding edges to the graph beginning from the one which has the least weight. Throughout, we shall keep checking that the spanning properties remain intact. In case, by adding one edge, the spanning tree property does not hold then we shall consider not to include the edge in the graph.

MST Graph step one
The least cost is 2 and edges involved are B,D and D,T. We add them. Adding them does not violate spanning tree properties, so we continue to our next edge selection.

Next cost is 3, and associated edges are A,C and C,D. We add them again −

MST Graph step two
Next cost in the table is 4, and we observe that adding it will create a circuit in the graph. −

MST Graph step three
We ignore it. In the process we shall ignore/avoid all edges that create a circuit.

MST Graph step four
We observe that edges with cost 5 and 6 also create circuits. We ignore them and move on.

MST Graph step five
Now we are left with only one node to be added. Between the two least cost edges available 7 and 8, we shall add the edge with cost 7.

MST Kruskals Algorithm
By adding edge S,A we have included all the nodes of the graph and we now have minimum cost spanning tree.


☛ Prim's Spanning Tree Algorithm 🚧
=====================================

Prim's algorithm to find minimum cost spanning tree (as Kruskal's algorithm) uses the greedy approach. Prim's algorithm shares a similarity with the shortest path first algorithms.

Prim's algorithm, in contrast with Kruskal's algorithm, treats the nodes as a single tree and keeps on adding new nodes to the spanning tree from the given graph.


🦇 Step 1 - Remove all loops and parallel edges
MST Graph with loops
Remove all loops and parallel edges from the given graph. In case of parallel edges, keep the one which has the least cost associated and remove all others.

MST Graph without loops
🦇 Step 2 - Choose any arbitrary node as root node
In this case, we choose S node as the root node of Prim's spanning tree. This node is arbitrarily chosen, so any node can be the root node. One may wonder why any video can be a root node. So the answer is, in the spanning tree all the nodes of a graph are included and because it is connected then there must be at least one edge, which will join it to the rest of the tree.

🦇 Step 3 - Check outgoing edges and select the one with less cost
After choosing the root node S, we see that S,A and S,C are two edges with weight 7 and 8, respectively. We choose the edge S,A as it is lesser than the other.

MST Graph Step 1
Now, the tree S-7-A is treated as one node and we check for all edges going out from it. We select the one which has the lowest cost and include it in the tree.

MST Graph Step 2
After this step, S-7-A-3-C tree is formed. Now we'll again treat it as a node and will check all the edges again. However, we will choose only the least cost edge. In this case, C-3-D is the new edge, which is less than other edges' cost 8, 6, 4, etc.

MST Graph Step 3
After adding node D to the spanning tree, we now have two edges going out of it having the same cost, i.e. D-2-T and D-2-B. Thus, we can add either one. But the next step will again yield edge 2 as the least cost. Hence, we are showing a spanning tree with both edges included.

MST Prim's Algorithm
We may find that the output spanning tree of the same graph using two different algorithms is same.

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------
☛ Heap  🚧
=============

🦖 Heap is a special case of balanced binary tree data structure where the root-node key is compared with its children and arranged accordingly. If α has child node β then −

key(α) ≥ key(β)

As the value of parent is greater than that of child, this property generates Max Heap. Based on this criteria, a heap can be of two types −

For Input → 35 33 42 10 14 19 27 44 26 31
Min-Heap − Where the value of the root node is less than or equal to either of its children.

🦖Max Heap Construction Algorithm
We shall use the same example to demonstrate how a Max Heap is created. The procedure to create Min Heap is similar but we go for min values instead of max values.
We are going to derive an algorithm for max heap by inserting one element at a time. At any point of time, heap must maintain its property. While insertion, we also assume that we are inserting a node in an already heapified tree.

Step 1 − Create a new node at the end of heap.
Step 2 − Assign new value to the node.
Step 3 − Compare the value of this child node with its parent.
Step 4 − If value of parent is less than child, then swap them.
Step 5 − Repeat step 3 & 4 until Heap property holds.
Note − In Min Heap construction algorithm, we expect the value of the parent node to be less than that of the child node.

Let's understand Max Heap construction by an animated illustration. We consider the same input sample that we used earlier.


🦖Max Heap Deletion Algorithm
Let us derive an algorithm to delete from max heap. Deletion in Max (or Min) Heap always happens at the root to remove the Maximum (or minimum) value.

Step 1 − Remove root node.
Step 2 − Move the last element of last level to root.
Step 3 − Compare the value of this child node with its parent.
Step 4 − If value of parent is less than child, then swap them.
Step 5 − Repeat step 3 & 4 until Heap property holds.

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------
☛ Data Structures 🚧
=======================
🐉 Data Definition defines a particular data with the following characteristics.
Atomic − Definition should define a single concept.
Traceable − Definition should be able to be mapped to some data element.
Accurate − Definition should be unambiguous.
Clear and Concise − Definition should be understandable.

🐉 Data Object represents an object having a data.

🐉Data type is a way to classify various types of data such as integer, string, etc. which determines the values that can be used with the corresponding type of data, the type of operations that can be performed on the corresponding type of data. There are two data types −

Built-in Data Type
Derived Data Type
Those data types for which a language has built-in support are known as Built-in Data types. For example, most of the languages provide the following built-in data types.

Integers
Boolean (true, false)
Floating (Decimal numbers)
Character and Strings
Derived Data Type
Those data types which are implementation independent as they can be implemented in one or the other way are known as derived data types. These data types are normally built by the combination of primary or built-in data types and associated operations on them. For example −

List
Array
Stack
Queue
Basic Operations
The data in the data structures are processed by certain operations. The particular data structure chosen largely depends on the frequency of the operation that needs to be performed on the data structure.

Traversing
Searching
Insertion
Deletion
Sorting
Merging


☛ Data Structures and Algorithms - Arrays 🚧
=============================================
🦞 Array is a container which can hold a fix number of items and these items should be of the same type. Most of the data structures make use of arrays to implement their algorithms. Following are the important terms to understand the concept of Array.

Element − Each item stored in an array is called an element.

Index − Each location of an element in an array has a numerical index, which is used to identify the element.

🦞 Array Representation
Arrays can be declared in various ways in different languages. For illustration, let's take C array declaration.

🦞 Array Declaration
Arrays can be declared in various ways in different languages. For illustration, let's take C array declaration.


🦞 Basic Operations
Following are the basic operations supported by an array.
Traverse − print all the array elements one by one.
Insertion − Adds an element at the given index.
Deletion − Deletes an element at the given index.
Search − Searches an element using the given index or by the value.
Update − Updates an element at the given index.

__________________________________________________
🦞 Example
Following program traverses and prints the elements of an array:

#include <stdio.h>
main() {
   int LA[] = {1,3,5,7,8};
   int item = 10, k = 3, n = 5;
   int i = 0, j = n;   
   printf("The original array elements are :\n");
   for(i = 0; i<n; i++) {
      printf("LA[%d] = %d \n", i, LA[i]);
   }
}
When we compile and execute the above program, it produces the following result −

🦞 Output
The original array elements are :
LA[0] = 1 
LA[1] = 3 
LA[2] = 5 
LA[3] = 7 
LA[4] = 8 
__________________________________________________

🦞 Insertion Operation
Insert operation is to insert one or more data elements into an array. Based on the requirement, a new element can be added at the beginning, end, or any given index of array.

Here, we see a practical implementation of insertion operation, where we add data at the end of the array −

Example
#include <stdio.h>

main() {
   int LA[] = {1,3,5,7,8};
   int item = 10, k = 3, n = 5;
   int i = 0, j = n;
   
   printf("The original array elements are :\n");

   for(i = 0; i<n; i++) {
      printf("LA[%d] = %d \n", i, LA[i]);
   }

   n = n + 1;
	
   while( j >= k) {
      LA[j+1] = LA[j];
      j = j - 1;
   }

   LA[k] = item;

   printf("The array elements after insertion :\n");

   for(i = 0; i<n; i++) {
      printf("LA[%d] = %d \n", i, LA[i]);
   }
}
When we compile and execute the above program, it produces the following result −

🦞 Output
The original array elements are :
LA[0] = 1 
LA[1] = 3 
LA[2] = 5 
LA[3] = 7 
LA[4] = 8 
The array elements after insertion :
LA[0] = 1 
LA[1] = 3 
LA[2] = 5 
LA[3] = 10 
LA[4] = 7 
LA[5] = 8 

__________________________________________________


🦞 Deletion Operation
Deletion refers to removing an existing element from the array and re-organizing all elements of an array.

Algorithm
Consider LA is a linear array with N elements and K is a positive integer such that K<=N. Following is the algorithm to delete an element available at the Kth position of LA.

1. Start
2. Set J = K
3. Repeat steps 4 and 5 while J < N
4. Set LA[J] = LA[J + 1]
5. Set J = J+1
6. Set N = N-1
7. Stop

Example
#include <stdio.h>

void main() {
   int LA[] = {1,3,5,7,8};
   int k = 3, n = 5;
   int i, j;
   
   printf("The original array elements are :\n");
	
   for(i = 0; i<n; i++) {
      printf("LA[%d] = %d \n", i, LA[i]);
   }
    
   j = k;
	
   while( j < n) {
      LA[j-1] = LA[j];
      j = j + 1;
   }
	
   n = n -1;
   
   printf("The array elements after deletion :\n");
	
   for(i = 0; i<n; i++) {
      printf("LA[%d] = %d \n", i, LA[i]);
   }
}
When we compile and execute the above program, it produces the following result −

🦞 Output
The original array elements are :
LA[0] = 1 
LA[1] = 3 
LA[2] = 5 
LA[3] = 7 
LA[4] = 8 
The array elements after deletion :
LA[0] = 1 
LA[1] = 3 
LA[2] = 7 
LA[3] = 8 

__________________________________________________
Search Operation
You can perform a search for an array element based on its value or its index.

🦞 Algorithm
Consider LA is a linear array with N elements and K is a positive integer such that K<=N. Following is the algorithm to find an element with a value of ITEM using sequential search.

1. Start
2. Set J = 0
3. Repeat steps 4 and 5 while J < N
4. IF LA[J] is equal ITEM THEN GOTO STEP 6
5. Set J = J +1
6. PRINT J, ITEM
7. Stop


🦞 Example
#include <stdio.h>

void main() {
   int LA[] = {1,3,5,7,8};
   int item = 5, n = 5;
   int i = 0, j = 0;
   
   printf("The original array elements are :\n");
	
   for(i = 0; i<n; i++) {
      printf("LA[%d] = %d \n", i, LA[i]);
   }
    
   while( j < n){
      if( LA[j] == item ) {
         break;
      }
		
      j = j + 1;
   }
	
   printf("Found element %d at position %d\n", item, j+1);
}
When we compile and execute the above program, it produces the following result −

🦞 Output
The original array elements are :
LA[0] = 1 
LA[1] = 3 
LA[2] = 5 
LA[3] = 7 
LA[4] = 8 
Found element 5 at position 3
__________________________________________________
🦞 Update Operation
Update operation refers to updating an existing element from the array at a given index.

🦞 Algorithm
Consider LA is a linear array with N elements and K is a positive integer such that K<=N. Following is the algorithm to update an element available at the Kth position of LA.

1. Start
2. Set LA[K-1] = ITEM
3. Stop


🦞 Example
#include <stdio.h>

void main() {
   int LA[] = {1,3,5,7,8};
   int k = 3, n = 5, item = 10;
   int i, j;
   
   printf("The original array elements are :\n");
	
   for(i = 0; i<n; i++) {
      printf("LA[%d] = %d \n", i, LA[i]);
   }
    
   LA[k-1] = item;

   printf("The array elements after updation :\n");
	
   for(i = 0; i<n; i++) {
      printf("LA[%d] = %d \n", i, LA[i]);
   }
}
When we compile and execute the above program, it produces the following result −

🦞 Output
The original array elements are :
LA[0] = 1 
LA[1] = 3 
LA[2] = 5 
LA[3] = 7 
LA[4] = 8 
The array elements after updation :
LA[0] = 1 
LA[1] = 3 
LA[2] = 10 
LA[3] = 7 
LA[4] = 8 


-----------------------------------------------------------------------------------------------------------------------------------------------------------------------

☛ Linked List 🚧
==================

🦅 A linked list is a sequence of data structures, which are connected together via links.
Linked List is a sequence of links which contains items. Each link contains a connection to another link. Linked list is the second most-used data structure after array. Following are the important terms to understand the concept of Linked List.

🦅 Link − Each link of a linked list can store a data called an element.
🦅 Next − Each link of a linked list contains a link to the next link called Next.

🦅 LinkedList − A Linked List contains the connection link to the first link called First.

Linked List Representation
Linked list can be visualized as a chain of nodes, where every node points to the next node.

🦅Linked List
As per the above illustration, following are the important points to be considered.

Linked List contains a link element called first.

Each link carries a data field(s) and a link field called next.

Each link is linked with its next link using its next link.

Last link carries a link as null to mark the end of the list.

Types of Linked List
Following are the various types of linked list.
🦅 Simple Linked List − Item navigation is forward only.
🦅 Doubly Linked List − Items can be navigated forward and backward.
🦅 Circular Linked List − Last item contains link of the first element as next and the first element has a link to the last element as previous.

🦅 Basic Operations
Following are the basic operations supported by a list.
Insertion − Adds an element at the beginning of the list.
Deletion − Deletes an element at the beginning of the list.
Display − Displays the complete list.
Search − Searches an element using the given key.
Delete − Deletes an element using the given key.



Insertion Operation
Adding a new node in linked list is a more than one step activity. We shall learn this with diagrams here. First, create a node using the same structure and find the location where it has to be inserted

🦅 Linked List Insertion
Imagine that we are inserting a node B (NewNode), between A (LeftNode) and C (RightNode). Then point B.next to C −
NewNode.next −> RightNode;
It should look like this −
Linked List Insertion
Now, the next node at the left should point to the new node.
LeftNode.next −> NewNode;
Linked List Insertion
This will put the new node in the middle of the two. The new list should look like this −
Linked List Insertion
Similar steps should be taken if the node is being inserted at the beginning of the list. While inserting it at the end, the second last node of the list should point to the new node and the new node will point to NULL.

🦅 Deletion Operation
Deletion is also a more than one step process. We shall learn with pictorial representation. First, locate the target node to be removed, by using searching algorithms.
Linked List Deletion
The left (previous) node of the target node now should point to the next node of the target node −
LeftNode.next −> TargetNode.next;
Linked List Deletion
This will remove the link that was pointing to the target node. Now, using the following code, we will remove what the target node is pointing at.
TargetNode.next −> NULL;
Linked List Deletion
We need to use the deleted node. We can keep that in memory otherwise we can simply deallocate memory and wipe off the target node completely.

🦅 Linked List Deletion
Reverse Operation
This operation is a thorough one. We need to make the last node to be pointed by the head node and reverse the whole linked list.

🦅 Linked List Reverse Operation
First, we traverse to the end of the list. It should be pointing to NULL. Now, we shall make it point to its previous node −
Linked List Reverse Operation
We have to make sure that the last node is not the last node. So we'll have some temp node, which looks like the head node pointing to the last node. Now, we shall make all left side nodes point to their previous nodes one by one.

🦅 Linked List Reverse Operation
Except the node (first node) pointed by the head node, all nodes should point to their predecessor, making them their new successor. The first node will point to NULL.

🦅 Linked List Reverse Operation
We'll make the head node point to the new first node by using the temp node.

☛ Doubly Linked List 🚧
========================
Doubly Linked List is a variation of Linked list in which navigation is possible in both ways, either forward and backward easily as compared to Single Linked List. Following are the important terms to understand the concept of doubly linked list.
🦅 Link − Each link of a linked list can store a data called an element.
🦅 Next − Each link of a linked list contains a link to the next link called Next.
🦅 Prev − Each link of a linked list contains a link to the previous link called Prev.
🦅 LinkedList − A Linked List contains the connection link to the first link called First and to the last link called Last.


🔵 Doubly Linked List Representation

🦅 Doubly Linked List
As per the above illustration, following are the important points to be considered.
Doubly Linked List contains a link element called first and last.
Each link carries a data field(s) and two link fields called next and prev.
Each link is linked with its next link using its next link.
Each link is linked with its previous link using its previous link.
The last link carries a link as null to mark the end of the list.

🔵 Basic Operations
Following are the basic operations supported by a list.
🦅 Insertion − Adds an element at the beginning of the list.
🦅 Deletion − Deletes an element at the beginning of the list.
🦅 Insert Last − Adds an element at the end of the list.
🦅 Delete Last − Deletes an element from the end of the list.
🦅 Insert After − Adds an element after an item of the list.
🦅 Delete − Deletes an element from the list using the key.
🦅 Display forward − Displays the complete list in a forward manner.
🦅 Display backward − Displays the complete list in a backward manner.


☛ Circular Linked List 🚧
===========================

🔵 Circular Linked List is a variation of Linked list in which the first element points to the last element and the last element points to the first element.
 Both Singly Linked List and Doubly Linked List can be made into a circular linked list.


⚪ Singly Linked List as Circular
In singly linked list, the next pointer of the last node points to the first node.

⚪ Doubly Linked List as Circular
In doubly linked list, the next pointer of the last node points to the first node and the previous pointer of the first node points to the last node making the circular in both directions.


🔵 As per the above illustration, following are the important points to be considered.
The last link's next points to the first link of the list in both cases of singly as well as doubly linked list.
The first link's previous points to the last of the list in case of doubly linked list.
Basic Operations
Following are the important operations supported by a circular list.
insert − Inserts an element at the start of the list.
delete − Deletes an element from the start of the list.
display − Displays the li


🦅 Insertion Operation
Following code demonstrates the insertion operation in a circular linked list based on single linked list.

Example
insertFirst(data):
Begin
   create a new node
   node -> data := data
   if the list is empty, then
      head := node
      next of node = head
   else
      temp := head
      while next of temp is not head, do
      temp := next of temp
      done
      next of node := head
      next of temp := node
      head := node
   end if
End
__________________________________________________

🦅 Deletion Operation
Following code demonstrates the deletion operation in a circular linked list based on single linked list.

deleteFirst():
Begin
   if head is null, then
      it is Underflow and return
   else if next of head = head, then
      head := null
      deallocate head
   else
      ptr := head
      while next of ptr is not head, do
         ptr := next of ptr
      next of ptr = next of head
      deallocate head
      head := next of ptr
   end if
End
__________________________________________________
🦅 Display List Operation
Following code demonstrates the display list operation in a circular linked list.

display():
Begin
   if head is null, then
      Nothing to print and return
   else
      ptr := head
      while next of ptr is not head, do
         display data of ptr
         ptr := next of ptr
      display data of ptr
   end if
End
-----------------------------------------------------------------------------------------------------------------------------------------------------------------------
☛  Stack 🚧
=============
⚪ A stack is an Abstract Data Type (ADT), commonly used in most programming languages. It is named stack as it behaves like a real-world stack, for example – a deck of cards or a pile of plates, etc.

Stack Example
A real-world stack allows operations at one end only. For example, we can place or remove a card or plate from the top of the stack only. Likewise, Stack ADT allows all data operations at one end only. At any given time, we can only access the top element of a stack.
This feature makes it LIFO data structure. LIFO stands for Last-in-first-out. Here, the element which is placed (inserted or added) last, is accessed first. In stack terminology, insertion operation is called PUSH operation and removal operation is called POP operation.


🔴 Basic Operations
Stack operations may involve initializing the stack, using it and then de-initializing it. Apart from these basic stuffs, a stack is used for the following two primary operations −

🥀 push() − Pushing (storing) an element on the stack.

🥀 pop() − Removing (accessing) an element from the stack.

When data is PUSHed onto stack.

To use a stack efficiently, we need to check the status of stack as well. For the same purpose, the following functionality is added to stacks −

🥀 peek() − get the top data element of the stack, without removing it.

🥀 isFull() − check if stack is full.

🥀 isEmpty() − check if stack is empty.

At all times, we maintain a pointer to the last PUSHed data on the stack. As this pointer always represents the top of the stack, hence named top. The top pointer provides top value of the stack without actually removing it.

__________________________________________________

➰ peek()
Algorithm of peek() function −

begin procedure peek
   return stack[top]
end procedure
Implementation of peek() function in C programming language −

➰ Example

int peek() {
   return stack[top];
}

__________________________________________________
➰ isfull()
Algorithm of isfull() function −

begin procedure isfull

   if top equals to MAXSIZE
      return true
   else
      return false
   endif
   
end procedure
Implementation of isfull() function in C programming language −

➰ Example

bool isfull() {
   if(top == MAXSIZE)
      return true;
   else
      return false;
}
__________________________________________________
➰ isempty()
Algorithm of isempty() function −

begin procedure isempty

   if top less than 1
      return true
   else
      return false
   endif
   
end procedure
Implementation of isempty() function in C programming language is slightly different. We initialize top at -1, as the index in array starts from 0. So we check if the top is below zero or -1 to determine if the stack is empty. Here's the code −

➰ Example

bool isempty() {
   if(top == -1)
      return true;
   else
      return false;
}
__________________________________________________

🔴 Push Operation
The process of putting a new data element onto stack is known as a Push Operation. Push operation involves a series of steps −

Step 1 − Checks if the stack is full.

Step 2 − If the stack is full, produces an error and exit.

Step 3 − If the stack is not full, increments top to point next empty space.

Step 4 − Adds data element to the stack location, where top is pointing.

Step 5 − Returns success.


➰ Algorithm for PUSH Operation
A simple algorithm for Push operation can be derived as follows −

begin procedure push: stack, data

   if stack is full
      return null
   endif
   
   top ← top + 1
   stack[top] ← data

end procedure
Implementation of this algorithm in C, is very easy. See the following code −

➰ Example

void push(int data) {
   if(!isFull()) {
      top = top + 1;   
      stack[top] = data;
   } else {
      printf("Could not insert data, Stack is full.\n");
   }
}
__________________________________________________
➰ Pop Operation
Accessing the content while removing it from the stack, is known as a Pop Operation. In an array implementation of pop() operation, the data element is not actually removed, instead top is decremented to a lower position in the stack to point to the next value. But in linked-list implementation, pop() actually removes data element and deallocates memory space.

A Pop operation may involve the following steps −

Step 1 − Checks if the stack is empty.

Step 2 − If the stack is empty, produces an error and exit.

Step 3 − If the stack is not empty, accesses the data element at which top is pointing.

Step 4 − Decreases the value of top by 1.

Step 5 − Returns success.

Stack Pop Operation
Algorithm for Pop Operation
A simple algorithm for Pop operation can be derived as follows −

begin procedure pop: stack

   if stack is empty
      return null
   endif
   
   data ← stack[top]
   top ← top - 1
   return data

end procedure
Implementation of this algorithm in C, is as follows −

➰ Example

int pop(int data) {

   if(!isempty()) {
      data = stack[top];
      top = top - 1;   
      return data;
   } else {
      printf("Could not retrieve data, Stack is empty.\n");
   }
}

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------

☛  Queue 🚧
=============

🔗 Queue is an abstract data structure, somewhat similar to Stacks. Unlike stacks, a queue is open at both its ends. One end is always used to insert data (enqueue) and the other is used to remove data (dequeue). Queue follows First-In-First-Out methodology, i.e., the data item stored first will be accessed first.
Queue Example
A real-world example of queue can be a single-lane one-way road, where the vehicle enters first, exits first. More real-world examples can be seen as queues at the ticket windows and bus-stops.

Basic Operations
Queue operations may involve initializing or defining the queue, utilizing it, and then completely erasing it from the memory. Here we shall try to understand the basic operations associated with queues −
🔗 enqueue() − add (store) an item to the queue.
🔗 dequeue() − remove (access) an item from the queue.

Few more functions are required to make the above-mentioned queue operation efficient. These are −

🔗 peek() − Gets the element at the front of the queue without removing it.

🔗 isfull() − Checks if the queue is full.

🔗 isempty() − Checks if the queue is empty.

In queue, we always dequeue (or access) data, pointed by front pointer and while enqueing (or storing) data in the queue we take help of rear pointer.
Let's first learn about supportive functions of a queue 


peek()
This function helps to see the data at the front of the queue. The algorithm of peek() function is as follows −

🔗 Algorithm

begin procedure peek
   return queue[front]
end procedure
Implementation of peek() function in C programming language −

🔗 Example

int peek() {
   return queue[front];
}

__________________________________________________

isfull()
As we are using single dimension array to implement queue, we just check for the rear pointer to reach at MAXSIZE to determine that the queue is full. In case we maintain the queue in a circular linked-list, the algorithm will differ. Algorithm of isfull() function −

🔗 Algorithm

begin procedure isfull

   if rear equals to MAXSIZE
      return true
   else
      return false
   endif
   
end procedure
Implementation of isfull() function in C programming language −

🔗 Example

bool isfull() {
   if(rear == MAXSIZE - 1)
      return true;
   else
      return false;
}

__________________________________________________

sempty()
Algorithm of isempty() function −

🔗Algorithm

begin procedure isempty

   if front is less than MIN  OR front is greater than rear
      return true
   else
      return false
   endif
   
end procedure
If the value of front is less than MIN or 0, it tells that the queue is not yet initialized, hence empty.

Here's the C programming code −

🔗Example

bool isempty() {
   if(front < 0 || front > rear) 
      return true;
   else
      return false;
}

__________________________________________________
🧷️ Enqueue Operation
Queues maintain two data pointers, front and rear. Therefore, its operations are comparatively difficult to implement than that of stacks.

The following steps should be taken to enqueue (insert) data into a queue −

Step 1 − Check if the queue is full.

Step 2 − If the queue is full, produce overflow error and exit.

Step 3 − If the queue is not full, increment rear pointer to point the next empty space.

Step 4 − Add data element to the queue location, where the rear is pointing.

Step 5 − return success.



🧷️ Algorithm for enqueue operation
procedure enqueue(data)      
   
   if queue is full
      return overflow
   endif
   
   rear ← rear + 1
   queue[rear] ← data
   return true
   
end procedure
Implementation of enqueue() in C programming language −

🧷️ Example

int enqueue(int data)      
   if(isfull())
      return 0;
   
   rear = rear + 1;
   queue[rear] = data;
   
   return 1;
end procedure

__________________________________________________

⛏ Dequeue Operation
Accessing data from the queue is a process of two tasks − access the data where front is pointing and remove the data after access. The following steps are taken to perform dequeue operation −

Step 1 − Check if the queue is empty.

Step 2 − If the queue is empty, produce underflow error and exit.

Step 3 − If the queue is not empty, access the data where front is pointing.

Step 4 − Increment front pointer to point to the next available data element.

Step 5 − Return success.

⛏ Algorithm for dequeue operation
procedure dequeue
   
   if queue is empty
      return underflow
   end if

   data = queue[front]
   front ← front + 1
   return true

end procedure
Implementation of dequeue() in C programming language −

⛏ Example

int dequeue() {
   if(isempty())
      return 0;

   int data = queue[front];
   front = front + 1;

   return data;
}

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------


With My Best Wishes ..✎ Waled Saied 



My advice to you is to use: https://visualgo.net/en  ✉
