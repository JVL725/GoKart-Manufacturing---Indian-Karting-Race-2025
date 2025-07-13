# Go-Kart-Manufacturing---Indian-Karting-Race-2025

## Project Overview

This repository documents the design and fabrication of a Go-Kart chassis as part of a collaborative engineering project. The primary objective was to develop a lightweight, structurally sound frame capable of supporting vehicle components and ensuring driver safety. The chassis was built from steel tubing and fabricated using conventional manufacturing techniques: cutting, grinding, and welding. 

## Team contributions

The important responsibilities to be handled were Designing, Analysis and finally the fabrication process which was carried out by the whole team. The design team modeled the chassis geometry using CAD and various load and stress calculations were performed using Ansys software by the analysis team. The base of a manufacturing process is deciding the material. I was responsible for researching and finalizing the chassis material. I also contributed in the fabrication process especially in the cutting and grinding processes.

## Design Consideration

* **Triangulated Geometry:** A space-frame design was chosen to efficiently handle stresses using triangulated members.
* **Driver Safety:** A roll cage was designed with adequate height and side impact protection.
* **Weldability and Fitment:** Joints were carefully designed for proper weld access and minimum stress concentrations.
* **Weight Distribution:** The layout was optimized to position heavy components (driver, engine) centrally and low.

## Material Selection Rationale

Several materials were evaluated based on strength, ductility, weldability, availability, and cost. The selection of material was done keeping in mind design constraints like the composition of material, final weight of chassis and dimension restraints and also keeping in mind the price limitations.

| Material  | Yield Strength (MPa) | Weldability | Cost   | Notes                             |
| --------- | -------------------- | ----------- | ------ | --------------------------------- |
| AISI 1018 | \~370                | Excellent   | Low    | Ductile, widely used in chassis   |
| AISI 1020 | \~350                | Good        | Low    | Slightly less ductile             |
| AISI 1026 | \~415                | Fair        | Medium | Higher strength, harder to weld   |
| AISI 4130 | \~560                | Moderate    | High   | High strength, TIG welding needed |

The materials considered were AISI 1018, AISI 4130, AISI 1026 and AISI 1020 among which AISI 1020 is not durable at the price it is available while AISI 1018 has better strength at arouund same price range; AISI 4130 has high strength to weight ratio but due to high carbon percentage, it is more vulnerable to machining and at the same time it is very expensive.

The modulus of elasticity of AISI 1018 is similar to that of AISI 4130 and at the same time, AISI 4130 is highly expepnsive so using AISI 1018 won’t affect the weight and stiffness in a member of same geometry.

The material chosen is AISI 1018 carbon steel. It has a good carbon content of 0.14-0.2 percentage which gives the material a sufficient hardness and yield strength, maintaining a good balance between ductility and toughness. It also has an excellent weldability and machinability and hence considered as best steel for carburizing parts.

After analyzing these options, **AISI 1018 Seamless Steel** was selected for the following reasons:

* Excellent weldability (suitable for MIG welding used in fabrication)
* Adequate strength and ductility
* Cost-effective and readily available in required dimensions

## Fabrication Process

### 1. Cutting

I participated in cutting steel tubes to exact lengths as per the CAD drawings. This was done using an abrasive cutoff saw, ensuring clean and square cuts. For angled cuts (required at joints), a manual miter setup was used. Each cut was verified with calipers to match dimensional tolerances and ensure proper fit-up in the jig.

### 2. Grinding and Notching

After cutting, I used a hand grinder and tube notcher to prepare the ends of each tube:

* **Surface Grinding:** Removed burrs and oxide layers to improve weld quality.
* **End Notching:** Shaped the ends of the tubes to ensure flush fitment at intersecting angles.
* **Deburring and Cleaning:** All tubes were cleaned with acetone to remove oil/grease before welding.
  This preparation ensured tight joints and clean weld penetration.

### 3. Welding

I helped align and tack-weld the frame in a jig to maintain geometry during full welding. MIG welding was used for all joints. The process was initiated with tack welding and proceeded with seam welding providing a very strong and durable joints.

### 4. Inspection

All welds were visually inspected for porosity and undercut. Any flawed sections were ground out and re-welded. The final frame was dimensionally checked for symmetry and alignment.

## Final Outcome

<img width="322" height="263" alt="Screenshot 2025-07-13 210644" src="https://github.com/user-attachments/assets/e9d3efa1-bc32-4842-9937-aa5762fe8d10" />

*Figure: Isometric view of the fabricated Go-Kart chassis.*

The completed chassis accurately matches the CAD design. The material selection, fabrication processes, and attention to detail resulted in a structurally sound and visually clean frame. The chassis meets all functional and safety goals, and is ready for component integration and testing.

