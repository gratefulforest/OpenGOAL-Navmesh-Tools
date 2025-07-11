# OpenGOAL-Navmesh-Tools

![Static Badge](https://img.shields.io/badge/language-python-%23306998) ![Static Badge](https://img.shields.io/badge/language-opengoal-yellow) ![Static Badge](https://img.shields.io/badge/one%20click%20export-blue)

**One-Click Monster Maker for Jak 1**

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
- Correctly formats all monster path points.
- Fills out route tables and bitpacks them.
- Types out all nav-spheres on navmesh’s first actors.
- Uses “nav-mesh-actor” for secondary actors.
- Redraws navmesh with minimum points to avoid hex limits.
- Fills out jump triangles based on painted regions.
- Re-exports update old navmeshes, future exports don't conflict.
- Handles everything in a way where 1 click generates all finished code.
