# 📚 Stack using Linked List: Stack Implementation (Top Element Display)

## 🎯 Aim

To write a Python program that implements a **stack**.  
The program allows inserting 3 elements from the user and then prints the **top element** of the stack.

---

## 🧠 Algorithm

1. **Start the program.**
2. **Initialize** an empty list called `stack` to simulate the stack.
3. **Repeat 3 times**:
   - Prompt the user to **input a value**.
   - Use `stack.append(value)` to **push** the value onto the stack.
4. After inserting 3 elements:
   - Access the **top element** using `stack[-1]`.
5. **Print** the top element.
6. **End the program.**

---

## 💻 Program
stack = []

stack.append('a')
stack.append('b')
stack.append('c')
stack.append('d')

print('Initial stack: ' + str(stack))

for i in range(len(stack)):
    top = stack[i]

print("\nElement at the top of the stack is .... ", top)

stack.pop()

for i in range(len(stack)):
    top = stack[i]

print("\nAfter removing an element from the stack.")
print("\nElement at the top of the stack is .... ", top)

## Output
<img width="913" height="300" alt="image" src="https://github.com/user-attachments/assets/551e1874-c11e-4033-9832-de7b7fb199c9" />

## Result
Thus the output is verified.
