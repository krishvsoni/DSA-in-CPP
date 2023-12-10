
## Stack

A Stack is a Last In First Out (LIFO) data structure. The lower portion of the stack is locked, and the upper portion is called the top. Elements are added/pushed and removed/popped only from the top of the stack. A common use case of a stack is the Recursion Call Stack.

## Functions

1. **push():** Inserts an element at the top. `void push(x)`

2. **pop():** Removes an element from the top. `void pop()`

3. **isEmpty():** Checks if the stack is empty or not. `bool isEmpty()`

4. **isFull():** Checks if the stack is full or not. `bool isFull()`

5. **size():** Checks the size of the stack. `int size()`

6. **top():** Checks the topmost element. `int top()`

### Best Implementation

The best implementation aims for constant time complexity, O(1).

## Stack Conditions

1. **Overflow:** Occurs when the capacity defined for the stack exceeds by adding more elements.

2. **Underflow:** Occurs when accessing/removing an element from an empty stack.
