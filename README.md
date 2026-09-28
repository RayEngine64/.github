# RayEngine64

**Modern ray-traced rendering for N64 recompilation projects, built on and extending RT64.**

RayEngine64 explores how modern rendering techniques can be integrated into recompilation-based Nintendo 64 games while preserving the visual identity, geometry, materials, and character of the originals.

It builds on the excellent foundation provided by **RT64** and extends it with an experimental rendering architecture focused on modern lighting, hardware ray tracing, atmospheric effects, temporal reconstruction, and reusable support across recompilation projects.

## Current development

The main RayEngine64 project is currently developed here:

**[charyou/rayengine64](https://github.com/charyou/rayengine64)**

This organization serves as the home for future RayEngine64-related tools, integrations, patchers, documentation, and supporting projects.

## Current focus

- Hardware ray tracing
- Ray-traced sun and local lighting
- Ambient occlusion and sky lighting
- Indirect lighting and reconstruction
- Atmospheric rendering
- Temporal reconstruction
- Renderer diagnostics and developer tooling
- Reusable support across N64 recompilation projects

## Philosophy

RayEngine64 is not intended to simply make N64 games look more modern.

The goal is to add modern rendering capabilities in a way that respects the original art direction and works with the limited information available from reconstructed N64 rendering pipelines.

That means treating modern rendering as an extension of the original presentation rather than a replacement for it.

## Credits

RayEngine64 is built on top of **RT64**, which provides the renderer foundation and much of the underlying infrastructure that makes this work possible.

RT64:
https://github.com/rt64/rt64

RayEngine64 would not exist without the work of the RT64 and N64 recompilation communities.

## Status

RayEngine64 is experimental and under active development.

APIs, compatibility, rendering techniques, tooling, and repository structure may change significantly as the project matures.
