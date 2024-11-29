# Cubesat Assembly JIG - Hole guide
This document serves as a guide for the hole pattern of the cubesat assembly JIG and the possible configurations for arranging CubeSat formats.
## References
- The CAD files uploaded to this repository serve as the primary reference for the design and orientation of each configuration. When the CAD files are opened in Inventor Professional 2024 (or later versions), the files that appear correspond to the symbols used in this document.


- The CubeSat formats for which the structure is designed are:
  - 1, 1.5, 2, 3, 4, 6, 8, 12, 16 U
  
Their sizes are derived from *Table 1* of the section "2.3 Cubesat Allowable Volume", of the [EXOpod Nova User manual](https://exolaunch.com/documents/EXOpod_Nova_User_Manual_March_2024.pdf).

-The symbology that will used is the following: 
Symbol | Cubesat format
--- | --- 
:U | 1, 1.5, 2, 3, 4 U
::U | 6, 8 U
:::U | 12, 16 U

- Reference frame for the cubesats:


<img src="https://github.com/user-attachments/assets/31dbc42c-4206-43e9-9f75-74a1149e02b2" alt="cubesat_xy_draw" width="500">

<img src="https://github.com/user-attachments/assets/40aa84de-cab7-4837-9805-54ef8a8f9aa9" alt="cubesat_yz_draw" width="500">

## Bracket clusters definition
### :U cubesats 
It is designated with 1 orientation, which consists of the following bracket clusters:
  
A/a | Bracket cluster
--- | --- 
1 | :U Core
2 | :U Extension 1
3 | :U Extension 2
4 | :U Extension 3

<img src="https://github.com/user-attachments/assets/2798c2ba-04de-4ee3-991f-4b84246b77fe" alt="cubesat_xy_draw" width="1000">

### ::U cubesats 
It is designated with two orientations, each consisting of the following bracket clusters:
 - Orientation 1

A/a | Bracket cluster 
--- | --- 
1 | ::U Orientation 1 Core
2 | ::U Orientation 1 Extension 1
3 | ::U Orientation 1 Extension 2

- Orientation 2
  
A/a | Bracket cluster 
--- | --- 
1 | ::U Orientation 2 Core
2 | ::U Orientation 2 Extension 1
3 | ::U Orientation 2 Extension 2

<img src="https://github.com/user-attachments/assets/834b2485-cfb8-4e30-b004-2f3966516dc2" alt="cubesat_xy_draw" width="1000">
<img src="https://github.com/user-attachments/assets/8ec6a037-adb0-4935-8d7a-083caca97714" alt="cubesat_xy_draw" width="1000">

### :::U cubesats 
It is designated with two orientations, each consisting of the following bracket clusters:
 - Orientation 1

A/a | Bracket cluster 
--- | --- 
1 | :::U Orientation 1 Core
2 | :::U Orientation 1 Extension 1
3 | :::U Orientation 1 Extension 2

- Orientation 2
  
A/a | Bracket cluster 
--- | --- 
1 | :::U Orientation 2 Core
2 | :::U Orientation 2 Extension 1
3 | :::U Orientation 2 Extension 2

<img src="https://github.com/user-attachments/assets/5edf5745-8c06-4ccd-9dc4-30554226f15b" alt="cubesat_xy_draw" width="1000">
<img src="https://github.com/user-attachments/assets/ad338f62-37bc-496d-947d-107ef6902910" alt="cubesat_xy_draw" width="1000">

## Cubesats positions
- The positions will be described using the following format:
  - (Cubesat Format)(Plane corresponding to the reference frame of the CubeSat), for example *1U XY*
  - Exceptions are the *::U XY* and *:::U XY* positions, where the **orientation** information is added in between, for example, *::U Orientation 1 XY*. These are the only positions where the orientation of the brackets affects how the corresponding CubeSat will be able to orient on its other planes.
 
### _Position_ :U XY
This position consists of the following bracket clusters:

A/a | Bracket cluster in use
--- | --- 
1 | :U Core
<img src="https://github.com/user-attachments/assets/ed3b735d-048b-419a-982c-3229d0b943fd" alt="cubesat_xy_draw" width="1000">

### __Position__ 1U XZ, YZ
This position consists of the following bracket clusters:

A/a | Bracket cluster in use
--- | --- 
1 | :U Core

<img src="https://github.com/user-attachments/assets/9d7d5165-e7d6-41ff-87ec-723dfe254c69" alt="cubesat_xy_draw" width="1000">


### __Position__ 1.5U XZ, YZ
This position consists of the following bracket clusters:

A/a | Bracket cluster in use
--- | --- 
1 | :U Core

<img src="https://github.com/user-attachments/assets/b003ca5c-f033-482f-a9ca-f334c7136cba" alt="cubesat_xy_draw" width="1000">

### __Position__ 2U XZ, YZ
This position consists of the following bracket clusters:

A/a | Bracket cluster in use
--- | --- 
1 | :U Core
2 | :U Extension 3

<img src="https://github.com/user-attachments/assets/834fcaaa-70ee-43ae-9332-a9c2953ec574" alt="cubesat_xy_draw" width="1000">


### __Position__ 3U XZ, YZ
This position consists of the following bracket clusters:

A/a | Bracket cluster in use
--- | --- 
1 | :U Core
2 | :U Extension 1

<img src="https://github.com/user-attachments/assets/53103c78-f9db-45b1-825c-c3c7b9ab41d0" alt="cubesat_xy_draw" width="1000">


### __Position__ 4U XZ, YZ
This position consists of the following bracket clusters:

A/a | Bracket cluster in use
--- | --- 
1 | :U Core
2 | :U Extension 1
3 | :U Extension 2

<img src="https://github.com/user-attachments/assets/fc5d0cf1-d704-4b23-b915-3b9c35b048d6" alt="cubesat_xy_draw" width="1000">

### _Position_ ::U Orientation 1 XY
This position consists of the following bracket clusters:

A/a | Bracket cluster in use
--- | --- 
1 | ::U Orientation 1 Core
<img src="https://github.com/user-attachments/assets/9eef3beb-7807-4b95-9551-955201663026" alt="cubesat_xy_draw" width="1000">


### _Position_ ::U Orientation 2 XY
This position consists of the following bracket clusters:

A/a | Bracket cluster in use
--- | --- 
1 | ::U Orientation 2 Core
<img src="https://github.com/user-attachments/assets/91b2b014-563e-4ab5-993a-adb045bd3781" alt="cubesat_xy_draw" width="1000">

### _Position_ 6U XZ
This position consists of the following bracket clusters:

A/a | Bracket cluster in use
--- | --- 
1 | ::U Orientation 2 Core
2 | ::U Orientation 2 Extension 1

<img src="https://github.com/user-attachments/assets/6b45bd33-a67a-4183-8930-c9bb15b49472" alt="cubesat_xy_draw" width="1000">

### _Position_ 6U YZ
This position consists of the following bracket clusters:

A/a | Bracket cluster in use
--- | --- 
1 | ::U Orientation 1 Core
2 | ::U Orientation 1 Extension 1

<img src="https://github.com/user-attachments/assets/13a84034-621e-4b91-bd8b-998c3e98b334" alt="cubesat_xy_draw" width="1000">

### _Position_ 8U XZ
This position consists of the following bracket clusters:

A/a | Bracket cluster in use
--- | --- 
1 | ::U Orientation 2 Core
2 | ::U Orientation 2 Extension 1
3 | ::U Orientation 2 Extension 2

<img src="https://github.com/user-attachments/assets/5f9d35e2-7e08-412c-aca3-3046d63258f3" alt="cubesat_xy_draw" width="1000">

### _Position_ 8U YZ
This position consists of the following bracket clusters:

A/a | Bracket cluster in use
--- | --- 
1 | ::U Orientation 1 Core
2 | ::U Orientation 1 Extension 1
3 | ::U Orientation 1 Extension 2

<img src="https://github.com/user-attachments/assets/1408b43d-5ebf-4a83-a604-f9a63e8fe7d2" alt="cubesat_xy_draw" width="1000">


### _Position_ :::U Orientation 1 XY
This position consists of the following bracket clusters:

A/a | Bracket cluster in use
--- | --- 
1 | :::U Orientation 1 Core
<img src="https://github.com/user-attachments/assets/87b8ba9e-a836-4015-b52d-2eff90b54e0c" alt="cubesat_xy_draw" width="1000">


### _Position_ :::U Orientation 2 XY
This position consists of the following bracket clusters:

A/a | Bracket cluster in use
--- | --- 
1 | :::U Orientation 2 Core
<img src="https://github.com/user-attachments/assets/1bb5a745-6dd7-4802-954c-259a33dd2ecf" alt="cubesat_xy_draw" width="1000">


### _Position_ 12U XZ
This position consists of the following bracket clusters:

A/a | Bracket cluster in use
--- | --- 
1 | :::U Orientation 1 Core


<img src="https://github.com/user-attachments/assets/501619c3-341a-4896-9f48-4b224b20b161" alt="cubesat_xy_draw" width="1000">


### _Position_ 12U YZ
This position consists of the following bracket clusters:

A/a | Bracket cluster in use
--- | --- 
1 | :::U Orientation 2 Core

<img src="https://github.com/user-attachments/assets/9701e7d2-2ebd-4292-8dcf-d8770b485a2d" alt="cubesat_xy_draw" width="1000">

### _Position_ 16U XZ
This position consists of the following bracket clusters:

A/a | Bracket cluster in use
--- | --- 
1 | :::U Orientation 1 Core
2 | :::U Orientation 1 Extension 1
3 | :::U Orientation 1 Extension 2

<img src="https://github.com/user-attachments/assets/f9678217-44cc-47d5-aaa1-d9d18e4c7f25" alt="cubesat_xy_draw" width="1000">

### _Position_ 16U YZ
This position consists of the following bracket clusters:

A/a | Bracket cluster in use
--- | --- 
1 | :::U Orientation 2 Core
2 | :::U Orientation 2 Extension 1
3 | :::U Orientation 2 Extension 2


<img src="https://github.com/user-attachments/assets/6c702c45-0468-4562-bdd8-a978b7d15951" alt="cubesat_xy_draw" width="1000">
