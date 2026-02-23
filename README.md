VGPlatform Public Incident Knowledge Base

Public incident summaries exported from VGPlatform, a local-first AI/OPS and reliability platform.

This repository contains sanitized incident knowledge for research, reliability engineering, and DevOps learning.

What is VGPlatform

VGPlatform is an experimental local-first platform focused on:

• incident capture
• automated diagnostics
• incident intelligence
• reliability learning
• knowledge accumulation

It converts operational failures into structured, searchable knowledge.

Repository contents

Each incident contains:

public/
  summary.public.md
  manifest.public.json
summary.public.md

Human-readable incident summary

Contains:

• incident ID
• timestamp
• component
• symptoms
• high-level context

No private data.

manifest.public.json

Machine-readable metadata:

• incident_id
• module
• timestamp
• checksum
• export metadata

Used for automated analysis and incident intelligence.

Privacy and Security

This repository contains:

✔ sanitized data only
✔ no private environment details
✔ no raw logs
✔ no secrets
✔ no credentials

VGPlatform export pipeline removes sensitive information.

Purpose

This repository exists to:

• share reliability knowledge
• enable incident intelligence research
• support DevOps learning
• demonstrate local-first incident intelligence

Incident Intelligence Vision

VGPlatform treats incidents as learning events.

Instead of losing operational knowledge, incidents become:

• searchable
• comparable
• reusable
• analyzable

This enables future automated root-cause assistance.

Status

Experimental research platform

Active development

License

MIT License

Maintained by

VGPlatform project
