# Skidan-Ruled-Surface

### **What is the Skidan Ruled Surface?**
The **Skidan Ruled Surface** is a mathematical surface that exhibits **beautiful geometric patterns**, often resembling a **flower-like structure**. It belongs to the family of **ruled surfaces**, meaning that every point on the surface lies on a straight line (a ruling). The **Skidan surface** is particularly interesting due to its oscillatory behavior, which creates elegant **petal-like structures**.

This surface is defined by a set of parametric equations that describe its 3D shape in terms of two parameters:  
- **\( u \) (primary parameter)**, which controls the spread of the surface  
- **\( v \) (secondary parameter)**, which determines the oscillations that form the petal-like structures  

It is used in **mathematical visualizations** and **generative art** because of its striking appearance.

---

### **Understanding the Equation**

The equation defining the Skidan Ruled Surface is:

![Image](https://github.com/user-attachments/assets/f5de2ac6-d617-45ef-a426-38e9d57f382c)

---

### **Breaking Down the Equation**
Each equation defines one coordinate **(x, y, z)** in terms of the parameters **\( u \) and \( v \)**.

#### **1. \( x \)-Coordinate:**

![Image](https://github.com/user-attachments/assets/b64e36b1-b0f0-45da-9a49-1673664047f7)


- The term **\( u sin(a) \)** controls how the surface expands outward.
- The term **\( b cos(a) \)** introduces oscillations that shape the **petals**.
- Multiplication by **\( cos(v) \)** ensures symmetry around the z-axis.

#### **2. \( y \)-Coordinate:**

![Image](https://github.com/user-attachments/assets/378ec74f-fa3b-4784-9650-5942b39d90f1)


- Similar to **\( x \)**, but with **\( sin(v) \)** instead of **\( cos(v) \)**.
- This transformation ensures a **circular symmetry**, forming the overall flower-like shape.

#### **3. \( z \)-Coordinate:**

![Image](https://github.com/user-attachments/assets/18664322-924c-45db-b0d4-bdebf7e7f710)


- The term **\( u cos(a) \)** determines the vertical height of the surface.
- The term **\( - b sin(a) \)** adds oscillatory variation to the height.

#### **4. The Oscillation Factor \( b = h | cos(nv) | \)**

![Image](https://github.com/user-attachments/assets/522699ab-afd3-4440-b99f-f8002e569850)


- The factor **\( h \)** is a scaling constant that controls the size of the petals.
- The **absolute cosine function \( |cos(nv)| \)** creates the petal-like oscillations.
- The **integer \( n \)** determines the number of petals in the shape.

---

### **How the Parameters Affect the Shape**
| Parameter | Effect |
|-----------|--------|
| **\( u \)** | Controls the overall spread of the surface |
| **\( v \)** | Determines the circular symmetry and shape |
| **\( a \)** | Rotates the surface, affecting the tilt |
| **\( h \)** | Scales the petal amplitude (size) |
| **\( n \)** | Determines the number of petals |

---

### **Why Does It Look Like a Flower? 🌸**
- The **cosine function in \( b = h | cos(nv) | \)** creates periodic **bulges** in the surface.
- The **multiplication with \( sin(v) \) and \( cos(v) \)** ensures rotational symmetry.
- As **\( v \)** varies from **\( 0 \) to \( 2π \)**, the oscillations repeat, forming **petals**.

---

### **Final Footnote**
The **Skidan Ruled Surface** is a great example of how simple **mathematical equations** can create **beautiful and intricate 3D shapes**. Its **ruled surface properties** make it visually appealing and ideal for applications in **mathematical art, computer graphics, and geometry studies**.
