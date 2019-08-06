# MIRACLE

Miracle是一群编程爱好者~~兼萌新~~编写的一个2D游戏引擎。  

## 构建

### 需求库

Miracle的代码并不是完全由它的编写者编写的，它使用一些库来方便编写者进行开发。  
Miracle需要以下库：

1. [GLEW](http://glew.sourceforge.net/)
2. [GLFW](http://www.glfw.org/)

你需要下载这些库的开发包（包含“包含文件”和库文件），把包含文件放入``third-party/include``文件夹内，库文件则放入``third-party/library``文件夹内。

### CMAKE

Miracle使用CMake来构建，你需要下载CMake，在该项目目录内执行命令``cmake -S . -B ./build``。  
之后CMake会在``./build``文件夹内生成用于构建本项目的平台相关的文件（Linux下通常是``Makefile``，Windows下通常是``*.sln``）。接下来你需要使用自己平台的方法构建此项目。
