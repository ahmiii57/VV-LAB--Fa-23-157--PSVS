# PSVS Defect Log

| Defect ID | Req ID | Category | Description | Evidence | Severity | Suggested Fix | Status |
|---|---|---|---|---|---|---|---|
| D01 | S1 | Incompleteness | Registration criteria are missing. | S1 says registered depositors but does not define registration. | Medium | Define registration criteria. | Open |
| D02 | S2 | Vagueness | Large number is unclear. | S2 does not specify a numeric capacity. | Medium | Specify capacity. | Open |
| D03 | S3 | Incompleteness | Capacity counting rules are unclear. | S3 gives limits but not how boxes are counted. | Low | Define capacity counting rules. | Open |
| D04 | S4 | Incompleteness | Ownership transfer rules are missing. | S4 does not explain ownership changes. | Medium | Define ownership transfer. | Open |
| D05 | S5 | Ambiguity | Emergency is undefined. | S5 does not define emergency conditions. | High | Define emergency criteria and approval. | Open |
| D06 | S6 | Vagueness | Safe temperature is not measurable. | S6 gives no exact temperature range. | High | Specify the safe range. | Open |
| D07 | S7 | Incompleteness | Monitoring details are missing. | S7 gives a limit but no monitoring interval. | High | Define monitoring frequency. | Open |
| D08 | S8 | Ambiguity | Maintenance conditions are unclear. | S8 does not specify duration or approval. | High | Define maintenance rules. | Open |
| D09 | S9 | Vagueness | Low viability and promptly are undefined. | S9 gives no threshold or response time. | High | Set a threshold and time limit. | Open |
| D10 | S10 | Incompleteness | Annual quota calculation is unclear. | S10 does not define the year or rounding method. | High | Define quota calculation rules. | Open |
| D11 | S11 | Incompleteness | Re-inspection criteria are missing. | S11 does not define inspection steps or pass criteria. | Medium | Define inspection procedure. | Open |
| D12 | S12 | Vagueness | Good audit trail is not measurable. | S12 does not specify required fields or retention. | Medium | Define audit fields and retention. | Open |
| D13 | S4 vs S5 | Contradiction | Withdrawal permissions may conflict. | S4 permits owner withdrawal; S5 allows emergency release to any requesting party. | High | Define emergency override rules. | Open |
| D14 | S7 vs S8 | Contradiction | Temperature rules appear to conflict. | S7 sets -18°C maximum; S8 permits 0°C during maintenance. | High | Define the maintenance exception. | Open |
| D15 | S1 vs S5 | Ambiguity | Emergency recipient eligibility is unclear. | S1 restricts deposits; S5 allows release to any requesting party. | High | Define recipient authorization. | Open |
| D16 | S10 | Non-verifiability | Quota compliance cannot be checked without withdrawal records. | S10 requires a yearly limit but does not specify tracking. | Medium | Define withdrawal history tracking. | Open |
| D17 | S12 | Incompleteness | Audit record retention rules are missing. | S12 does not specify how long records are kept. | Low | Define retention duration. | Open |
