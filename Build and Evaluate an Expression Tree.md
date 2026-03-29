# Ex. No: 15E - Build and Evaluate an Expression Tree


## AIM:
To write a Python program to build and evaluate the given Expression tree.

---

## ALGORITHM:

1. **Start the program.**
2. Create nodes for operators and operands.
3. Build the expression tree by connecting nodes in the correct hierarchical structure.
4. Define a recursive function `evaluate(root)`:
   - If the node is a number (leaf), return it.
   - Else, recursively evaluate left and right subtrees.
   - Apply the operator at the current node to the results.
5. Return the final result from the root node.
6. **End the program.**

---

## PROGRAM:

```
from binarytree import heap,build,Node
def heaptree(L):
  x=L
  t=build(x)
  for i in t.values:
    print(i,"-->",end='')
  print("\nHeight : ",t.height)
  print("Is max heap? : ",t.is_max_heap)
  print("Is complete tree? : ",t.is_complete)

```

## OUTPUT:
![image](https://github.com/user-attachments/assets/7b47d030-1224-4604-b300-a9ce26c9e934)


## RESULT:
Thus, Python program to build and evaluate the given Expression tree was successfully implemented and verified.
