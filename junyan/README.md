## Junyan's Worklog

- [Junyan's Worklog](#junyans-worklog)
- [2026-02-09: 1st Proposal drafting](#2026-02-09-1st-proposal-drafting-team)
- [2026-02-16: Proposal Revision and Requirement Refinement](#2026-02-16-proposal-revision-and-requirement-refinement-team)
- [2026-02-23: PCB Architecture and Control Subsystem Planning](#2026-02-23-pcb-architecture-and-control-subsystem-planning-individual)
- [2026-03-02: Schematic Development and Power Planning](#2026-03-02-schematic-development-and-power-planning-individual)
- [2026-03-09: Design Document Drafting](#2026-03-09-design-document-drafting-team)
- [2026-03-16: PCB Layout and Design Rule Check](#2026-03-16-pcb-layout-and-design-rule-check-individual)
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

## 2026-03-02: Schematic Development and Power Planning (Individual)

### Objectives
- Work on schematic design for the control PCB
- Plan power regulation and motor power distribution
- Include safety-related electrical features

### Record
- Developed the schematic for the ESP32-based control subsystem.
- Worked on the power path from the battery to the motor drivers and logic regulator.
- Considered how to reduce brownout risk during motor stall or high-current conditions.
- Added supporting passive components such as resistors, capacitors, and indicator LEDs.
- Discussed whether current sensing should be included to help monitor motor load and protect components.

### Figures
- **Fig. 1** Power subsystem schematic section.
- **Fig. 2** ESP32 control schematic section.

### Equations
- **Eq. 1** Regulator input power estimate:
  `P_in = V_battery I_input`

### Attachments / Sources
- **Doc. A** Schematic Draft
- **Doc. B** Component Selection Notes

### Next Steps
- Finish schematic review
- Begin PCB layout
- Check component footprints before ordering

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

## 2026-03-16: PCB Layout and Design Rule Check (Individual)

### Objectives
- Create PCB layout for the control and power board
- Place major components and connectors
- Check routing and design rules

### Record
- Worked on PCB layout using the schematic as the reference.
- Placed the ESP32 module, motor driver connections, regulator components, and external connectors.
- Considered current path width for motor power traces and battery input traces.
- Kept the USB/programming side accessible based on mechanical constraints.
- Ran design rule checks and fixed routing/spacing issues found during the layout process.

### Figures
- **Fig. 1** PCB top-layer layout.
- **Fig. 2** PCB bottom-layer layout.

### Equations
- **Eq. 1** Approximate trace current margin:
  `Margin = I_trace_limit / I_expected`

### Attachments / Sources
- **Doc. A** PCB Layout Screenshot
- **Doc. B** DRC Result Notes

### Next Steps
- Finalize PCB layout
- Review footprints before fabrication
- Prepare board for assembly


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