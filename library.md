- [Graphics](computer-graphics#Library)



## Memory
- [TCMalloc](https://github.com/google/tcmalloc) is Google's customized implementation of C's malloc() and C++'s operator new used for memory allocation within our C and C++ code. TCMalloc is a fast, multi-threaded malloc implementation.
- [jemalloc](https://github.com/jemalloc/jemalloc) is a general purpose malloc(3) implementation that emphasizes
fragmentation avoidance and scalable concurrency support. 



## I/O Event 
- [libevent](https://github.com/libevent/libevent) – an event notification library
- [libev](http://software.schmorp.de/pkg/libev.html), libuv 的 unix 部分曾以此为基础
- [libuv](https://github.com/libuv/libuv) Cross-platform asynchronous I/O https://libuv.org/
  - [An Introduction to libuv](https://github.com/nikhilm/uvbook)
  - [libuv 初窥](http://blog.codingnow.com/2012/01/libuv.html) - 云风的 BLOG
  - [Learn uv](https://github.com/thlorenz/learnuv) for fun and profit, a self guided workshop to the library that powers Node.js.



## [Coroutine](https://en.wikipedia.org/wiki/Coroutine)
- [Protothreads](http://dunkels.com/adam/pt/index.html)
  - [zserge/pt](https://github.com/zserge/pt)
- [Libco](https://github.com/Tencent/libco) is a c/c++ coroutine library that is widely used in WeChat services. It has been running on tens of thousands of machines since 2013.
- [libaco](https://github.com/hnes/libaco) - A blazing fast and lightweight C asymmetric coroutine library.
- [libdill](http://libdill.org/index.html): Structured Concurrency for C



## Serialization
- [protocolbuffers/protobuf](https://github.com/protocolbuffers/protobuf) - Google's data interchange format https://developers.google.com/protocol-buffers/
  - [protobuf.js](https://github.com/protobufjs/protobuf.js) Protocol Buffers for JavaScript (& TypeScript).
  - [protocolbuffers/upb](https://github.com/protocolbuffers/upb) a small protobuf implementation in C
  - [nanopb](https://github.com/nanopb/nanopb), Protocol Buffers with small code size https://jpa.kapsi.fi/nanopb/
- [google/flatbuffers](https://github.com/google/flatbuffers): Memory Efficient Serialization Library http://google.github.io/flatbuffers/



## GUI
- [Immediate mode GUI](https://en.wikipedia.org/wiki/Immediate_mode_GUI) in computer graphics is a GUI implemented using an immediate mode pattern, where the event processing is directly controlled by the application.
  - [Retained Mode Versus Immediate Mode](https://docs.microsoft.com/en-us/windows/win32/learnwin32/retained-mode-versus-immediate-mode)
  - [Slate UI Framework - Motivation](https://docs.unrealengine.com/en-US/Programming/Slate/Architecture/index.html)
  - [@游戏开发者，ImGUI 能成为 GUI 的未来吗？](https://mp.weixin.qq.com/s?__biz=MjM5MjAwODM4MA==&mid=2650721530&idx=3&sn=f5ba60b684705c1621d834eb2480648b)
- [Dear ImGui](https://github.com/ocornut/imgui): Bloat-free Immediate Mode Graphical User interface for C++ with minimal dependencies
  - [imgui_club](https://github.com/ocornut/imgui_club) Nice things to use along dear imgui
  - [imgui-node-editor](https://github.com/thedmd/imgui-node-editor), This is an implementaion of node editor with ImGui-like API. Project purpose is to serve as a basis for more complex solutions like blueprint editors.
  - [ImGuizmo](https://github.com/CedricGuillemet/ImGuizmo), Immediate mode 3D gizmo for scene editing and other controls based on Dear Imgui
  - [imgui_markdown](https://github.com/juliettef/imgui_markdown) Markdown for Dear ImGui
  - [cimgui](https://github.com/cimgui/cimgui) This is a thin c-api wrapper programmatically generated for the excellent C++ immediate mode gui Dear ImGui.
  - [imgui-go](https://github.com/inkyblackness/imgui-go) This library is a Go wrapper for Dear ImGui.
    - [giu](https://github.com/AllenDang/giu) Cross platform rapid GUI framework for golang based on imgui and the great golang binding imgui-go.
  - [love-imgui](https://github.com/slages/love-imgui) imgui module for the LÖVE game engine
  - [Native ImGui in the Browser](https://pbrfrat.com/post/imgui_in_browser.html)
- [Nuklear](https://github.com/Immediate-Mode-UI/Nuklear) A single-header ANSI C immediate mode cross-platform GUI library
  - [vurtun/nuklear](https://github.com/vurtun/nuklear) Archived
  - [golang-ui/nuklear](https://github.com/golang-ui/nuklear) This project provides Go bindings for nuklear.h — a small ANSI C GUI library. https://github.com/vurtun/nuklear
- [libui](https://github.com/andlabs/libui): a portable GUI library for C
- [nanogui](https://github.com/wjakob/nanogui) Minimalistic GUI library for OpenGL
- [microui](https://github.com/rxi/microui) Tiny immediate-mode UI library

