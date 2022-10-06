## Vector : 
**syntax**:
 
    //1d vector
    vector  <int>  v(sz);
    //2d vector
    vector  <vector  <int>>  grid(rows);
    vector  <vector  <int>>  grid(rows , vector <int> (cols , initial value));
 
#### Functions on vectors
 - [begin()](https://www.geeksforgeeks.org/vectorbegin-vectorend-c-stl/)
	  Returns an iterator pointing to the first element in the vector
-   [end()](https://www.geeksforgeeks.org/vectorbegin-vectorend-c-stl/) 	
     Returns an iterator pointing to the theoretical element that follows the last element in the vector
- [rbegin()](https://www.geeksforgeeks.org/vector-rbegin-and-rend-function-in-c-stl/) 
     Returns a reverse iterator pointing to the last element in the vector (reverse beginning). It moves from last to first element
 -   [rend()](https://www.geeksforgeeks.org/vector-rbegin-and-rend-function-in-c-stl/) – Returns a reverse iterator pointing to the theoretical element preceding the first element in the vector (considered as reverse end)
-   [resize()](https://www.geeksforgeeks.org/vector-chttps://pastebin.com/begin-vector-cend-c-stl/) 
	  change the size of the vector without deleting or affecting existing elements
-   [assign()](https://www.geeksforgeeks.org/vector-assign-in-c-stl/)
	   erases existing elements and creats a new vector with given size and element
-  [emplace()](https://www.geeksforgeeks.org/vector-emplace-function-in-c-stl/) ,  [emplace_back()](https://www.geeksforgeeks.org/vectoremplace_back-c-stl/) ,  [v.inset(position , val)](https://www.geeksforgeeks.org/vector-insert-function-in-c-stl/) ,  [v.push_back()](https://www.geeksforgeeks.org/vectorpush_back-vectorpop_back-c-stl/) 
      Insert a new element.
vector
-  [pop_back()](https://www.geeksforgeeks.org/vectorpush_back-vectorpop_back-c-stl/) 
		 pop or remove elements from from the back.
-  [erase()](https://www.geeksforgeeks.org/vectorclear-vectorerase-c-stl/)
      remove elements from a container from the specified position or range.
-  [clear()](https://www.geeksforgeeks.org/vectorclear-vectorerase-c-stl/)
		 remove all the elements of the vector container
-  [swap()](https://www.geeksforgeeks.org/vectorat-vectorswap-c-stl/) 
		swap the contents of one vector with another vector of same type. Sizes may differ.
 
 
 
#
**The time complexity for doing various operations on vectors is**
-   Random access – constant O(1)
-   Insertion or removal of elements at the end – constant O(1)
-   Insertion or removal of elements – linear in the distance to the end of the vector O(N)
-   Knowing the size – constant O(1)
-   Resizing the vector- Linear O(N) 
#
**Articals**

[geeksforgeeks](https://www.geeksforgeeks.org/vector-in-cpp-stl/?ref=gcse)


[cplusplus](https://cplusplus.com/reference/vector/vector/)

#
 
**Problems**

[Maintain Multiple Sequences](https://atcoder.jp/contests/abc271/tasks/abc271_b)

[Team Olympiad](https://codeforces.com/problemset/problem/490/A)

#
