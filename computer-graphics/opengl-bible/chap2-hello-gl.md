# Chapter 2 - Hello OpenGL

## Basic concepts

- `OpenGL`: Open Graphics Library - A library that exposes simple API in such a way that programmers can manipulate hardware under the machine without going into too much detail. It's not too abstract, but enough to work with.
- `GLFW`: An open souce library that supports creates windows, attach context and things that are not related to the graphic itself. Its purpose is to bridge from OpenGL to the OS. it is cross-platform.
- All examples in this documentation will be represented in `PyOpenGL` and `GLFW`.

## GLFW - Basic

Example: https://github.com/huyqut/bootcamp-opengl/blob/master/application.py

- `glfw.window_hint(target, hint)`: Sets the specified window hint to the desired value. Wrapper for: `void glfwWindowHint(int target, int hint);`

