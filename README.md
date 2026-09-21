# PRMedic

> Portable agent for diagnosing missing contribution and pull-request guidance.

## What it does

PRMedic checks project evidence for contribution or pull-request guidance and reports when that workflow is difficult to discover. The goal is to make the contribution boundary explicit.

### Diagnostic fingerprint

**Contribution signals → review-readiness finding → evidence → action**

## Why this agent is distinct

PRMedic is concerned with how code changes enter a repository. It does not attempt to judge the quality of a pull request from filenames alone. Instead, it checks whether the repository exposes recognizable contribution guidance.

## Workflow

```text
Repository
    ↓
Contribution scanner
    ↓
PR-readiness rule
    ↓
Observed evidence
    ↓
Improvement plan
```

## Verification

The repository includes:
- OpenGAP passport metadata
- contribution-focused fixture
- explainability and duty contracts
- four portability adapters
- automated adapter checks

OpenGAP validation passed and all four generated exports were exercised successfully.

## Design principle

**Make the contribution path visible.** A project that clearly documents how changes should be proposed is easier to maintain and easier to extend.

## Medic family

PRMedic is one focused node in the Medic family of portable engineering agents. Shared architecture enables interoperability without collapsing every diagnostic into one generic reviewer.