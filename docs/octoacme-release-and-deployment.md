# OctoAcme — Release & Deployment Guide

## Purpose
Standardize how OctoAcme releases features to production to reduce risk and improve observability.

## Release Types
- Patch: hotfixes addressing critical production issues
- Minor: incremental features and improvements
- Major: significant functionality or breaking changes

## Pre-release requirements
- All acceptance criteria met and PRs merged
- Passing CI and security scans
- Release notes drafted (Technical Writer; reviewed by Product Manager)
- Change request submitted and approved by Change Manager (required for Major releases)
- Stakeholder change notification sent by Change Manager
- Rollback / mitigation plan documented
- Smoke tests prepared

## Deployment Checklist
- [ ] Change request approved by Change Manager (Major releases)
- [ ] Stakeholder change notification sent
- [ ] Deployment window scheduled (if needed)
- [ ] Backup or snapshot (if applicable)
- [ ] Deploy to staging and run smoke tests
- [ ] Deploy to production (automated pipeline preferred)
- [ ] Run post-deploy verifications
- [ ] Announce release to stakeholders and support

## Rollback & Incident Playbook
- If a deployment fails or causes a critical issue:
  - Trigger incident response and notify on-call
  - Change Manager notifies affected stakeholders
  - Rollback to last known-good release if necessary
  - Triage root cause and capture action items

## Release Notes Template
- Release name / number:
- Date:
- Summary:
- Notable changes:
- Migration steps (if any):
- Known issues:

## Related Roles
- **Change Manager** — owns change advisory process and stakeholder notifications; see [Personas](./octoacme-roles-and-personas.md#change-manager)
- **Technical Writer** — drafts and publishes release notes; see [Personas](./octoacme-roles-and-personas.md#technical-writer)
- See also: [RACI Matrix — Release phase](./octoacme-raci-matrix.md#lifecycle-phase-release)
