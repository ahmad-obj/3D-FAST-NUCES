# AGENTS.md

This repository is the long-term reconstruction of the FAST-NUCES Islamabad campus in 3D.

## Required reading before any work
1. `README.md`
2. `docs/STATUS.md`
3. `docs/superpowers/specs/2026-09-06-campus-reconstruction-foundation-design.md`

## Core rules
- Blender is the authoritative source of truth for the campus model.
- Maintain one high-quality master campus; derive optimized real-time outputs from it.
- Accuracy comes before detail.
- Build and validate the full campus blockout before campus-wide detailing.
- Refine one building at a time after the blockout is accepted.
- Use maps, measurements, photographs, and free reconstruction tools as evidence.
- Never silently invent uncertain architecture. Mark uncertain geometry/documentation explicitly.
- Keep major decisions, status changes, evidence assumptions, and workflow changes documented in the repository.
- Experimental quality tests must remain separate from the production campus model until explicitly promoted.

## Current project state
The main campus reconstruction is intentionally FROZEN while a separate building-quality experiment is used to evaluate how far the Blender workflow can be pushed from supplied photographs.

See `docs/STATUS.md` for the live state.