📌 Advanced Market Product Management Using Data Structures (Python)
"University Project – Data Structures"
</hr>
📘 This project is an advanced product management system implemented in Python, designed for a university Data Structures course.
The system manages market products and performs operations such as:

1. Adding and deleting products
2. Storing historical prices
3. Calculating median prices
4. Retrieving sorted prices
5. Searching products by name or price
6. Returning products inside specific price ranges

The project is fully implemented using custom Data Structures, including:

1. Doubly Circular Linked List
2. Binary Search Trees (BSTs)
3. Custom List-to-Tree Conversions

These structures ensure efficient storage, search, insertion, deletion, and price analysis.

🎯 Features:

1. Product Management
   Add new product
   Add new price to an existing product
   Delete product

2. Price Analysis
   Compute median price via BST
   List products sorted by smallest price
   List products sorted by largest price
   Show all products within a price range

3. Searching
   Search product by name using BST
   Search product by exact price using BST

🧵 Data Structures Used

1. Doubly Circular Linked List
   Used for storing the list of prices for each product.
   Supports:
   Insert
   Delete
   Find
   Convert linked list to Python list
   Efficient traversal

2. Binary Search Tree (BST)
   Two separate BSTs are used:

(1) ProductBST (sorted by product name)
That used for:
Fast insertion
Fast alphabetical search
Fast deletion

2. PriceBST (sorted by product price)
   Used for:
   Sorted output (smallest → biggest)
   Reverse sorted output
   Searching price
   Returning products in a price range

3. Additional Structures
   Node class for Linked List
   TreeNode & BSTNode for trees

⚙️ How to Run
You need Python 3.8+ and no external libraries needed.
At first Clone this repository using this code:
git clone https://github.com/AfroozBehrooznick/Advanced-Market-Product-Management-With-Data-Structures-Create-With-Python-
Then run the program with:
python main.py

📊 Median Calculation
The median price is computed by:
Converting the product’s linked list to a Python list
Building a BST from the list
Performing an inorder traversal to get sorted data
Returning the median value

📝 "Afrooz behrooznick"
"Data Structures Course"
