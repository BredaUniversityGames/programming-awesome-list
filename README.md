# BUas Game Programming awesome list

A curated list of useful tools, libraries, resources all around the topic of game development / game programming for the [Games](https://www.buas.nl/en/games) course at [Breda University of Applied Sciences](https://www.buas.nl/en/games).

## Content
- [Tools](#tools)
- [Libraries & Frameworks](#libraries--frameworks)
  - [Graphics](#graphics)
  - [ECS](#ecs)
  - [Scripting Languages](#scripting-languages)
  - [C interface languages](#c-interface-languages)
  - [AI](#ai)
  - [Math](#math)
  - [XML Json](#json-xml)
  - [Physics](#physic)
  - [Networking](#networking)
  - [Other](#other)
 - [Engines Plugins](#engines-plugins)
 - [Resources](#resources)
    - [Video](#videos)
    - [Books](#books)
    - [Articles](#articles--papers)
    - [Websites, Blogs, Webtools](#websites-blogs-webtools)
    - [Courses](#courses)
  - [Other Awesome lists](#other-awesome-lists)

## Tools
- [Jenkins](https://www.jenkins.io/) - Easy to install CI and CD solution.
- [GitHub Actions](https://github.com/features/actions) GitHub CI and CD
- [Resharper](https://www.jetbrains.com/resharper-cpp/) Support you with your work in Visual Studio (Student licence available)
- [Visual Assist](https://www.wholetomato.com/features) Improvements to Visual Studio like Resharper. (Student licence available)
  - [Visual Assist for UE4](https://www.wholetomato.com/visual-assist-ue4-unreal-engine) 
- [VS Code](https://code.visualstudio.com/)
  - [VS Code C++](https://code.visualstudio.com/docs/languages/cpp)
  - [VS Code rust](https://levelup.gitconnected.com/rust-with-visual-studio-code-46404befed8)
- [Premake](https://premake.github.io/) Simple LUA based powerfully simple build configuration tool.
- [CMake](https://cmake.org/) Powerfull Meta Build System, to build build systems
- [Clang](https://clang.llvm.org/)
  - [Use Clang in Visual Studios](https://docs.microsoft.com/en-us/cpp/build/clang-support-msbuild?view=msvc-160)
  - [Clang Tooling](https://clang.llvm.org/docs/Tooling.html) Different parts of clang explanation/starting page
    - [ClangFormt](https://clang.llvm.org/docs/ClangFormat.html) fromat your code
    - [ClangCheck](https://clang.llvm.org/docs/ClangCheck.html) check your code 
    - [AddressSanitizer](https://clang.llvm.org/docs/AddressSanitizer.html) check for memory issues
      - [AddressSanitizer (ASan) for Windows with MSVC](https://devblogs.microsoft.com/cppblog/addresssanitizer-asan-for-windows-with-msvc/)
- [Devkitpro](https://github.com/devkitPro) Retro Game Dev
- [VLD](https://github.com/KindDragon/vld) Visual Leak Detector
- [Tiled Map Editor](https://www.mapeditor.org/) A flexible level editor 2D tiled map
- [Rust Analyzer](https://github.com/rust-analyzer/rust-analyzer) rust-analyzer is an experimental modular compiler frontend for the Rust language.
- [RenderDoc](https://renderdoc.org/) Render Debugger
- [NVIDIA® Nsight™ Graphics](https://developer.nvidia.com/nsight-graphics) is a standalone developer tool that enables you to debug, profile, and export frames built with Direct3D (11, 12, DXR), Vulkan (1.2, NV Vulkan Ray Tracing Extension), OpenGL, OpenVR, and the Oculus SDK.
- [MTuner](https://github.com/milostosic/MTuner)  is a C/C++ memory profiler and memory leak finder for Windows, PlayStation 4 and 3, Android and other platforms
- [optick](https://github.com/bombomby/optick) C++ Profiler For Games
- [Agones](https://github.com/googleforgames/agones) Host, Run and Scale dedicated game servers on Kubernetes
- [Circle Language](https://github.com/seanbaxter/circle) The C++ Automation Language, C++17 with meta (reflection) and Shader support (C++ in shaders)
- [DDS](https://github.com/vector-of-bool/dds) dds - A Build System and Library Manager
- [Mantis Bug Tracker](https://github.com/mantisbt/mantisbt) (PHP)
- [evoke](https://github.com/dascandy/evoke) Magical Build System



## Libraries & Frameworks:

### Graphics

#### C / C++
- [Dear IMGUI](https://github.com/ocornut/imgui) the immediate mode GUI
- [sokol](https://github.com/floooh/sokol) Simple STB-style cross-platform libraries for C and C++, written in C.
- [bgfx](https://github.com/bkaradzic/bgfx) (Bring Your Own Engine/Framework) Cross-platform, graphics API agnostic, "Bring Your Own Engine/Framework" style rendering library.
- **stb**
  - [stb_image.h](https://github.com/nothings/stb/blob/master/stb_image.h) image loader
  - [stb_image_write.h](https://github.com/nothings/stb/blob/master/stb_image_write.h) image writer
  - [stb_image_resize.h](stb_image_resize.h) image resizer
  - [stb_truetype.h](stb_truetype.h) font text rasterizer
 - [DirectXShaderCompiler](https://github.com/microsoft/DirectXShaderCompiler) This repo hosts the source for the DirectX Shader Compiler which is based on LLVM/Clang.
- [Assimp](https://github.com/assimp/assimp) The official Open-Asset-Importer-Library Repository. Loads 40+ 3D-file-formats into one unified and clean data structure.
- [DiligentEngine](https://github.com/DiligentGraphics/DiligentEngine) A modern cross-platform low-level graphics library and rendering framework


#### rust
- [rust-gpu](https://github.com/EmbarkStudios/rust-gpu) - Making Rust a first-class language and ecosystem for GPU code
- [egui](https://github.com/emilk/egui) - egui: an easy-to-use immediate mode GUI in pure Rust
- [gpu-allocator](https://github.com/Traverse-Research/gpu-allocator) - Memory allocator written in Rust for Vulkan and DX12
- [rspirv-reflect](https://github.com/Traverse-Research/rspirv-reflect) - SPIR-V reflection library written in Rust
- [hassle-rs](https://github.com/Traverse-Research/hassle-rs) - Rust bindings for the DirectXShaderCompiler library

### ECS

#### C / C++
- [EnTT](https://github.com/skypjack/entt) - Gaming meets modern C++ - a fast and reliable entity component system (ECS) and much more
- [flecs](https://github.com/SanderMertens/flecs) -A fast entity component system (ECS) for C & C++
- [EntityX](https://github.com/alecthomas/entityx)

#### rust
- [bevy](https://github.com/bevyengine/bevy) Engine but ECS driven
- [legion](https://github.com/amethyst/legion) High performance Rust ECS library

### C#
- [Unity's DOTS](https://unity.com/dots)
- [Svelto.ECS](https://github.com/sebas77/Svelto.ECS) - Svelto ECS C# Lightweight Data Oriented Entity Component System Framework
- [Entitas-CSharp](https://github.com/sschmid/Entitas-CSharp) -Entitas is a super fast Entity Component System (ECS) Framework specifically made for C# and Unity

### Scripting Languages
- [wren](https://wren.io/) - minimal scripting language OOP
- [lua](http://www.lua.org/)
  - [Sol2 Lua binding](https://github.com/ThePhD/sol2) Sol3 (sol2 v3.0) - a C++ <-> Lua API wrapper with advanced features and top notch performance
 - [ChaiScript](https://github.com/ChaiScript/ChaiScript)

### C Interface languages
- [rust](http://rustlang.org/)
- [zig](https://ziglang.org/) Zig is a general-purpose programming language and toolchain for maintaining robust, optimal, and reusable software. Can bind to C / C++
- [vlang](https://vlang.io/) Simple, fast, safe, compiled. For developing maintainable software. Can compile to c
- [Odin](https://github.com/odin-lang)
  - [How to bind to C](https://github.com/odin-lang/Odin/wiki/binding-to-c)

### Math

#### C++
- [DirectXMath](https://github.com/Microsoft/DirectXMath)
- [glm](https://github.com/g-truc/glm) OpenGL Mathematics (GLM)
- [eigen](https://github.com/PX4/eigen) Eigen is a C++ template library for linear algebra: matrices, vectors, numerical solvers, and related algorithms. http://eigen.tuxfamily.org/
- [google/mathfu](https://github.com/google/mathfu) C++ math library developed primarily for games focused on simplicity and efficiency.

### JSON, XML

#### C++
- [PugiXML](https://github.com/zeux/pugixml) Light-weight, simple and fast XML parser for C++ with XPath support
- [JsonCpp](https://github.com/open-source-parsers/jsoncpp) A C++ library for interacting with JSON.
- [tmxlite](https://github.com/fallahn/tmxlite) lightweight C++14 parser for Tiled tmx files
- [nlohmann/json](https://github.com/nlohmann/json) JSON for Modern C++ (not very fast but simple)
- [rapidjson](https://rapidjson.org/) fast but complicated JSON lib

### Physic

#### C++
- [Box2D](https://box2d.org/) A 2D Physics Engine for Games
- [PhysX](https://github.com/NVIDIAGameWorks/PhysX) NVIDIA PhysX SDK
- [projectchrono](https://projectchrono.org/) An Open Source Multi-physics Simulation Engine
- [ReactPhysics3D](https://www.reactphysics3d.com/) C++ physics engine library for 3D simulations and games

### AI
*nothing yet*

### Networking

### C/C++
- [ValveSoftware/GameNetworkingSockets](https://github.com/ValveSoftware/GameNetworkingSockets) Reliable & unreliable messages over UDP. Robust message fragmentation & reassembly. Encryption.
- [ENet](http://enet.bespin.org/) ENet's purpose is to provide a relatively thin, simple and robust network communication layer on top of UDP (User Datagram Protocol).The primary feature it provides is optional reliable, in-order delivery of packets.
- [Message oriented networking library using TCP transport.](https://github.com/bkaradzic/bnet#bnet---message-oriented-networking-library)
- [librg](https://github.com/zpl-c/librg) Single-header cross-platform world replication in pure C99.

### rust
- [libpnet/libpnet](https://github.com/libpnet/libpnet) — A cross-platform, low level networking
- [smoltcp-rs/smoltcp](https://github.com/smoltcp-rs/smoltcp) — A standalone, event-driven TCP/IP stack that is designed for bare-metal, real-time systems
- [tokio-rs/tokio](https://github.com/tokio-rs/tokio) — A network application framework for rapid development and highly scalable production deployments of clients and servers.
- [dylanmckay/protocol](https://github.com/dylanmckay/protocol) — Custom TCP/UDP protocol definitions
- [actix/actix](https://github.com/actix/actix) — Actor library for Rust

### Other

- [Libclang for Python](https://pypi.org/project/libclang/) Much simpeler python api

#### C# / Unity
- [Steamworks wrapper for Unity / C#](https://github.com/rlabrecque/Steamworks.NET)

#### C / C++
- [fmod](https://www.fmod.com/) proprietary audio lib
- [Portaudio](http://www.portaudio.com/) PortAudio is a free, cross-platform, open-source, audio I/O library.
- [OpenAL](https://openal.org/) OpenAL is a cross-platform three-dimensional audio API.
- [Asio](https://think-async.com/) Asio is a cross-platform C++ library for network and low-level I/O programming that provides developers with a consistent asynchronous model using a modern C++ approach.
- [stb](https://github.com/nothings/stb) stb single-file public domain libraries for C/C++
- [cereal](https://uscilab.github.io/cereal/) A C++11 library for serialization
- [Rttr](https://rttr.org) C++ Reflection Library
- [spdlog](https://github.com/gabime/spdlog) Fast C++ logging library. 
- [copperspice](https://www.copperspice.com/) Like QT but OpenSource, GUI library
- [SFML](https://www.sfml-dev.org/) Simple and Fast Multimedia Library, Easy for quick prototyping
- [Steamworks SDK](https://partner.steamgames.com/doc/sdk)
- [STX](https://github.com/lamarrr/STX) C++17 & C++ 20 error-handling and utility extensions
- [C++ frame profiler](https://github.com/wolfpld/tracy) C++ frame profiler
- [Scope Guard & Defer C++](https://github.com/Neargye/scope_guard)
- [fmt](https://github.com/fmtlib/fmt) A modern formatting library
- [quill](https://github.com/odygrd/quill) Asynchronous Low Latency C++ Logging Library
- [rocket](https://github.com/tripleslash/rocket) rocket - Fast single header signal/slots library for C++
- [cxxopts](https://github.com/jarro2783/cxxopts) Lightweight C++ command line option parser

##### C++ Common Libs
- [EASTL](https://github.com/electronicarts/EASTL) Electronic Arts Standard Template Library. It is an extensive and robust implementation that has an emphasis on high performance.
- [abseil](https://github.com/abseil/abseil-cpp) Googles C++ STD extensions (fast hasmaps)
- [folly](https://github.com/facebook/folly) Facebook's C++ STD extensions (fast hashmaps)
  - [F14 Hash Table](https://github.com/facebook/folly/blob/master/folly/container/F14.md)
- [Guidelines Support Library](https://github.com/microsoft/GSL) The Guidelines Support Library (GSL) contains functions and types that are suggested for use by the C++ Core Guidelines maintained by the Standard C++ Foundation. This repo contains Microsoft's implementation of GSL. (C++14)
- [eventpp](https://github.com/wqking/eventpp) Event Dispatcher and callback list for C++
- [cli](https://github.com/daniele77/cli) A library for interactive command line interfaces in modern C++
 
#### Web Technolgy
- [BabylonJS](https://www.babylonjs.com/) -About
Babylon.js is a powerful, beautiful, simple, and open game and rendering engine packed into a friendly JavaScript framework.
- [ThreeJS](https://threejs.org/) - JavaScript 3D library.
## Engines Plugins
### Unreal Engine Plugins
- [Discord Messenger](https://unrealengine.com/marketplace/en-US/product/discord-messenger)
### Unity Plugins
## Resources
### Videos

*AI*
- [Winding Road Ahead: Designing Utility AI with Curvature](https://www.youtube.com/watch?v=TCf1GdRrerw) Tools: Debugging, Designing etc with Curvature

*Graphics*
- [Introduction to Computer Graphics](https://youtu.be/vLSphLtKQ0o) Introduction to Computer Graphics.
School of Computing, University of Utah.
- [Computer Graphics (CMU 15-462/662)](https://www.youtube.com/playlist?list=PL9_jI1bdZmz2emSh0UQ5iOdT2xRHFHL7E) Lecture videos for the introductory Computer Graphics class at Carnegie Mellon University.

*C++*
- [Cᐩᐩ Weekly With Jason Turner](https://www.youtube.com/user/lefticus1/playlists) C++ Weeklies
- [CppCon](https://www.youtube.com/user/CppCon) Biggest C++ Conference
- [Meeting C++](https://www.youtube.com/user/MeetingCPP) Biggest C++ Conference in Europe (Berlin) (Take students as volunteers)
- [Cpp Now](https://www.youtube.com/user/BoostCon)
- [CopperSpice](https://www.youtube.com/channel/UC-lNlWEq0kpMcThO-I81ZdQ) Move Semantics, Multi Threading, C++17, Templates, Modern C++
- [Building a C++ Reflection System in One Weekend Using Clang and LLVM - Arvid Gerstmann](https://www.youtube.com/watch?v=XoYVeduK4yI)

*Game Dev*
- [GDC](https://www.youtube.com/channel/UC0JB7TSe49lg56u6qH8y_MQ)
- [GDC Vault](https://www.gdcvault.com/)
- [Adopting Continuous Delivery (In Sea of Thieves) - GDC talk](https://youtube.com/watch?v=cKfz2nEgaX8) QA CI/CD
- [Horizon Zero Dawn: A QA Open World Case Study - GDC talk](https://youtube.com/watch?v=2VDlX3Dqm0w) QA CI/CD
- [https://www.youtube.com/watch?v=SHinxAhv1ZE](https://www.youtube.com/watch?v=SHinxAhv1ZE) GDC
- [Math for Game Programmers: Fast and Funky 1D Nonlinear Transformations](https://www.youtube.com/watch?v=mr5xkf6zSzk&t=2s) GDC
- [Build Great Tools: Workflow Guidelines from Vicarious Visions](https://www.youtube.com/watch?v=XUjAs92UUP4) GDC - UI / UX For tools programming

*Data Oriented Design*
- [Overwatch Gameplay Architecture and Netcode](https://www.youtube.com/watch?v=W3aieHjyNvw) (Blizzard, GDC)
- [Data-Oriented Design and C++](https://www.youtube.com/watch?v=rX0ItVEVjHc) (Mike Acton, CppCon)
- [CPU caches and why you care](https://vimeo.com/97337258) (Scott Meyers, NDC)
- [Culling the Battlefield: Data Oriented Design in Practice](https://www.gdcvault.com/play/1014491/Culling-the-Battlefield-Data-Oriented) (DICE, GDC)
- [Game Engine Entity/Object systems](https://www.youtube.com/watch?v=jjEsB611kxs) (Bobby Anguelov, presentation)
- [Understanding Data Oriented Design for Entity Component Systems](https://www.youtube.com/watch?v=0_Byw9UMn9g) (Unity, GDC)

*Network*
- [Physics for Game Programmers : Networking for Physics Programmers](https://www.gdcvault.com/play/1022195/Physics-for-Game-Programmers-Networking) (Glenn Fiedler)
- [Networking in C++ Part #1: MMO Client/Server, ASIO & Framework Basics](https://www.youtube.com/watch?v=2hNdkYInj4g)
- [Overwatch Gameplay Architecture and Netcode](https://www.youtube.com/watch?v=W3aieHjyNvw)
- [World of Warcraft's Network Serialization and Routing](https://www.youtube.com/watch?v=hCsEHYwjqVE)
- [I Shot You First: Networking the Gameplay of Halo: Reach](https://www.youtube.com/watch?v=h47zZrqjgLc)
- [Move fast and don't break things: High-performance networking in Rust — Joshua Liebow-Feeser](https://www.youtube.com/watch?v=UfMOOxOGCmA)

*CMake*
- [Modern Cmake: An introduction](https://www.youtube.com/watch?v=bDdkJu-nVTo&t=538s)
- [CppCon 2017: Mathieu Ropert “Using Modern CMake Patterns to Enforce a Good Modular Design”](https://www.youtube.com/watch?v=eC9-iRN2b04)
- [C++Now 2017: Daniel Pfeifer “Effective CMake"](https://www.youtube.com/watch?v=bsXLMQ6WgIk&t=2693s)

*Computer Siences*
- [MIT 6.006 Introduction to Algorithms](https://www.youtube.com/watch?v=HtSuA80QTyo)
- [So you want to write an interpreter?](https://www.youtube.com/watch?v=LCslqgM48D4)
- [How to Build a Virtual Machine](https://www.youtube.com/watch?v=OjaAToVkoTw)

*Others*
- [Kubernetes Tutorial for Beginners [FULL COURSE in 4 Hours]](https://www.youtube.com/watch?v=X48VuDVv0do)

### Books
- [Ray tracing in a weekend](https://raytracing.github.io/books/RayTracingInOneWeekend.html)
- [Data-Oriented Design Book](https://www.dataorienteddesign.com/dodbook/) (In BUas Lib)
- [Open Data Structures](http://opendatastructures.org/)
- [Mazes for programmers](http://www.mazesforprogrammers.com/)
- [Raytracing Gems](https://www.realtimerendering.com/raytracinggems/)
- [Real-Time Rendering](https://www.realtimerendering.com/)  (In BUas Lib)
- [Calculus Volume 1](https://openstax.org/details/books/calculus-volume-1)
- [Mastering C++ Multithreading](https://www.packtpub.com/product/mastering-c-multithreading/9781787121706)
- [Network Programming with Rust](https://www.packtpub.com/product/network-programming-with-rust/9781788624893)
- [Multiplayer Game Programming: Architecting Networked Games](https://www.oreilly.com/library/view/multiplayer-game-programming/9780134034355/)  (In BUas Lib)
- [The Fundamentals of C/C++ Game Programming: Using Target-based Development on SBC's](http://scratchpadgames.net/Book.html) If you work on the Raspberry pi
- [Foundations of Game Engine Development](https://foundationsofgameenginedev.com) Book Series
  - [Volume 1: Mathematics 1st Edition](https://foundationsofgameenginedev.com/#fged1)
  - [Volume 2: Rendering](https://foundationsofgameenginedev.com/#fged2)
  - [Volume 3: Models & Materials](https://foundationsofgameenginedev.com/#fged3)
  - [Volume 4: Physics](https://foundationsofgameenginedev.com/#fged4)
- [Effective Modern C++ by Scott Meyers](https://www.oreilly.com/library/view/effective-modern-c/9781491908419/) Covers Modern C++ 11,14,17 Topics: e.g., auto type declarations, move semantics, lambda expressions, and concurrency support, template

### Articles / Papers
*Graphics*
- [Moving Frostbite to Physically Based Rendering 3.0](https://seblagarde.files.wordpress.com/2015/07/course_notes_moving_frostbite_to_pbr_v32.pdf)
- [Advances in Real-Time Rendering in 3D Graphics and Games](http://advances.realtimerendering.com/)  SIGGRAPH courses slides
- [Real-Time Physically Based Rendering and BRDFs](https://mechanicsfoundry.github.io/Physically-Based-Rendering-and-BRDFs/)
- [Linear Interpolation](https://www.alanzucconi.com/2021/01/24/linear-interpolation/)
- [Pixels? Triangles? What’s the difference? — How (I think) Nanite renderes a demo with 10¹¹ tris](https://www.reddit.com/r/hardware/comments/gkcd9b/pixels_triangles_whats_the_difference_how_i_think/)
- [Vulkan Shader Resource Binding](https://developer.nvidia.com/vulkan-shader-resource-binding)
- [Tutorials and Documents by Anders Lindqvist](https://www.breakin.se/learn/index.html)
- [Publications by Peter-Pike Sloan](https://www.ppsloan.org/publications/)

*Data Oriented Design*

- [ECS Faq](https://github.com/SanderMertens/ecs-faq) - Frequently asked questions about Entity Component Systems
- [Understanding Data Oriented Design](https://learn.unity.com/tutorial/part-1-understand-data-oriented-design?courseId=60132919edbc2a56f9d439c3&signup=true&uv=2020.1) (Unity, Tutorial)
- [Entities, Components and Systems](https://medium.com/ingeniouslysimple/entities-components-and-systems-89c31464240d) (Mark Jordan, blog)
- [Why Vanilla ECS is not enough](https://ajmmertens.medium.com/why-vanilla-ecs-is-not-enough-d7ed4e3bebe5) (Sander Mertens, blog)
- [Formalisation of Concepts behind ECS and Entitas](https://medium.com/@icex33/formalisation-of-concepts-behind-ecs-and-entitas-8efe535d9516) (Maxim Zaks, blog)
- [Entity Component System and Rendering](https://ourmachinery.com/post/ecs-and-rendering/) (Our Machinery, blog)
- [Specs and Legion, two very different approaches to ECS](https://csherratt.github.io/blog/posts/specs-and-legion/) (Cora Sherrat, blog)
- [Archetypes and Vectorization](https://medium.com/@ajmmertens/building-an-ecs-2-archetypes-and-vectorization-fe21690805f9) (Sander Mertens, blog)
- [ECS back & forth](https://skypjack.github.io/2019-02-14-ecs-baf-part-1/) (Michele Caini, blog series)

*Algorithms, Data Structures*
- [Sparse Set](https://www.geeksforgeeks.org/sparse-set/) (Geeks for Geeks)
- [Hibitset](https://docs.rs/hibitset/0.6.3/hibitset/) (DOCS.RS)
- [Perlin Noise](https://adrianb.io/2014/08/09/perlinnoise.html) Understanding Perlin Noise
- [Perlin Noise](https://www.khanacademy.org/computing/computer-programming/programming-natural-simulations/programming-noise/a/perlin-noise) khanacademy article
- [The Wavefunction Collapse Algorithm explained very clearly](https://robertheaton.com/2018/12/17/wavefunction-collapse-algorithm)
- [Open-sourcing F14 for faster, more memory-efficient hash tables](https://engineering.fb.com/2019/04/25/developer-tools/f14/)

*Physics*
- [Physics Info](https://physics.info/)
- [Visualizing the GJK Collision detection algorithm](https://www.haroldserrano.com/blog/visualizing-the-gjk-collision-algorithm)
- [realtimerendering: intersections](http://www.realtimerendering.com/intersections.html)
- [Geometrics](https://www.geometrictools.com/Samples/Geometrics.html)

*Networking & Enycription*
- [Security analysis of DTLS 1.2
implementations](https://www.cs.ru.nl/bachelors-theses/2018/Niels_Drueten___4496604___Security_analysis_of_DTLS_1_2_implementations.pdf)
- [1500 Archers on a 28.8: Network Programming in Age of Empires and Beyond](https://www.gamasutra.com/view/feature/131503/1500_archers_on_a_288_network_.php) Lockstep
- [Lockstep multiplayer first steps](https://blog.gemserk.com/2016/08/30/lockstep-multiplayer-first-steps/)

*Others*
- [HOW TO IMPLEMENT A NODE-BASED SCRIPTING LANGUAGE](http://gamepipeline.com/how-to-implement-a-node-based-scripting-language-part-1/) Good overview of the foundation
- [Let’s Build A Simple Interpreter. Part 1.](https://ruslanspivak.com/lsbasi-part1/) Can be adpoted to C/C++
- [craftinginterpreters](https://craftinginterpreters.com/introduction.html)
- [Write your Own Virtual Machine](https://justinmeiners.github.io/lc3-vm/) for LC3 Assembly
- [Getting started Libclang](https://shaharmike.com/cpp/libclang/)
- [retro game dev gba tutorials](https://www.coranac.com/tonc/text/toc.htm)And the best gba tutorials ever if peopel are really enthusiastic
- [AddressSanitizer for Windows: x64 and Debug Build Support](https://devblogs.microsoft.com/cppblog/asan-for-windows-x64-and-debug-build-support/)
- [Bit-level operations – bit flags and bit masks](https://blog.podkalicki.com/bit-level-operations-bit-flags-and-bit-masks/)
- [Multithreading - C++17 and C++20](http://www.modernescpp.com/index.php/category/multithreading-c-17-and-c-20) Collection of Articles, General Puprose not specific game dev
- [Multithreading - Memory Model](http://www.modernescpp.com/index.php/category/multithreading-memory-model)  Collection of Articles, General Puprose not specific game dev
- [Multithreading - Applications](http://www.modernescpp.com/index.php/category/multithreading-application)  Collection of Articles, General Puprose not specific game dev
- [How to debug in rust with VS Code](https://www.forrestthewoods.com/blog/how-to-debug-rust-with-visual-studio-code/)
- [Using Git Sparse Checkout](https://briancoyner.github.io/articles/2013-06-05-git-sparse-checkout/)
- [How C++ Resolves a Function Call](https://preshing.com/20210315/how-cpp-resolves-a-function-call/)

### Websites, Blogs, Webtools
*Algorithms, Data Structures*
- [Red Blob Games](https://www.redblobgames.com/) hex grid, A*, grids, graphs
- [Maze Generation Serires](http://weblog.jamisbuck.org/2010/12/27/maze-generation-recursive-backtracking)

*C++*
- [Fluent C++](https://www.fluentcpp.com/)
- [C++ Core Guidelines](https://isocpp.github.io/CppCoreGuidelines/CppCoreGuidelines)
- [Cpp Cast](https://cppcast.com/) a C++ Podcast
- [Modern C++](http://www.modernescpp.com/) A blog full of good sources

*Rust*
- [rust book](https://doc.rust-lang.org/book/) Learn rust
- [Rust in a Week](https://this-week-in-rust.org/) Learn rust in a week
- [Rust Times](https://rusttimes.com/) News, Jobs, Articles
- [Crates](https://crates.io/) Rust Packes search online

*Graphics*
- [Ray tracing in a weekend - website](https://raytracing.github.io/)
- [3D Game Engine Programming](https://www.3dgep.com/) Direct X 12
  - [Learning DirectX12](https://github.com/jpvanoosten/LearningDirectX12) GitRepo
- [Graphics Programming Weekly](https://www.jendrikillner.com/post/) over 150 posts about Graphics Programming
  - [Graphics Programming Article database](https://www.jendrikillner.com/article_database/)
- [Vulkan Diagrams](https://github.com/David-DiGioia/vulkan-diagrams) Diagrams showing relationships between Vulkan objects and how they're used.
- [learnopengl.com](https://learnopengl.com/) A great place to start learning OpenGL
- [opengl-tutorial.org](http://www.opengl-tutorial.org/) A great collection of OpenGL Tutorials
- [Scratchapixel 2.0](https://www.scratchapixel.com/) Learn Computer Graphics From Scratch!

*Web tools*
- [Compiler Explorer](https://godbolt.org/) - lets you compile many different languages such as C,C++ or rust and inspect the Assembly or test
- [CPP Insights](https://cppinsights.io/) - Shows you what the compiler does with your C++ code. How does a for each loop looks to the compiler?
- [Quick Benchmarks](https://quick-bench.com/) Quick benchmarks online
- [Quick Builld](https://build-bench.com/#) Check build times of your code
- [Shader Toy](https://www.shadertoy.com/) Play with shaders in the browser

*Others*
- [gafferongames](https://gafferongames.com/) All around Network programming
- [Openstax](https://openstax.org) Free High quality Textbooks

### Courses
- [Jenkins Essential Training (linkedin)](https://www.linkedin.com/learning/jenkins-essential-training/from-code-to-production-with-jenkins?u=36359204)
- [Programming Natural-Simulations](https://www.khanacademy.org/computing/computer-programming/programming-natural-simulations) In JavaScript but can be transferd to C/C++, rust , C#
- [Trigonometry - khanacademy](https://www.khanacademy.org/math/trigonometry)
- [Geometry - khanacademy](https://www.khanacademy.org/math/geometry)
- [Precalculus - khanacademy](https://www.khanacademy.org/math/precalculus)
- [Linear-Algebra - khanacademy](https://www.khanacademy.org/math/linear-algebra)
- [Calculus AB - khanacademy](https://www.khanacademy.org/math/ap-calculus-ab)
- [Calculus BC - khanacademy](https://www.khanacademy.org/math/ap-calculus-bc)
- [Refresher Physics khanacademy](https://www.khanacademy.org/science/high-school-physics)
- [Physics 1 khanacademy](https://www.khanacademy.org/science/ap-physics-1)
- [Network Programming with Rust: The Course Overview | packtpub.com](https://www.youtube.com/watch?v=K7hlPhtAZ48&list=PLTgRMOcmRb3M2fbwAgclKI0yt4uVchwZH)
## Other (Awesome) lists
- [Memory Managment](https://gist.github.com/simonrenger/d1da2a10d11f8a971fc6f1b574ab3e99)
- [Magic Tools - A Game Programming list](https://github.com/ellisonleao/magictools)
- [Unity List](https://github.com/RyanNielson/awesome-unity#readme)
- [Game Talks](https://github.com/hzoo/awesome-gametalks#readme)
- [Awesome Entity Component System](https://github.com/jslee02/awesome-entity-component-system) (Jeongseok Lee, link collection)
- [C++ Links a link collection by MattPD](https://github.com/MattPD/cpplinks)
  - [Memory Performance Tools](https://github.com/MattPD/cpplinks/blob/master/performance.tools.md#memory) a list by [MattPD](https://github.com/MattPD)
  - [Atomics, lock free, memory model](https://github.com/MattPD/cpplinks/blob/master/atomics.lockfree.memory_model.md) a list by [MattPD](https://github.com/MattPD)
  - [Cache](https://github.com/MattPD/cpplinks/blob/master/comparch.micro.channels.md#cache) a list by [MattPD](https://github.com/MattPD)
  - [Prefetch](https://github.com/MattPD/cpplinks/blob/master/comparch.micro.channels.md#prefetch) a list by [MattPD](https://github.com/MattPD)
  - [Memory Bus](https://github.com/MattPD/cpplinks/blob/master/comparch.micro.channels.md#memory-bus) a list by [MattPD](https://github.com/MattPD)
 - [gamedev libraries](https://github.com/raizam/gamedev_libraries) collection of C / C++ libs for game devs
 - [Awesome CMake](https://github.com/onqtam/awesome-cmake) A curated list of awesome CMake resources, scripts, modules and examples.
