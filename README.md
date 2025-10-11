# NavSwarms

NavSwarms is a Unreal plugin to provide 3D pathfinding for Unreal Engine 5. Primarily designed for baking large voxel grids, and using the provided ANavSwarmsManager to queue pathfinding queries using an optimized custom A* algorithm.

This plugin is focused on providing an easy and efficient way to manage aerial AI which needs a system that is not covered by the Unreal native AI navigation system.

Key features:
- Navigation Manager Actor for configuring the map navigation grid
- API to manage pathfinding queries and retrieve finished paths
- Threaded pathfinding which can run continuously or just once
- Baked pathfinding grid, allowing fast load on large maps
- Efficient debug visualization of grid size, occupied voxels and even current paths


## Getting started

Simply drag the contents to the `Plugins` folder on your Unreal project, if there's no `Plugins` folder you can create a new folder with that exact name. Make sure that Visual Studio 2022 is also installed with the `game development with C++` modules.

Locate the `.uproject` of your project, right click and select `Generate Visual Studio Project`

Finally go to Edit->Plugins and make sure that the plugin is enabled, if it is already enabled don't worry, you can just skip this step.

## Future features

- Placeable volume Actor or component to dynamically change movable objects
- Infinite world support
- Custom AI nodes