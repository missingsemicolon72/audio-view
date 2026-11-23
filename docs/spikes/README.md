# Spike reports

Time-boxed experiments from Milestone M0. One file per spike: `S1-overlay.md`, `S2-capture.md`, `S3-ipc.md`.
Per guardrail G14, every claim is either backed by a recorded measurement/test or labelled **unverified**.

## Template

```markdown
# SN. Title

- Date: YYYY-MM-DD
- Machine: Windows build, CPU/GPU, displays (and DPI scale)
- Time box: how long we allowed ourselves

## Question
What this spike must answer.

## Method
Exact commands and setup, so the run can be repeated.

## Measurements
Tables with numbers and units. Name the tool that produced each number.

## Result
Pass / fail / partial against the success criteria in the task.

## Unverified
Anything assumed but not measured.

## Decision needed from the owner
Only if the spike failed or changes direction.
```
