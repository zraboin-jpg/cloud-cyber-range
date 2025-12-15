# Detection Gap Analysis

## Technique: T1110 – Password Spraying

Observed:
Low-frequency attempts bypassed static thresholds.

Root Cause:
Detection tuned too high without behavior correlation.

Remediation:
Added time-based aggregation and UEBA logic.

Result:
Detection time reduced from hours to minutes.
