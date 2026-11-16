## Risk Assessment

| ID | Function / requirement | Failure mode | Effect on patient / data | S | P | D | RPN | Risk | Mitigation | Verified by | Status |
|---|---|---|---|---|---|---|---|---|---|---|---|
| R-001 | URS-010 Audit trail | Audit trail not recording changes | Loss of data integrity | 3 | 1 | 2 | 6 | Medium | Vendor config locked, OQ test | TS-OQ-003 | Open |
| R-002 | URS-020 Access control | User gets wrong role | Unauthorized change to GxP data | 3 | 2 | 2 | 12 | High | Role matrix, periodic access review | TS-OQ-005 | Open |
| R-003 | URS-030 Data export | Export truncates records | Incomplete reporting | 2 | 1 | 1 | 2 | Low | Standard function, vendor tested | Vendor doc | Closed |
