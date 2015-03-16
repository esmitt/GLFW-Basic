#Hello Triangle using GLFW

This is a basic template to use [GLFW] under Windows and Linux. The project was generated using Visual Studio 2012, and DLL libraries to GLFW (instead the static version) and the 32-bit library (instead the 64 bit version), all under Windows 8 (that really doesn't matter).

The project contains the basic draw, keyboard, initialize and resize function such as GLUT. Also, contains the definition of GLFW_DLL and the usage in Windows of 
```sh
#pragma comment
```

Functions and variables related to GLFW are encapsulated into a namespace called glfwFunc (nothing special about the name).

### Linux
To compile in Linux:

```sh
g++ main.cpp -o main.o -lGL -lGLU -lglfw3 -lX11 -lXxf86vm -lXrandr -lpthread -lXi
```

The final render is the colores triangle.
[GLFW]:http://www.glfw.org/