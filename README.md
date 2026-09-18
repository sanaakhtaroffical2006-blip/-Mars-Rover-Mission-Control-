# Mars Rover Mission Control - Lab Task 2

## Functional Requirements (FRs)
- **FR-01:** The rover shall receive commands from Mission Control and execute valid commands.
- **FR-02:** The rover shall report its current position, battery level, temperature, and communication status.
- **FR-03:** The system shall reject invalid or unauthorized commands.
- **FR-04 (CR-01):** The rover shall enter Safe Mode within 3 seconds when battery temperature exceeds the critical threshold or battery capacity falls below the defined emergency level.
- **FR-05:** Mission Control shall receive command execution status.
- **FR-06:** All commands and critical rover events shall be recorded with timestamp and operator ID.

## Non-Functional Requirements (NFRs)
- **NFR-01:** Command processing should normally complete within 5 seconds after a command is received by the rover.
- **NFR-02 (CR-03):** The system shall require authenticated and role-authorized operators before accepting rover commands.
- **NFR-03:** The system shall continue operating despite temporary communication interruptions.
- **NFR-04 (CR-02):** The system shall support at least 20 simultaneously connected rovers.
