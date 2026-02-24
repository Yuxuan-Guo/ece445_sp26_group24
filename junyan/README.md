## Junyan's Worklog

- [Junyan's Worklog](#junyans-worklog)
- [2026-02-09: 1st Proposal drafting](#2026-02-09-1st-proposal-drafting-team)
- [2026-02-16: Proposal Revision and Requirement Refinement](#2026-02-16-proposal-revision-and-requirement-refinement-team)
- [2026-02-23: PCB Architecture and Control Subsystem Planning](#2026-02-23-pcb-architecture-and-control-subsystem-planning-individual)
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

## 2026-02-23: PCB Architecture and Control Subsystem Planning (Individual)

### Objectives
- Plan the control PCB architecture
- Select key electrical subsystem blocks
- Define ESP32, motor driver, power, and sensing interfaces

### Record
- Worked on the electrical system architecture centered around the ESP32 control board.
- Planned the interface between the ESP32, motor drivers, battery input, and logic power rail.
- Considered how the PCB should support wireless communication, motor control, and safety shutdown.
- Identified important connector locations for motor outputs, battery input, and programming/debug access.
- Discussed mechanical placement constraints with teammate to make sure the PCB could fit inside the chassis.

### Figures
- **Fig. 1** Electrical subsystem block diagram.
- **Fig. 2** Early PCB interface sketch.

### Equations
- **Eq. 1** Logic rail current requirement:
  `I_total = I_ESP32 + I_sensors + I_LEDs + I_margin`

### Attachments / Sources
- **Doc. A** PCB Architecture Notes
- **Doc. B** ESP32 Pin Planning Notes

### Next Steps
- Continue schematic design
- Confirm motor driver and regulator choices
- Coordinate PCB dimensions with CAD layout


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