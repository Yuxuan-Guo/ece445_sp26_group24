## Yuxuan's Worklog

- [Yuxuan's Worklog](#yuxuans-worklog)
- [2026-02-09: 1st Proposal drafting](#2026-02-09-1st-proposal-drafting-team)
- [2026-02-16: Proposal Revision and Requirement Refinement](#2026-02-16-proposal-revision-and-requirement-refinement-team)
- [2026-02-23: CAD Layout and Mechanical Planning](#2026-02-23-cad-layout-and-mechanical-planning-individual)
- [2026-03-02: Parts Ordering and Mechanical Integration Planning](#2026-03-02-parts-ordering-and-mechanical-integration-planning-individual)
- [2026-03-09: Design Document Drafting](#2026-03-09-design-document-drafting-team)
- [Template](#yyyy-mm-dd)

## 2026-02-09: 1st Proposal drafting (Team)

### Objectives
- Block diagram 
- Three high-level requirements 
- Subsystem requirements (one for each subsystem) 
- Lab notebook

### Record
- Completed all above objectives
- Prepared questions for the upcoming TA meeting

### Attachments / Sources
- Doc. A: Block Diagram (Draft)

### Next Steps
- Complete Project Proposal
- learn how to purchase parts/place orders

## 2026-02-16: Proposal Revision and Requirement Refinement (Team)

### Objectives
- Refine the project proposal after initial feedback
- Clarify the high-level requirements for the antweight battlebot
- Improve the subsystem division and requirement wording
- Prepare questions for TA discussion

### Record
- Reviewed the first proposal draft as a team and identified unclear parts in the subsystem descriptions.
- Refined the high-level requirements to focus on control reliability, drivetrain pushing ability, and safe shutdown behavior.
- Discussed how the wedge, powered roller, 4WD drivetrain, ESP32 control board, and power subsystem should connect together.
- Prepared questions about subsystem requirement measurability and how to present the safety mechanism clearly.

### Figures
- **Fig. 1** Updated project block diagram showing control, power, drivetrain, and weapon/roller subsystems.

### Equations
- **Eq. 1** Estimated required pushing force:
  `F_required = μmg`

### Attachments / Sources
- **Doc. A** Revised Proposal Draft
- **Doc. B** Updated Block Diagram

### Next Steps
- Finalize proposal wording
- Start detailed CAD layout and PCB planning
- Confirm key component dimensions before ordering

## 2026-02-23: CAD Layout and Mechanical Planning (Individual)

### Objectives
- Create an initial chassis layout for the antweight battlebot
- Reserve space for motors, wheels, battery, PCB, and servo/roller mechanism
- Decide the approximate placement of internal components

### Record
- Worked on the early CAD layout of the robot chassis.
- Planned a low-profile wedge front with room for a powered roller above the wedge.
- Reserved internal space for the battery, PCB, drive motors, and wiring paths.
- Considered how to place the PCB so the USB-C connector remains accessible from the side while avoiding interference with the chassis wall.
- Checked the approximate size relationship between the PCB, battery, and drive motors to avoid packaging conflicts.

### Figures
- **Fig. 1** Initial top-view chassis layout with component placement.
- **Fig. 2** Side-view sketch showing wedge angle and roller position.

### Equations
- **Eq. 1** Approximate robot weight budget:
  `m_total = m_chassis + m_battery + m_PCB + m_motors + m_wheels + m_weapon`

### Attachments / Sources
- **Doc. A** Fusion 360 CAD Draft
- **Doc. B** Component Dimension Notes

### Next Steps
- Refine chassis wall thickness and mounting points
- Add motor holders and wheel clearance
- Confirm whether the roller mechanism has enough vertical clearance

## 2026-03-02: Parts Ordering and Mechanical Integration Planning (Individual)

### Objectives
- Identify required components for drivetrain, battery, and mechanical assembly
- Prepare material order information
- Check compatibility between purchased parts and the CAD design

### Record
- Researched and selected parts needed for the drivetrain and power system.
- Prepared ordering information and business justifications for key components.
- Checked the battery connector type and motor shaft size to make sure they matched the planned design.
- Updated the CAD layout based on the expected motor and battery dimensions.
- Discussed with teammate how the PCB and power wiring should be routed inside the chassis.

### Figures
- **Fig. 1** Updated CAD layout with reserved battery and PCB areas.
- **Fig. 2** Motor-to-wheel connection sketch.

### Equations
- **Eq. 1** Estimated available drive force:
  `F_available = T_motor / r_wheel`

### Attachments / Sources
- **Doc. A** Parts List Draft
- **Doc. B** Order Justification Notes
- **Doc. C** Updated CAD Screenshot

### Next Steps
- Continue CAD refinement after parts arrive
- Design wheel hub geometry for the motor shaft
- Coordinate with teammate on PCB mounting hole placement

## 2026-03-09: Design Document Drafting (Team)

### Objectives
- Work on the design document structure
- Add subsystem descriptions and requirements
- Prepare testing and verification plans
- Improve the problem/solution and visual aid sections

### Record
- Met as a team to divide the design document sections.
- Discussed how to describe the novelty of the design, especially the combination of wedge, powered roller, and 4WD drivetrain.
- Added more measurable subsystem requirements for control, power, drivetrain, and weapon/roller operation.
- Planned verification tests for link-loss shutdown, drive pushing force, roller movement, and power stability.
- Reviewed how the block diagram should match the written subsystem descriptions.

### Figures
- **Fig. 1** System-level visual aid showing the robot, user controller, and wireless communication.
- **Fig. 2** Updated block diagram with clearer subsystem boundaries.

### Equations
- **Eq. 1** Battery voltage sag estimate:
  `V_sag = I_peak R_internal`

### Attachments / Sources
- **Doc. A** Design Document Draft
- **Doc. B** Updated Block Diagram
- **Doc. C** Verification Plan Notes

### Next Steps
- Complete individual assigned sections
- Add tolerance analysis calculations
- Review document formatting before submission


## YYYY-MM-DD

### Objectives
-

### Record
- 

### Figures
- **Fig. 1**

### Equations
- **Eq. 1**

### Attachments / Sources
- **Doc. A**

### Next Steps
- 