# Pure Hash-Based Fingerprint (no GitHub keyword linking)

This file's commit message deliberately contains no literal issue-number reference (no owner/repo#N pattern), so GitHub's built-in cross-referencing will NOT link this commit to the issue automatically.

The link instead exists only as a cryptographic fingerprint that a human or script can independently recompute and verify:

Canonical input (fields fetched from the GitHub API for the issue):
- repo full name: gh-agentic-demo/demo
- issue node_id: I_kwDOTaWh_s8AAAABJEh0yw
- issue created_at: 2026-07-16T15:43:34Z

SHA-256 fingerprint:
e64c880c5914900ac1f336ac6b9e2b5334692e388b14987642dac2ae7879c592

To verify: fetch the issue via the API, rebuild the canonical string, hash it, and compare to the Issue-Ref-Hash trailer in this commit's message. A match proves the two artifacts are related without relying on any textual issue-number mention.
