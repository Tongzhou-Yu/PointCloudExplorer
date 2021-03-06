PointCloudExplorer
=====================

**PointCloudExplorer** is an experimental project using point cloud data on Unity by https://github.com/mattatz/PointCloudExplorer

<img src="https://raw.githubusercontent.com/mattatz/PointCloudExplorer/master/Captures/Frustum.gif" width="640">

<img src="https://raw.githubusercontent.com/mattatz/PointCloudExplorer/master/Captures/Scanline.gif" width="640">

<img src="https://raw.githubusercontent.com/mattatz/PointCloudExplorer/master/Captures/Pulse.gif" width="640">

<img src="https://raw.githubusercontent.com/mattatz/PointCloudExplorer/master/Captures/Transition.gif" width="640">

## Rendering with uniform grids

Rendering performance can be improved by dividing the point cloud into uniform grids.

![Grid](https://raw.githubusercontent.com/mattatz/PointCloudExplorer/master/Captures/Grid.gif)

PLYimporter
=====================

Keijiro's **Pcx** is merged into this project for PLY format support. https://github.com/keijiro/Pcx  
I edit 185 line of **PlyImporter.cs** in Pcx package to make PLY files readable from mesh.UploadMeshData(false); to mesh.UploadMeshData(true);  

<img src="https://github.com/Tongzhou-Yu/PointCloudExplorer/blob/main/Captures/Custom%20Point%20Cloud%20Rendering.png" width="640">

<img src="https://github.com/Tongzhou-Yu/PointCloudExplorer/blob/main/Captures/Mesh%20From%20PLY.png" width="640">

<img src="https://github.com/Tongzhou-Yu/PointCloudExplorer/blob/main/Captures/Use%20Mesh%20From%20PLY.png" width="640">

## Compatibility

Tested on Unity 2020.3.27f1c1, windows 10.

## Sources

- Standard Male Figure(CC BY 3.0) - https://clara.io/view/d49ee603-8e6c-4720-bd20-9e3d7b13978a
- Tainan Daina City(CC BY 4.0) - https://sketchfab.com/3d-models/01799eb873164aa0aa9791526f7c865d
- Hintze Hall, NHM London [point cloud](CC BY-NC 4.0) - https://sketchfab.com/3d-models/hintze-hall-nhm-london-point-cloud-be909aa8afa545118be6d36397529e2f
- Choshi-Otaki Falls, Oirase Valley, Aomori(CC BY-NC-SA 4.0) - https://sketchfab.com/3d-models/choshi-otaki-falls-oirase-valley-aomori-ea1ef9e7f82f418ea0776ceb6894ebd1

