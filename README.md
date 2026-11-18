# RepoSentinel

Local-first open-source repository maintenance debt analyzer.

## The Problem

Open-source projects die silently. Dependencies go unmaintained, READMEs fall out of sync, test coverage erodes, and critical knowledge concentrates in one person. Existing tools scan for security vulnerabilities, but none give maintainers a holistic **Maintenance Debt Score** with actionable remediation steps.

## What RepoSentinel Does

RepoSentinel scans a local git repository and produces:

1. A **Maintenance Debt Score** (0–100).
2. Detected issues categorized by severity (Critical, High, Medium, Low).
3. An executable remediation checklist with suggested fixes.

## Installation

