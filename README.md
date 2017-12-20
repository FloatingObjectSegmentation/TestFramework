## What is it?

TestFramework is a simple framework for object segmentation, built on the basis of PCL. Its purpose is to be the basis of further research on a master thesis.

The goal is to:

- **Support a small range of segmentation methods for .pcd files**. This is a TODO.
- **Transforming a .pcd file into a labeled pointcloud of segments should be easy - by a single method call. The method call should be easily changeable**. This is a TODO.
- **Have support for LAS files**. There is currently no way of doing this within PCL. Plugins exist that integrate LibLAS, and will probably be added to the project at some point.
- **Support visualization**. Visualization is supported through PCL.


## Installation instructions

##### The only currently supported platform is Windows, Visual Studio 2013 x86

1. Install Visual Studio 2013 x86
2. Download the PCL 1.8.0 Visual Studio 2013 x86 installer
[here](
https://onedrive.live.com/?authkey=%21ANl0c3A-90fFJ8k&cid=EC9EBB2646FF189A&id=EC9EBB2646FF189A%2151752&parId=EC9EBB2646FF189A%2151744&action=locate).
3. Install using default settings. This way CMake will automatically find out where the headers, libraries and Dlls are.
4. Install CMake version > 3.1.0
5. Generate a new project using CMake
6. Move OpenNI.dll to the solution directory
7. Open the project in Visual Studio 2013, build and run it.

## Usage

#### Configuration

- Currently configured through variables in the code.
