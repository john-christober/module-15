# Ex. No: 15D - Build a Heap Tree Using Python

## AIM:
To write a Python program to build a heap tree using appropriate Python package and function.

---

## ALGORITHM:

1. **Start the program.**
2. Import the `heapq` module.
3. Define a function `heaptree(H)` that takes a list `H` as input.
4. Use `heapq.heapify(H)` to convert the list into a min-heap.
5. Print the created heap.
6. **End the program.**

---

## PROGRAM:

```
Name : John chrisotber
Reg No : 212222060098
from binarytree import heap,build,Node
def min_max_heap(L): 
    x=L
    t=build(x)
    for i in (t.values):
        print(i,"-->",end='')
    if (t.is_complete):
        print("\nComplete binary tree")
        if (t.is_max_heap):
            print("\nMax heap tree")
        else:
            print("\nMin heap tree")
    else:
        print("\nNot a Complete binary tree")
```

## OUTPUT
<img width="1126" height="288" alt="image" src="https://github.com/user-attachments/assets/bd0cd462-d6e1-4706-829d-0102cc80e50a" />

## RESULT
Thus ,a Python program to build a heap tree using appropriate Python package and function is successfully executed.
