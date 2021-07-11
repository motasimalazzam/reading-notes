# What is a Stack

The stack is a linear data structure that is used to store the collection of objects. In other words it used to store `Nodes`.

## Common terminology for a stack is

1. **Push** Nodes or items that are put into the stack are **pushed**.

2. **Pop** Nodes or items that are removed from the stack are **popped**. When you attempt to pop an empty stack an exception will be raised.

3. **Top** This is the top of the stack.

4. **Peek** When you peek you will view the value of the top Node in the stack. When you attempt to peek an empty stack an exception will be raised.

5. **IsEmpty** returns true when stack is empty otherwise returns false.

## Concepts:

* **FILO**: First In Last Out. That means the first item added in the stack will be the last item go out of the collection.

* **LIFO**: Last In First Out. That means the last item added in the stack will be the first item go out of the collection.

* **Stack Visualization**: When **push** (add item) something to stack it becomes the new `top` and when **pop** (remove item) that means remove cuurent `top` and set the next `top` as `top.next`.

