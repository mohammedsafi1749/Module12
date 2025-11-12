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

    print("Insert the first element:")
    print("Insert the second element:") 
    print("Insert the third element:") 

    for i in range(3):
        stack.append(input())
    
    print('Initial stack: ' + str(stack))

    top = stack.pop()

    print("\nElement at the top of the stack is .... ", top)

## Output
<img width="1134" height="291" alt="image" src="https://github.com/user-attachments/assets/e663310f-197e-42bf-9cc8-20c8f06866f1" />

## Result
Thus the program executed successfully .
