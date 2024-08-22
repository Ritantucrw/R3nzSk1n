<div align="center">

# R3nzSkin

**&gt; English &lt;** | [简体中文](README_zh.md)

</div>

# Building

1. Clone the source with `git clone --recursive https://github.com/hydy100/R3nzSkin.git`

   - **If you don't modify this source code, compiling and using it on Chinese servers will definitely result in a ban. The functionality is fine, but if you know how to modify it, you can make it as safe as the version I released.**

2. Build in Visual Studio 2019/2022 with configuration "Your Region - x64"

   > Quick tip: RiotServers uses `SetWindowsHookEx` for injection. That's all there is to it, so please don't ask me about it anymore.

# Usage

1. Compile source or [download](https://github.com/hydy100/R3nzSkin/releases/latest) a compiled version.
2. Then check: [Instructions for use](https://hydy100.top/) ,I've written the detailed instructions inside.

# About the project

- I include some explanations for each release in the description of [Releases](https://github.com/hydy100/R3nzSkin/releases/latest).
- **I've hardly posted this project on any other platform, so if you share it, please help solve some issues rather than redirecting everything to me. Alternatively, provide [R3nzSkin](https://github.com/hydy100/R3nzSkin) so they can submit issues there.**
- **There is no paid version or any other versions, and there is no requirement to join any groups. I've released all the files, I just left a contact method.**
- The project is currently purely non-profit, just like the original [R3nzSkin](https://github.com/R3nzTheCodeGOD/R3nzSkin). I haven't made any money from it
- There are some issues I can't solve very well, so I welcome anyone with the ability to help resolve them, if you're willing.

# Further optimizations

If your CPU supports AVX / AVX2 / AVX-512 instruction set, you can enable it in project settings. This should result in more performant code, optimized for your CPU. Currently SSE2 instructions are selected in project settings.

# Credits

This program is an improved and updated version of the [R3nzTheCodeGOD](https://github.com/R3nzTheCodeGOD)/[R3nzSkin](https://github.com/R3nzTheCodeGOD/R3nzSkin) project.
