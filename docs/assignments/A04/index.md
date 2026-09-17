# A4 – Motor Mount

## Objective
- Design a motor mount for a Brushed 24V DC Gear Motor
- The mount is attached to a rigid wall and designed as an L-bracket with two different features
- Feature #1 is a horizontal plate that bolts to the motor
- Feature #2 is a vertical plate that bolts to the wall
- Both features are analyzed as cantilever beams

## Feature #1
To design Feature #1, I started by listing everything given in the assignment, which includes the 300 N load, the safety factor of 3, and the 0.30 mm max deflection. I chose to use ABS as my material because it's in SolidWorks, and I used its 2000 N/mm² elastic modulus and 30 N/mm² tensile strength. I drew Feature 1 as a cantilever beam, fixed where it connects with Feature 2, with a 300 N load and an 18 mm moment. I derived the stress and deflection equations before plugging in any numbers. Eventually, I chose the length to be 40 mm, and the width to be 32 mm. At first, I chose the width to be 25 mm, but changed this while designing the CAD part because there wasn't enough room around the bolt holes. Solving for h, I found the thickness to be 15.88 mm, which I rounded to 16 mm. 

<img width="3169" height="2160" alt="image" src="https://github.com/user-attachments/assets/c25bbfcd-fa76-48ed-b6a6-39bacdb80880" />
<img width="2160" height="3034" alt="image" src="https://github.com/user-attachments/assets/65a614ee-3a62-459a-aa67-f5e2d85a3c17" />
<img width="2334" height="2160" alt="image" src="https://github.com/user-attachments/assets/8b7d6f66-68da-4584-99ab-bfe5d1da1f4e" />


## Feature #2
Feature 2 is different than Feature #1, as it's the vertical plane that bolts to a wall. Looking at Appendix B, it experiences the same moment that Feature #1 generated. For my calculations, I used some of the same numbers, like the 12,000 N*m moment, safety factor of n = 3, and the material properties of ABS. After solving both symbolically and numerically, the stress and max deflection were very similar, so I rounded both to a thickness of 16 mm, the  same as Feature #1. 

<img width="2160" height="2477" alt="image" src="https://github.com/user-attachments/assets/da760a9e-63a8-4ee3-9f3b-76f7a59f5d19" />
<img width="2160" height="2476" alt="image" src="https://github.com/user-attachments/assets/20ace94d-160c-41bd-b288-d4622a0de3a2" />


## Sketch of Mount
Here is an isometric sketch of the motor mount, which includes the dimensions for Features #1 and #2, the shaft diameter, bolt clearance diameters, the pocket diameter, and the material of the mount.

<img width="2308" height="2160" alt="image" src="https://github.com/user-attachments/assets/ae6195ef-49fb-4c89-a59f-2a20171eb9bb" />

## CAD Model 
To model the mount in SolidWorks, I started by making an L-shaped sketch that is 56 mm long (40 + 16 to include the thickness of Feature #2), 46 mm tall, and extruded with a depth of 32 mm. After that, I cut a ⌀18 mm pocket on feature one to hold the motor. Then, I made a ⌀7 mm hole that cuts entirely through Feature #1, creating clearance for the shaft. On the same sketch, I made the 4 * Ø3.4 mm clearance holes, cutting through all. Moving on to Feature #2, I made the same 4 * Ø3.4 mm clearance holes for the vertical plane. Finally, I included a fillet where the two features connect, just to make it look better. 

<img width="1138" height="815" alt="image" src="https://github.com/user-attachments/assets/56f041c0-184e-4aa5-a8f3-2e70c9dd2d17" />
<img width="882" height="720" alt="image" src="https://github.com/user-attachments/assets/47601bff-ad8a-4f19-9f80-e158f1aa1976" />
<img width="742" height="643" alt="image" src="https://github.com/user-attachments/assets/ce38787c-2f6b-4650-8889-e287fb298581" />
<img width="746" height="724" alt="image" src="https://github.com/user-attachments/assets/27b354d6-4f7a-4ba1-ace1-b1f272f89a1e" />
<img width="947" height="800" alt="image" src="https://github.com/user-attachments/assets/c827e490-bec0-4b90-9597-8ece9aaaf200" />
[SophDes(A4).zip](https://github.com/user-attachments/files/32318200/SophDes.A4.zip)



## Drawing of CAD Model
Listed here is a photo of the drawing I made of my motor bracket
<img width="821" height="634" alt="image" src="https://github.com/user-attachments/assets/62ecc516-c591-490b-8465-3439d02ceae1" />


## Lessons Learned 
The biggest lesson I learned is to be consistent with your units throughout each assingment. When I first started making my CAD part, I was still in IPS on SolidWorks. After getting halfway through the model, I realized I was using the wrong units. I did the same thing when making my drawing. When my dimensions started to show on the drawing, I was confused because they didn't match the model, but thats because I had to switch to MMGS. I also learned about how to use the drawings tool in SolidWorks. I hadn't used it much, but was familar with the concept from using Creo Parametric to design the air engine in MEGR 2152. I spent 7 hours on this assingment.
