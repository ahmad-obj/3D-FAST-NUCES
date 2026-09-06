# Campus Reconstruction Foundation Design

Date: 2026-09-06
Status: Approved foundation; production temporarily frozen for workflow testing

## Objective
Reconstruct the FAST-NUCES Islamabad campus as a high-quality, proportionally accurate 3D environment suitable for both cinematic Blender output and optimized real-time use.

## Approved architecture
1. Maintain one authoritative high-quality Blender master.
2. Derive optimized real-time exports/LODs from that master; do not independently remodel a separate real-time campus.
3. Establish the entire campus first as an accurate low-detail/blockout model.
4. Validate campus-wide footprints, placement, orientation, heights, roads, paths, terrain, and major spatial relationships before extensive detailing.
5. After the blockout is accepted, refine one building at a time.
6. Use maps, user-supplied photographs, direct measurements when available, and free reconstruction/photogrammetry tools as evidence.
7. Prefer evidence-driven reconstruction over unconstrained AI generation for campus-critical geometry.
8. Reuse common architectural/environment assets where appropriate without sacrificing campus-specific accuracy.
9. Keep major decisions, evidence assumptions, status, and workflow changes documented for future agents.
10. Unknown or weakly supported geometry must be marked as uncertain rather than silently invented.

## Development order
- Foundation and documentation
- Evidence collection
- Campus geospatial/site reconstruction
- Full low-detail campus blockout
- Blockout validation
- First building taken through the complete high-quality pipeline
- Workflow review and improvement
- Scale the validated workflow to the remaining campus
- Environment/detail passes
- Optimization and derived real-time exports

## Quality strategy
The project does not attempt to reproduce a proprietary image-to-3D generator by prompt alone. Quality should come from combining:
- disciplined reference analysis;
- proportion and scale validation;
- Blender modeling;
- photogrammetry/reconstruction where useful;
- reusable procedural/manual techniques;
- repeated visual comparison against real photographs;
- a project-specific skill/workflow refined from experiments.

## Current deviation: building-quality experiment
The production campus reconstruction is intentionally frozen before implementation.

A separate experimental track will test how well a building can be reconstructed in Blender from photographs supplied by the user. The experiment exists to discover, benchmark, and improve the eventual production workflow. Experimental geometry is not campus production geometry unless explicitly promoted after review.

## Persistent project principle
Accuracy first, detail second. A beautiful but proportionally incorrect campus is considered a failure; a correct blockout is the required foundation for later visual quality.