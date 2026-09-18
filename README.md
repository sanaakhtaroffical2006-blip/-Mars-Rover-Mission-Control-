# -Mars-Rover-Mission-Control-
Requirements analysis for the Mars Rover Mission Control system, including functional, non-functional, and updated CR requirements.
# Mars Rover Mission Control - Lab Task 2

## Functional Requirements (FRs)
- **FR-01:** Receive and execute valid commands.
- **FR-02:** Report current position, battery level, temperature, and communication status.
- **FR-03:** Reject invalid or unauthorized commands.
- **FR-04:** Enter Safe Mode within 3 seconds when battery temperature exceeds critical threshold or battery capacity falls below emergency level.
- **FR-05:** Mission Control shall receive command execution status.
- **FR-06:** Record all commands and critical events with timestamp and operator ID.

## Non-Functional Requirements (NFRs)
- **NFR-01:** Command processing should complete within 5 seconds.
- **NFR-02:** Require authenticated and role-authorized operators before accepting commands.
- **NFR-03:** System shall continue operating despite temporary communication interruptions.
- **NFR-04:** Support at least 20 simultaneously connected rovers.
