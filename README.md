# 3-DOF Articulated Robotic Arm for Pick-and-Place Application

## Project Overview

This repository contains the design, CAD files, report materials, and supporting documentation for a **Three-Degree-of-Freedom (3-DOF) Articulated Robotic Arm** developed for a pick-and-place application.

The robotic arm was designed for the **SKEM1503 Computer Aided Engineering Design** group project at **Universiti Teknologi Malaysia (UTM)**. The prototype uses a simple hydraulic actuation system made from **three pairs of syringes** connected with flexible tubing. The structure is built using **20 mm outer-diameter PVC pipe links**, 3D-printed joints, a 3D-printed hook end effector, and a rack-and-pinion base mechanism.

The required task is to pick a **20 mm ring** from a **20 mm high platform**, place it on a **110 mm high platform**, and return it to the original position.

---

## Course Information

| Item        | Details                                    |
| ----------- | ------------------------------------------ |
| Course      | SKEM1503 Computer Aided Engineering Design |
| Semester    | 2025/2026 - 2                              |
| Project     | Group Project                              |
| Group       | 07                                         |
| Institution | Universiti Teknologi Malaysia              |
| Faculty     | Faculty of Electrical Engineering          |
| Lecturer    | AP Dr Leow Pei Ling                        |

---

---

## Project Objectives

The objectives of this project are:

1. To design a functional 3-DOF articulated robotic arm using SolidWorks.
2. To develop a syringe-based hydraulic actuation system for joints J1, J2, and J3.
3. To fabricate and assemble the robotic arm using PVC pipes, 3D-printed parts, syringes, tubing, and off-the-shelf components.
4. To perform a pick-and-place task using a 20 mm ring between platforms of 20 mm and 110 mm height.
5. To produce proper CAD drawings, exploded assembly drawings, BOM, and technical report documentation.

---

## Design Requirements

The robotic arm was designed based on the following project requirements:

* Use **three pairs of syringes** as the hydraulic driving system for joints **J1, J2, and J3**.
* Show the **tubing for the syringe pairs** in the SolidWorks assembly.
* Use **PVC pipes with 20 mm outer diameter and 2 mm wall thickness** for links **L2, L3, and L4**.
* Use a **3D-printed hook** as the end effector.
* Include a base consisting of **Link L1 and Joint J1**.
* Include CAD part drawings, assembly drawing, exploded assembly drawing, BOM, and report appendices.
* Complete the required pick-and-place movement using the developed prototype.

---

## Main Components

| Component        | Description                      | Function                                              |
| ---------------- | -------------------------------- | ----------------------------------------------------- |
| Plastic Syringes | 6 units / 3 pairs                | Hydraulic control for J1, J2, and J3                  |
| Flexible Tubing  | Plastic / silicone / vinyl tube  | Transfers fluid pressure between syringe pairs        |
| PVC Pipe         | 20 mm OD, 2 mm wall thickness    | Used for links L2, L3, and L4                         |
| 3D-Printed Hook  | Hook end effector                | Picks and places the 20 mm ring                       |
| Joint Connectors | 3D-printed parts                 | Connect PVC links and allow joint motion              |
| Syringe Holders  | 3D-printed brackets              | Hold syringes in position                             |
| Rack and Pinion  | 3D-printed base mechanism        | Provides J1 base rotation                             |
| Bearing Balls    | Off-the-shelf component          | Reduce friction and support the base                  |
| Glue / Adhesive  | General-purpose adhesive         | Tightens loose 3D-printed sockets and PVC connections |
| Base Plate       | Plywood / acrylic / printed base | Supports the complete robotic arm                     |

---

## Link Dimensions and Motion Ranges

| Link / Joint            | Designed / Intended Value | Actual / Measured Value | Remarks                              |
| ----------------------- | ------------------------- | ----------------------- | ------------------------------------ |
| L2 / Shoulder Link      | 180 mm                    | 180 mm                  | PVC link                             |
| L3 / Biceps Link        | 100 mm                    | 100 mm                  | Intermediate PVC link                |
| L4 / Forearm Link       | 240 mm                    | 240 mm                  | End-effector PVC link                |
| J1 Base Rotation        | Up to 90°                 | Approx. 90°             | Positive counter-clockwise, top view |
| J2 Biceps Motion        | -5° to +23°               | Approx. 28° total       | Positive upward rotation             |
| J3 Forearm Motion       | -66° to -45°              | Approx. 21° total       | Relative forearm motion              |
| Absolute Forearm Motion | -71° to -22°              | Approx. 49° total       | Calculated from J2 and J3 angles     |

---

## Hydraulic Actuation System

The robotic arm uses a simple hydraulic control system.

Each joint is controlled using one syringe pair:

```text
Control Syringe → Flexible Tube → Actuator Syringe → Joint Motion
```

When the control syringe is pushed, water pressure is transferred through the flexible tubing to the actuator syringe. This causes the actuator syringe to extend or retract, producing movement at the corresponding joint.

The system includes:

* Syringe pair 1 for **J1 base rotation**
* Syringe pair 2 for **J2 arm movement**
* Syringe pair 3 for **J3 forearm / hook movement**

---

## Repository Structure

The repository may be arranged as follows:

```text
3DOF-Robotic-Arm/
│
├── README.md
├── Report/
│   ├── IEEE_Group7_Robotic_Arm_Final_Report.docx
│   └── IEEE_Group7_Robotic_Arm_Final_Report.pdf
│
├── SolidWorks/
│   ├── Assembly/
│   ├── Parts/
│   ├── Drawings/
│   └── Pack_and_Go/
│
├── BOM/
│   └── Bill_of_Materials.xlsx
│
├── Images/
│   ├── Actual_Prototype/
│   ├── CAD_Screenshots/
│   └── Measurement_Notes/
│
├── Drawings/
│   ├── Part_Drawings/
│   ├── Assembly_Drawing/
│   └── Exploded_Assembly_Drawing/
│
└── Submission_Checklist/
```

---

## CAD Drawings

The project includes the following SolidWorks drawing requirements:

* Full-page 2D part drawings
* Full-page CAD assembly drawing
* Full-page exploded assembly drawing
* Balloon numbering for exploded view
* BOM / parts list
* Completed title block / information table

Recommended part drawings include:

1. Hook end effector
2. Joint connector
3. PVC pipe link
4. Base / rack-and-pinion mechanism
5. Syringe hydraulic actuator
6. Syringe holder

---

## Manufacturing and Assembly

The robotic arm was assembled using 3D-printed components, PVC pipe links, syringes, tubing, and supporting fasteners.

General assembly process:

1. Print the base, joint connectors, syringe holders, rack-and-pinion mechanism, and hook.
2. Cut PVC pipes according to the required link dimensions.
3. Insert PVC pipes into the 3D-printed sockets.
4. Apply glue or adhesive to improve tightness and reduce looseness.
5. Install the syringes at the required joint positions.
6. Connect syringe pairs using flexible tubing.
7. Fill the hydraulic system with water and remove air bubbles.
8. Test joint motion individually before testing the full pick-and-place operation.

---

## Testing Summary

The completed prototype was tested by moving a 20 mm ring from a 20 mm platform to a 110 mm platform and returning it to the original position.

The prototype successfully demonstrated:

* Hydraulic movement using three syringe pairs
* Functional joint movement at J1, J2, and J3
* Use of PVC links as structural members
* Hook-based ring pickup and placement
* Working rack-and-pinion base rotation
* Practical integration of CAD design, 3D printing, and mechanical assembly

---

## Challenges and Improvements

| Challenge                                   | Solution / Improvement                                                                                    |
| ------------------------------------------- | --------------------------------------------------------------------------------------------------------- |
| Loose PVC and 3D-printed socket connections | Adhesive was applied to tighten the joints                                                                |
| Tubing disconnecting from syringe tips      | Connections were secured and checked for leakage                                                          |
| Base sliding during arm extension           | Base was restrained during testing; future improvement includes rubber feet, clamps, or larger base plate |
| 3D printing tolerance issues                | Glue, fitting adjustment, and careful assembly were used                                                  |
| Limited stability under extended reach      | Future improvement includes stronger base support and better joint reinforcement                          |

---

## Submission Notes

The complete project submission should include:

* Final report in Word format
* Final report in PDF format
* SolidWorks Pack-and-Go files
* Part drawings
* Assembly drawing
* Exploded assembly drawing
* BOM in Excel format
* Turnitin similarity report below 40%
* Any required lecturer-approved supporting evidence

If videos are not required by the lecturer, state this clearly in the report or submission checklist.

---

## Important Academic Note

This repository is prepared for academic submission and documentation purposes. All design files, drawings, report materials, and images should be used responsibly and should not be copied directly by other groups or students.

---

## License

This project is for educational use only. Reuse of the design, report, or CAD files should credit the original project group.
