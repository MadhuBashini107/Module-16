# Ex. No: 16A - Constructing and Printing an AVL Tree in Python

## AIM:
To write a Python program to construct an **AVL tree** and print the nodes of it using the appropriate packages and built-in function.

---

## ALGORITHM:

**Step 1**: Start the program.

**Step 2**: Define a function `getDictTree(tree)` to return the **dict_tree** of an AVL tree.

**Step 3**: Define a function `Construct_AVL(L)` to:
- Create an **AVL tree** from the list `L`.
- Get and print the **dict_tree** using `getDictTree(tree)`.

**Step 4**: Define a list `L` with integer values.

**Step 5**: Call `Construct_AVL(L)` to build the tree and print the result.

**Step 6**: End the program.

---

## PYTHON PROGRAM
```python
from TreeAVL.AVL import AVL
def getDictTree(self):
    return self.dict_tree
def Construct_AVL(L):
    tree=AVL(L)
    print(getDictTree(tree))
```

## OUTPUT

<img width="1862" height="204" alt="image" src="https://github.com/user-attachments/assets/ff1ea168-0448-4805-9df3-9df5fa15164c" />


## RESULT
Thus the program to construct an AVL tree and print the nodes of it has been implemented and executed successfully.
