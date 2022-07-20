Project 1: [22,27,16,2,18,6] -> Insertion Sort
1.	The stages according to the sort type:
[2,27,16,22,18,6]
[2,6,16,22,18,27]
[2,6,16,18,22,27]
2.	Big-O notation illustarition: 
Best Case: O(n)
Average Case: O(n^2)
Worst Case: O(n^2)
3.	Time Complexity: 
Average case: [22,27,2,16,18,6]
Worst case:  [27,22,18,16,6,2]
Best case:    [2,6,16,18,22,27]
4.	The case of number ’18’ during the finel stage of sort: Average Case.

5.	First 4 steps for Insertion Sort of [7,3,5,8,2,9,4,15,6]:
[2,3,5,8,7,9,4,15,6]
[2,3,4,8,7,9,5,15,6]
[2,3,4,5,7,9,8,15,6]
[2,3,4,5,6,9,8,15,7]

Project 2: [16,21,11,8,12,22] -> Merge Sort
•	The stages according to the Merge Sort:
[16,21,11]  [8,12,22]
[16] [21,11]   [8,12] [22]
[16] [21] [11]   [8] [12] [22]
[16] [11,21]  [8,12] [22]
[11,16,21]  [8,12,22]
[8,11,12,16,21,22]
•	Big-O notation: 2^x = n --> log(n) = x --> O(nlogn)

Project 3: [7, 5, 1, 8, 3, 6, 0, 9, 4, 2] -> Binary-Search-Tree: Root has been selected as 6.

				6
			5		7
		1				8
			3				9
		0	
			4
		2			
