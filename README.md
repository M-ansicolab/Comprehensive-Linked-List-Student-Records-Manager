# Comprehensive-Linked-List-Student-Records-Manager
# Student Record Processor – C (Doubly Linked List)

This C program manages and transforms a doubly linked list of student records using various advanced operations. It supports:

- Head node deletion
- Removal of duplicate IDs (keeping oldest)
- List reversal
- Rotation by `k` positions
- GPA-based sorting

---

##  Features

- **deleteHead**: Removes the head of the list.
- **removeDuplicates**: Deletes all duplicate records for a given ID, keeping only the oldest.
- **reverse**: Reverses the entire list in-place.
- **rotateByKplaces**: Rotates the list to the right by `k` positions.
- **createSortedList**: Generates a new list sorted in ascending order of GPA.

---

## 🛠 Technologies Used

- Language: C
- Data Structure: Doubly Linked List
- Standard Libraries: `stdio.h`, `stdlib.h`

---

##  Input Format

1. First line:  
n k duplicate_id- `n`: number of records  
- `k`: rotation positions  
- `duplicate_id`: ID for which duplicates will be removed

2. Next `n` lines:  
id gpa

---

##  How It Works

1. Reads and creates a doubly linked list of student records.
2. Performs:
- Head deletion
- Duplicate removal for `duplicate_id`
- Reversal of the list
- Rotation by `k` positions
3. Prints the final list in forward and reverse order.
4. Sorts the list by GPA and prints again in both directions.

---



---

##  Memory Management

- All nodes are allocated using `malloc`.
- The program avoids memory leaks during node manipulation.
- You may optionally add `free()` calls to deallocate memory before program termination.

---



