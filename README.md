# CEREBRON F83 — Flight Simulation & Digital Twin

Status: SCAFFOLDED / NOT YET VALIDATED

## Mission
Aircraft/drone digital twins and coupled flight simulation.

## Candidate open-source stack
JSBSim; FlightGear; Gazebo; PX4

## Reality rules
- SIMULATION != TEST
- WORKFLOW_SUCCESS != SCIENTIFIC_VALIDATION
- CLAIM <= EVIDENCE
- Record simulator/version/config/seed/inputs/outputs.
- Compare against an analytical, published, or independently reproduced reference before promotion.

## Validation ladder
E0 architecture -> E1 deterministic smoke test -> E2 reference case -> E3 coupled simulation -> E4 SIL/HIL where applicable -> F33 Red Team -> F35 replication -> F37 test design -> F72 Reality/Evidence -> AFAH.

No simulator listed here is considered installed or validated merely because it is named.
