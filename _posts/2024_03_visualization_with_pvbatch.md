## Visualization with pvbatch

This article is a quick guide on paraview, its file formats, and visualization using pvbatch.

---

#### ParaView

ParaView is a powerful visualization and image processing tool that is widely used in scientific computing and CFD community. Paraview is built on top of the Visualization Toolkit (VTK).

#### vtk

VTK is primarily written in C++. It offers functionalities for creating, rendering, and interating with 3D visualizations. VTK supports various file formats, they can be divided into two catagories: 1. legacy, serial format; 2. XML formats. 


#### File format


##### pvd
```bash
<?xml version="1.0"?>
<VTKFile type="Collection" version="0.1" ByteOrder="LittleEndian">
  <Collection>
    <DataSet timestep="0" group="" part="0" file="solution-00000.pvtu"/>
  </Collection>
</VTKFile>
```
##### pvtu

##### vtu


References

https://docs.vtk.org/en/latest/design_documents/VTKFileFormats.html
