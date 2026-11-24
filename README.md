# Awesome-Digital-Sculpting-Medical-3D-Modeling

markdown

## Top Digital Sculpting & Medical 3D Modeling Ecosystem



**Curated List of SaaS/Hosted & Commercial Platforms & Open-Source GitHub Projects**  

*Focused on High-Resolution Digital Sculpting, Voxel & Dynamic-Topology Mesh Modeling, Biomedical STL/DICOM 3D Reconstruction, Retopology & Browser/VR Sculpting*  

**Last updated: November 2026**



This repository tracks notable **SaaS/hosted & commercial platforms** and **open-source projects** for **Digital Sculpting & Medical 3D Modeling**. These tools sculpt, remesh, decimate, boolean-edit, segment, and reconstruct high-density organic meshes and patient-specific anatomical 3D models across desktop sculpting studios, browser WebGL canvases, VR sculpting tools, and medical DICOM-to-STL workflows.



**Examples** include ZBrush, Blender Cloud (Blender Studio), Autodesk Mudbox, Nomad Sculpt, 3D-Coat, SculptGL, Forger 3D, Autodesk Meshmixer, Shapelab, Maxon Cinema 4D, and islandmed/sculptforge (the category leaders and popular runtimes). 



**Open-source emphasis**: This section is heavily expanded with every major active project for digital sculpting & browser/desktop mesh modeling (`Blender Sculpt Mode`, `SculptGL`, `islandmed/sculptforge`, `MeshLab`, `Dust3D`, `Instant Meshes`), medical DICOM-to-3D anatomical modeling (`3D Slicer`, `ITK-SNAP`, `InVesalius 3`), and geometry-processing C++/Python libraries (`libigl`, `PyVista`, `Open3D`) — ideal for 3D character artists, biomedical engineers, surgical planning researchers, and 3D-printing makers.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saashosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Support & Share](#support--share)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[ZBrush (Maxon)](https://maxon.net)**  

  Industry-standard digital sculpting and painting platform featuring DynaMesh, ZRemesher, Sculptris Pro, and multi-million-polygon brush workflows for film, games, and medical illustration.



- **[Maxon Cinema 4D & Maxon One Cloud](https://maxon.net)**  

  Professional 3D modeling, volume-builder sculpting, and motion graphics suite featuring procedural MoGraph cloners, VDB volume meshing, and cloud asset libraries.



- **[Nomad Sculpt](https://nomadsculpt.com)**  

  High-performance portable digital sculpting and vertex-painting studio for iPad, Android, and desktop featuring voxel remeshing, dynamic topology, PBR rendering, and `.obj`/`.stl`/`.glb` export.



- **[3D-Coat & 3D-Coat Print](https://3dcoat.com)**  

  Voxel-based digital sculpting, auto-retopology, UV mapping, and PBR texturing suite engineered for organic characters, hard-surface assets, and 3D-printable models.



- **[Autodesk Mudbox](https://autodesk.com)**  

  3D digital sculpting and multi-channel texture painting software offering subdivision-level workflows, PTEX painting, and seamless Maya/3ds Max interoperability.



- **[Autodesk Meshmixer](https://meshmixer.com)**  

  Freeware triangle-mesh cleanup, hollowing, support-generation, and organic sculpting utility widely adopted in dental, prosthetic, and 3D-printing preparation pipelines.



- **[Shapelab (Leopoly)](https://shapelabvr.com)**  

  VR and desktop polygon/voxel sculpting application enabling intuitive spatial 3D modeling, dynamic tessellation, and high-resolution mesh export.



- **[Forger 3D (Maxon)](https://maxon.net)**  

  Mobile-first 3D sculpting and polygonal modeling studio bringing ZBrush-inspired brushes, symmetry, and remeshing tools to iPadOS.



- **[Blender Studio (formerly Blender Cloud)](https://blender.org)**  

  Official cloud training, production asset repository, and open-movie platform supporting the development of open-source Blender and its Sculpt Mode ecosystem.



- **[Materialise Mimics Innovation Suite (Cloud & Enterprise)](https://materialise.com)**  

  Clinical-grade medical 3D modeling and DICOM segmentation platform converting CT/MRI scans into anatomical 3D models, surgical guides, and implants.





## Open-Source GitHub Projects



- **[islandmed/sculptforge](https://github.com)**  

  Open-source digital sculpting and medical 3D modeling toolkit engineered to streamline anatomical mesh sculpting, surface refinement, and 3D modeling workflows.



- **[Blender (`blender/blender`)](https://github.com)**  

  Flagship open-source 3D creation suite featuring a high-performance Sculpt Mode with Dyntopo dynamic topology, Voxel/Quadriflow remeshing, cloth/multires brushes, and full Cycles rendering.



- **[SculptGL (`stephomi/sculptgl`)](https://github.com)**  

  Pioneering open-source WebGL digital sculpting web application supporting dynamic subdivision, voxel remeshing, PBR matcaps, symmetry, and `.obj`/`.stl`/`.ply` import/export right in the browser.



- **[3D Slicer (`Slicer/Slicer`)](https://github.com)**  

  Gold-standard open-source software platform for medical image informatics, CT/MRI DICOM segmentation, and patient-specific 3D anatomical surface mesh reconstruction.



- **[ITK-SNAP (`pyushkevich/itksnap`)](https://github.com)**  

  Interactive open-source biomedical 3D segmentation application providing active-contour (snake) 3D segmentation, manual brush sculpting across orthogonal slices, and STL/VTK mesh export.



- **[InVesalius 3 (`invesalius/invesalius3`)](https://github.com)**  

  Open-source medical imaging and 3D reconstruction software generating virtual anatomical models from CT and MRI DICOM slices for surgical planning and 3D printing.



- **[MeshLab (`cnr-isti-vclab/meshlab`)](https://github.com)**  

  Comprehensive open-source system for processing, cleaning, healing, decimating, remeshing, and inspecting large unstructured 3D triangular meshes and point clouds.



- **[Instant Meshes (`wjakob/instant-meshes`)](https://github.com)**  

  Interactive open-source field-aligned auto-retopology tool converting dense, messy sculpted meshes and medical scans into clean, animation-ready quad-dominant topology.



- **[Dust3D (`huxingyi/dust3d`)](https://github.com)**  

  Cross-platform open-source 3D modeling software enabling rapid creation of watertight, auto-rigged, UV-unwrapped organic 3D models from node-based skeletal spheres.



- **[libigl (`libigl/libigl`) & CGAL (`CGAL/cgal`)](https://github.com)**  

  Foundational open-source C++ geometry processing libraries providing discrete differential geometry, Laplacian smoothing, booleans, parameterization, and surface reconstruction algorithms.



- **[PyVista (`pyvista/pyvista`) & Open3D (`isl-org/Open3D`)](https://github.com)**  

  Modern open-source Python 3D visualization and mesh processing libraries (wrapping VTK and C++ kernels) for programmatic anatomical surface manipulation, slicing, and voxelization.



### Additional Strong Open-Source Options



- **[OpenVDB (`AcademySoftwareFoundation/openvdb`)](https://github.com)** for the Academy Award-winning open-source C++ sparse volumetric data structure powering high-resolution voxel sculpting and boolean operations.

- **[Bforartists (`Bforartists/Bforartists`)](https://github.com)** for an open-source Blender fork redesigned with an icon-driven, artist-friendly UI layout for sculpting and 3D modeling.

- **[Womp-Style SDF & Signed Distance Field Sculptors — Clayxels / libfive (`libfive/libfive`)](https://github.com)** for open-source implicit surface and Signed Distance Function (SDF) solid modeling with smooth organic blending.

- **[Manifold (`elalish/manifold`)](https://github.com)** for a blazing-fast open-source C++/WASM geometry library guaranteeing watertight, topologically valid 3D mesh booleans for medical 3D printing.

- **[Orthanc (`orthanc-server/orthanc`)](https://github.com)** for a lightweight, self-hosted open-source DICOM server storing and routing medical CT/MRI studies upstream of 3D Slicer or InVesalius.



**Frameworks for building custom systems**: Combine **3D Slicer** or **InVesalius 3** for DICOM-to-STL anatomical segmentation, **Blender Sculpt Mode + Instant Meshes + MeshLab** for high-resolution sculpting and watertight mesh cleanup, and **SculptGL** or **libigl + Manifold** for custom browser and C++/Python 3D modeling tools.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS/hosted or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Support & Share



If you find this curated list helpful, consider supporting the project:



- ⭐ **Star this repository** to help others discover it.

- 🍴 **Fork & Share** it with your team, friends, or community on X/Twitter, LinkedIn, and Reddit.

- ☕ **Buy me a coffee / Sponsor** my open-source work on [GitHub Sponsors](https://github.com) — featuring tiers for profile badges, README shoutouts, logo placements, and prioritized bug fixes/features!



[![Sponsor @ishandutta2007](https://shields.io)](https://github.com)



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

Use code with caution.

• Medical & Clinical Safety Notice: Open-source medical 3D modeling tools (3D Slicer, ITK-SNAP, InVesalius 3, MeshLab) are intended for research, visualization, and educational use only and are not FDA-cleared or CE-marked as medical devices for primary clinical diagnosis or surgical implantation.

• Note that Autodesk Meshmixer is proprietary freeware rather than open-source, while Blender, SculptGL, 3D Slicer, ITK-SNAP, InVesalius 3, and MeshLab are open-source.

Made for 3D digital sculptors, biomedical engineers, surgical planning researchers, 3D-printing makers, and open-source contributors.

Let's make digital sculpting and medical 3D modeling more open, accurate, and accessible.
