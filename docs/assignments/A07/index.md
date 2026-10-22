# A7 – FEA on Bracket

## Objectives
- Use Finite Element Analysis (FEA) to improve the bracket design from previous assignments.
- Ensure high stiffness, strength, and lightweight optimization through iterative design.
- Conduct multiple FEA simulations, refining geometry based on results.
- Perform static stress analysis, including constraints, loading, and meshing selection.
- Interpret data by identifying max stress, displacement, and safety factors.
- Optimize the design by modifying geometry to enhance performance.
- Document the entire process with images, calculations, and insights.
- Reflect on key engineering lessons learned and time spent.

## Initial Design 
For this portfolio assignment, I will continue to use the same bracket model I made for A6. The material used is 6061-T6 Aluminum. 

<img width="1016" height="776" alt="image" src="https://github.com/user-attachments/assets/7e70d024-155e-456d-b71a-a81793eb8a0f" />
<img width="677" height="353" alt="image" src="https://github.com/user-attachments/assets/4c0fb2cb-df31-459a-9a3a-222e9b61c2e0" />

Below, you can see the location of the fixed geometry and the load. The fixed geometry is under Feature E, which is shown with the green arrows. The 1,200 lbf load is applied to Feature A and is shown with the purple arrows.
<img width="1351" height="521" alt="image" src="https://github.com/user-attachments/assets/2ba41135-a508-402b-9944-97b8a5005b83" />
<img width="1472" height="812" alt="image" src="https://github.com/user-attachments/assets/aec86ab1-66be-42da-ac71-858d18bc7cce" />


## Design #1 
Shown below is the first study I made for this assignment. I ran three different studies, and each time, I decreased the max element size and recorded the change in stress. The first stress and displacement study is from the first attempt, and the second stress study is from the third attempt

<img width="1535" height="784" alt="image" src="https://github.com/user-attachments/assets/629f0ae0-a149-4c3d-aa14-01a1e93b15f2" />
<img width="1540" height="784" alt="image" src="https://github.com/user-attachments/assets/0b480d97-1e7c-48dc-a317-ee0c1cfe0445" />
<img width="487" height="743" alt="image" src="https://github.com/user-attachments/assets/091af7c0-7d44-4f7f-8911-5ec12095b976" />
<img width="429" height="427" alt="image" src="https://github.com/user-attachments/assets/6741f6d3-dbac-4692-b2b0-98c324ecf48b" />
<img width="1525" height="784" alt="image" src="https://github.com/user-attachments/assets/9c3b4cd9-95bf-4273-8aee-c38d442e92ae" />
<img width="562" height="168" alt="image" src="https://github.com/user-attachments/assets/0646dc17-d70a-454d-9b3a-e8e5eda345fb" />
<img width="382" height="285" alt="image" src="https://github.com/user-attachments/assets/a15bf05a-8fa0-4ac7-9a19-140b5183a647" />



## Design #2

Shown below is the second study I made for this assignment. My design change for this one was to add a .06in filet, located at the edge where features A and B connect. For this study, I used 0.162 for the mesh. After looking at the study, I realized I had to use a local mesh where the fillet is located. I put a .015 in local mesh on that face, which was small enough for the fillet.

<img width="1456" height="812" alt="image" src="https://github.com/user-attachments/assets/19677124-ccd5-474c-bbba-55a2afdd3739" />
<img width="1526" height="784" alt="image" src="https://github.com/user-attachments/assets/97f9ed3a-c779-493b-a0eb-627c295d371d" />
<img width="405" height="429" alt="image" src="https://github.com/user-attachments/assets/9a00a85c-41c0-4fa5-9149-63f0a01a4b6f" />
<img width="486" height="745" alt="image" src="https://github.com/user-attachments/assets/e691966a-96a9-4c1b-bf52-44655dd9397f" />
<img width="382" height="373" alt="image" src="https://github.com/user-attachments/assets/0dfd8a90-7735-4158-aa79-bee5e3eb39a2" />


## Design #3

Shown below is the third study I made for this assignment. My design change for this one was to change the thickness of Feature D from 0.25 in to 0.15 in. I also reused the different mesh settings from design 2 because the fillet was not changed. 

<img width="1539" height="784" alt="image" src="https://github.com/user-attachments/assets/124ac6f7-fd97-440e-b565-214ce7810e13" />
<img width="1526" height="784" alt="image" src="https://github.com/user-attachments/assets/883fba35-7630-4ab0-bfae-e85b77d656e1" />
<img width="487" height="743" alt="image" src="https://github.com/user-attachments/assets/0e79679b-cfd4-4ca0-997a-e3c1b7ee078a" />
<img width="389" height="356" alt="image" src="https://github.com/user-attachments/assets/197f481d-4641-4ca8-be75-db54e297dabd" />
<img width="383" height="283" alt="image" src="https://github.com/user-attachments/assets/58e1c4a0-1d05-4378-aff5-a85fea30bc26" />

Below is a table summarizing the studies for all three designs
<img width="563" height="226" alt="image" src="https://github.com/user-attachments/assets/6073ca56-e978-4b0a-b392-20a3957808da" />


## Linkage Initial Design

This is the original design for my linkage, which was used for Study #1.

<img width="719" height="798" alt="image" src="https://github.com/user-attachments/assets/bd03c19d-b81d-43f4-952e-7fb09fd6805a" />
<img width="1510" height="764" alt="image" src="https://github.com/user-attachments/assets/5f3343e3-572c-46ee-8a44-e4289faf3ef0" />
<img width="676" height="262" alt="image" src="https://github.com/user-attachments/assets/7e15d1c5-8f62-4966-be22-d5de238ecd1f" />



## Linkage Design #1

This was the first linkage study run. For this study, the design was left unchanged from A6.

<img width="1544" height="784" alt="image" src="https://github.com/user-attachments/assets/97628616-76e1-4d24-b989-71e4f263a751" />
<img width="1549" height="784" alt="image" src="https://github.com/user-attachments/assets/d4afb69c-6ad1-4030-b7e7-0337ee50c385" />
<img width="487" height="744" alt="image" src="https://github.com/user-attachments/assets/343d8b03-4669-4d69-b25d-e38f0e522e8b" />
<img width="443" height="407" alt="image" src="https://github.com/user-attachments/assets/c4712caf-1191-43fa-bfa2-25012b8ee85e" />
<img width="562" height="221" alt="image" src="https://github.com/user-attachments/assets/0c951104-5d11-43ee-bd91-d84884d84996" />

## Linkage Design #2

This was the second linkage study run. For this study, the design change was to add a .1 in fillet to the 1.0 in bottom hole. 

<img width="1017" height="803" alt="image" src="https://github.com/user-attachments/assets/ba646e86-f079-43ca-888b-ce34d5996b4b" />
<img width="1522" height="784" alt="image" src="https://github.com/user-attachments/assets/287cd205-c3d3-4147-babb-a604cd6e8caa" />
<img width="1540" height="784" alt="image" src="https://github.com/user-attachments/assets/53255f02-b548-4aed-a74b-b96e36e0b586" />
<img width="486" height="745" alt="image" src="https://github.com/user-attachments/assets/99369433-d3c6-4cc8-9426-f3798aad57b4" />
<img width="565" height="224" alt="image" src="https://github.com/user-attachments/assets/0ff7f24e-d469-4bdc-9e27-12e43ea5641c" />



## Linkage Design #3

This was the third linkage study run. For this study, I kept the design change from study #2, and then lowered the thickness from 0.25 in to 0.2 in

<img width="676" height="251" alt="image" src="https://github.com/user-attachments/assets/6cf12d0f-f396-4877-a503-6ec150824c4f" />
<img width="1119" height="844" alt="image" src="https://github.com/user-attachments/assets/1dd8fef1-ae50-4d21-8178-c52a5a0e04af" />
<img width="1136" height="791" alt="image" src="https://github.com/user-attachments/assets/9b6cc22e-c3f6-4601-8a5b-eb8dbcc19d67" />
<img width="486" height="745" alt="image" src="https://github.com/user-attachments/assets/0f18fce7-894a-463d-8522-692c3dc1a031" />
<img width="377" height="277" alt="image" src="https://github.com/user-attachments/assets/a33d7be5-0493-4955-8cb2-0c31b83bcbc3" />



Below is a table summarizing the studies for all three designs
<img width="563" height="240" alt="image" src="https://github.com/user-attachments/assets/caa5711a-a53f-4256-a622-9303f2fab3b5" />


# Reflection
From this assignment, I learned even more about the simulation feature in SolidWorks. I made many mistakes while completing this assignment, and I found it quite tedious. My first issue was setting up the study because I was unsure where to place the fixed geometry and external load. I had a second issue with the external load, which was the direction. At first, I had it in the normal direction and placed it on feature A. I later found that using a normal direction lowered the stress by roughly a factor of two. To fix this, I used the selected direction feature for external loads and fixed it using an edge on feature D. I also learned about meshes in SolidWorks. Beforehand, I had no idea what they were, but after this assignment, I understand them better. One thing I noticed while changing the mesh in Design #1 was the increase in stress as I lowered the mesh value. During my three studies, the stress increased from  615 MPa to 748 MPa to 1,114 MPa.




CAD Files
[SophDes.A6.zip](https://github.com/user-attachments/files/33796936/SophDes.A6.zip)
[SophDes(A6_Linkage).zip](https://github.com/user-attachments/files/33796873/SophDes.A6_Linkage.zip)

I spent 9 hours on this assignment 
