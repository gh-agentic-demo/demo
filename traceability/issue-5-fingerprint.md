# Issue-to-Commit Fingerprint

This file demonstrates a loosely-coupled, hash-based link between an issue and this commit.

Canonical input string:
`gh-agentic-demo/demo#5@I_kwDOTaWh_s8AAAABJEh0yw@2026-07-16T15:43:34Z`

Fields used (all pulled from the GitHub API for the issue, independent of any "#5" text mention):
- repo full name: gh-agentic-demo/demo
- issue number: 5
- issue node_id: I_kwDOTaWh_s8AAAABJEh0yw
- issue created_at: 2026-07-16T15:43:34Z

SHA-256(canonical input):
e64c880c5914900ac1f336ac6b9e2b5334692e388b14987642dac2ae7879c592

This hash is also included in the commit message trailer as `Issue-Ref-Hash`. Anyone can recompute this hash from the issue's API data to verify the link, without relying on GitHub's keyword parsing of issue numbers.
