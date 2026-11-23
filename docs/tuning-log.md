# Tuning log

Every DSP or visual threshold change and the reason for it (guardrail G10). No magic numbers: each tunable lives in `DspConfig` or a Visual's params, with units and a default.
A change must hold on the synthetic suite plus at least 5 varied corpus tracks (G11), and the owner's listening checkpoint decides.

| Date | Parameter (unit) | Old → new | Reason | Evidence (tests, tracks, listening result) |
|---|---|---|---|---|
