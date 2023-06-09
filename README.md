# Geodesics_in_heat
A C++ implementation of geodesic distance computation on triangular meshes based on the paper "Geodesics in Heat:A New Approach to Computing Distance Based on Heat Flow" by Keenan Crane et al. using the Visualization and Computer Graphics Library
![alt text](https://github.com/IasonManolas/Geodesics_in_heat/blob/master/fertility.png)

# Build

- Build System: [xmake](https://xmake.io/#/guide/installation)
- Compilation Toolchain: [Visual Studio](https://visualstudio.microsoft.com/)（If Visual Studio is not needed, you can download the [Microsoft C++ Build Tools](https://visualstudio.microsoft.com/visual-cpp-build-tools/)）

> It is recommended to install Visual Studio in the default directory.

Clone repo, then try:
```sh
xmake -y
```

You need to put your model file in `src/main:46` before run.

```sh
xmake run
```
