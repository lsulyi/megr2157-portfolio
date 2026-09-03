# A2 – Truss Stress Analysis

## Objective
- Design a lightweight planar truss using A500 steel or an alternative material.
- Create free body diagrams (FBDs) for joints and critical pins.
- Calculate the required cross-sectional area of truss elements with a safety factor.
- Determine pin sizes based on shear forces with a safety factor.
- Solve equations symbolically and numerically for both truss and pin design.
- Estimate the total weight of the truss and pins.
- Create a CAD model with accurate dimensions and connections.
- Compare CAD weight predictions with hand calculations.
- Document key engineering lessons learned from the process.
- Given parameters include: P = 20-30kn, a = 0.4m, b = 0.3m, A = Pin Support, B = Roller Support
## Analyze
**Designing Truss Geometry** 

(**2ai**) To start this assignment, I drew different truss examples that would work. Eventually, I came up with my final truss, which is a 7-member truss with 5 joints. At first, I drew a truss with 8 members and 6 joints, but realized using that truss would include a heavy workload, so I chose a simpler truss. I also drew a truss with 4 members and 4 joints, but it  wouldn't have enough support to resist a load and would likely collapse. Before committing to this truss as my final draft, I calculated whether my truss was statically determinate and rigid. If it wasn't, then solving for each force would've been impossible, but luckily my truss was statically determinate. 
<img width="3840" height="1962" alt="image" src="https://github.com/user-attachments/assets/55566dd6-3481-4d75-b42a-4c79a6c2fce4" />

**Free Body Diagrams**

(**2aii**) Once confirming my truss design, I drew the free body diagram for each individual joint. While drawing the free body diagrams, I assumed that every member was in tension, and knew that if the calculation resulted in a negative value, then that means the force is actually in compression. At first, I drew most of my diagrams incorrectly, as I forgot to draw the external forces at both joints A and B, and then I drew both P forces pointing upwards, forgetting that the force was pointing down in the diagram within the assignment's instructions.

<img width="2997" height="2160" alt="image" src="https://github.com/user-attachments/assets/659d9ff2-d242-42c4-82bd-568ec3428f83" />

**Symbolically Solving for all Forces**

(**2aiii**) In my opinion, this was the most tedious part of the entire assignment. I spent the most time on this portion, compared to every other section for this assignment. I don't know why, but working with just variables was much more complicated to me than it should've been. The purpose of calculating the external forces is to ensure the truss is in static equilibrium, and the purpose of calculating the internal forces is to see which members are in tension or compression, so a safe truss can be made. I found that solving for the three external forces to be simple, but getting every internal force was a grind. This is also the most important part of the assignment, as an error during this process can lead to an improperly designed truss, which could fail.

<img width="2179" height="2160" alt="image" src="https://github.com/user-attachments/assets/e35035e1-192c-4ba2-8c0f-1c5ccf8078a7" />
<img width="2370" height="1986" alt="image" src="https://github.com/user-attachments/assets/a3caf75d-5384-44ca-ae22-6af457d339c6" />

**Numerically solve for all  forces**

(**2aiv**) To solve for the force of each member, I used the method of joints. I started with joint B because there were only two known forces, and I had already calculated By because it was an external force. After solving for the two forces in joint B, I moved to joint A because it also had only two unknowns, since Ax equaled zero. I had to spend some extra time calculating every required angle, which was more complicated than I anticipated. After solving for every force within the truss, I listed every force, including joint CD, which turned out to be a zero-force member. 


<img width="3618" height="2081" alt="image" src="https://github.com/user-attachments/assets/904e546e-efcd-4d53-904c-2f160e3639fb" />
<img width="2160" height="2914" alt="image" src="https://github.com/user-attachments/assets/dad799a4-10f8-4915-8ba2-bb1721814336" />
<img width="2893" height="2160" alt="image" src="https://github.com/user-attachments/assets/7a9e10ad-f620-4812-ae9f-0553c1df76b4" />
<img width="2716" height="2160" alt="image" src="https://github.com/user-attachments/assets/4384cc07-d05b-4142-b989-6123972a0709" />

**Listing knowns and unknowns for calculation of cross-sectional area**

(**2bi**) Here, I have listed the knowns and unknowns for determining the cross-sectional area of the truss. Every variable was given, except for the largest internal force of the truss, which was member DE, with a force of 24.04kn in tension. The only unknowns are the cross-sectional area and the weight of the truss, but both values are calculated later on.

<img width="3588" height="931" alt="image" src="https://github.com/user-attachments/assets/fbaee26b-45cd-47fc-b555-fab59944b9ba" />

**Symbolically solving for minimum cross-sectional area**

(**2bii**) The derivation of the minimum cross-sectional area starts with the normal stress equation. The equation for that is σ = F / A. To ensure safety, we must also calculate an allowable stress, which is greater than the actual stress. The formula for allowable stress is σ_yield / safety factor. Setting the actual stress and allowable stress equal allows you to solve for the cross-sectional area. To do so, multiply the area to both sides, multiply the safety factor on both sides, and then divide by σ_yield. Doing so creates the equation Area = (Force * Safety Factor) /  σ_yield.

<img width="3334" height="983" alt="image" src="https://github.com/user-attachments/assets/a56bbd56-67e5-445c-ae57-1f4d50ba77c9" />


**Numerically solving for cross-sectional area, approximating the weight of the truss**

(**2biii & 2biv**) To find the area, I can plug in my values after deriving its equation. Before plugging in my numbers, I converted the 24.04 kN to kips, which equates to 5.405 kips. Once that was done, I could plug my numbers in, and doing so gave the minimum cross-sectional area of 0.411 in^2. Every member of the truss should be built to at least this area, or else the truss would collapse. To get the weight of the truss, I needed to calculate the total length of the truss by adding the length of each member. Adding each member's length equaled 3.321 m, which equals 130.76 in. To get the total volume, I multiplied the length by the cross-sectional area. To get the weight of the truss, I multiplied its volume, which came out to be 53.75 in^3, by the density of A500 Steel, which is .284 lb/in^3, giving an estimated weight of 15.3 lb.

<img width="2298" height="2160" alt="image" src="https://github.com/user-attachments/assets/1d70911e-eb5e-4816-938b-40e0e6b52cfd" />

**List all the knowns and unknowns for calculating the cross-sectional area of the connecting pins and the free-body diagram of the pin**

(**3ai and 3aii**) The knowns for this calculation include the safety factor, yield shear strength, pin density, number of pins, and the number of shear planes. The only unknown is the minimum cross-sectional area of the connecting pins. Joint A has the largest reaction force at 10 kN (Ay = By), and I have chosen this joint for calculating the pin's area. The joint has two known forces, Ay and Ax, and two unknown forces, AD and AE. 

<img width="3421" height="2160" alt="image" src="https://github.com/user-attachments/assets/d95f63bb-ff9d-4363-854c-60480a46176a" />

**Symbolically and numerically solve for the cross-sectional area**

(**3aiii and 3aiv**) To calculate the cross-sectional area of a pin, we must use the shear stress equation, which is τ = V / A_pin. V is the reaction force across a single shear plane, and A_pin is the area of the pin. Just like for the normal stress, an allowable shear stress must be calculated, which is τ_yield / SF. To solve for the area, you must equate the actual and allowable stress. For the algebra, it's the same as the normal stress, giving you A_pin = (V * SF) / τ_yield. This equation can be rewritten as A_pin = (F_reaction * SF) /  τ_yield because V is the reaction force. To calculate the pin's area, I converted the 10 kN to kips, which equates to around 2.248 kips. After that conversion, you can calculate the area. A_pin = (2.248 kips)(4) / 170 ksi =  0.0529 in^2. 

<img width="2484" height="2160" alt="image" src="https://github.com/user-attachments/assets/545b0926-884c-46c6-953f-2780eaa22ff4" />

**Determine the approximate combined weight of the pins**

(**3av**) To find the approximate combined weight of the pins, I started by calculating the volume of a single pin. To do so, I multiplied its cross-sectional area by its length, which is 0.0529 in^2 * 0.5 in, and got .0264 in^3. Multiplying the volume of one pin by 5 gives the total volume of every pin, which is .1322 in^3. Finally, to get the weight of the pins, I multiplied the total volume by the pin material's density. 0.1322 in^3 * 0.278 lb/in^3 = 0.037 lb.

<img width="3314" height="1224" alt="image" src="https://github.com/user-attachments/assets/2f1f98b9-df21-4472-9653-b6dc1a375d0f" />

**CAD Model of Truss**

(**4a and 4b**) Shown below is an image of my modeled truss, without the pins, in SolidWorks. The initial sketch was dimensioned using the geometry that was already given or found from the truss drawing, including the 1.2 m length of members AE and BE, the height from joints B and C to be 0.3 m, and the length of member CD being 0.4 m. Once the sketch was fully defined, I used the Structural Member feature in SolidWorks to complete my truss. To model the joints, I made another sketch on the truss, which was making a cylinder where each pin would be located, and giving it a .26 in diameter. Each joint was extruded through the truss, but not long enough to make them visible.

<img width="1428" height="469" alt="image" src="https://github.com/user-attachments/assets/9cafa772-ffdc-45dc-8823-6e0050ad8579" />
<img width="1358" height="692" alt="image" src="https://github.com/user-attachments/assets/df4fd121-e0b2-480f-a68c-09dd0514d08e" />
<img width="593" height="686" alt="image" src="https://github.com/user-attachments/assets/64122fae-76ae-4d85-8b45-d67b1a90ba95" />

[SophDes(A2) (2).zip](https://github.com/user-attachments/files/31768289/SophDes.A2.2.zip)


**Ensuring Truss Design and Implementation of Mass Properties**

(**4c and 4d**) I calculated the minimum cross-sectional area to be 0.411 in^2. Most of the pipe sizes had an area that was too small for my truss, except for the pipe size 33.7 mm * 4 mm, which equals 0.579 in^2. Using this area satisfied the safety factor, while still being fairly close to the minimum cross-sectional area. Every joint location and member length was dimensioned to match my drawing, maintaining the 7-member 5-joint structure. Following the same geometry that I drew meant the truss was statically determinate and rigid, which was already confirmed before modeling the truss in CAD. I ran the mass properties twice to see the difference with and without the pins by suppressing them in the feature tree. The mass properties on the left are without the pins, and it has a mass of 21.01 lb. Including the pins, the truss has a mass of 21.05 lb, which is seen with the mass properties on the right. Subtracting the two shows the pins' weight of 0.04 lb, which is very close to my calculation of 0.037 lb. Comparing the mass, my hand calculation is six pounds off, but that is because of the area of the pip size I used. If a different size or type was used, then the two masses would be closer.

<img width="485" height="741" alt="image" src="https://github.com/user-attachments/assets/5cf6c756-6bab-4e61-8371-40b20bec463e" />
<img width="492" height="748" alt="image" src="https://github.com/user-attachments/assets/2de0599b-3e9c-427c-9a51-bd8fd1bafc54" />


**Engineering Lesson Learned**

(**5**) The engineering lesson I learned from this assignment was how to use the mass properties function in SolidWorks, which reveals key information needed before manufacturing a part. I knew what the tool was, but I never knew what it did until now. The tool is very informative, showing the user the mass, weight, surface area, center of mass, and more. You wouldn't know how heavy a part was until it was manufactured and measured for mass properties, which makes engineers' lives much easier. Without the tool, a part could be too heavy and may lead to something breaking in a product. 


**2157 Students Only**

**Part 1**

Identify: Members AD, BE, and DE will likely fail due to yielding, while members BC, AE, and CE result in yielding-governed behavior rather than buckling-governed behavior. 

State: A500 Grade B steel is ductile carbon steel, as its strength level causes it to be ductile instead of being brittle. 


Support: The heaviest tension member is at only 20% of yield stress, and the three compression members' critical buckling stress is around 89-246 ksi, which is above the 46 ksi yield strength. 

Propose: For every member in tension, using A500 Grade C steel would create a larger safety factor margin without changing the geometry. 

**Part 2**

Identify: The pins are expected to fail by direct shear across the single shear plane they are lined up with. 

Support: Pin connections like this can fail in different ways, like the pin shearing off, crushing into a hole, or it tearing. The pins are also made of a  much stronger steel, so if one of them did fail, it would be much more random than if one of the members failed.

Propose: Converting to a double-shear connection would double the shear capacity for the same pin size.



<img width="626" height="398" alt="image" src="https://github.com/user-attachments/assets/16f53b46-8139-4a1c-9498-51e01016eb3b" />
<img width="737" height="803" alt="image" src="https://github.com/user-attachments/assets/940c3b17-a98b-4384-983d-2c9c7cec2fe3" />
<img width="715" height="594" alt="image" src="https://github.com/user-attachments/assets/dadc84c8-eb51-493e-bda3-7b01b93a2976" />
<img width="717" height="621" alt="image" src="https://github.com/user-attachments/assets/c15ef9ef-b454-44e5-8035-441c99dfc3a2" />


My guess is I took around 12 hours for this assignment, which might be a little excessive.




