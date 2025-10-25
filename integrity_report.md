# Data Integrity Report

**Generated:** 2025-10-25 01:42:27.421647

## Summary

- **Total JSON files:** 150
- **Successful conversations:** 119
- **Failed conversations:** 31
- **Unique run_ids:** 150
- **Duplicate run_ids:** 0
- **Files missing metrics:** 31

## Conversations by Model × Arm

| model                             |   baseline |   belief_audit |   fact_table |   grounding_pilot |
|:----------------------------------|-----------:|---------------:|-------------:|------------------:|
| anthropic:claude-3-5-haiku-latest |         10 |             10 |           10 |                10 |
| google:gemini-2.0-flash           |          9 |             10 |           10 |                10 |
| openai:gpt-4o-mini                |         10 |             10 |           10 |                10 |



⚠️ **Deviations from expected N=10:**

- google:gemini-2.0-flash, baseline: 9


## CSV vs JSON Comparison

- **JSON successful:** 119
- **CSV rows:** 119
- **Match:** ✅


## Missing Values in CSV

- **correction_latency_turn:** 6 (5.0%)

- **blame_shift_severity:** 91 (76.5%)

- **confab_entities:** 10 (8.4%)
