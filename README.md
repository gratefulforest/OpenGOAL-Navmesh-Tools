# OpenGOAL-Navmesh-Tools
"One-Click" Monster Maker for Jak 1

Features:
- Do nothing but drag a shape to make an area monsters roam in.
- Instant menus- take no action other than choose what you want.
- Instant export- all happens in 1 second, do nothing but CTRL-V to see your monsters in game.

Instructions:
1. Install the Blender add-on.
2. Add support for [navmeshes](https://github.com/LuminarLight/LL-OpenGOAL-ModBase/commit/4f897008fa2ec8809e04c2b32d5ef9c329afede8?diff=unified&w=0). (Thanks to LuminarLight for their original navmesh implementation)
3. Go to N-Panel and export.

Behind the One-Click:
- Cleans navmesh to minimize hex limits.
- Supports untriangulated meshes.
- Formats route tables.
- Fills out monster paths.
- Links monsters with nav-meshes.
- Efficiently uses "nav-mesh-actor".
- Fills out nav-spheres on navmesh's first actor.
- Formats gap triangles.
- Re-exports update old navmeshes, future exports don't conflict.
- Prints all code in one click.
