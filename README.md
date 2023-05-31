*This markdown contains answers for projects in the patika.dev course of data structures and algorithms.*

# Project-1

### [22,27,16,2,18,6] -> Insertion Sort  

 - **Phase 1**
Array: [22, 27, 16, 2, 18, 6]
Sorted portion: [22]
Unsorted portion: [27, 16, 2, 18, 6]

- **Phase 2**
Array: [22, 27, 16, 2, 18, 6]
Sorted portion: [22, 27]
Unsorted portion: [16, 2, 18, 6]

- **Phase 3**
Array: [22, 27, 16, 2, 18, 6]
Sorted portion: [16, 22, 27]
Unsorted portion: [2, 18, 6]

- **Phase 4**
Array: [22, 27, 16, 2, 18, 6]
Sorted portion: [2, 16, 22, 27]
Unsorted portion: [18, 6]

- **Phase 5**
Array: [2, 16, 18, 22, 27, 6]
Sorted portion: [2, 16, 18, 22, 27]
Unsorted portion: [6]

- **Phase 6**
Array: [2, 6, 16, 18, 22, 27]
Sorted portion: [2, 6, 16, 18, 22, 27]
Unsorted portion: []

### Big-O Notation of Insertion Sort Algorithm
> Worst case - O(n^2)
> Best case - O(n)
> Average case - O(n^2)

### After the sequence is sorted the time complexity of the number 18 falls into
> Best case scenerio

### [7,3,5,8,2,9,4,15,6] -> Selection Sort Algorithm -> The first four phases

 - **Phase 1**
Array: [7, 3, 5, 8, 2, 9, 4, 15, 6]
Minimum element: 2
Swap elements: [2, 3, 5, 8, 7, 9, 4, 15, 6]

 - **Phase 2**
Array: [2, 3, 5, 8, 7, 9, 4, 15, 6]
Minimum element: 3
Swap elements: [2, 3, 5, 8, 7, 9, 4, 15, 6]

 - **Phase 3**
Array: [2, 3, 5, 8, 7, 9, 4, 15, 6]
Minimum element: 4
Swap elements: [2, 3, 4, 8, 7, 9, 5, 15, 6]

 - **Phase 4**
Array: [2, 3, 4, 8, 7, 9, 5, 15, 6]
Minimum element: 5
Swap elements: [2, 3, 4, 5, 7, 9, 8, 15, 6]

### Time complexity of the selection sort algorithm

> O(n^2)

# Project-2

### [16,21,11,8,12,22] -> Merge Sort

 - **Phase 1**
Array: [16, 21, 11, 8, 12, 22]
Divide: [16, 21, 11] [8, 12, 22]

- **Phase 2**
Array: [16, 21, 11]
Divide: [16] [21, 11]

- **Phase 3**
Array: [21, 11]
Divide: [21] [11]

- **Phase 4**
Array: [16]
Merge: [16]
Array: [21]
Merge: [11, 21]
Merge: [11, 16, 21]

- **Phase 5**
Array: [8, 12, 22]
Divide: [8] [12, 22]

- **Phase 6**
Array: [12, 22]
Divide: [12] [22]

- **Phase 7**
Array: [12]
Merge: [12]
Array: [22]
Merge: [12, 22]

- **Phase 8**
Merge: [8, 12, 22]

- **Phase 9**
Merge: [8, 11, 12, 16, 21, 22]

### Time complexity of the merge sort algorithm

> O(n log n)

# Project 3

### **[7, 5, 1, 8, 3, 6, 0, 9, 4, 2]** -> Binary Search Tree Phases

            7
           / \
          5   8
         / \   \
        1   6   9
       / \
      0   3
     / \
    2   4

### Best-case scenario

> O(n log n)

### Worst-case scenario

> O(n^2)