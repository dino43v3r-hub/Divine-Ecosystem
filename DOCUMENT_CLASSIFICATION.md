# DOCUMENT_CLASSIFICATION.md

# Divine Ecosystem Document Classification Guide

**Status:** Canonical

## Purpose

This document provides a decision framework for determining where new ideas, principles, policies, architectural decisions, and project work belong within the Divine Ecosystem.

Its purpose is to preserve a clear separation between constitutional principles, architectural implementation, governance, workflow, planning, and development.

Correct classification protects the long-term stability of the project by ensuring that each document contains only the material appropriate to its purpose.

---

# Classification Questions

Every proposed addition should begin with one question:

> **What kind of idea is this?**

The answer determines where it belongs.

---

## Constitutional Principle

Ask:

* Does this establish an enduring theological or constitutional principle?
* Would it remain true if the architecture completely changed?
* Would it remain true if every application disappeared?
* Would changing it require constitutional amendment?

If yes:

→ Constitution

---

## Architectural Decision

Ask:

* Does this describe how Divine Ecosystem fulfills a constitutional principle?
* Does it define system structure, reasoning pipelines, engines, data flow, or implementation?
* Could it reasonably change as technology improves?

If yes:

→ Architecture

---

## Governance

Ask:

* Does this define project stewardship?
* Does it establish review processes, approvals, constitutional amendments, contributor responsibilities, releases, or decision-making?

If yes:

→ Governance

---

## Workflow

Ask:

* Does this describe how canonical documents are developed?
* Does it define drafting, review, verification, or approval procedures?

If yes:

→ Project Workflow

---

## Roadmap

Ask:

* Is this planned future work?
* Does it describe a future direction rather than a current principle?

If yes:

→ Roadmap

---

## Backlog

Ask:

* Is this unfinished work?
* Is it an idea that still requires discussion, discovery, or implementation?

If yes:

→ Backlog

---

# Classification Principles

When uncertainty exists:

* Enduring principles belong in the Constitution.
* Implementation belongs in Architecture.
* Stewardship belongs in Governance.
* Process belongs in Project Workflow.
* Planning belongs in the Roadmap.
* Unfinished work belongs in the Backlog.

---

# Final Test

Before adding any new material, ask:

> **If this project were completely rewritten twenty years from now, where would this idea still belong?**

The answer will normally identify the correct canonical document.
