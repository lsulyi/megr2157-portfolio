# A3 – [Parametric and FEA]

## Objective
- Use axial deflection modeling to design its dimensions
- Use parametric design to determine a bars length
- Introduce you to FEA (Finite Element Analysis)
- Introduce you to linking dimensions to appropriate parameters in CAD.
- Compare and contrast the different analysis

## Analyze
**Parametric Design**

**1a and 1b: Choosing Dimensions and Calculating Length of Bar**

Before doing any CAD work, I had to start by listing every given value or constraint to understand the guidelines for my bar. I wrote down the range for our load of choice, the maximum axial deflection, which was given, and the range for Young's modulus. After writing the givens, I calculated the area, stress, and safety factor for many different diameters. For example, I knew that if I made my bar's diameter 2.5 in, the bar would be oversized, as the stress was quite small,  and it would be way too long. If I used a very small diameter like 0.15 in, the safety would be too small at 1.77. I eventually went with 0.25 in diameter, which gave a safety factor of 4.91. I also found that A = 0.0491 in^2, and σ = 8,146.64 psi. To calculate the length of my bar, I used the direct tension elongation equation from Machinery's Handbook, which is δ = FL / AE. After rearranging this equation to solve for L, I got L = δAE / F. δ is the maximum axial deflection, 0.009 in; A is the area of the bar, 0.0491 in^2; E is Young's modulus, which I chose to be 10×10⁶ psi; and F is the force, which I chose to be 400 lb. After plugging each number into its respective variable, I found the length of my bar to be 11.05 in.

<img width="2610" height="2160" alt="image" src="https://github.com/user-attachments/assets/f758389c-e682-432d-9021-f79351e675dc" />

<img width="3031" height="2160" alt="image" src="https://github.com/user-attachments/assets/68983697-6596-4921-b6b5-76795be11770" />

**1c Parametric Model of Bar**

Before making any sketches in SolidWorks, I started by plugging my global variables into the Equations feature, so the bar is made through my calculations rather than manually inputting the diameter and length. Once all of my variables were set, I sketched a circle on the front plane, with its diameter set to the variable "d", which was assigned as 0.25 in. Next, I made an extrude on the circle, with its length set to the variable "L", which SolidWorks calculated as 11.04 in. SolidWorks rounded my length down, but I rounded mine up. I'm not sure why it rounded down because my exact value for length was 11.0475 in, but that's no big deal. I also had to input the diameter and length multiple times because SolidWorks did not recognize my variables at first. Once the dimensions of my bar were synced to my variables, I set the bar's material to Aluminum 6061-T6 and checked its properties. The material's properties closely matched my calculations, as the Young's Modulus was 10.01×10⁶ psi, and the yield strength was 39,885 psi. 

<img width="800" height="331" alt="image" src="https://github.com/user-attachments/assets/d19df4e4-700d-440f-893f-1b2927ade44a" />
<img width="708" height="442" alt="image" src="https://github.com/user-attachments/assets/15b0c28f-414f-4cf6-95bd-6c5288b3cef9" />
<img width="1581" height="511" alt="image" src="https://github.com/user-attachments/assets/f4128e78-c81f-436f-8cf9-e2f13aa35c5f" />
<img width="814" height="602" alt="image" src="https://github.com/user-attachments/assets/4c887f7e-39d6-4e58-bdb3-bdf4b0de4564" />

**Finite Element Analysis**

**2a and 2b: Deflection and Von Mises Stress Map**

After designing my bar, I had to run an FEA on the bar to see the Deflection and Von Mises Stress Map. The deflection map showed a maximum displacement of 0.2284 mm, which converts to 0.00899 in. The displacement that the map gives is nearly identical to our given displacement of 0.009 in. The stress map shows a nearly uniform stress distribution along the bar. There is a small stress increase on the fixed end of the bar, but I am unsure what the stress value is for that part.

<img width="1521" height="642" alt="image" src="https://github.com/user-attachments/assets/5e7f190d-dd59-4961-b025-9029be12d6d5" />
<img width="1536" height="629" alt="image" src="https://github.com/user-attachments/assets/bf8bd6e2-a11d-4623-9628-5baeea5808dd" />

**2c: Safety Factor Check** 

Comparing the FEA max stress to the given 8,626 psi is much less than 40,000 psi, so that checks out. I also redid the safety factor using the FEA max stress and got SF = 40,00 psi / 8,624 psi, which equals 4.64

<img width="3840" height="1169" alt="image" src="https://github.com/user-attachments/assets/eb8ff326-3fed-4d33-a92f-c276c2232323" />


**Design Reflection**

**3a Hand-Calculations vs FEA**



<img width="3343" height="2160" alt="image" src="https://github.com/user-attachments/assets/e885d32e-454f-4285-a7fe-da7b0f5f1633" />








