# A9 – Pulleys

## Objective
Design a pulley system to transfer power between two parallel axes separated by a center distance of 4–6 inches. The system must meet the following requirements:

- Pulley Diameter: Both pulleys shall have a diameter of 3 inches.
- Rotational Speed: Select an operating speed between 1000–2000 rpm.
- Belt Tension (Static): Select a belt tension between 4–6 lbf under stationary conditions.
- Material: Pulleys may be made from aluminum, ABS, or steel, and may include a groove and shaft diameter of your choosing (within reasonable manufacturing limits).
- Safety Factor: The design must satisfy a minimum safety factor of 3.

## Belt Selection
For some of my design choices for this assignment, I chose: Center Distance = 5.0 in, Pulley Diameter = 3.0 in, Speed = 1500 rpm, Pulley material = Aluminum, and a Coefficient of Friction = 0.5. I listed my knowns and unknowns and symbolically solved for T1 and T2, normal stress, belt area and diameter, and the belt's circumference. I found T1 to be 8.279 lbf, T2 to be 1.721 lbf, Area to be 0.0527 in^2, Diameter to be 0.259 in, and the Circumference to be 21.05 in. As for choosing my belt, I used my circumference of 21 in and a diameter slightly bigger than my calculation, which ended up being 0.375 in. My belt of choice is the McMaster-Carr 3044K608, polyurethane round belt


<img width="2160" height="2693" alt="image" src="https://github.com/user-attachments/assets/0ea7fe21-730e-416e-bdf6-0b7d16916aaf" />
<img width="929" height="489" alt="image" src="https://github.com/user-attachments/assets/891d966a-13f7-47e0-9b37-99c446f2f685" />


## Shaft Diameter

For calculating the shaft diameter, I now know my torque values (T1 and T2). Using these values, I found the yield strength for 1060 hardened steel to be 98,200 psi. Using this information. I calculated the shaft's diameter to be 0.151 in, and the area to be 0.0179 in^2.

<img width="2160" height="2675" alt="image" src="https://github.com/user-attachments/assets/17d67ebf-aa36-4a25-b7c6-21c74ec18e55" />


## Journal Bearing

To calculate the PV of my journal bearing, I had to use the shaft's diameter I calculated and also pick the bearing's length. I picked a length of 0.35 in, and using my equation provided below, found the pressure to be 189 psi. I then calculated the velocity by converting rpm to ft/in, and got a value of 59.3 ft/min. Multiplying these two led to a PV value of 11,200 psi·ft/min. Using the sintered metal or non-metallic table, I chose the bearing's material to be porous iron because it passes all three tests and has the highest load capacity. 

<img width="2170" height="2160" alt="image" src="https://github.com/user-attachments/assets/dffb9b14-00d3-4927-8cd1-cdeb6fe1efd3" />
<img width="636" height="465" alt="image" src="https://github.com/user-attachments/assets/d642d53a-2a47-405c-bdb7-b48fa2f817e1" />



## Frame Design
For my frame design, I wasn't sure how I should design it, so I just decided to go with the provided example in Appendix A. Below is my frame design with listed geometry, which includes a thickness of 0.5 in, a hole diameter of 0.375 in, a width of 1.0 in, and a total length of 6.0 in. I was unsure of what else to do for this section, so I included some calculations regarding the holes, which include the area, stress, and safety factor, but these might be unnecessary. 


<img width="2743" height="2160" alt="image" src="https://github.com/user-attachments/assets/3ddf59c3-6294-4cb1-a25e-2ab1a524e26a" />



## Lessons Learned

I learned more about navigating the McMaster-Carr website during this assignment, as I looked at other parts such as compression springs, shock absorbers, timing belt pulleys, and more. I think it's a great website to practice assemblies in CAD because you can download many mechanical parts, rather than having to design them yourself. I was also reminded that solving algebraically is good practice, rather than just crunching the numbers. I did so at first when working on the belt selection, and got the wrong numbers and had to restart. 

I spent a little more than 4 hours on this assignment
