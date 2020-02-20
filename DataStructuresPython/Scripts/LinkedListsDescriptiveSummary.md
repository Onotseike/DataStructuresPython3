# Introduction
A member of the category of linear data structures, the Linked list consists of elements which are seperate from each other. 
Each element is classed as a Node which at its basic definition is charaterized as having a ***Data*** and ***Next Pointer*** which serves as a reference to the next Node element

# Types of Linked List
  - **Singly Linked List**: With this type of linked list, every node stores a *data* property and a *reference* to the next node in the list. The last list in the node doesn't store any reference and has a value of NULL/NONE.
  - **Doubly Linked List**: Here, the fundamental description of the node is slightly augmented. A doubly linked list typical node is characterised by three instead of the above mentioned two definitions: ***Data, Next Pointer && Previous Pointer*** with the explanation of the two formers (Data and Next Pointer) remaining as is and the later, the Previous Pointer is a refrence to the previous node in the linked list. The first node in this type of list has a NULL/NONE value for its previous pointer whilst the last node in the list has a NULL/NONE value for its next pointer.
  - **Circular Linked List**: Comparing the singly and circular list, at first glance, they seem eerily similar. However, a fundamental difference could be noticed at the last node's next pointer value. For a singly linked list, the value is NULL/NONE. This is not the case for a the circular linked list, the value is a reference to the first node of the list. This creates a looping list hence the name circular linked list.

# Merits and Demrits of Linked Lists
  - **Merits**:
    | Singly        | Doubly        | Circular|
    | ------------- |-------------| -----|
    | Fetch time element **O(n)**| Fetch time element**O(n)**| Fetch time element **O(n)** |
    | Appending & Prepending time of element **O(1)**| Appending & Prepending time of element **O(1)**| Appending & Prepending time of element **O(1)**|
    | Insertion time with valid position given **O(1)** | Insertion time with valid position given **O(1)** | Insertion time with valid position given **O(1)** |
    | Insertion time without position given **O(n)** | Insertion time without position given **O(n)**  | Insertion time without position given **O(n)**|
    | Deletion time with valid position given **O(1)** |Deletion time with valid position given **O(1)**   |Deletion time with valid position given **O(1)** |
    | Deletion time without position given **O(n)**| Deletion time without position given **O(n)**   |   Deletion time without position given **O(n)**|
    
  - **De-Merits**:
    | Singly        | Doubly        | Circular|
    | ------------- |-------------  | -----|
    | Its unidirectional approach prevents the ability for backwards travesal| Although bi-directional travesal this comes at a cost| Its unidirectional approach prevents the ability for backwards travesal|
    | Random access of elements is not possible| Random access of elements is not possible| Random access of elements is not possible|
    | Memory wastage is limited when compared to Doubly | Memory wastage arises when a doubly linked list solves the uni-directional issues face by other lists by adding a previous node pointer to each node  | Memory wastage is limited when compared to Doubly|
