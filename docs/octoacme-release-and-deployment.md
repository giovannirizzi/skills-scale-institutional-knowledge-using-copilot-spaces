# OctoAcme — Release & Deployment Guide

## Purpose
Standardize how OctoAcme releases features to production to reduce risk and improve observability.

## Release Types
- Patch: hotfixes addressing critical production issues
- Minor: incremental features and improvements
- Major: significant functionality or breaking changes

## Pre-release requirements
- All acceptance criteria met and PRs merged
- Passing CI and security scans (Security/Compliance Stakeholder sign-off where required)
- QA/Test Engineer has completed testing and provided release sign-off
- Designer has verified UI fidelity for any UI-facing changes
- Release notes drafted
- Rollback / mitigation plan documented
- Smoke tests prepared
- Support/Customer Success notified and support documentation updated

## Deployment Checklist
- [ ] Deployment window scheduled (if needed)
- [ ] Backup or snapshot (if applicable)
- [ ] Deploy to staging and run smoke tests
- [ ] QA/Test Engineer sign-off on staging verification
- [ ] Security/Compliance Stakeholder sign-off (if applicable)
- [ ] Deploy to production (automated pipeline preferred)
- [ ] Run post-deploy verifications
- [ ] Announce release to stakeholders and support (including Support/Customer Success and Executive Sponsor)

## Rollback & Incident Playbook
- If a deployment fails or causes a critical issue:
  - Trigger incident response and notify on-call
  - Rollback to last known-good release if necessary
  - Triage root cause and capture action items

## Release Notes Template
- Release name / number:
- Date:
- Summary:
- Notable changes:
- Migration steps (if any):
- Known issues:
