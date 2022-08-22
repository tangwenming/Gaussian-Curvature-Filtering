# Gaussian-Curvature-Filtering
 GCF adopts a novel multi tangent plane projection strategy to achieve Gaussian curvature minimization while preserving the meshes’ features.

The specific usage is:

1. Put the mesh to be optimized in the same root directory as GCF.exe (supported mesh formats: obj, off, stl, wrl, ply).

2. Execute commands such as: GCF.exe input_mesh.obj 40 (input_mesh.obj is the mesh to be optimized, and 40 is the number of iterations).

3. The output is GCF_input_mesh_40.off (the optimized mesh output is in the same root directory).  


GCE_LINUX is the linux (ubuntu 16.04) version of GCF. The usage is the same as the widows version. It is worth noting that please ignore the error warning message after the program is running. This is the eigen version warning and can be ignored.

The GPU version and source code will be released after the paper is published.
