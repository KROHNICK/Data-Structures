Answer the following questions for each of the data structures you implemented as part of this project.

## Queue

1. What is the runtime complexity of `enqueue`? Constant

2. What is the runtime complexity of `dequeue`? Constant

3. What is the runtime complexity of `len`? Constant

## Binary Search Tree

1. What is the runtime complexity of `insert`? log(n), worst case scenario O(n)

2. What is the runtime complexity of `contains`? log(n), worst case scenario O(n)

3. What is the runtime complexity of `get_max`? log(n), worst case scenario O(n)

## Heap

1. What is the runtime complexity of `_bubble_up`? log(n)

2. What is the runtime complexity of `_sift_down`? log(n)

3. What is the runtime complexity of `insert`? log(n)

4. What is the runtime complexity of `delete`? log(n)

5. What is the runtime complexity of `get_max`? constant

## Doubly Linked List

1. What is the runtime complexity of `ListNode.insert_after`? Constant

2. What is the runtime complexity of `ListNode.insert_before`? Constant

3. What is the runtime complexity of `ListNode.delete`? Constant

4. What is the runtime complexity of `DoublyLinkedList.add_to_head`? Constant

5. What is the runtime complexity of `DoublyLinkedList.remove_from_head`? Constant

6. What is the runtime complexity of `DoublyLinkedList.add_to_tail`? Constant

7. What is the runtime complexity of `DoublyLinkedList.remove_from_tail`? Constant

8. What is the runtime complexity of `DoublyLinkedList.move_to_front`? Constant

9. What is the runtime complexity of `DoublyLinkedList.move_to_end`? Constant

10. What is the runtime complexity of `DoublyLinkedList.delete`? Constant

    a. Compare the runtime of the doubly linked list's `delete` method with the worst-case runtime of the JS `Array.splice` method. Which method generally performs better?

    the delete runs faster than the array, difference changes as the size gets bigger
