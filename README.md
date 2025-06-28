# OpenGOAL-Navmesh-Tools
"One-Click" Monster Maker for Jak 1

![2025-06-2817-05-33-ezgif com-video-to-gif-converter](https://github.com/user-attachments/assets/5125c12d-e60c-4292-8ff6-e150484fafed)

Features:
- Do nothing but drag a shape to make an area monsters roam in.
- Instant menus: Take no action other than decide what you want.
- Instant export: All code formatted in 1 second, do nothing but CTRL-V to see your monsters in game.

Instructions:
1. Drag the .zip file on Blender.
2. Add support for [navmeshes](https://github.com/LuminarLight/LL-OpenGOAL-ModBase/commit/4f897008fa2ec8809e04c2b32d5ef9c329afede8?diff=unified&w=0). (Thanks to LuminarLight for their original navmesh implementation)
3. Go to right of 3D view and export.

Behind the One-Click:
- Redraws your shape with minimum points.
- Clear info statements for hex limits.
- Supports quads and triangles.
- Correctly formats all monster path points.
- Calculates route in bitpacked format.
- Handles monster/nav-mesh relationships.
- Uses "nav-mesh-actor" for secondary actors.
- Types out nav-spheres on navmesh's first actors.
- Marks gap trianlges based on painted regions.
- Re-exports update old navmeshes, future exports don't conflict.
- Handles everything in a way where 1 click generates all finished code.
