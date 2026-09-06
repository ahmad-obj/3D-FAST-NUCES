# Experiments

This directory is for workflow and quality tests that are not part of the authoritative FAST campus model.

## Current experiment — Gropius House photo reconstruction benchmark
Target: Gropius House, Lincoln, Massachusetts.

Primary reference set: the public `Photos Through the Years` gallery on gropius.house.

### Benchmark protocol
1. Reconstruct the exterior from photographs only.
2. Do not use the site's blueprints/floor plans to set geometry during the blind reconstruction pass.
3. After the photo-only model reaches a stable result, reveal the site's original blueprints/floor plans and use them as ground truth for quantitative validation.
4. Record major proportion errors, geometry errors, missing details, material/lighting shortcomings, and workflow bottlenecks.
5. Refine the workflow/skill from the measured failures before applying lessons to FAST campus production.

The website contains multiple historical and current exterior viewpoints plus interior imagery, while its separate construction section contains original blueprints. This makes it suitable as a controlled reconstruction benchmark.

## Isolation rule
Nothing in this directory becomes production campus geometry merely because it looks good. Techniques may be promoted after evaluation; geometry/assets require explicit review before entering the authoritative campus project.

Important experiment findings should later be summarized into the project's permanent workflow documentation.
