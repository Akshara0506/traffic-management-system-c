# 🚦 Traffic Management System (C-Programming Project)

A complete Traffic Management System implemented in **C**, using **Linked Lists**, **Binary Search Trees**, **Merge Sort**, and **Bubble Sort** to simulate intelligent vehicle handling at road intersections.

---

## 📌 Features

### ✅ 1. Add Vehicles to Lanes  
Each vehicle stores:
- Registration Number  
- Arrival Time (HH MM SS)  
- Priority (1 = Ambulance, 2 = VIP, 3 = Normal)

Stored using **Linked Lists**.

---

### ✅ 2. Display All Lanes  
Shows all vehicles in each lane with:
- Reg No  
- Time  
- Priority  

---

### ✅ 3. Sorting Features  
#### 🔹 Merge Sort → Sort by Priority  
Order: Ambulance → VIP → Normal  
(Works lane-wise using linked list → array → linked list method)

#### 🔹 Bubble Sort → Sort by Arrival Time  
Earliest arrival first.

---

### ✅ 4. Searching Options  
#### 🔸 Linear Search (Linked Lists)  
Searches through each lane.

#### 🔸 Binary Search Tree Search  
Fast searching using a BST where every Reg No is inserted.

---

### ✅ 5. Open Traffic Signal  
Automatically selects **which vehicle passes next** based on:  
1. Priority  
2. Earliest arrival time (if priority is equal)  

Vehicle is removed from the lane after passing.

---

### ✅ 6. Green Light Duration Calculation  
Uses vehicle counts from each road to assign green-light time:  
- Allocated proportionally  
- Ensures **MIN_TIME = 10 sec**  
- Ensures **MAX_TIME = 120 sec**  
- Avoids unfair distribution

---

## 🧠 Data Structures Used

| Feature | Data Structure |
|--------|----------------|
| Lane vehicles | Linked List |
| Fast searching | Binary Search Tree |
| Priority sorting | Merge Sort |
| Arrival sorting | Bubble Sort |
| Lane storage | Array of Linked Lists |

---


