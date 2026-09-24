# A5 – Bracket Design

## Objective

- Conduct stress analysis to determine appropriate dimensions for structural features
- Generate free body diagrams (FBDs) to visualize forces and constraints for each feature
- Identify and document known and unknown variables, assumptions, and algebraic models for stress calculations
- Perform stiffness analysis to establish minimum required dimensions based on deflection constraints
- Compare stress and stiffness analyses to ensure structural integrity and compliance with given constraints
- Create detailed multiview sketches illustrating dimensions derived from both stress and stiffness analyses
- Reflect on and document key engineering lessons learned throughout the process

## Calculating Dimensions for Stress Analysis 
Design Parameters
- Applied load: F = 600 lbf (per strap leg), P = 2F = 1,200 lbf
- Safety factor: SF = 4
- Material: Aluminum 6061-T6, Sy = 40,000 psi, E = 10,000 ksi (10,000,000 psi)
- Allowable stress: σ_allow = Sy / SF = 10,000 psi
- Allowable deflection: δ_allow = 0.005 in 
- Strap contact length: L = 1 in

  
**Feature A: Cantilever Beam**

For Feature A, I listed my knowns: F = 600 lbf,  W = 2F, SF = 4, and material (6061-T6). The unknowns for this feature are σ_allow, section modulus (z), and radius (r). Solving for each, I got σ_allow = 10,000 psi, Z = 0.06in^3, and r = 0.424 in / w = 0.85in. 

<img width="2160" height="3026" alt="image" src="https://github.com/user-attachments/assets/7e96e180-4960-4522-acf0-9ef7fee59e64" />

**Feature B: Axial Loaded Bar**

For Feature B, I listed my knowns, including: P = 2F = 1,200 lbf, width =  0.848 in,  σ_allow = 10,000 psi. The unknowns for this feature are the thickness, vertical length, and cross-sectional area. Solving for thickness using the stress formula, I found that the thickness of Feature B is 0.142 in. 

<img width="2623" height="2160" alt="image" src="https://github.com/user-attachments/assets/5efdf7f3-066d-45fc-9bab-926275b3424f" />

**Feature C: Simply Supported Beam**

For Feature C, I listed my knowns, including: P = 2F = 1,200 lbf, L = 2.5 in (2(0.9942) + 0.498 = 2.5), d = 1 in (Design Choice), and σ_allow = 10,000 psi. The unknown for this feature is the height. After calculating the maximum moment at the center and the section modulus, I found the height to equal 0.67 in.

<img width="3364" height="1719" alt="image" src="https://github.com/user-attachments/assets/0bd92fe9-fee2-4a52-957c-4a782393d473" />
<img width="2977" height="2160" alt="image" src="https://github.com/user-attachments/assets/9f78e199-9889-4728-8d40-46419551fa60" />

**Feature D: Axial Loaded Bar**

For Feature D, I listed my knowns, including F = 600 lbf, SF = 4, depth = 1.0 in, σ_allow = 10,000 psi. The unknown for this feature is the thickness. Using the stress equation and changing the area to depth * thickness, I calculated that the thickness of Feature D is 0.06 in. 

<img width="3490" height="2076" alt="image" src="https://github.com/user-attachments/assets/2a49cb3a-b5e4-4dbf-a36b-d0ee76441775" />

**Feature E: Cantilever Beam**

For Feature E, I listed my knowns, including F = 600 lbf, L = 0.9992 (from b in Figure #1), d = 1.0 in, and σ_allow = 10,000 psi. The unknowns for this feature are the moment of inertia and height. To find the height, I used the formula for bending stress and calculated the height to be 0.42 in. 

<img width="2160" height="2824" alt="image" src="https://github.com/user-attachments/assets/473e40b4-27b1-4503-9aa0-337d4d952c6b" />


##  Calculating Dimensions from Stiffness Analysis

  
**Feature A: Cantilever Beam**

For Feature A, I listed my knowns: P = 2F = 1200 lbf, L = 1.0 in, E = 10,000 ksi, and δ_allow = 0.005 in. The unknowns for this feature are the moment of inertia and the radius. To find the radius, I used the maximum deflection of a cantilever beam under a uniformly distributed load. I set that equal to I and found the moment of inertia to be 0.003 in^4. Setting the moment of inertia equal to the radius, I calculated the radius to be 0.249 in.

<img width="2160" height="2908" alt="image" src="https://github.com/user-attachments/assets/a765a286-5338-4c8b-829c-93e039de9a27" />

**Feature B: Axial Loaded Bar**

For Feature B, I listed my knowns: P = 2F = 1200 lbf, L = 0.5 in (Design Choice), E = 10,000 ksi, δ_allow = 0.005 in, and w = 0.848. The unknowns for this feature are the cross-sectional area and thickness. To calculate the thickness, I used the deformation equation for axially loaded bars. Setting that equation equal to the area, I got 0.012 in^2, and divided that by the width to get a thickness of 0.0142 in. 

<img width="2160" height="2729" alt="image" src="https://github.com/user-attachments/assets/f799bd37-b283-41f0-877a-431671ef8dcd" />

**Feature C: Simply Supported Beam**

For Feature C, I listed my knowns: P = 2F = 1200 lbf, E = 10,000 ksi, δ_allow = 0.005 in, and L = 2.5 in. The unknown for this feature is the height. Using the max deflection of a simply supported beam, I found the moment of inertia to be 0.00781 in^4, and then found the height to be 0.454 in. 

<img width="2160" height="2637" alt="image" src="https://github.com/user-attachments/assets/7aa375ee-380d-4a08-ad73-3f9aace3dc0a" />

**Feature D: Axial Loaded Bar**

For Feature D, I listed my knowns: F = 600 lbf, E = 10,000 ksi, δ_allow = 0.005 in, d = 1.0 in, and L = 1.0 in. The unknowns for this feature are the area and thickness. Using the deformation equation for axially loaded bars, I found the area to be 0.012 in^2 and divided that by the depth to get a thickness of 0.012 in. 

<img width="2160" height="2250" alt="image" src="https://github.com/user-attachments/assets/46ae0d4e-fcb4-4f17-a05d-565300bc5dd3" />

**Feature E: Cantilever Beam**

For Feature E, I listed my knowns: F = 600 lbf, L = 0.9992 in, d = 1.0 in, E = 10,000 ksi, and  δ_allow = 0.005. The unknowns for this feature are the moment of inertia and height. Using the maximum deflection of a cantilever beam under a uniformly distributed load equation, I found the moment of inertia to be 0.00146 in^4, and the height to be 0.260 in. 

<img width="2160" height="2478" alt="image" src="https://github.com/user-attachments/assets/716aae28-c453-4992-8df3-b7debaa2115f" />


## Multiview Sketches

**Stress Multiview Sketch** 

Below is a very rough sketch of the stress bracket. I will note that I'm sorry for my sloppy drawing; I suck at drawing things in 3D. The lengths for each feature are: Feature A: 0.424 in; Feature B: 0.142 in; Feature C: 0.670 in; Feature D: 0.06 in; and Feature E: 0.424 in. 

<img width="2820" height="2160" alt="image" src="https://github.com/user-attachments/assets/108afd77-4574-47a4-acee-1800c780d9d1" />

**Stiffness Multiview Sketch** 

Below is a very rough sketch of the stiffness bracket. The lengths for each feature are: Feature A: 0.249 in; Feature B: 0.0142 in; Feature C: 0.454 in; Feature D: 0.0012 in; and Feature E: 0.260 in. 

<img width="2696" height="2160" alt="image" src="https://github.com/user-attachments/assets/eb6989a9-46bb-4f8a-a775-7bf7030a9c9d" />


## Lessons Learned

**Governing failure mode:** 

Stress governed every feature of my design. The difference between the two analyses varies, as Feature B had a measurement of 0.142 in for stress, and 0.0142 in for stiffness. That is a 10x difference between the two. Feature C had two similar measurements because of the 0.045 deflection limit. Stress had a measurement of 0.670 in, and stiffness had a measurement of 0.454 in. The difference between these two is only 1.5x. 

**Error propagation:** 

I had a hard time knowing whether to use F or 2F in some calculations, like in Feature C. I had used F = 600 lbf, which was a mistake, and later used 2F. I made the opposite mistake in Feature D, but caught it before my initial calculation. 

**Assumption sensitivity:** 

One big assumption for this assignment was the material, and the yield strength to go with it. I chose 6061-T6, which equates to a yield strength of 40,000 psi. Choosing the material was dictated by allowable stress, and every measurement would've been different if I had chosen one of the other required material choices.


## Link Design 

The link plate is designed so it can withstand the same 1,200 lbf the bracket does. I chose a thickness of 0.25 in, which was used to calculate the width: 1.48 in. Checking for the deflection limit resulted in a length of 5.0 in. Feature A's hole uses an RC5 running fit, which is bored/reamed and turned. The shaft hole gets an FN1 light drive fit, which is bored/reamed and assembled with a light press fit. 

<img width="2160" height="2317" alt="image" src="https://github.com/user-attachments/assets/e7ad2b32-2a46-4f8f-813b-1d06e1bc70fa" />
<img width="3803" height="2160" alt="image" src="https://github.com/user-attachments/assets/9bb62ee2-dea9-4dd2-b177-967810b32635" />

I spent 8 hours on this assignment. 


