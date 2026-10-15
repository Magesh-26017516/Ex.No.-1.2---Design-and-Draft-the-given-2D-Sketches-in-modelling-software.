# Ex.No.-1.2-Design and Draft the given 2D Sketches in modelling software.

## AIM
 To sketch the given drawing with dimensions using fusion 360 tool.
 
## REQUIREMENTS
 1. Autodesk fusion 360
 2. Windows 10
 3. 16 GB of RAM (integrated graphics recommend 1 GB or more)
 4. 2.5 Mbps or faster download; 500 Kbps or faster upload 
## Procedure:

Step 1: Set Up Reference Axes & Base Grid

1. Draw primary vertical and horizontal centerline axes intersecting at the origin (0, 0).

2. Offset the main vertical centerline to the left and right by 50𝑚𝑚 to establish parallel
centerlines at 𝑥 =− 50 and 𝑥 =+ 50.

3. Offset the main horizontal centerline up and down by 60𝑚𝑚 to establish horizontal lines at
𝑦 =+ 60 and 𝑦 =− 60.

4. Mark the 6 outer hole centers:
* **Top-left:** (− 50, 60)
* **Top-right:** (50, 60)

* **Middle-left:** (− 70, 0) (offset 20𝑚𝑚 further left from 𝑥 =− 50)

* **Middle-right:** (70, 0) (offset 20𝑚𝑚 further right from 𝑥 =+ 50)

* **Bottom-left:** (− 50, − 60)

* **Bottom-right:** (50, − 60)
<img width="622" height="519" alt="image" src="https://github.com/user-attachments/assets/ddb6a3a3-1b6b-4b8e-a1c3-6e1c7def6fa5" />

Step 2: Draw Central Geometry


1. From center origin (0, 0):
* Draw the innermost circle with radius **𝑅16**.* Draw concentric reference circles with radii **𝑅21**, **𝑅32**, and **𝑅40**.


2. Construct the central web pattern:


* Draw vertical parallel offset lines at 𝑥 =± 3 (total gap width 6𝑚𝑚) through the center.


* Construct 6 radial slots/spokes within the annular region between **𝑅21** and **𝑅32**.

<img width="621" height="514" alt="image" src="https://github.com/user-attachments/assets/1d869b82-dedf-4818-a750-2f21ff197db6" />

Step 3: Construct Outer Circular Features


1. **Hole Circles:** Draw circles of radius **𝑅15** at all 6 outer center points.2. **Outer Bosses:**

* At top-left (− 50, 60), top-right (50, 60), bottom-left (− 50, − 60), and bottom-right
(50, − 60), draw outer arcs of radius **𝑅21**.




* At middle-left (− 70, 0) and middle-right (70, 0), draw outer concentric circles of radius **
𝑅20**.




Step 4: Connect Tangent Lines & Fillets


1. **Outer Straight Tangents:** Draw straight line segments tangent to the outer arcs
connecting:

* Top-left arc (𝑅21) to middle-left arc (𝑅20).
* Bottom-left arc (𝑅21) to middle-left arc (𝑅20).
* Top-right arc (𝑅21) to middle-right arc (𝑅20).
* Bottom-right arc (𝑅21) to middle-right arc (𝑅20).


2. **Top & Bottom Inner Fillets:**
* Create internal tangent fillets of radius **𝑅20** connecting the top-left arc (𝑅21) and
top-right arc (𝑅21), resting smoothly against the central **𝑅40** boundary.




* Create identical **𝑅20** internal fillets at the bottom connecting the bottom-left arc (𝑅21)
and bottom-right arc (𝑅21).Step 5: Final Cleanup & Dimensioning

1. Trim all overlapping construction geometry to leave a clean outer boundary and inner
features.

2. Apply centerlines, dimensions, hatch/shading, and radius annotations matching the
technical drawing.
<img width="622" height="436" alt="image" src="https://github.com/user-attachments/assets/b4dc79e6-06e5-4ce7-93e9-bc46df139b22" />

Step 5: Final Cleanup & Dimensioning
1. Trim all overlapping construction geometry to leave a clean outer boundary and inner
features.



2. Apply centerlines, dimensions, hatch/shading, and radius annotations matching the
technical drawing.


 
 ## SKETCH
 ![image](https://user-images.githubusercontent.com/113594316/198233336-dd9f5c19-481b-486a-928a-99c32a732f89.png)

 ## OUTPUT
 
<img width="626" height="439" alt="image" src="https://github.com/user-attachments/assets/c45b3408-10dc-44b9-8a7e-45e93f434971" />
<img width="621" height="447" alt="image" src="https://github.com/user-attachments/assets/907d2500-789f-4816-9b87-712d529fa82e" />


 
 ## RESULT
 Thus the given sketch is drawn and drafted using fusion 360 tool.
