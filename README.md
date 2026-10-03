# API Version Sunset Readiness Checker

Review API retirement plans for migration evidence and consumer communication.

## Run

    python3 agent.py examples/good-input.json
    python3 tools/review-api-version-sunset-readiness-checker.py examples/good-input.json

Input requirements and thresholds are listed in metadata.json. Output contains status, score, checked rules, and evidence-backed findings.

## Limits

Offline, deterministic review aid. Cannot establish facts beyond supplied evidence; a human must review before acting.
