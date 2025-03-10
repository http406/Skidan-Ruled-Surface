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

\[
\begin{cases}
x = (u \sin(a) + b \cos(a)) \cos(v) \\
y = (u \sin(a) + b \cos(a)) \sin(v) \\
z = u \cos(a) - b \sin(a)
\end{cases}
\]

with:

\[
0 \leq u \leq 4\pi, \quad 0 \leq v \leq 2\pi
\]

\[
b = h | \cos(nv) |
\]

---

### **Breaking Down the Equation**
Each equation defines one coordinate **(x, y, z)** in terms of the parameters **\( u \) and \( v \)**.

#### **1. \( x \)-Coordinate:**
\[
x = (u \sin(a) + b \cos(a)) \cos(v)
\]
- The term **\( u \sin(a) \)** controls how the surface expands outward.
- The term **\( b \cos(a) \)** introduces oscillations that shape the **petals**.
- Multiplication by **\( \cos(v) \)** ensures symmetry around the z-axis.

#### **2. \( y \)-Coordinate:**
\[
y = (u \sin(a) + b \cos(a)) \sin(v)
\]
- Similar to **\( x \)**, but with **\( \sin(v) \)** instead of **\( \cos(v) \)**.
- This transformation ensures a **circular symmetry**, forming the overall flower-like shape.

#### **3. \( z \)-Coordinate:**
\[
z = u \cos(a) - b \sin(a)
\]
- The term **\( u \cos(a) \)** determines the vertical height of the surface.
- The term **\( - b \sin(a) \)** adds oscillatory variation to the height.

#### **4. The Oscillation Factor \( b = h | \cos(nv) | \)**
\[
b = h | \cos(nv) |
\]
- The factor **\( h \)** is a scaling constant that controls the size of the petals.
- The **absolute cosine function \( |\cos(nv)| \)** creates the petal-like oscillations.
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
- The **cosine function in \( b = h | \cos(nv) | \)** creates periodic **bulges** in the surface.
- The **multiplication with \( \sin(v) \) and \( \cos(v) \)** ensures rotational symmetry.
- As **\( v \)** varies from **\( 0 \) to \( 2\pi \)**, the oscillations repeat, forming **petals**.

---

### **Final Footnote**
The **Skidan Ruled Surface** is a great example of how simple **mathematical equations** can create **beautiful and intricate 3D shapes**. Its **ruled surface properties** make it visually appealing and ideal for applications in **mathematical art, computer graphics, and geometry studies**.
