# Structural_Analysis-Project
This simulation explores the deformation behavior of a metal safety barrier under impact loading using Ansys Workbench. A STEP-based CAD model representing a multi-rail guardrail was imported and prepared for analysis. Fixed support conditions were applied at the base of both vertical posts to simulate realistic anchoring to the ground.

A horizontal impact force was introduced at the mid-span of the top rail—mimicking a collision scenario such as a vehicle strike. The model was assigned material properties consistent with structural steel and meshed using a refined, automatic setup to ensure result accuracy near high-stress zones.

#🧱 1. Geometry
* Imported a STEP file representing a multi-rail guardrail or safety barrier.
* Opened and processed in Ansys DesignModeler.
* Verified solid geometry and prepared it for meshing.
* Applied Fixed Supports at the bottom faces of the vertical posts to simulate ground anchoring.
<img width="1066" height="449" alt="image" src="https://github.com/user-attachments/assets/f3064e07-db3f-4487-8ea3-f32fd20976bd" />


#⚙️ 2. Material Properties
* Assigned Structural Steel to the entire model:
* Young’s Modulus: 200 GPa
* Poisson’s Ratio: 0.3
* Density: 7800 kg/m³

# 🕸️ 3. Meshing
* Used Automatic Mesh with local refinements near critical zones.
* Ensured mesh quality for accurate stress and deformation prediction.
* Mesh settings balanced accuracy and computational performance.


# 4. Boundary Conditions
* Fixed support at the bottom rail.
<img width="593" height="541" alt="image" src="https://github.com/user-attachments/assets/8ce496ab-8be2-4db3-af01-7ddf02ea1b1c" />

# 5. Loading Conditions
Simulated impact scenario:
* Applied a 10kN horizontal force at the mid-span of the top rail (front face).
* Direction aligned with expected vehicle impact or lateral collision force.
<img width="596" height="616" alt="image" src="https://github.com/user-attachments/assets/288a38d0-5160-49d3-8aa0-de754edc8de0" />

# 🧮 6. Simulation Type
* Ran Static Structural Analysis using Ansys Mechanical.
* Solver evaluated deformation and stress distribution under impact conditions.

# Result
<img width="1530" height="746" alt="image" src="https://github.com/user-attachments/assets/08f9ea36-808a-413f-8a05-db95b5c9dc7d" />
The static structural simulation of the metal safety barrier under an impact load reveals that the maximum deformation occurs near one edge, even though the force was applied at the mid-span of the top horizontal rail. The total deformation measured was approximately 2.93 mm, which falls within the acceptable limits for elastic behavior, assuming the material is structural steel.

<img width="1530" height="746" alt="image" src="https://github.com/user-attachments/assets/b04f082b-9d57-421d-83e6-9b9a18cf448b" />
Despite the high localized stress, no widespread yielding was observed, indicating that the structure can withstand the current load within its elastic limits. However, the stress at the hotspot (≈155 MPa) should be compared against the material yield strength of structural steel (~250 MPa for mild steel) to ensure long-term reliability

