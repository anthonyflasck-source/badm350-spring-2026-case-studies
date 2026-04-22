# Campus Closet Automation Proof

This folder contains working automation evidence for BADM 350 Module 3.2.

## What's Included

- `automation-tools/run-automations.ps1`: PowerShell script that runs the two automations.
- `automation-proof/20260421-221830/`: First proof run output.
- `automation-proof/20260421-223428/`: Second proof run output.

## What This Demonstrates

- Social Content Pipeline automation executes and generates content output.
- User Feedback Analyzer automation executes and generates analysis/action outputs.
- Each run writes a proof log plus markdown deliverables in a timestamped folder.

## How To Re-Run

From PowerShell:

```powershell
powershell -ExecutionPolicy Bypass -File .\case-studies\campus-closet-automation-proof\automation-tools\run-automations.ps1
```

Expected result: a new timestamped folder appears under `automation-proof/` with fresh output files.
