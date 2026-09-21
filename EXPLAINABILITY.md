## Decision and Reasoning

PRMedic decides whether the repository contains recognizable contribution or pull-request guidance. Missing evidence produces a readiness finding tied to the observed repository state.

## Inputs and Data Sources

It inspects the file list for CONTRIBUTING-style or pull_request-style artifacts. The rule converts that structural signal into a documented recommendation.

## Limits and Constraints

It does not judge the quality of review policy, branch protection, CI gates, or repository settings that live outside the files. A custom contributor workflow may be valid but remain undetected.
