```text
 _  _  ____                      _                                   
| || ||___ \ _   _ __  _   _ ___| |__        _____      ____ _ _ __  
| || |_ __) (_) | '_ \| | | / __| '_ \ _____/ __\ \ /\ / / _` | '_ \ 
|__   _/ __/ _  | |_) | |_| \__ \ | | |_____\__ \\ V  V / (_| | |_) |
   |_||_____(_) | .__/ \__,_|___/_| |_|     |___/ \_/\_/ \__,_| .__/ 
                |_|                                           |_|    
```

### **Overview**

Sort an array of integers with the least number of steps.

---

### **Learnings**
- Deeper understanding of linked lists

---

### **About**

👉 [**Project requirement**](https://github.com/Mecha-Coder/42-push-swap/blob/main/demo/en.subject.pdf)

This project is about sorting a list of integers as few steps as possible. We are allowed to use one helper array / stack to assist with sorting and a fixed set of operations.

![Figure1](https://github.com/Mecha-Coder/42-push-swap/blob/main/demo/figure1.png)

- sa / sb  — Swap the first two elements at the top of stack A or B
- ra / rb — Rotate: the first element moves to the bottom, and all others shift up
- rra / rrb — Reverse rotate: the last element moves to the top, and all others shift down
- pa / pb — Push: move the top element from one stack to the other

This link takes you to a game that visualizes how the program sorts numbers: https://vscza.itch.io/push-swap

I used the Turk algorithm, which involves calculating the cost (in number of moves) for each possible push and selecting the cheapest move at every iteration. See the resource section for more details on how the algorithm works.

The main technical challenge of this project was managing the linked list — ensuring proper node detachment and reattachment to avoid any memory leaks


---

### **How to run**

---

### **Resource**
- https://medium.com/@ayogun/push-swap-c1f5d2d41e97

--- 
### **Demo**
