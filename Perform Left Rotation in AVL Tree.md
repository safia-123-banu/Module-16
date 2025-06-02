# Ex. No: 16E - Perform Left Rotation in AVL Tree and Insert '7'

## AIM:
To write a Python function `def leftRotate(self, z):` to perform the left rotation operation in an AVL Tree and insert the element '7' into it.

---

## ALGORITHM:

### Step 1: Start the program.

### Step 2: Define the `TreeNode` class to represent each node in the AVL Tree:
- Key value
- Left and right child pointers
- Height of the node

### Step 3: Define the `AVL_Tree` class to manage AVL operations.

### Step 4: In the `insert()` method:
- Insert the key using standard Binary Search Tree logic.
- Update the height of the current node.
- Calculate the balance factor to detect imbalance.
- Based on balance factor and key position, perform necessary rotations.

### Step 5: Define `leftRotate(z)` method:
- Let `y = z.right` and `T2 = y.left`
- Make `z` the left child of `y`
- Assign `T2` as the right child of `z`
- Update heights of `z` and `y`
- Return `y` as the new root of the subtree

### Step 6: Insert the key `'7'` using the `insert()` method. If it causes imbalance, perform appropriate rotation.

### Step 7: Display the tree using `preOrder()` traversal to show the structure after insertion and rotation.

### Step 8: End the program.

---

## PYTHON PROGRAM

```
from TreeAVL.AVL import AVL



def getDictTree(self):
 return self.dict_tree

def Construct_AVL(L):
  tree = AVL(L)
  print("AVL Tree Before Balancing\n",getDictTree(tree))
  tree.BalanceTree()
  print("AVL Tree After Balancing\n",getDictTree(tree))


L=[11,8,18,5,13,17,4,7,2]

```

## OUTPUT
![image](https://github.com/user-attachments/assets/e791ff65-f366-49f3-97cc-1dd27f911320)

## RESULT
Thus the python program was initialised and executed successfully.
