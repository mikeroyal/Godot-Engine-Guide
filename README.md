<h1 align="center">
 <img src="https://user-images.githubusercontent.com/45159366/147890939-356a7e63-42d3-448c-9b53-2bc2e412e461.png">
  <br />
Godot Engine Guide
</h1>

#### A guide covering Godot Engine including the applications, libraries and tools that will make you a better and more efficient Godot Engine development.

**Note: You can easily convert this markdown file to a PDF in [VSCode](https://code.visualstudio.com/) using this handy extension [Markdown PDF](https://marketplace.visualstudio.com/items?itemName=yzane.markdown-pdf).**

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/147890949-3ef6d54a-1507-4ace-9379-f96df20559f7.png">
  <br />
</p>


# Table of Contents

1. [Getting Started with Godot Engine](https://github.com/mikeroyal/Godot-Engine-Guide#Augmented-Reality-AR--Virtual-Reality-VR-learning-resources)

2. [VS Code Development](https://github.com/mikeroyal/Godot-Engine-Guide#vs-code-development)

    - [VS Code Extensions for Developer Productivity](https://github.com/mikeroyal/Godot-Engine-Guide#vs-code-Extensions-for-Developer-Productivity)

3. [Xcode Development](https://github.com/mikeroyal/Godot-Engine-Guide#)

4. [Game Development](https://github.com/mikeroyal/Godot-Engine-Guide#game-development)

5. [Augmented Reality (AR) & Virtual Reality (VR) ](https://github.com/mikeroyal/Godot-Engine-Guide#Augmented-Reality-AR--Virtual-Reality-VR-tools-and-frameworks)

6. [Vulkan Development](https://github.com/mikeroyal/Godot-Engine-Guide#vulkan-development)

7. [C/C++ Development](https://github.com/mikeroyal/Godot-Engine-Guide#cc-development)

8. [C# Development](https://github.com/mikeroyal/Godot-Engine-Guide#c-development)

9. [Python Development](https://github.com/mikeroyal/Godot-Engine-Guide#python-development)

10. [Lua Development](https://github.com/mikeroyal/Godot-Engine-Guide#lua-development)

11. [Networking](https://github.com/mikeroyal/Godot-Engine-Guide#networking)

# Getting Started with Godot
[Back to the Top](https://github.com/mikeroyal/Godot-Engine-Guide#table-of-contents)

[Godot Engine](https://godotengine.org/) is a feature-packed, cross-platform game engine to create 2D and 3D games from a unified interface. It provides a comprehensive set of common tools, so that you can focus on making games without having to reinvent the wheel. Checkout the [Godot Engine Documentation](https://docs.godotengine.org/) for moe info.

[If you would like to Donate to the Godot Project](https://www.patreon.com/godotengine)

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/104788134-3f85e980-5746-11eb-94c4-d97165ee888b.jpeg">
  <br />
  Godot Engine
</p>

[Godot Asset Library](https://godotengine.org/asset-library/asset)

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/147890951-0aa968e8-7651-4536-9148-afa40c7fea4f.png">
  <br />
  Godot Asset Library
</p>

[Introduction to Godot Engine](https://docs.godotengine.org/en/latest/getting_started/introduction/index.html#introduction)

[Godot Engine GitHub](https://github.com/godotengine)

[Supported languages for Godot Engine](https://docs.godotengine.org/en/latest/tutorials/scripting/gdnative/what_is_gdnative.html#supported-languages)

[GDNative](https://docs.godotengine.org/en/latest/tutorials/scripting/gdnative/what_is_gdnative.html#what-is-gdnative) is a Godot-specific technology that lets the engine interact with native [shared libraries](https://en.wikipedia.org/wiki/Library_(computing)#Shared_libraries) at run-time. You can use it to run native code without compiling it with the engine. GDNative is not a scripting language and has no relation to [GDScript](https://docs.godotengine.org/en/latest/tutorials/scripting/gdscript/gdscript_basics.html#doc-gdscript).

**Community supported languages for Godot Engine**

The bindings below are developed and maintained by the community (may not be production-ready):

[Python](https://github.com/touilleMan/godot-python)

[Rust](https://github.com/godot-rust/godot-rust)

[Kotlin](https://github.com/utopia-rise/godot-kotlin)

[D](https://github.com/godot-d/godot-d)

[Nim](https://github.com/pragmagic/godot-nim)

# VS Code Development
[Back to the Top](https://github.com/mikeroyal/Godot-Engine-Guide#table-of-contents)
<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/140833078-77973dcf-d3a6-421f-b6a7-b6e63fb1e97c.png">
  <br />
</p>

## Getting Started with VS Code

[Visual Studio Code](https://code.visualstudio.com) is a lightweight but powerful source code editor which runs on your desktop and is available for Windows, macOS and Linux. It comes with built-in support for JavaScript, TypeScript and Node.js and has a rich ecosystem of extensions for other languages (such as C++, C#, Java, Python, PHP, Go) and runtimes (such as .NET and Unity).

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/140832435-49e53589-e9e1-47fe-a1bd-d9800cfc1274.png">
<br />
VS Code
</p>

[Visual Studio Marketplace](https://marketplace.visualstudio.com/VSCode) is a marketplace for all extensions for Visual Studio, Azure DevOps Services, Azure DevOps Server and Visual Studio Code.

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/140832440-0247a088-4eeb-4c57-ae7d-90894d56d629.png">
<br />
VS Code Marketplace
</p>


[VS Code Documentation](https://code.visualstudio.com/docs)

[Working with GitHub in VS Code](https://code.visualstudio.com/docs/editor/github)

[Code Server](https://coder.com/) is a tool that allows you to run [VS Code](https://code.visualstudio.com/) on any machine anywhere and access it in the browser.

[GitHub Codespaces](https://docs.github.com/en/free-pro-team@latest/github/developing-online-with-codespaces) is an integrated development environment(IDE) on GitHub. That allows developers to develop entirely in the cloud using Visual Studio and Visual Studio Code. Also, from any repo or pull request on GitHub you can simply press the period (.) key on your keyboard to bring up the browser-based VS Code environment with the source code file ready for editing. That dot (.) press to bring up the web-based VS Code editor takes you to https://github.dev/.

[Language Server Protocol (LSP)](https://microsoft.github.io/language-server-protocol/) is a tool that defines the protocol used between an editor or IDE and a language server that provides language features like auto complete, go to definition, find all references.

### VS Code Extensions for Developer Productivity

[Visual Studio Live Share](https://visualstudio.microsoft.com/services/live-share/) is a service/ extension that enables you to collaboratively edit and debug with others in real time, regardless of the programming languages you're using or app types you're building. You can instantly and securely share your current project, start a joint debugging session, share terminal instances, forward localhost web apps, have voice calls, and more.

[GistPad](https://marketplace.visualstudio.com/items?itemName=vsls-contrib.gistfs) is a Visual Studio Code extension that allows you to edit GitHub Gists and repositories from the comfort of your favorite editor. You can open, create, delete, fork and star gists and repositories, and then seamlessly begin editing files as if they were local, without ever cloning, pushing or pulling anything.

[Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer) is an extension for Visual Studio Code that launches a development local Server with live reload feature for static & dynamic pages.

[GitHub Pull Requests and Issues](https://marketplace.visualstudio.com/items?itemName=GitHub.vscode-pull-request-github) is an extension for Visual Studio Code that allows you to review and manage GitHub pull requests and issues in Visual Studio Code.

[Terminal](https://marketplace.visualstudio.com/items?itemName=formulahendry.terminal) is an extension for Visual Studio Code that lets you run terminal command directly in the Editor.

[Profile Switcher](https://marketplace.visualstudio.com/items?itemName=aaronpowell.vscode-profile-switcher) is an extension for Visual Studio Code that allows you to switch between different profiles you have created.

[Material Icon Theme](https://marketplace.visualstudio.com/items?itemName=PKief.material-icon-theme) is an extension for Visual Studio Code that gets the Material Design icons into your VS Code.

[One Dark Pro](https://marketplace.visualstudio.com/items?itemName=zhuangtongfa.Material-theme) is an extension for Visual Studio Code that adds Atom's iconic One Dark theme, which is one of the most installed themes for VS Code.

[VSCode Icons](https://marketplace.visualstudio.com/items?itemName=vscode-icons-team.vscode-icons) is an extension for Visual Studio Code that brings icons to your Visual Studio Code setup.

[GitLens](https://marketplace.visualstudio.com/items?itemName=eamodio.gitlens) is an extension for Visual Studio Code that helps you visualize code authorship at a glance via Git blame annotations and code lens, seamlessly navigate and explore Git repositories, gain valuable insights via powerful comparison commands, and so much more.

[Import Cost](https://marketplace.visualstudio.com/items?itemName=wix.vscode-import-cost) is an extension for Visual Studio Code that will display inline in the editor the size of the imported/required package. The extension utilizes webpack with babili-webpack-plugin in order to detect the imported size.

[Markdown All in One](https://marketplace.visualstudio.com/items?itemName=yzhang.markdown-all-in-one) is an extension for Visual Studio Code that gives you everything you need to write Markdown (keyboard shortcuts, table of contents, auto preview and more).

[Bracket Pair Colorizer](https://marketplace.visualstudio.com/items?itemName=CoenraadS.bracket-pair-colorizer) is an extension for Visual Studio Code that allows matching brackets to be identified with colours. The user can define which characters to match, and which colours to use.

[Auto Rename Tag](https://marketplace.visualstudio.com/items?itemName=formulahendry.auto-rename-tag) is an extension for Visual Studio Code that automatically add HTML/XML close tag, same as Visual Studio IDE or Sublime Text.

[Auto-Close Tag](https://marketplace.visualstudio.com/items?itemName=formulahendry.auto-close-tag) is an extension for Visual Studio Code that automatically add HTML/XML close tag, same as Visual Studio IDE or Sublime Text does.

[Settings Sync](https://marketplace.visualstudio.com/items?itemName=Shan.code-settings-sync) is an extension for Visual Studio Code that synchronizes Settings, Snippets, Themes, File Icons, Launch, Keybindings, Workspaces and Extensions Across Multiple Machines Using GitHub Gist.

[Bookmarks](https://marketplace.visualstudio.com/items?itemName=alefragnani.Bookmarks) is an extension for Visual Studio Code that lets you mark lines of code and jump to them.

[Better Comments](https://marketplace.visualstudio.com/items?itemName=aaron-bond.better-comments) is an extension for Visual Studio Code that improves your code commenting by annotating with alert, informational, TODOs, and more.

[Code Spell Checker](https://marketplace.visualstudio.com/items?itemName=streetsidesoftware.code-spell-checker) is an extension for Visual Studio Code that works as a spelling checker for source code.

[CSS Peak](https://marketplace.visualstudio.com/items?itemName=pranaygp.vscode-css-peek) is an extension for Visual Studio Code that allows peeking to css ID and class strings as definitions from html files to respective CSS. It also allows peek and goto definition.

[Tailwind CSS IntelliSense](https://marketplace.visualstudio.com/items?itemName=bradlc.vscode-tailwindcss) is an extension for Visual Studio Code that enhances the Tailwind development experience by providing Visual Studio Code users with advanced features such as autocomplete, syntax highlighting, and linting.

[Prettier](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode) is an extension for Visual Studio Code that is an opinionated code formatter. It enforces a consistent style by parsing your code and re-printing it with its own rules that take the maximum line length into account, wrapping code when necessary.

[NPM Intellisense](https://marketplace.visualstudio.com/items?itemName=christian-kohler.npm-intellisense) is an extension for Visual Studio Code that autocompletes npm modules in import statements.

[Path Intellisense](https://marketplace.visualstudio.com/items?itemName=christian-kohler.path-intellisense) is an extension for Visual Studio Code that autocompletes filenames.

[Relative Path](https://marketplace.visualstudio.com/items?itemName=jakob101.RelativePath) is an extension for Visual Studio Code that gets the relative url paths from files in the current workspace.

[Path Autocomplete](https://marketplace.visualstudio.com/items?itemName=ionutvmi.path-autocomplete) is an extension for Visual Studio Code that provides path completion for visual studio code.

[Discord Presence](https://marketplace.visualstudio.com/items?itemName=icrawl.discord-vscode) is an extension for Visual Studio Code that updates your discord status with a rich presence.

[Code Runner](https://marketplace.visualstudio.com/items?itemName=formulahendry.code-runner) is an extension for Visual Studio Code that runs code snippets or code files for multiple languages: C/C++, Java, JavaScript, PHP, Python, Perl, Ruby, Go, Lua, Groovy, PowerShell, BASH/SH, C#, F#, .NET Core, TypeScript, CoffeeScript, Scala, Swift, Julia, OCaml, R, Elixir, Clojure, Haxe, Objective-C, Rust, Racket, Scheme, Kotlin, Dart, Haskell, Nim, D, CUDA, and custom command.

[Kite](https://marketplace.visualstudio.com/items?itemName=kiteco.kite) is an extension for Visual Studio Code that provides an AI-powered programming assistant that helps you write code faster inside Visual Studio Code. Kite works for all major programming languages: Python, Java, Go, PHP, C/C#/C++, Javascript, HTML/CSS, Typescript, React, Ruby, Scala, Kotlin, Bash, Vue and React.

[Tabnine](https://marketplace.visualstudio.com/items?itemName=TabNine.tabnine-vscode) is an extension for Visual Studio Code that provides an AI code completion tool trusted by millions of developers to code faster with fewer errors. Whether you are a new dev or a seasoned pro, working solo or part of a team, Tabnine will help push your productivity to new heights while cutting your QA time in your favorite IDE.

# Xcode Development
[Back to the Top](https://github.com/mikeroyal/Godot-Engine-Guide#table-of-contents)

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/141201793-f31f4899-7317-49a7-808b-6e551df23bf9.png">
  <br />
  Xcode Guide
</p>

## Getting Started with Xcode

[Apple Developer Documentation for Xcode](https://developer.apple.com/documentation/xcode)

[Xcode](https://developer.apple.com/xcode/) includes everything developers need to create great applications for Mac, iPhone, iPad, Apple TV, and Apple Watch. Xcode provides developers a unified workflow for user interface design, coding, testing, and debugging. Xcode 12 is built as an Universal app that runs 100% natively on Intel-based CPUs and Apple Silicon. It includes a unified macOS SDK that features all the frameworks, compilers, debuggers, and other tools you need to build apps that run natively on Apple Silicon and the Intel x86_64 CPU.

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/110880054-dd9fb700-8292-11eb-9478-a5d62dc76f9d.png">
<br />
Developing with SwiftUI in Xcode 12
</p>

[Xcode Cloud](https://developer.apple.com/xcode-cloud/) is a continuous integration and delivery service built into Xcode and designed expressly for Apple developers. It accelerates the development and delivery of high-quality apps by bringing together cloud-based tools that help you build apps, run automated tests in parallel, deliver apps to testers, and view and manage user feedback.

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/121821101-9cc98c80-cc4b-11eb-9dde-e3efa2ea8154.png">
<br />
</p>

**Xcode Cloud. Source: [Apple](https://developer.apple.com/xcode-cloud/)**

[SwiftUI](https://developer.apple.com/documentation/swiftui) is a user interface toolkit that provides views, controls, and layout structures for declaring your app's user interface. The SwiftUI framework provides event handlers for delivering taps, gestures, and other types of input to your application.

[UIKit](https://developer.apple.com/documentation/uikit) is a framework provides the required infrastructure for your iOS or tvOS apps. It provides the window and view architecture for implementing your interface, the event handling infrastructure for delivering Multi-Touch and other types of input to your app, and the main run loop needed to manage interactions among the user, the system, and your app.

[AppKit](https://developer.apple.com/documentation/appkit) is a graphical user interface toolkit that contains all the objects you need to implement the user interface for a macOS app such as windows, panels, buttons, menus, scrollers, and text fields, and it handles all the details for you as it efficiently draws on the screen, communicates with hardware devices and screen buffers, clears areas of the screen before drawing, and clips views.

[ARKit](https://developer.apple.com/augmented-reality/arkit/) is a set set of software development tools to enable developers to build augmented-reality apps for iOS developed by Apple. The latest version ARKit 3.5 takes advantage of the new LiDAR Scanner and depth sensing system on iPad Pro(2020) to support a new generation of AR apps that use Scene Geometry for enhanced scene understanding and object occlusion.

[RealityKit](https://developer.apple.com/documentation/realitykit) is a framework to implement high-performance 3D simulation and rendering with information provided by the ARKit framework to seamlessly integrate virtual objects into the real world.

[SceneKit](https://developer.apple.com/scenekit/) is a high-level 3D graphics framework that helps you create 3D animated scenes and effects in your iOS apps.

[Mac Catalyst](https://developer.apple.com/mac-catalyst/) is a set of Apple APIs that developers can use to rapidly port their iOS apps to [Apple Silicon M1 Chip](https://www.apple.com/mac/m1/) and take full advantage of the new capabilities on the new Apple hardware.

[Instruments](https://help.apple.com/instruments/mac/current/#/dev7b09c84f5) is a powerful and flexible performance-analysis and testing tool that’s part of the Xcode tool set. It’s designed to help you profile your iOS, watchOS, tvOS, and macOS apps, processes, and devices in order to better understand and optimize their behavior and performance.

[TestFlight](https://developer.apple.com/testflight/) is a tool that makes it easy to invite users to test your apps and App Clips and collect valuable feedback before releasing your apps on the App Store. It allows you to invite up to 10,000 testers using just their email address or by sharing a public link.

## Xcode Developer Platforms for Apps

[macOS](https://www.apple.com/macos/monterey/) is an advanced desktop operating system (OS) for Apple's series of desktops and laptops.

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/121821090-8d4a4380-cc4b-11eb-896a-74e1be0fb3c6.png">
<br />
</p>

**macOS Monterey. Source: [Apple](https://www.apple.com/macos/monterey/)**

[iOS](https://www.apple.com/ios/ios-15/) is an advanced mobile operating system (OS) for Apple's series of iPhone products.

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/121821096-976c4200-cc4b-11eb-9006-641b1c99a9e7.png">
<br />
</p>

**iOS 15. Source: [Apple](https://www.apple.com/ios/ios-15/)**

[iPadOS](https://www.apple.com/ipados/ipados-15/) is an advanced mobile operating system (OS) for Apple's series of iPad products.

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/121821093-93402480-cc4b-11eb-9a02-42e75c811c39.png">
<br />
</p>

**iPadOS 15. Source: [Apple](https://www.apple.com/ipados/ipados-15/)**

[WatchOS](https://www.apple.com/watchos/watchos-8/) is an advanced mobile operating system (OS) for Apple's series of Watch products.

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/121821100-9b985f80-cc4b-11eb-9c10-1e3aac33feda.png">
<br />
</p>

**WatchOS 8. Source: [Apple](https://www.apple.com/watchos/watchos-8/)**

[tvOS](https://developer.apple.com/tvos/) is an advanced mobile operating system (OS) for Apple's series of TV products.

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/141201806-71144a22-879d-474a-a7ef-45ace396584c.png">
<br />
</p>

**tvOS 15. Source: [Apple](https://developer.apple.com/tvos/)**

# Game Development
[Back to the Top](https://github.com/mikeroyal/Godot-Engine-Guide#table-of-contents)

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/97361059-45151700-185c-11eb-9d12-dae51c79eb8a.png">
  <br />
</p>

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/119279021-ea6b5000-bbdd-11eb-9f59-5251fc3ac751.png">
  <br />
</p>

## Game Development Tools

[NVIDIA Reflex](https://developer.nvidia.com/reflex/get-started) is a new feature that was introduced with the RTX 30(3000) series GPUs that allows game developers to implement a low latency mode that aligns game engine work to complete just-in-time for rendering, eliminating the GPU render queue and reducing CPU back pressure in GPU-bound scenarios. In addition to latency reduction functions, the SDK also features measurement markers to calculate both Game and Render Latency that are great for debugging and visualizing in-game performance counter.

[NVIDIA DLSS (Deep Learning Super Sampling)](https://developer.nvidia.com/dlss) is a temporal image upscaling AI rendering technology that increases graphics performance using dedicated Tensor Core AI processors on GeForce RTX™ GPUs. DLSS uses the power of a deep learning neural network to boost frame rates and generate beautiful, sharp images for your games.

[AMD FidelityFX Super Resolution (FSR)](https://www.amd.com/en/technologies/radeon-software-fidelityfx) is an open source, high-quality solution for producing high resolution frames from lower resolution inputs. It uses a collection of cutting-edge Deep Learning algorithms with a particular emphasis on creating high-quality edges, giving large performance improvements compared to rendering at native resolution directly. FSR enables “practical performance” for costly render operations, such as hardware ray tracing for the AMD RDNA™ and AMD RDNA™ 2 architectures.

[Intel Xe Super Sampling (XeSS)](https://www.youtube.com/watch?v=Y9hfpf-SqEg) is a temporal image upscaling AI rendering technology that increases graphics performance similar to NVIDIA's [DLSS (Deep Learning Super Sampling)](https://developer.nvidia.com/dlss). Intel's Arc GPU architecture (early 2022) will have GPUs that feature dedicated Xe-cores to run XeSS. The GPUs will have Xe Matrix eXtenstions matrix (XMX) engines for hardware-accelerated AI processing. XeSS will be able to run on devices without XMX, including integrated graphics, though, the performance of XeSS will be lower on non-Intel graphics cards because it will be powered by [DP4a instruction](https://www.intel.com/content/dam/www/public/us/en/documents/reference-guides/11th-gen-quick-reference-guide.pdf).

[Unigine](https://unigine.com) is a cross-platform game engine designed for development teams (C++/C# programmers, 3D artists) working on interactive 3D apps.

[Frostbite](https://www.ea.com/frostbite/engine) is a game engine developed by [DICE](https://www.dice.se/), designed for cross-platform use on Microsoft Windows and game consoles such as PlayStation 3 Xbox 360,  PlayStation 4, Xbox One, Nintendo Switch, PlayStation 5, and Xbox Series X/S.

[Panda3D](https://www.panda3d.org/) is a game engine, a framework for 3D rendering and game development for Python and C++ programs, developed by Disney and CMU. Panda3D is open-source and free for any purpose, including commercial ventures.

[Source 2](https://developer.valvesoftware.com/wiki/Source_2) is a 3D video game engine in development by Valve as a successor to Source. It is used in Dota 2, Artifact, Dota Underlords, parts of The Lab, SteamVR Home, and Half-Life: Alyx.

[Havok](https://www.havok.com/) is a middleware software suite that provides a realistic physics engine component and related functions to video games. It is supported  and optimized across all major platforms, including Nintendo Switch, PlayStation®, Stadia, and Xbox. Along with integrations for Unity and Unreal Engine and are used in countless proprietary game engines.

[AutoDesk 3ds Max](https://www.autodesk.com/products/3ds-max/overview) is a professional software program for 3D modeling, animation, rendering, and visualization. 3ds Max allows you to create stunning game environments, design visualizations, and virtual reality experiences.

[Houdini](https://www.sidefx.com/) is a 3D procedural software for modeling, rigging, animation, VFX, look development, lighting and rendering in film, TV, advertising and video game pipelines.

[A-Frame](https://aframe.io) is a web framework for building virtual reality experiences in WebVR with HTML and Entity-Component. A-Frame works on Vive, Rift, desktop, mobile platforms.

[AppGameKit](https://www.appgamekit.com) is a powerful game development engine, ideal for Hobbyist and Indie developers. Where you can start coding in the easy to learn AppGameKit BASIC or use the libraries in C++ & XCode.

[Amazon Lumberyard](https://aws.amazon.com/lumberyard/) is an open source, AAA game engine(based on CryEngine) that gives you the tools you need to create high quality games. Deeply integrated with AWS and Twitch, Amazon Lumberyard includes full source code, allowing you to customize your project at any level.

[Blender](https://www.blender.org) is the free and open source 3D creation suite. It supports the entirety of the 3D pipeline—modeling, rigging, animation, simulation, rendering, compositing and motion tracking, video editing and 2D animation pipeline.

[CryEngine](https://www.cryengine.com) is a powerful real-time game development platform created by Crytek.

[GameMaker Studio 2](https://www.yoyogames.com/gamemaker) is the latest and greatest incarnation of GameMaker. It has everything you need to take your idea from concept to finished game. With no barriers to entry and powerful functionality, GameMaker Studio 2 is the ultimate 2D development environment.

[Godot](https://godotengine.org) is a feature-packed, cross-platform game engine to create 2D and 3D games from a unified interface. It provides a comprehensive set of common tools, so that users can focus on making games without having to reinvent the wheel. Games can be exported in one click to a number of platforms, including the major desktop platforms (Linux, Mac OSX, Windows) as well as mobile (Android, iOS) and web-based (HTML5) platforms.

[Open Graphics Library(OpenGL)](https://www.opengl.org/) is an API used acrossed mulitple  programming languages and platforms for hardware-accelerated rendering of 2D/3D vector graphics currently developed by the [Khronos Group](https://www.khronos.org/).

[Open Computing Language (OpenCL)](https://www.khronos.org/opencl/) is an open standard for [parallel programming](https://www.coursera.org/lecture/parprog1/introduction-to-parallel-computing-zNrIS) of heterogeneous platforms consisting of CPUs, GPUs, and other hardware accelerators found in supercomputers, cloud servers, personal computers, mobile devices and embedded platforms.

[OpenGL Shading Language(GLSL)](https://www.khronos.org/opengl/wiki/Core_Language_(GLSL)) is a High Level Shading Language based on the C-style language, so it covers most of the features a user would expect with such a language.  Such as control structures (for-loops, if-else statements, etc) exist in GLSL, including the switch statement.

[High Level Shading Language(HLSL)](https://docs.microsoft.com/en-us/windows/win32/direct3dhlsl/dx-graphics-hlsl) is the High Level Shading Language for DirectX. Using HLSL, the user can create C-like programmable shaders for the Direct3D pipeline. HLSL was first created with DirectX 9 to set up the programmable 3D pipeline.

[DirectX 12 Ultimate](https://github.com/Microsoft/DirectX-Graphics-Samples) is an API(for high performance 2D & 3D graphics) from Microsoft. DirectX 12 Ultimate brings support for ray tracing, mesh shaders, variable rate shading, and sampler feedback. Available in Windows 2004 version(May 2020 Update).

[Vulkan](https://www.khronos.org/vulkan/) is a modern cross-platform graphics and compute API that provides high-efficiency, cross-platform access to modern GPUs used in a wide variety of devices from PCs and consoles to mobile phones and embedded platforms. Vulkan is currently in development by the Khronos consortium.

[Metal](https://developer.apple.com/metal/) is a low-level GPU programming framework used for rendering 2D and 3D graphics on Apple platforms such as iOS, iPadOS, macOS, watchOS and tvOS.

[MoltenVK](https://moltengl.com/moltenvk) is an implementation of Vulkan running on iOS and macOS using Apple's [Metal](https://developer.apple.com/metal/) graphics framework.

[MoltenGL](https://moltengl.com) is an implementation of the OpenGL ES 2.0 API that runs on Apple's [Metal](https://developer.apple.com/metal/) graphics framework.

[Mesa 3D Graphics Library](https://docs.mesa3d.org/index.html) is a project began as an open-source implementation of the OpenGL specification. A system for rendering interactive 3D graphics. Mesa ties into several other open-source projects: the [Direct Rendering Infrastructure](https://dri.freedesktop.org/), [X.org](https://x.org/), and [Wayland](https://wayland.freedesktop.org/) to provide OpenGL support on Linux, FreeBSD, and other operating systems.

[OpenGL ES](https://www.khronos.org/opengles/) is the mobile subset of OpenGL. It's supported on all major mobile platforms, and is also the base for WebGL.

[OpenCL](https://www.khronos.org/opencl/) is a framework for writing programs that execute across heterogeneous platforms consisting of CPUs, GPUs, DSPs, FPGAs and other processors or hardware accelerators.

[EGL](https://www.khronos.org/egl/) is an interface between Khronos rendering APIs such as OpenGL or OpenVG and the underlying native platform window system.

[VDPAU](https://www.freedesktop.org/wiki/Software/VDPAU/) is the Video Decode and Presentation API for UNIX. It provides an interface to video decode acceleration and presentation hardware present in modern GPUs.

[VA API](https://freedesktop.org/wiki/Software/vaapi/) is an open-source library and API specification, which provides access to graphics hardware acceleration capabilities for video processing.

[XvMC](https://en.wikipedia.org/wiki/X-Video_Motion_Compensation) is an extension of the X video extension (Xv) for the X Window System. The XvMC API allows video programs to offload portions of the video decoding process to the GPU hardware.

[AMD Radeon ProRender](https://www.amd.com/en/technologies/radeon-prorender) is a powerful physically-based rendering engine that enables creative professionals to produce stunningly photorealistic images on virtually any GPU, any CPU, and any OS in over a dozen leading digital content creation and CAD applications.

[NVIDIA Omniverse](https://developer.nvidia.com/nvidia-omniverse-platform) is a powerful, multi-GPU, real-time simulation and collaboration platform for 3D production pipelines based on Pixar's Universal Scene Description and NVIDIA RTX.

[LibGDX](https://github.com/libgdx/libgdx) is a cross-platform Java game development framework based on OpenGL (ES) that works on Windows, Linux, Mac OS X, Android, your WebGL enabled browser and iOS.

[cocos2d-x](https://github.com/cocos2d/cocos2d-x) is a multi-platform framework for building 2d games, interactive books, demos and other graphical applications. It is based on cocos2d-iphone, but instead of using Objective-C, it uses C++. It works on iOS, Android, macOS, Windows and Linux.

[MonoGame](https://github.com/MonoGame/MonoGame) is a framework for creating powerful cross-platform games. The spiritual successor to XNA with thousands of titles shipped across desktop, mobile, and console platforms. MonoGame is a fully managed .NET open source game framework without any black boxes.

[Three.js](https://threejs.org) is a cross-browser JavaScript library and application programming interface used to create and display animated 3D computer graphics in a web browser using WebGL.

[Superpowers](http://superpowers-html5.com/) is a downloadable HTML5 app for real-time collaborative projects . You can use it solo like a regular offline game maker, or setup a password and let friends join in on your project through their Web browser.

[URHO3D](https://urho3d.github.io/) is a free lightweight, cross-platform 2D and 3D game engine implemented in C++ and released under the MIT license. Greatly inspired by OGRE and Horde3D.

[Vivox](https://www.vivox.com/) is a voice & text chat platform that's trusted by the world's biggest gaming brands and titles such as Fortnite, PUBG, League of Legends, and Rainbow Six Siege.

[HGIG](https://www.hgig.org/) is a volunteer group of companies from the game and TV display industries that meet to specify and make available for the public guidelines to improve consumer gaming experiences in HDR.

[GameBlocks](https://www.gameblocks.com/) is a Server Side Anti-Cheat & Middleware software.

# Augmented Reality (AR) & Virtual Reality (VR)
[Back to the Top](https://github.com/mikeroyal/Godot-Engine-Guide#table-of-contents)

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/130368380-37b7c0cd-ed71-4a52-8b16-4ac802e059d4.png">
  <br />
</p>

# Augmented Reality (AR) & Virtual Reality (VR) Learning Resources

[Augmented Reality (AR)](https://en.wikipedia.org/wiki/Augmented_reality) is an interactive experience of a real-world environment where the objects that reside in the real world are enhanced by computer-generated perceptual information.

[Virtual Reality (VR)](https://en.wikipedia.org/wiki/Virtual_reality) is a simulated experience that can be similar to or completely different from the real world. The applications of virtual reality include entertainment (video games), education (medical or military training) and business (virtual meetings).

[Mixed Reality (MR)](https://en.wikipedia.org/wiki/Mixed_reality) is the merging of real and virtual worlds to produce new environments and visualizations, where physical and digital objects co-exist and interact in real time.

[Extended Reality (XR)](https://en.wikipedia.org/wiki/Extended_reality) is a concept referring to all real-and-virtual combined environments and human-machine interactions generated by computer technology and wearables. Including augmented reality (AR), mixed reality (MR) and virtual reality (VR).

[Virtual Reality - Experiences and Devices](https://www.microsoft.com/en-us/mixed-reality/windows-mixed-reality)

[Oculus | VR Headsets, Games & Equipment](https://www.oculus.com/)

[Virtual Reality on Steam](https://store.steampowered.com/vr/)

[Valve Index® VR Headset](https://store.steampowered.com/valveindex)

[PlayStation VR](https://www.playstation.com/explore/playstation-vr/)

[HTC Vive VR Headset](https://www.vive.com/us/)

[Augmented Reality applications - Apple](https://www.apple.com/augmented-reality/)

[Unity Learn Training Program](https://learn.unity.com)

[Unity Manual: XR](https://docs.unity3d.com/Manual/XR.html)

[Intro to XR: VR, AR, and MR Foundations - Unity Learn](https://learn.unity.com/course/introduction-to-xr-vr-ar-and-mr-foundations)

[Unity XR: Build VR and AR Apps](https://unity3d.com/learn/unity-xr-apps)

[Top Virtual Reality Courses Online | Udemy](https://www.udemy.com/topic/virtual-reality/)

[Top Augmented Reality Courses Online | Udemy](https://www.udemy.com/topic/augmented-reality/)

[Google AR & VR Online Courses | Coursera](https://www.coursera.org/googlearvr)

[Top Augmented Reality Courses | Coursera](https://www.coursera.org/courses?query=augmented%20reality)

[Learn Augmented Reality with Online Courses and Lessons | edX](https://www.edx.org/learn/augmented-reality)

## Augmented Reality (AR) & Virtual Reality (VR) Tools and Frameworks

[ARKit](https://developer.apple.com/augmented-reality/arkit/) is a set set of software development tools to enable developers to build augmented-reality apps for iOS developed by Apple. The latest version ARKit 3.5 takes advantage of the new LiDAR Scanner and depth sensing system on iPad Pro(2020) to support a new generation of AR apps that use Scene Geometry for enhanced scene understanding and object occlusion.

[RealityKit](https://developer.apple.com/documentation/realitykit) is a framework to implement high-performance 3D simulation and rendering with information provided by the ARKit framework to seamlessly integrate virtual objects into the real world.

[SceneKit](https://developer.apple.com/scenekit/) is a high-level 3D graphics framework that helps you create 3D animated scenes and effects in your iOS apps.

[GPUImage framework](https://github.com/BradLarson/GPUImage) is a BSD-licensed iOS library that lets you apply GPU-accelerated filters and other effects to images, live camera video, and movies. In comparison to Core Image (part of iOS 5.0), GPUImage allows you to write your own custom filters, supports deployment to iOS 4.0, and has a simpler interface. However, it currently lacks some of the more advanced features of Core Image, such as facial detection.

[GPUImage3](https://github.com/BradLarson/GPUImage3) is the third generation of the [GPUImage framework](https://github.com/BradLarson/GPUImage), an open source project for performing GPU-accelerated image and video processing on Mac and iOS. The original GPUImage framework was written in Objective-C and targeted Mac and iOS, the second iteration rewritten in Swift using OpenGL to target Mac, iOS, and Linux, and now this third generation is redesigned to use [Apple's Metal](https://developer.apple.com/metal/) in place of OpenGL.

[ARCore](https://developers.google.com/ar/) is a software development kit developed by Google that allows for augmented reality applications in the real world. These tools include environmental understanding, which allows devices to detect horizontal and vertical surfaces and planes. It also includes motion tracking, which lets phones understand and track their positions relative to the world. Also ARCore’s Light Estimation API lets your digital objects appear realistically as if they’re actually part of the physical world.

[Adobe Aero](https://www.adobe.com/products/aero.html) is a powerful new [augmented reality (AR)](https://en.wikipedia.org/wiki/Augmented_reality) authoring tool that makes it easier for designers to create immersive content.

[Vuforia](https://developer.vuforia.com/) is a comprehensive, scalable enterprise AR platform. Our wide-ranging solution suite ensures that we can provide the right AR technology to every customer based on their business needs.

[Vuforia Studio](https://www.ptc.com/en/products/vuforia/vuforia-studio) is a tool that allows anyone to create beautiful 3D augmented reality (AR) experiences in a matter of minutes with no coding required.

[OpenVX™](https://www.khronos.org/openvx/) is an open-source, royalty-free standard for cross platform acceleration of computer vision applications. OpenVX enables performance and power-optimized computer vision processing, especially important in embedded and real-time use cases such as face, body and gesture tracking, smart video surveillance, advanced driver assistance systems (ADAS), object and scene reconstruction, augmented reality, visual inspection, robotics and more.

[NVIDIA Flex](https://github.com/NVIDIAGameWorks/FleX) is a particle-based simulation library designed for real-time applications.

[ARToolKit](https://artoolkit.org) is a fast and modern open source tracking and recognition SDK which enables computers to see and understand more in the environment around them. It's built from the ground up using modern computer vision techniques.

[ARmedia](https://www.inglobetechnologies.com/ar-media/) is a plugin tool that makes it easy to develop and create AR experiences without coding.

[Kundan](https://www.kudan.io/) is a tool that provides proprietary Artificial Perception technologies based on SLAM to enable use cases with significant market potential and impact on our lives such as autonomous driving, robotics, AR/VR and smart cities.

[OVR Toolkit](https://store.steampowered.com/app/1068820/OVR_Toolkit/) is a utility application designed to make viewing the desktop in VR simple and fast, it allows for viewing the desktop within VR, placing desktop windows around the world, mouse input, typing with a virtual keyboard, and quickly switching between windows.

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/117720758-e843d300-b193-11eb-9796-bde15aebed71.png">
<br />
</p>

Microsoft HoloLens Headset. Source: [Microsoft](https://www.microsoft.com/en-us/hololens/buy)

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/117720763-e9750000-b193-11eb-888a-e4bccd6c30eb.png">
<br />
</p>

PlayStation VR Headset. Source: [PlayStation](https://www.playstation.com/en-us/ps-vr/)

[SteamVR](https://store.steampowered.com/steamvr) is the ultimate tool for experiencing VR content on the hardware of your choice. SteamVR supports the Valve Index, HTC Vive, Oculus Rift, Windows Mixed Reality headsets, and others.

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/110881514-543db400-8295-11eb-9543-fd5d385ddb05.png">
<br />

SteamVR Home
</p>

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/117720776-ed088700-b193-11eb-8538-9831999b5104.png">
<br />
</p>
Valve Index VR Headset. Source: [Steam](https://store.steampowered.com/valveindex)


[OpenVR](https://github.com/ValveSoftware/openvr) is an API and runtime that allows access to VR hardware(Steam Index, HTC Vive, and Oculus Rift) from multiple vendors without requiring that applications have specific knowledge of the hardware they are targeting.

[OpenVR Benchmark on Steam](https://store.steampowered.com/app/955610/OpenVR_Benchmark/) is the first benchmark tool for reproducibly testing your real VR performance, rendering inside of your VR headset.

[OpenHMD](http://www.openhmd.net/) is open source API and drivers that supports a wide range of HMD(head-mounted display) devices such as Oculus Rift, HTC Vive, Sony PSVR, and others.

[openXR](https://www.khronos.org/OpenXR/) is a free, open standard that provides high-performance access to Augmented Reality (AR) and Virtual Reality (VR) collectively known as XR—platforms and devices.

[Monado](https://monado.dev/) is the first OpenXR™ runtime for GNU/Linux. Monado aims to jump-start development of an open source XR ecosystem and provide the fundamental building blocks for device vendors to target the GNU/Linux platform.

[Libsurvive](https://github.com/cntools/libsurvive) is a set of tools and libraries that enable 6 dof tracking on lighthouse and vive based systems that is completely open source and can run on any device. It currently supports both SteamVR 1.0 and SteamVR 2.0 generation of devices and should support any tracked object commercially available.

[Simula](https://github.com/SimulaVR/Simula) is a VR window manager for Linux that runs on top of Godot. It takes less than 1 minute to install. Simula is officially compatible with SteamVR headsets equipped with Linux drivers (e.g. HTC Vive, HTC Vive Pro, & Valve Index). We have also added experimental support to OpenXR headsets that have Monado drivers (e.g. North Star, OSVR HDK, and PSVR). Some people have gotten the Oculus Rift S to run Simula via OpenHMD ([see here](https://github.com/OpenHMD/OpenHMD/issues/225#issuecomment-638454156)).

# Vulkan Development
[Back to the Top](https://github.com/mikeroyal/Godot-Engine-Guide#table-of-contents)

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/129622224-8c4cca51-9200-4d70-9d16-2610d704713a.png">
  <br />
</p>

## Vulkan Learning Resources

[Vulkan®](https://www.khronos.org/vulkan/) is a modern cross-platform graphics and compute API that provides high-efficiency, cross-platform access to modern GPUs used in a wide variety of devices from PCs and consoles to mobile phones and embedded platforms. Vulkan is currently in development by the Khronos consortium.

[Khronos Group GitHub](https://github.com/KhronosGroup)

[Vulkan Documentation](https://github.com/KhronosGroup/Vulkan-Docs)

[HLSL to SPIR-V Feature Mapping Manual](https://github.com/microsoft/DirectXShaderCompiler/blob/master/docs/SPIR-V.rst)

[Vulkan GLSL Ray Tracing Emulator Tutorial](https://www.gsn-lib.org/docs/nodes/raytracing.php)

[Getting Started with Vulkan](https://vulkan-tutorial.com/)

[Vulkan Samples](https://github.com/KhronosGroup/Vulkan-Samples)

[Khronos Community Forums](https://community.khronos.org/)

## Vulkan Tools, Libraries, and Frameworks

[Vulkan SDK](https://vulkan.lunarg.com) is a set of tools that enables Vulkan developers to develop Vulkan applications.

[SPIR-V](https://www.khronos.org/spir/) is a set of tools that enables high-level language front-ends to emit programs in a standardized intermediate form to be ingested by Vulkan, OpenGL or OpenCL drivers. It eliminates the need for high-level language front-end compilers in device drivers, significantly reducing driver complexity, enables a broad range of language and framework front-ends to run on diverse hardware architectures and encourages a vibrant ecosystem of open source analysis, porting, debug and optimization tools.

[SPIRV-Reflect](https://github.com/KhronosGroup/SPIRV-Reflect) is a lightweight library that provides a C/C++ reflection API for SPIR-V shader bytecode in Vulkan applications.

[Vulkan® Tools](https://github.com/KhronosGroup/Vulkan-Tools) is a project that provides Khronos official Vulkan Tools and Utilities for Windows, Linux, Android, and macOS.

[Vulkan-Hpp](https://github.com/KhronosGroup/Vulkan-Hpp) is a API that provides a header only C++ bindings for the Vulkan C API to improve the developers Vulkan experience without introducing CPU runtime cost. It adds features like type safety for enums and bitfields, STL container support, exceptions and simple enumerations.

[Vulkan® Memory Allocator (VMA)](https://gpuopen.com/vulkan-memory-allocator/) is a  library that provides a simple and easy to integrate API to help you allocate memory for Vulkan® buffer and image storage.

[AMD Open Source Driver for Vulkan®](https://gpuopen.com/amd-open-source-driver-for-vulkan/) is an open-source Vulkan driver for AMD Radeon™ graphics adapters on Linux®.

[NVIDIA® Nsight™ Visual Studio Edition](https://developer.nvidia.com/nsight-visual-studio-edition) is an application development environment for heterogeneous platforms which brings GPU computing into Microsoft Visual Studio. NVIDIA Nsight™ VSE allows you to build and debug integrated GPU kernels and native CPU code as well as inspect the state of the GPU and memory.

[Radeon™ GPU Profiler](https://gpuopen.com/rgp/) is a performance tool that can be used by developers to optimize DirectX®12, Vulkan® and OpenCL™ applications for AMD RDNA™ and GCN hardware.

[Radeon™ GPU Analyzer](https://gpuopen.com/rga/) is a compiler and code analysis tool for Vulkan®, DirectX®, OpenGL® and OpenCL™.

[Radeon™ Memory Visualizer (RMV)](https://gpuopen.com/rmv/) is a tool provided by AMD for use by game engine developers. It allows engineers to examine, diagnose, and understand the GPU memory management within their projects.

[DXVK](https://github.com/doitsujin/dxvk) is a Vulkan-based translation layer for Direct3D 9/10/11 which allows running 3D applications on Linux using Wine.

[MoltenVK](https://moltengl.com/moltenvk) is an implementation of Vulkan running on iOS and macOS using Apple's [Metal](https://developer.apple.com/metal/) graphics framework.

[RenderDoc](https://renderdoc.org) is a stand-alone graphics debugger that allows quick and easy single-frame capture and detailed introspection of any application using Vulkan, D3D11, OpenGL & OpenGL ES or D3D12 across Windows, Linux, Android, Stadia, or Nintendo Switch™.

[PerfDoc](https://github.com/ARM-software/perfdoc) is a cross-platform Vulkan layer which checks Vulkan applications for [best practices on Arm Mali](https://developer.arm.com/graphics/developer-guides/mali-gpu-best-practices) devices.

[GLFW](https://www.glfw.org/) is an Open Source, multi-platform library for OpenGL, OpenGL ES and Vulkan application development. It provides a simple, platform-independent API for creating windows, contexts and surfaces, reading input, handling events, etc. GLFW natively supports Windows, macOS and Linux and other Unix-like systems. On Linux both X11 and Wayland are supported.

[VulkanSharp](https://github.com/mono/VulkanSharp) is a project provides a .NET binding for the Vulkan API.

[Vortice.Vulkan](https://github.com/amerkoleci/Vortice.Vulkan) is a .NET Standard 2.0 and .NET5 low-level bindings for Vulkan API.

[VKD3D-Proton](https://github.com/HansKristian-Work/vkd3d-proton) is a fork of VKD3D, which aims to implement the full Direct3D 12 API on top of Vulkan.

[ImGui](https://github.com/ocornut/imgui) is a bloat-free graphical user interface library for C++. It outputs optimized vertex buffers that you can render anytime in your 3D-pipeline enabled application. It is fast, portable, renderer agnostic and self-contained (no external dependencies).

[Ash](https://github.com/MaikKlein/ash) is a very lightweight wrapper around Vulkan.

[gfx-rs](https://github.com/gfx-rs/gfx) is a low-level, cross-platform graphics and compute abstraction library in Rust.

[Vulkan.jl](https://github.com/JuliaGPU/Vulkan.jl) is a lightweight wrapper around the Vulkan graphics and compute library. It exposes abstractions over the underlying C interface, primarily geared towards developers looking for a more natural way to work with Vulkan with minimal overhead.

# C/C++ Development
[Back to the Top](https://github.com/mikeroyal/Godot-Engine-Guide#table-of-contents)

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/115297894-961e0d80-a111-11eb-81c3-e2bd2ac9a7cd.png">
  <br />
</p>

## C/C++ Learning Resources

[C++](https://www.cplusplus.com/doc/tutorial/) is a cross-platform language that can be used to build high-performance applications developed by Bjarne Stroustrup, as an extension to the C language.

[C](https://www.iso.org/standard/74528.html) is a general-purpose, high-level language that was originally developed by Dennis M. Ritchie to develop the UNIX operating system at Bell Labs. It supports structured programming, lexical variable scope, and recursion, with a static type system. C also provides constructs that map efficiently to typical machine instructions, which makes it one was of the most widely used programming languages today.

[Embedded C](https://en.wikipedia.org/wiki/Embedded_C) is a set of language extensions for the C programming language by the [C Standards Committee](https://isocpp.org/std/the-committee) to address issues that exist between C extensions for different [embedded systems](https://en.wikipedia.org/wiki/Embedded_system). The extensions hep enhance microprocessor features such as fixed-point arithmetic, multiple distinct memory banks, and basic I/O operations. This makes Embedded C the most popular embedded software language in the world.

[C & C++ Developer Tools from JetBrains](https://www.jetbrains.com/cpp/)

[Open source C++ libraries on cppreference.com](https://en.cppreference.com/w/cpp/links/libs)

[C++ Graphics libraries](https://cpp.libhunt.com/libs/graphics)

[C++ Libraries in MATLAB](https://www.mathworks.com/help/matlab/call-cpp-library-functions.html)

[C++ Tools and Libraries Articles](https://www.cplusplus.com/articles/tools/)

[Google C++ Style Guide](https://google.github.io/styleguide/cppguide.html)

[Introduction C++ Education course on Google Developers](https://developers.google.com/edu/c++/)

[C++ style guide for Fuchsia](https://fuchsia.dev/fuchsia-src/development/languages/c-cpp/cpp-style)

[C and C++ Coding Style Guide by OpenTitan](https://docs.opentitan.org/doc/rm/c_cpp_coding_style/)

[Chromium C++ Style Guide](https://chromium.googlesource.com/chromium/src/+/master/styleguide/c++/c++.md)

[C++ Core Guidelines](https://github.com/isocpp/CppCoreGuidelines/blob/master/CppCoreGuidelines.md)

[C++ Style Guide for ROS](http://wiki.ros.org/CppStyleGuide)

[Learn C++](https://www.learncpp.com/)

[Learn C : An Interactive C Tutorial](https://www.learn-c.org/)

[C++ Institute](https://cppinstitute.org/free-c-and-c-courses)

[C++ Online Training Courses on LinkedIn Learning](https://www.linkedin.com/learning/topics/c-plus-plus)

[C++ Tutorials on W3Schools](https://www.w3schools.com/cpp/default.asp)

[Learn C Programming Online Courses on edX](https://www.edx.org/learn/c-programming)

[Learn C++ with Online Courses on edX](https://www.edx.org/learn/c-plus-plus)

[Learn C++ on Codecademy](https://www.codecademy.com/learn/learn-c-plus-plus)

[Coding for Everyone: C and C++ course on Coursera](https://www.coursera.org/specializations/coding-for-everyone)

[C++ For C Programmers on Coursera](https://www.coursera.org/learn/c-plus-plus-a)

[Top C Courses on Coursera](https://www.coursera.org/courses?query=c%20programming)

[C++ Online Courses on Udemy](https://www.udemy.com/topic/c-plus-plus/)

[Top C Courses on Udemy](https://www.udemy.com/topic/c-programming/)

[Basics of Embedded C Programming for Beginners on Udemy](https://www.udemy.com/course/embedded-c-programming-for-embedded-systems/)

[C++ For Programmers Course on Udacity](https://www.udacity.com/course/c-for-programmers--ud210)

[C++ Fundamentals Course on Pluralsight](https://www.pluralsight.com/courses/learn-program-cplusplus)

[Introduction to C++ on MIT Free Online Course Materials](https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-096-introduction-to-c-january-iap-2011/)

[Introduction to C++ for Programmers | Harvard ](https://online-learning.harvard.edu/course/introduction-c-programmers)

[Online C Courses | Harvard University](https://online-learning.harvard.edu/subject/c)


## C/C++ Tools and Frameworks

[AWS SDK for C++](https://aws.amazon.com/sdk-for-cpp/)

[Azure SDK for C++](https://github.com/Azure/azure-sdk-for-cpp)

[Azure SDK for C](https://github.com/Azure/azure-sdk-for-c)

[C++ Client Libraries for Google Cloud Services](https://github.com/googleapis/google-cloud-cpp)

[Visual Studio](https://visualstudio.microsoft.com/) is an integrated development environment (IDE) from Microsoft; which is a feature-rich application that can be used for many aspects of software development. Visual Studio makes it easy to edit, debug, build, and publish your app. By using Microsoft software development platforms such as Windows API, Windows Forms, Windows Presentation Foundation, and Windows Store.

[Visual Studio Code](https://code.visualstudio.com/) is a code editor redefined and optimized for building and debugging modern web and cloud applications.

[Vcpkg](https://github.com/microsoft/vcpkg) is a C++ Library Manager for Windows, Linux, and MacOS.

[ReSharper C++](https://www.jetbrains.com/resharper-cpp/features/) is a Visual Studio Extension for C++ developers developed by JetBrains.

[AppCode](https://www.jetbrains.com/objc/) is constantly monitoring the quality of your code. It warns you of errors and smells and suggests quick-fixes to resolve them automatically. AppCode provides lots of code inspections for Objective-C, Swift, C/C++, and a number of code inspections for other supported languages. All code inspections are run on the fly.

[CLion](https://www.jetbrains.com/clion/features/) is a cross-platform IDE for C and C++ developers developed by JetBrains.

[Code::Blocks](https://www.codeblocks.org/) is a free C/C++ and Fortran IDE built to meet the most demanding needs of its users. It is designed to be very extensible and fully configurable. Built around a plugin framework, Code::Blocks can be extended with plugins.

[CppSharp](https://github.com/mono/CppSharp) is a tool and set of libraries which facilitates the usage of native C/C++ code with the .NET ecosystem. It consumes C/C++ header and library files and generates the necessary glue code to surface the native API as a managed API. Such an API can be used to consume an existing native library in your managed code or add managed scripting support to a native codebase.

[Conan](https://conan.io/) is an Open Source Package Manager for C++ development and dependency management into the 21st century and on par with the other development ecosystems.

[High Performance Computing (HPC) SDK](https://developer.nvidia.com/hpc) is a comprehensive toolbox for GPU accelerating HPC modeling and simulation applications. It includes the C, C++, and Fortran compilers, libraries, and analysis tools necessary for developing HPC applications on the NVIDIA platform.

[Thrust](https://github.com/NVIDIA/thrust) is a C++ parallel programming library which resembles the C++ Standard Library. Thrust's high-level interface greatly enhances programmer productivity while enabling performance portability between GPUs and multicore CPUs. Interoperability with established technologies such as CUDA, TBB, and OpenMP integrates with existing software.

[Boost](https://www.boost.org/) is an educational opportunity focused on cutting-edge C++. Boost has been a participant in the annual Google Summer of Code since 2007, in which students develop their skills by working on Boost Library development.

[Automake](https://www.gnu.org/software/automake/) is a tool for automatically generating Makefile.in files compliant with the GNU Coding Standards. Automake requires the use of GNU Autoconf.

[Cmake](https://cmake.org/) is an open-source, cross-platform family of tools designed to build, test and package software. CMake is used to control the software compilation process using simple platform and compiler independent configuration files, and generate native makefiles and workspaces that can be used in the compiler environment of your choice.

[GDB](http://www.gnu.org/software/gdb/) is a debugger, that allows you to see what is going on `inside' another program while it executes or what another program was doing at the moment it crashed.

[GCC](https://gcc.gnu.org/) is a compiler Collection that includes front ends for C, C++, Objective-C, Fortran, Ada, Go, and D, as well as libraries for these languages.

[GSL](https://www.gnu.org/software/gsl/) is a numerical library for C and C++ programmers. It is free software under the GNU General Public License. The library provides a wide range of mathematical routines such as random number generators, special functions and least-squares fitting. There are over 1000 functions in total with an extensive test suite.

[OpenGL Extension Wrangler Library (GLEW)](https://www.opengl.org/sdk/libs/GLEW/) is a cross-platform open-source C/C++ extension loading library. GLEW provides efficient run-time mechanisms for determining which OpenGL extensions are supported on the target platform.

[Libtool](https://www.gnu.org/software/libtool/) is a generic library support script that hides the complexity of using shared libraries behind a consistent, portable interface. To use Libtool, add the new generic library building commands to your Makefile, Makefile.in, or Makefile.am.

[Maven](https://maven.apache.org/) is a software project management and comprehension tool. Based on the concept of a project object model (POM), Maven can manage a project's build, reporting and documentation from a central piece of information.

[TAU (Tuning And Analysis Utilities)](http://www.cs.uoregon.edu/research/tau/home.php) is capable of gathering performance information through instrumentation of functions, methods, basic blocks, and statements as well as event-based sampling. All C++ language features are supported including templates and namespaces.

[Clang](https://clang.llvm.org/) is a production quality C, Objective-C, C++ and Objective-C++ compiler when targeting X86-32, X86-64, and ARM (other targets may have caveats, but are usually easy to fix). Clang is used in production to build performance-critical software like Google Chrome or Firefox.

[OpenCV](https://opencv.org/) is a highly optimized library with focus on real-time applications. Cross-Platform C++, Python and Java interfaces support Linux, MacOS, Windows, iOS, and Android.

[Libcu++](https://nvidia.github.io/libcudacxx) is the NVIDIA C++ Standard Library for your entire system. It provides a heterogeneous implementation of the C++ Standard Library that can be used in and between CPU and GPU code.

[ANTLR (ANother Tool for Language Recognition)](https://www.antlr.org/) is a powerful parser generator for reading, processing, executing, or translating structured text or binary files. It's widely used to build languages, tools, and frameworks. From a grammar, ANTLR generates a parser that can build parse trees and also generates a listener interface that makes it easy to respond to the recognition of phrases of interest.

[Oat++](https://oatpp.io/) is a light and powerful C++ web framework for highly scalable and resource-efficient web application. It's zero-dependency and easy-portable.

[JavaCPP](https://github.com/bytedeco/javacpp) is a program that provides efficient access to native C++ inside Java, not unlike the way some C/C++ compilers interact with assembly language.

[Cython](https://cython.org/) is a language that makes writing C extensions for Python as easy as Python itself. Cython is based on Pyrex, but supports more cutting edge functionality and optimizations such as calling C functions and declaring C types on variables and class attributes.

[Spdlog](https://github.com/gabime/spdlog) is a very fast, header-only/compiled, C++ logging library.

[Infer](https://fbinfer.com/) is a static analysis tool for Java, C++, Objective-C, and C. Infer is written in [OCaml](https://ocaml.org/).


# C# Development
[Back to the Top](https://github.com/mikeroyal/Godot-Engine-Guide#table-of-contents)

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/94306457-d6c0fa00-ff27-11ea-85dc-83dbb8f3e3e6.png">
  <br />
</p>

## C# Learning Resources

[C#](https://docs.microsoft.com/en-us/dotnet/csharp/) is a modern and object-oriented programming language developed by Microsoft to write any application using the C# programming language on the .NET platform.

[Taking your first steps with C#](https://docs.microsoft.com/en-us/learn/paths/csharp-first-steps/)

[Learning C#](https://dotnet.microsoft.com/learn/csharp)

[C# development with Visual Studio](https://docs.microsoft.com/en-us/visualstudio/get-started/csharp/)

[C# programming with Visual Studio Code](https://code.visualstudio.com/Docs/languages/csharp)

[Working with data in C#](https://docs.microsoft.com/en-us/learn/paths/csharp-data/)

[C# Tutorial by W3Schools](https://www.w3schools.com/cs/)

[Windows Forms for .NET 5 and .NET Core 3.1](https://docs.microsoft.com/en-us/dotnet/desktop/winforms/?view=netdesktop-5.0)

[Xamarin documentation](https://docs.microsoft.com/en-us/xamarin/)

[Advanced Topics in C# by Udemy](https://www.udemy.com/course/advanced-topics-csharp/)

[The complete C# tutorial](https://csharp.net-tutorials.com/)

[Unity C# Survival Guide](https://learn.unity.com/course/unity-c-survival-guide)

[RabbitMQ .NET/C# Client API](https://www.rabbitmq.com/dotnet-api-guide.html)

## C# Tools, Libraries and Frameworks

[Mono](https://www.mono-project.com/) is a software platform designed to allow developers to easily create cross platform applications. It is an open source implementation of Microsoft's .NET Framework based on the ECMA standards for C# and the Common Language Runtime.

[Visual Studio](https://visualstudio.microsoft.com/) is an integrated development environment (IDE) from Microsoft; which is a feature-rich application that can be used for many aspects of software development. Visual Studio makes it easy to edit, debug, build, and publish your app. By using Microsoft software development platforms such as Windows API, Windows Forms, Windows Presentation Foundation, and Windows Store.

[MSBuild](https://github.com/dotnet/msbuild) is the build platform for .NET and Visual Studio. MSBuild, provides an XML schema for a project file that controls how the build platform processes and builds software. Visual Studio uses MSBuild to perform team builds through Azure DevOps Server, but MSBuild can run without Visual Studio.

[Roslyn](https://docs.microsoft.com/dotnet/csharp/roslyn-sdk/) is a .NET compiler developed by Microsoft that provides C# and Visual Basic languages with rich code analysis APIs.

[Bot Framework](https://github.com/microsoft/botframework-sdk) is a framework developed by Microsoft that provides the most comprehensive experience for building conversation applications. Developers can model and build sophisticated conversation using their favorite programming languages including C#, JS, Python and Java or using Bot Framework Composer, an open-source, visual authoring canvas for developers and multi-disciplinary teams to design and build conversational experiences with Language.

[Uno Platform](https://platform.uno/) is a Universal Windows Platform Bridge that allows UWP-based code (C# and XAML) to run on iOS, Android, macOS, WebAssembly, Linux and Windows 7. It provides the full definitions of the UWP [Windows 10 2004 (19041)](https://docs.microsoft.com/en-us/windows/uwp/whats-new/windows-10-build-19041), and the implementation of a growing number of parts of the UWP API, such as Windows.UI.Xaml, to enable UWP and WinUI applications to run on these platforms.

[Rider](https://www.jetbrains.com/rider/) is a fast and powerful, cross-platform .NET IDE devloped by JetBrains to develop .NET, ASP.NET, .NET Core, Xamarin; or Unity applications for Windows, Mac, Linux.

[Resharper](https://www.jetbrains.com/resharper/) is a [Visual Studio](https://visualstudio.microsoft.com/) Extension for .NET Developers that has On-the-fly code quality analysis for C#, VB.NET, XAML, ASP.NET, ASP.NET MVC, JavaScript, TypeScript, CSS, HTML, and XML. Letting you know right away if your code needs to be improved.

[dotPeek](https://www.jetbrains.com/decompiler/) is a tool developed by JetBrains based on ReSharper's bundled decompiler. It can reliably decompile any .NET assembly into equivalent C# or CIL code.

[dotTrace](https://www.jetbrains.com/profiler/) is an .NET performance Profiler developed by Jet Brains. It helps users locate performance bottlenecks in a variety of .NET applications: desktop applications, .NET Core, ASP.NET, ASP.NET Core applications hosted on IIS or IIS Express web servers, Silverlight, WCF services, Windows services, Universal Windows Platform applications, and unit tests.

[dotMemory](https://www.jetbrains.com/dotmemory/) is an .NET memory Profiler developed by Jet Brains. It allows the user to analyze memory usage in a variety of .NET and .NET Core applications: desktop applications, Windows services, ASP.NET web applications, IIS, IIS Express, arbitrary .NET processes, and more.

[dotCover](https://www.jetbrains.com/dotcover/) is an .NET unit test runner and code coverage tool developed by Jet Brains. It helps the user figure out on-the-fly which unit tests are affected by your latest code changes, and automatically re-runs the affected tests for you. The continuous testing mode can be switched on for any unit test session.

[Json.NET](https://www.newtonsoft.com/json) is a popular high-performance JSON framework for .NET.

[Quasar](https://github.com/quasar/Quasar) is a fast and light-weight remote administration tool coded in C#. The usage ranges from user support through day-to-day administrative work to employee monitoring. Providing high stability and an easy-to-use user interface, Quasar is the perfect remote administration solution for you.

[CodeMaid](https://github.com/codecadwallader/codemaid) is an open source Visual Studio extension to cleanup and simplify our C#, C++, F#, VB, PHP, PowerShell, JSON, XAML, XML, ASP, HTML, CSS, LESS, SCSS, JavaScript and TypeScript coding.

[.NET Fiddle](https://dotnetfiddle.net/) is an advanced online compiler for C# that allows you to create, run and share your code online.

[Octopus Deploy](https://octopus.com/) is a single place for your team to manage releases, automate deployments, and automate the runbooks that keeps your software operating.

[Appveyor](https://ci.appveyor.com/) is a cloud-based continuous integration system that integrates natively with your source control and allows CI configuration files to live alongside your projects.

[AppHarbor](https://appharbor.com/) is a .NET Platform-as-a-Service that let's developers deploy and scale any standard .NET application to the cloud.

[ANTLR (ANother Tool for Language Recognition)](https://www.antlr.org/) is a powerful parser generator for reading, processing, executing, or translating structured text or binary files. It's widely used to build languages, tools, and frameworks. From a grammar, ANTLR generates a parser that can build parse trees and also generates a listener interface that makes it easy to respond to the recognition of phrases of interest.

[AutoRest](https://github.com/Azure/autorest) is a tool generates client libraries for accessing RESTful web services using the [OpenAPI Specification](https://github.com/OAI/OpenAPI-Specification) format. It Supports C#, PowerShell, Go, Java, Node.js, TypeScript, Python, Ruby.

[Markdig](https://github.com/lunet-io/markdig) is a fast, powerful, [CommonMark](https://commonmark.org/) compliant, extensible Markdown processor for .NET.

# Python Development
[Back to the Top](https://github.com/mikeroyal/Godot-Engine-Guide#table-of-contents)

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/93133273-ce490380-f68b-11ea-81d0-7f6a3debe6c0.png">
  <br />
</p>

## Python Learning Resources

[Python](https://www.python.org) is an interpreted, high-level programming language. Python is used heavily in the fields of Data Science and Machine Learning.

[Python Developer’s Guide](https://devguide.python.org) is a comprehensive resource for contributing to Python – for both new and experienced contributors. It is maintained by the same community that maintains Python.

[Azure Functions Python developer guide](https://docs.microsoft.com/en-us/azure/azure-functions/functions-reference-python) is an introduction to developing Azure Functions using Python. The content below assumes that you've already read the [Azure Functions developers guide](https://docs.microsoft.com/en-us/azure/azure-functions/functions-reference).

[CheckiO](https://checkio.org/) is a programming learning platform and a gamified website that teaches Python through solving code challenges and competing for the most elegant and creative solutions.

[Python Institute](https://pythoninstitute.org)

[PCEP – Certified Entry-Level Python Programmer certification](https://pythoninstitute.org/pcep-certification-entry-level/)

[PCAP – Certified Associate in Python Programming certification](https://pythoninstitute.org/pcap-certification-associate/)

[PCPP – Certified Professional in Python Programming 1 certification](https://pythoninstitute.org/pcpp-certification-professional/)

[PCPP – Certified Professional in Python Programming 2](https://pythoninstitute.org/pcpp-certification-professional/)

[MTA: Introduction to Programming Using Python Certification](https://docs.microsoft.com/en-us/learn/certifications/mta-introduction-to-programming-using-python)

[Getting Started with Python in Visual Studio Code](https://code.visualstudio.com/docs/python/python-tutorial)

[Google's Python Style Guide](https://google.github.io/styleguide/pyguide.html)

[Google's Python Education Class](https://developers.google.com/edu/python/)

[Real Python](https://realpython.com)

[The Python Open Source Computer Science Degree by Forrest Knight](https://github.com/ForrestKnight/open-source-cs-python)

[Intro to Python for Data Science](https://www.datacamp.com/courses/intro-to-python-for-data-science)

[Intro to Python by W3schools](https://www.w3schools.com/python/python_intro.asp)

[Codecademy's Python 3 course](https://www.codecademy.com/learn/learn-python-3)

[Learn Python with Online Courses and Classes from edX](https://www.edx.org/learn/python)

[Python Courses Online from Coursera](https://www.coursera.org/courses?query=python)

## Python Frameworks, Libraries, and Tools

[Python Package Index (PyPI)](https://pypi.org/) is a repository of software for the Python programming language. PyPI helps you find and install software developed and shared by the Python community.

[PyCharm](https://www.jetbrains.com/pycharm/) is the best IDE I've ever used. With PyCharm, you can access the command line, connect to a database, create a virtual environment, and manage your version control system all in one place, saving time by avoiding constantly switching between windows.

[Python Tools for Visual Studio(PTVS)](https://microsoft.github.io/PTVS/) is a free, open source plugin that turns Visual Studio into a Python IDE. It supports editing, browsing, IntelliSense, mixed Python/C++ debugging, remote Linux/MacOS debugging, profiling, IPython, and web development with Django and other frameworks.

[Django](https://www.djangoproject.com/) is a high-level Python Web framework that encourages rapid development and clean, pragmatic design.

[Flask](https://flask.palletsprojects.com/) is a micro web framework written in Python. It is classified as a microframework because it does not require particular tools or libraries.

[Web2py](http://web2py.com/) is an open-source web application framework written in Python allowing allows web developers to program dynamic web content. One web2py instance can run multiple web sites using different databases.

[AWS Chalice](https://github.com/aws/chalice) is a framework for writing serverless apps in python. It allows you to quickly create and deploy applications that use AWS Lambda.

[Tornado](https://www.tornadoweb.org/) is a Python web framework and asynchronous networking library. Tornado uses a non-blocking network I/O, which can scale to tens of thousands of open connections.

[HTTPie](https://github.com/httpie/httpie) is a command line HTTP client that makes CLI interaction with web services as easy as possible. HTTPie is designed for testing, debugging, and generally interacting with APIs & HTTP servers.

[Scrapy](https://scrapy.org/) is a fast high-level web crawling and web scraping framework, used to crawl websites and extract structured data from their pages. It can be used for a wide range of purposes, from data mining to monitoring and automated testing.

[Sentry](https://sentry.io/) is a service that helps you monitor and fix crashes in realtime. The server is in Python, but it contains a full API for sending events from any language, in any application.

[Pipenv](https://github.com/pypa/pipenv) is a tool that aims to bring the best of all packaging worlds (bundler, composer, npm, cargo, yarn, etc.) to the Python world.

[Python Fire](https://github.com/google/python-fire) is a library for automatically generating command line interfaces (CLIs) from absolutely any Python object.

[Bottle](https://github.com/bottlepy/bottle) is a fast, simple and lightweight [WSGI](https://www.wsgi.org/) micro web-framework for Python. It is distributed as a single file module and has no dependencies other than the [Python Standard Library](https://docs.python.org/library/).

[CherryPy](https://cherrypy.org) is a minimalist Python object-oriented HTTP web framework.

[Sanic](https://github.com/huge-success/sanic) is a Python 3.6+ web server and web framework that's written to go fast.

[Pyramid](https://trypyramid.com) is a small and fast open source Python web framework. It makes real-world web application development and deployment more fun and more productive.

[TurboGears](https://turbogears.org) is a hybrid web framework able to act both as a Full Stack framework or as a Microframework.

[Falcon](https://falconframework.org/) is a reliable, high-performance Python web framework for building large-scale app backends and microservices with support for MongoDB, Pluggable Applications and autogenerated Admin.

[Neural Network Intelligence(NNI)](https://github.com/microsoft/nni) is an open source AutoML toolkit for automate machine learning lifecycle, including [Feature Engineering](https://github.com/microsoft/nni/blob/master/docs/en_US/FeatureEngineering/Overview.md), [Neural Architecture Search](https://github.com/microsoft/nni/blob/master/docs/en_US/NAS/Overview.md), [Model Compression](https://github.com/microsoft/nni/blob/master/docs/en_US/Compressor/Overview.md) and [Hyperparameter Tuning](https://github.com/microsoft/nni/blob/master/docs/en_US/Tuner/BuiltinTuner.md).

[Dash](https://plotly.com/dash) is a popular Python framework for building ML & data science web apps for Python, R, Julia, and Jupyter.

[Luigi](https://github.com/spotify/luigi) is a Python module that helps you build complex pipelines of batch jobs. It handles dependency resolution, workflow management, visualization etc. It also comes with Hadoop support built-in.

[Locust](https://github.com/locustio/locust) is an easy to use, scriptable and scalable performance testing tool.

[spaCy](https://github.com/explosion/spaCy) is a library for advanced Natural Language Processing in Python and Cython.

[NumPy](https://www.numpy.org/) is the fundamental package needed for scientific computing with Python.

[Pillow](https://python-pillow.org/) is a friendly PIL(Python Imaging Library) fork.

[IPython](https://ipython.org/) is a command shell for interactive computing in multiple programming languages, originally developed for the Python programming language, that offers enhanced introspection, rich media, additional shell syntax, tab completion, and rich history.

[GraphLab Create](https://turi.com/) is a Python library, backed by a C++ engine, for quickly building large-scale, high-performance machine learning models.

[Pandas](https://pandas.pydata.org/) is a fast, powerful, and easy to use open source data structrures, data analysis and manipulation tool, built on top of the Python programming language.

[PuLP](https://coin-or.github.io/pulp/) is an Linear Programming modeler written in python. PuLP can generate LP files and call on use highly optimized solvers, GLPK, COIN CLP/CBC, CPLEX, and GUROBI, to solve these linear problems.

[Matplotlib](https://matplotlib.org/) is a 2D plotting library for creating static, animated, and interactive visualizations in Python. Matplotlib produces publication-quality figures in a variety of hardcopy formats and interactive environments across platforms.

[Scikit-Learn](https://scikit-learn.org/stable/index.html) is a simple and efficient tool for data mining and data analysis. It is built on NumPy,SciPy, and mathplotlib.

# Lua Development
[Back to the Top](https://github.com/mikeroyal/Godot-Engine-Guide#table-of-contents)

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/99859431-e1bd9280-2b44-11eb-84f7-854d3e015e21.png">
  <br />
</p>

## Lua Learning Resources

[Lua](https://www.lua.org/) is a subset of the C programming language designed to be a lightweight embeddable scripting language used by many frameworks and games.

[Programming in Lua ebook](https://www.lua.org/pil/contents.html)

[Getting started with Lua](https://www.lua.org/start.html)

[Intro to Lua from Core Academy](https://learn.coregames.com/courses/intro-to-lua/)

[Online Lua Classes on Skillshare](https://www.skillshare.com/browse/lua)

[Online Lua Classes on Udemy](https://www.udemy.com/topic/lua/?ratings=4.0&sort=popularity)

[Lua Training Courses from Nobleprog](https://www.nobleprog.com/lua-training)

[RoboCode Academy from Roblox](https://corp.roblox.com/education/)

## Lua Tools, Libraries, and Frameworks

[Lua Language Server](https://github.com/sumneko/lua-language-server) is an extension for VSCode that provides support for the Lua Language Server.

[Apache APISIX](https://github.com/apache/apisix) is a dynamic, real-time, high-performance API gateway, based on the Nginx library and etcd.

[NodeMCU](https://github.com/nodemcu/nodemcu-firmware) is an open source Lua based firmware for the [ESP8266 WiFi SOC from Espressif](https://espressif.com/en/products/esp8266/) and uses an on-module flash-based [SPIFFS](https://github.com/pellepl/spiffs) file system.

[GopherLua](https://github.com/yuin/gopher-lua) is a Lua 5.1 VM and compiler written in Go.

[MoonScript](https://github.com/leafo/moonscript) is a programmer friendly language that compiles into Lua.

[Lapis](https://github.com/leafo/lapis) is a web framework for Lua/MoonScript supporting [OpenResty](https://openresty.org/en/) or [http.server](https://github.com/daurnimator/lua-http).

[Algernon](https://algernon.roboticoverlords.org) is a web server with built-in support for QUIC, HTTP/2, Lua, Markdown, Pongo2, HyperApp, Amber, Sass(SCSS), GCSS, JSX, BoltDB (built-in, stores the database in a file, like SQLite), Redis, PostgreSQL, MariaDB/MySQL, rate limiting, graceful shutdown, plugins, users and permissions.

[Lua Fun](https://luafun.github.io/) is a high-performance functional programming library for Lua designed with LuaJIT's trace compiler in mind.

[Luakit](https://luakit.github.io/) is a fast, light and simple to use micro-browser framework extensible by Lua using the WebKit web content engine and the GTK+ toolkit.

[Lua Resty HTTP](https://github.com/ledgetech/lua-resty-http) is an HTTP client cosocket driver for [OpenResty](https://openresty.org/en/)/ [ngx_lua](https://github.com/openresty/lua-nginx-module).

[NLua](https://github.com/NLua/NLua) is a bridge between Lua world and the .NET (compatible with .NET Core/UWP/Mac/Linux/Android/iOS/tvOS).

# Networking
[Back to the Top](https://github.com/mikeroyal/Godot-Engine-Guide#table-of-contents)

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/82833053-d1687b80-9e71-11ea-8c6d-074100f2f54b.png">
  <br />
</p>

## Networking Tools & Concepts

[cURL](https://curl.se/) is a computer software project providing a library and command-line tool for transferring data using various network protocols(HTTP, HTTPS, FTP, FTPS, SCP, SFTP, TFTP, DICT, TELNET, LDAP LDAPS, MQTT, POP3, POP3S, RTMP, RTMPS, RTSP, SCP, SFTP, SMB, SMBS, SMTP or SMTPS). cURL is also used in cars, television sets, routers, printers, audio equipment, mobile phones, tablets, settop boxes, media players and is the Internet transfer engine for thousands of software applications in over ten billion installations.

[cURL Fuzzer](https://github.com/curl/curl-fuzzer) is a quality assurance testing for the curl project.

[DoH](https://github.com/curl/doh) is a stand-alone application for DoH (DNS-over-HTTPS) name resolves and lookups.

[Authelia](https://www.authelia.com/) is an open-source highly-available authentication server providing single sign-on capability and two-factor authentication to applications running behind [NGINX](https://nginx.org/en/).

[nginx(engine x)](https://nginx.org/en/) is an HTTP and reverse proxy server, a mail proxy server, and a generic TCP/UDP proxy server, originally written by Igor Sysoev.

[Proxmox Virtual Environment(VE)](https://www.proxmox.com/en/) is a complete open-source platform for enterprise virtualization. It inlcudes a built-in web interface that you can easily manage VMs and containers, software-defined storage and networking, high-availability clustering, and multiple out-of-the-box tools on a single solution.

[Wireshark](https://www.wireshark.org/) is a very popular network protocol analyzer that is commonly used for network troubleshooting, analysis, and communications protocol development. Learn more about the other useful [Wireshark Tools](https://wiki.wireshark.org/Tools) available.

[HTTPie](https://github.com/httpie/httpie) is a command-line HTTP client. Its goal is to make CLI interaction with web services as human-friendly as possible. HTTPie is designed for testing, debugging, and generally interacting with APIs & HTTP servers.

[HTTPStat](https://github.com/reorx/httpstat) is a tool that visualizes curl statistics in a simple layout.

[Wuzz](https://github.com/asciimoo/wuzz) is an interactive cli tool for HTTP inspection. It can be used to inspect/modify requests copied from the browser's network inspector with the "copy as cURL" feature.

[Websocat](https://github.com/vi/websocat) is a ommand-line client for WebSockets, like netcat (or curl) for ws:// with advanced socat-like functions.

    • Connection: In networking, a connection refers to pieces of related information that are transferred through a network. This generally infers that a connection is built before the data transfer (by following the procedures laid out in a protocol) and then is deconstructed at the at the end of the data transfer.

    • Packet: A packet is, generally speaking, the most basic unit that is transferred over a network. When communicating over a network, packets are the envelopes that carry your data (in pieces) from one end point to the other.

Packets have a header portion that contains information about the packet including the source and destination, timestamps, network hops. The main portion of a packet contains the actual data being transferred. It is sometimes called the body or the payload.

    • Network Interface: A network interface can refer to any kind of software interface to networking hardware. For instance, if you have two network cards in your computer, you can control and configure each network interface associated with them individually.

A network interface may be associated with a physical device, or it may be a representation of a virtual interface. The "loop-back" device, which is a virtual interface to the local machine, is an example of this.

    • LAN: LAN stands for "local area network". It refers to a network or a portion of a network that is not publicly accessible to the greater internet. A home or office network is an example of a LAN.

    • WAN: WAN stands for "wide area network". It means a network that is much more extensive than a LAN. While WAN is the relevant term to use to describe large, dispersed networks in general, it is usually meant to mean the internet, as a whole.
If an interface is connected to the WAN, it is generally assumed that it is reachable through the internet.

    • Protocol: A protocol is a set of rules and standards that basically define a language that devices can use to communicate. There are a great number of protocols in use extensively in networking, and they are often implemented in different layers.

Some low level protocols are TCP, UDP, IP, and ICMP. Some familiar examples of application layer protocols, built on these lower protocols, are HTTP (for accessing web content), SSH, TLS/SSL, and FTP.

    • Port: A port is an address on a single machine that can be tied to a specific piece of software. It is not a physical interface or location, but it allows your server to be able to communicate using more than one application.

    • Firewall: A firewall is a program that decides whether traffic coming into a server or going out should be allowed. A firewall usually works by creating rules for which type of traffic is acceptable on which ports. Generally, firewalls block ports that are not used by a specific application on a server.

    • NAT: Network address translation is a way to translate requests that are incoming into a routing server to the relevant devices or servers that it knows about in the LAN. This is usually implemented in physical LANs as a way to route requests through one IP address to the necessary backend servers.

    • VPN: Virtual private network is a means of connecting separate LANs through the internet, while maintaining privacy. This is used as a means of connecting remote systems as if they were on a local network, often for security reasons.

## Network Layers

	While networking is often discussed in terms of topology in a horizontal way, between hosts, its implementation is layered in a vertical fashion throughout a computer or network. This means is that there are multiple technologies and protocols that are built on top of each other in order for communication to function more easily. Each successive, higher layer abstracts the raw data a little bit more, and makes it simpler to use for applications and users. It also allows you to leverage lower layers in new ways without having to invest the time and energy to develop the protocols and applications that handle those types of traffic.

	As data is sent out of one machine, it begins at the top of the stack and filters downwards. At the lowest level, actual transmission to another machine takes place. At this point, the data travels back up through the layers of the other computer. Each layer has the ability to add its own "wrapper" around the data that it receives from the adjacent layer, which will help the layers that come after decide what to do with the data when it is passed off.

	One method of talking about the different layers of network communication is the OSI model. OSI stands for Open Systems Interconnect.This model defines seven separate layers. The layers in this model are:

    • Application: The application layer is the layer that the users and user-applications most often interact with. Network communication is discussed in terms of availability of resources, partners to communicate with, and data synchronization.

    • Presentation: The presentation layer is responsible for mapping resources and creating context. It is used to translate lower level networking data into data that applications expect to see.

    • Session: The session layer is a connection handler. It creates, maintains, and destroys connections between nodes in a persistent way.

    • Transport: The transport layer is responsible for handing the layers above it a reliable connection. In this context, reliable refers to the ability to verify that a piece of data was received intact at the other end of the connection. This layer can resend information that has been dropped or corrupted and can acknowledge the receipt of data to remote computers.

    • Network: The network layer is used to route data between different nodes on the network. It uses addresses to be able to tell which computer to send information to. This layer can also break apart larger messages into smaller chunks to be reassembled on the opposite end.

    • Data Link: This layer is implemented as a method of establishing and maintaining reliable links between different nodes or devices on a network using existing physical connections.

    • Physical: The physical layer is responsible for handling the actual physical devices that are used to make a connection. This layer involves the bare software that manages physical connections as well as the hardware itself (like Ethernet).

The TCP/IP model, more commonly known as the Internet protocol suite, is another layering model that is simpler and has been widely adopted.It defines the four separate layers, some of which overlap with the OSI model:

    • Application: In this model, the application layer is responsible for creating and transmitting user data between applications. The applications can be on remote systems, and should appear to operate as if locally to the end user.
The communication takes place between peers network.

    • Transport: The transport layer is responsible for communication between processes. This level of networking utilizes ports to address different services. It can build up unreliable or reliable connections depending on the type of protocol used.

    • Internet: The internet layer is used to transport data from node to node in a network. This layer is aware of the endpoints of the connections, but does not worry about the actual connection needed to get from one place to another. IP addresses are defined in this layer as a way of reaching remote systems in an addressable manner.

    • Link: The link layer implements the actual topology of the local network that allows the internet layer to present an addressable interface. It establishes connections between neighboring nodes to send data.

### Interfaces
**Interfaces** are networking communication points for your computer. Each interface is associated with a physical or virtual networking device. Typically, your server will have one configurable network interface for each Ethernet or wireless internet card you have. In addition, it will define a virtual network interface called the "loopback" or localhost interface. This is used as an interface to connect applications and processes on a single computer to other applications and processes. You can see this referenced as the "lo" interface in many tools.

## Network Protocols

Networking works by piggybacks on a number of different protocols on top of each other. In this way, one piece of data can be transmitted using multiple protocols encapsulated within one another.

**Media Access Control(MAC)** is a communications protocol that is used to distinguish specific devices. Each device is supposed to get a unique MAC address during the manufacturing process that differentiates it from every other device on the internet. Addressing hardware by the MAC address allows you to reference a device by a unique value even when the software on top may change the name for that specific device during operation. Media access control is one of the only protocols from the link layer that you are likely to interact with on a regular basis.

**The IP protocol** is one of the fundamental protocols that allow the internet to work. IP addresses are unique on each network and they allow machines to address each other across a network. It is implemented on the internet layer in the IP/TCP model. Networks can be linked together, but traffic must be routed when crossing network boundaries. This protocol assumes an unreliable network and multiple paths to the same destination that it can dynamically change between. There are a number of different implementations of the protocol. The most common implementation today is IPv4, although IPv6 is growing in popularity as an alternative due to the scarcity of IPv4 addresses available and improvements in the protocols capabilities.

**ICMP: internet control message protocol** is used to send messages between devices to indicate the availability or error conditions. These packets are used in a variety of network diagnostic tools, such as ping and traceroute. Usually ICMP packets are transmitted when a packet of a different kind meets some kind of a problem. Basically, they are used as a feedback mechanism for network communications.

**TCP: Transmission control protocol** is implemented in the transport layer of the IP/TCP model and is used to establish reliable connections. TCP is one of the protocols that encapsulates data into packets. It then transfers these to the remote end of the connection using the methods available on the lower layers. On the other end, it can check for errors, request certain pieces to be resent, and reassemble the information into one logical piece to send to the application layer. The protocol builds up a connection prior to data transfer using a system called a three-way handshake. This is a way for the two ends of the communication to acknowledge the request and agree upon a method of ensuring data reliability. After the data has been sent, the connection is torn down using a similar four-way handshake. TCP is the protocol of choice for many of the most popular uses for the internet, including WWW, FTP, SSH, and email. It is safe to say that the internet we know today would not be here without TCP.

**UDP: User datagram protocol** is a popular companion protocol to TCP and is also implemented in the transport layer. The fundamental difference between UDP and TCP is that UDP offers unreliable data transfer. It does not verify that data has been received on the other end of the connection. This might sound like a bad thing, and for many purposes, it is. However, it is also extremely important for some functions. It’s not required to wait for confirmation that the data was received and forced to resend data, UDP is much faster than TCP. It does not establish a connection with the remote host, it simply fires off the data to that host and doesn't care if it is accepted or not. Since UDP is a simple transaction, it is useful for simple communications like querying for network resources. It also doesn't maintain a state, which makes it great for transmitting data from one machine to many real-time clients. This makes it ideal for VOIP, games, and other applications that cannot afford delays.

**HTTP: Hypertext transfer protocol** is a protocol defined in the application layer that forms the basis for communication on the web. HTTP defines a number of functions that tell the remote system what you are requesting. For instance, GET, POST, and DELETE all interact with the requested data in a different way.

**FTP: File transfer protocol** is in the application layer and provides a way of transferring complete files from one host to another. It is inherently insecure, so it is not recommended for any externally facing network unless it is implemented as a public, download-only resource.

**DNS: Domain name system** is an application layer protocol used to provide a human-friendly naming mechanism for internet resources. It is what ties a domain name to an IP address and allows you to access sites by name in your browser.

**SSH: Secure shell** is an encrypted protocol implemented in the application layer that can be used to communicate with a remote server in a secure way. Many additional technologies are built around this protocol because of its end-to-end encryption and ubiquity. There are many other protocols that we haven't covered that are equally important. However, this should give you a good overview of some of the fundamental technologies that make the internet and networking possible.

[REST(REpresentational State Transfer)](https://www.codecademy.com/articles/what-is-rest) is an architectural style for providing standards between computer systems on the web, making it easier for systems to communicate with each other.

[JSON Web Token (JWT)](https://jwt.io) is a compact URL-safe means of representing claims to be transferred between two parties. The claims in a JWT are encoded as a JSON object that is digitally signed using JSON Web Signature (JWS).

[OAuth 2.0](https://oauth.net/2/) is an open source authorization framework that enables applications to obtain limited access to user accounts on an HTTP service, such as Amazon, Google, Facebook, Microsoft, Twitter GitHub, and DigitalOcean. It works by delegating user authentication to the service that hosts the user account, and authorizing third-party applications to access the user account.


## Contribute

- [x] If would you like to contribute to this guide simply make a [Pull Request](https://github.com/mikeroyal/Godot-Engine-Guide/pulls).


## License
[Back to the Top](https://github.com/mikeroyal/Godot-Engine-Guide#table-of-contents)

Distributed under the [Creative Commons Attribution 4.0 International (CC BY 4.0) Public License](https://creativecommons.org/licenses/by/4.0/).

