transform-feedback-particle-system
==================================

An example of how to calculate and render particles on the GPU with OpenGL 3.2 and transform feedback. This is one of many ways implementing a GPU based particle system. Transform feedback enables us to read output variables of the vertex shader. Other (more elegant) solutions include the use of [compute shader](http://www.opengl.org/wiki/Compute_Shader) or [OpenCL](http://www.khronos.org/opencl/).

![Animation of particle system](https://github.com/bestimmaa/transform-feedback-particle-system/blob/master/animation.gif?raw=true)


Note: This code is messy and contains a lot of dependencies listed in the base project at https://github.com/bestimmaa/CGFramework.
