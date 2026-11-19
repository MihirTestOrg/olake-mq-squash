Sandbox markers, read by every stubbed job (see the "Mock <job>" step):
- `.mock/fail`: one job id per line, optionally prefixed by an event, e.g. `unit-tests`
  or `merge_group/unit-tests`. A matching stubbed job fails.
- `.mock/sleep`: seconds each stubbed job sleeps (default 15).
