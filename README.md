# Master thesis

**Title :** Exploring Trajectory Planning in Volume Rendering alongside Transfer Function Interpolation based on Perceptually Uniform Color Spaces

<p align="center">
  <img src="https://github.com/user-attachments/assets/b3d43643-d3f2-4b20-bf39-6048dcc919ac" width=70%/>  
</p>
<p align="center">
Figure 1: Diagram illustrating the volume visualization pipeline for the video export framework presented in this master thesis.
</p>


## Abstract
Creation of fluid and visually appealing animations is a crucial factor for the effective communication of ideas and concepts. In this context, this thesis visualises and animates volumetric data used, for example, in pre-operative planning, material analysis and promotional content, among others. For this purpose techniques for camera path planning and for the export of high-quality videos were designed and implemented using the Visualisation Toolkit (VTK) in C++. Furthermore, a method for interpolation of transfer functions is presented that allows to isolate regions of interest that may change over time during the animation. Another research focus addresses a gap in the literature regarding the use of perceptually uniform color spaces in this context. Such color spaces have the potential to produce more accurate and perceptually consistent color transitions. We compare transfer functions defined in CIERGB with those using perceptually uniform color spaces such as ProLAB and CIELAB, as well as custom spaces designed specifically to minimize the CIEDE2000 color difference. The evaluation of the presented techniques shows the effectiveness of this framework in different scenarios and provides a solid basis for future research on perceptually uniform colour spaces in volume rendering.
