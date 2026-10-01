# A6 – Bracket Drawing

## Objective
- For this assignment, we are to turn our work from A5 into a CAD model and access it from there 

## Analyze

**Part 1: Parametric Design**

I included every feature I found in A5 in my model using the Equations Manager in SolidWorks 

- A_radius: 0.424 in
- B_thickness: 0.142 in
- C_height: 0.670 in
- D_thickness: 0.25 in
- E_height: 0.424 in

There were some other dimensions for this model that I chose myself or changed while modeling the part

- A_length: 1.0 in
- B_length: 0.5 in
- C_depth: 1.0in
- E_length: 0.9992 in

T-Beam dimensions
- A_dim: 0.498 in, RC7 fit
- B_dim: 0.992 in, RC3 fit
- C_dim: 1.499 in, RC4 fit

<img width="651" height="364" alt="image" src="https://github.com/user-attachments/assets/9d9d6068-cfee-44f5-a8d2-a578b89d45a8" />

**Feature A**

Below is the sketch for Feature A, dimensioned at 2*A_radius for a 0.85 in. diameter. It is extruded at a length of 1 in, which is also included in the Equations Manager.

<img width="864" height="836" alt="image" src="https://github.com/user-attachments/assets/52baf513-e3e6-43d9-8b1b-a720602a4117" />

**Feature B**

Below is the sketch for Feature B. It has a width of 2*A_radius for 0.85 in, and a length of B_length, 0.5 in. This feature was extruded with B_thickness, 0.142 in. This feature was attached to the back of the bracket, so I modeled Feature A on the back as well, so the design is more visually appealing. 

<img width="767" height="674" alt="image" src="https://github.com/user-attachments/assets/da6b9552-d7dd-48a2-8f9c-949f10eb0cef" />

**Feature C**

Below is the sketch for Feature C. This feature was sketched as a rectangle, with a C_height of 0.670 in and a length of 3.0 in. The feature was extruded with C_depth = 1.0 in. The equation for the length of C is A_dim + 2 x B_dim + 2 x D_thickness

<img width="1251" height="633" alt="image" src="https://github.com/user-attachments/assets/f20eb8ea-b4fb-44a7-b4c2-26c3077622c1" />


**Feature D**

Below is the sketch for Feature D. This feature is sketched on top of Feature C. It has a height of C_dim = 1.499 in, and a thickness of D_thickness = 0.25 in. The thickness was changed from what I had calculated, as that was only 0.06 in, and I found that to be too small. This feature was extruded using C_depth = 1.0 in. 

<img width="1147" height="710" alt="image" src="https://github.com/user-attachments/assets/1bb80ced-3871-4831-9b1c-d7e2fd80c424" />

**Feature E**

Below is the sketch for Feature E. This feature was sketched as two rectangles on top of Feature D. The feature has a height of E_height = 0.424 in, and a length of B_dim = 0.9992 in. The length of the gap between the two rectangles is A_dim = 0.498 in, and the feature was extruded by C_depth = 1.0 in.


<img width="943" height="815" alt="image" src="https://github.com/user-attachments/assets/aebbc49c-87c1-4ba1-af41-b4b92e18a485" />

Photo of Bracket:

<img width="918" height="798" alt="image" src="https://github.com/user-attachments/assets/997a8b01-2eaa-4d68-bcc5-b3626d5fec8c" />


**Part 2: Engineering Drawing**

Below is a photo of my engineering drawing of the bracket. I added an extra back view because I had issues modeling Feature B to the front, as it cannot be seen in the isometric view. It is a little messy, but it gets the job done. It also includes the T-beam dimensions and their tolerances. I will note that the A_dim dimensions have an error and cannot display the tolerance, but it has a tolerance of +0.0016 and -.0000. 

<img width="982" height="757" alt="image" src="https://github.com/user-attachments/assets/db37ec0d-905b-4052-8965-18731ff28899" />

Link to part and drawing:
[SophDes(A6).zip](https://github.com/user-attachments/files/32883422/SophDes.A6.zip)


## Reflections

**Equation leading to dimension**

For Feature D's thickness, I originally calculated it to be 0.06 in. I set this as my variable for D_Thickness in SolidWorks, and then modeled it using this dimension. After using the dimensions, I recognized the thickness was very small and would be very hard to manufacture. I changed it to 0.25 in. I used 0.06 in for the width, and it automatically updated to 0.25 in. Anything tied to the variable simultaneously updated. 

**Tolerance Comparison**

The tightest tolerance in this model uses the RC4 fit. This tolerance is a mating interface against the T-beam because we were instructed to have accuracy for functionality. The loosest tolerance is the two-place decimal, as they are non-mating for dimensions like C_depth and B_length. If a tighter tolerance was used for each dimension, unimportant features would need precise machining, which would be unnecessary, 


## Linkage 
Below is a sketch of my linkage. It has a width of 1.48 in, a length of 4.0 in, an RC 5 Fit hole with a diameter of 0.85 in, and an FN1 Fit hole with a diameter of 1.0 in. It also has a thickness of 0.25 in, which was used to extrude the linkage.

<img width="1043" height="735" alt="image" src="https://github.com/user-attachments/assets/e4190eea-1dc7-46bb-a493-283579a54b4a" />
<img width="676" height="268" alt="image" src="https://github.com/user-attachments/assets/7bb3c1cf-e9a1-4f13-90ad-b7065ff95ca5" />

Below is an Isometric view of my model:
<img width="941" height="711" alt="image" src="https://github.com/user-attachments/assets/acdd4e47-8b94-46fb-8b41-028bd75d5f7d" />

Below is an Engineering Drawing of the Linkage:
<img width="879" height="678" alt="image" src="https://github.com/user-attachments/assets/7b980708-d50e-45db-933a-9104ec9b8cd1" />

Link to part and drawing:
[SophDes(A6_Linkage).zip](https://github.com/user-attachments/files/32885654/SophDes.A6_Linkage.zip)

I spent 6 hours on this assignment. 


