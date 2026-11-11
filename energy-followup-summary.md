# Q3 Campus Energy Audit — Academic Committee Follow-Up Summary

**Prepared for:** Academic Committee Meeting
**Committee meeting date:** November 18, 2026 (Auditorium B, Main Campus)
**Source:** campus_energy_audit.pdf (Q3 campus energy audit), weekly meter export meter_readings.csv
**Data project:** BigQuery dataset `facilities_energy`, table `meter_readings` (5 weekly readings, loaded 2026-11-18)

## Total Energy Consumption (Q3)

- **Total kWh across 5 weekly meter readings: 5,630 kWh**
- **Readings count: 5** (matches the expected 5 weekly readings)
- **No discrepancy flagged:** loaded totals match the expected export of 5,630 kWh.

## Key Findings (from page 3 of the audit — saved as key_findings.pdf)

- Peak demand down 18% after chiller retrofit
- Solar canopy adds 32 kWh per day
- Night setback saves 4% of baseline load

## Recommended Next Steps for the Committee

1. Review the attached key-findings page (key_findings.pdf) as the formal audit attachment.
2. Note the 18% peak demand reduction from the chiller retrofit as the headline efficiency win for Q3.
3. Track the solar canopy's 32 kWh/day contribution in Q4 projections.
4. Validate the night-setback savings (4% of baseline load) against next quarter's meter data in `facilities_energy.meter_readings`.

*Follow-up owner: Facilities Coordinator. Data verified in BigQuery on 2026-11-18 (5 readings, 5,630 kWh total).*
