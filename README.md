# Sha Sha — Design A / Heritage Bistro

Blender-built architectural concept and self-contained Three.js static website.

## Open locally

Run `python -m http.server 4173 --directory dist` from this folder, then visit http://localhost:4173. Use an HTTP server, not a file:// URL.

## Files

- `blender/Sha-Sha-Design-A.blend`: editable scene with materials, equipment and animated walkthrough camera (frames 1–460).
- `blender/build.py`: reproducible scene generator for Blender 5.2.
- `dist/assets/heritage-a.glb`: exported model used by the website.
- `dist/`: website including vendored Three.js 0.180.0.

## Controls

Choose five section stops, run/pause the guided tour, drag to look, use WASD or arrows to move along the circulation route, switch daylight/evening, or inspect cutaway. Mobile includes forward/back buttons. Reset returns to the selected section. Download the GLB from the footer.

## Scope

Design A only. Based on A01–A10 Heritage Bistro concept references. Envelope assumes 10 feet internal width, 44 feet depth and 10 feet ceiling. The model interprets the imagery; it is not a measured construction plan. Site measurements, kitchen services, equipment sizes and circulation need professional verification before construction. The walkthrough uses constrained navigation, not a physics engine. Blender's procedural materials are represented by browser-compatible PBR materials.
