<div align="center">

   # Re换肤

[English](README.md)|**&gt; 简体中文 &lt;** 

</div>

# 编译

1. 通过输入命令： `git clone --recursive https://github.com/hydy100/R3nzSkin.git`或者直接下载下载 [R3nzSkin](https://github.com/hydy100/R3nzSkin/archive/refs/heads/main.zip)到本地

   - **如果你不修改这个源代码，在中国服务器上编译和使用它肯定会导致禁令。但如果你知道如何修改它，你可以让它和我发布的版本一样安全。**

2. 在Visual Studio 2019/2022中构建，配置为 "你所在的地区  x64"。

   > 小提示: 外服的注入方式是`SetWindowsHookEx`, 不需要说更多了，也别在问我了。

# 使用

1. 编译源代码或下载 [编译版本](https://github.com/hydy100/R3nzSkin/releases/latest)。
2. 然后查看: [使用说明](https://hydy100.top/zh/) ，我在里面写了详细的说明。

# 关于这个项目

- 每次发布的一些说明我都写在[Releases](https://github.com/hydy100/R3nzSkin/releases/latest)的描述里。
- **我几乎没在其他任何平台发过此项目，所以如果你转发了，请同时帮忙解决一些问题，而不是让他们都找到我，或者提供[此项目的地址](https://github.com/hydy100/R3nzSkin)，让他提issues**。
- **没有付费版或者其他版本，没有强制加群，只不过是留了个联系方式，所有的文件我都发布了**。
- 项目目前纯公益，像原来的[R3](https://github.com/R3nzTheCodeGOD/R3nzSkin)一样，我没有通过这个项目赚过钱。
- 有些问题我无法很好地解决，所以如果你愿意，我欢迎任何有能力帮助解决这些问题的人。

# 进一步优化

如果您的CPU支持AVX / AVX2 / AVX-512指令集，您可以在项目设置中启用它。这应该会产生性能更高的代码，并针对您的 CPU 进行了优化。目前在项目设置中选择了SSE2指令。

# 制作人员

该程序是 [R3nzTheCodeGOD](https://github.com/R3nzTheCodeGOD)/[R3nzSkin](https://github.com/R3nzTheCodeGOD/R3nzSkin) 项目的改进和更新版本。