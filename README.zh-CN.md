# PhotoCraft 中文指南

[English](README.md) · **简体中文**

[PhotoCraft](https://github.com/storytold/photocraft) 是用 Rust 编写的开源 Photoshop 替代品。这里是它的非官方实用指南，正文在 **[photocraft.im](https://photocraft.im/zh/)**，提供中文和英文版本。本仓库是指南的目录，也是反馈入口：发现指南写错了、过时了或缺了内容，欢迎[提交 Issue](https://github.com/clearlove567/photocraft-guide/issues/new/choose)。

> **非官方声明：** photocraft.im 是社区项目，与开发 PhotoCraft 的 ArtCraft 团队没有关联。站内所有下载链接都指向 [GitHub 官方发布页](https://github.com/storytold/photocraft/releases)，本站不托管任何安装包。PhotoCraft 的官方地址是 [storytold/photocraft](https://github.com/storytold/photocraft) 和 [getartcraft.com](https://getartcraft.com/apps/photocraft)。PhotoCraft 软件本身的 Bug 请提交到[上游仓库](https://github.com/storytold/photocraft/issues)，不要提交到这里。

指南目前对应 **PhotoCraft v0.7.0**（2026 年 10 月）。上游几乎每一两天就发一个新版本，所以每篇指南都列出了参考来源和最后核对日期。

## 在浏览器里直接用

- **[在线编辑器](https://photocraft.im/zh/online)**：在 [photocraft.im/app/](https://photocraft.im/app/) 运行未经修改的 PhotoCraft 官方网页版。页面会显示版本号和发布包的 SHA-256，可以和官方 `SHA256SUMS.txt` 对照。图片只在你自己的设备上处理，不会上传。网页版目前只有英文界面，想用中文界面请安装桌面版。

## 下载与安装

| 指南 | 内容 |
|---|---|
| [Windows 版](https://photocraft.im/zh/download/windows) | MSI 和便携版怎么选（x64、ARM64、x86），安装向导，SHA256 校验，`photocraft-cli.exe` 在哪里，Intel 显卡启动崩溃等问题的解决办法。 |
| [Mac 版](https://photocraft.im/zh/download/mac) | 已签名并公证的通用 DMG（支持 Apple 芯片和 Intel），社区维护的 Homebrew cask，单独安装命令行工具，老款 Mac 启动问题。 |
| [Linux 版](https://photocraft.im/zh/download/linux) | AppImage、deb、rpm、Flatpak 和压缩包（x86_64、ARM64，另有 RISC-V 压缩包），Wayland 下拖放失效与 X11 开关，数位板问题，以及 FreeBSD 版。 |
| [网页版（WebAssembly）](https://photocraft.im/zh/download/web) | `photocraft-web.zip` 里有什么，怎么部署到静态服务器或 Docker，浏览器要求（WebGPU 或 WebGL2），以及和桌面版的区别。 |

所有平台见[下载页](https://photocraft.im/zh/download)。

## 使用指南

| 指南 | 内容 |
|---|---|
| [设置中文界面](https://photocraft.im/zh/guides/language) | 官方版自带简体中文和繁體中文，共 17 种界面语言，切换无需重启；附中文输入法提示和仍是英文的部分。 |
| [快捷键大全](https://photocraft.im/zh/guides/shortcuts) | 按 v0.7.0 源码核对的全部默认快捷键，分 Windows、Linux 与 macOS 列出：菜单命令、工具切换、画笔大小、数字键调不透明度、图层、裁剪，以及如何自定义。 |
| [支持的文件格式](https://photocraft.im/zh/guides/file-formats) | 能打开、能保存哪些文件：PSD/PSB、Affinity、Paint.NET、OpenRaster、SVG、HEIC、相机 RAW、TIFF、WebP、EXR 等，附位深说明、其他软件文件转 PSD 的方法和网页版的限制。 |
| [CLI 与 MCP 自动化](https://photocraft.im/zh/guides/mcp-cli) | 用 `photocraft-cli` 批量转换和处理图片；接入 PhotoCraft 的 MCP 服务器，让 Claude Code、Claude Desktop、Cursor 等 AI 助手修图导出，文件访问限定在你指定的目录。 |
| [故障排除](https://photocraft.im/zh/guides/troubleshooting) | 启动闪退、显卡与 Wayland 兼容、数位板没有压感、无法保存、文字 Bug 等问题，标明各问题在哪个版本修复，以及日志位置和反馈 Bug 的方法。 |

## 版本更新

每个版本更新了什么，用通俗的话讲清楚：[全部版本更新](https://photocraft.im/zh/releases)。

- [v0.5.0](https://photocraft.im/zh/releases/v0.5.0)：一键移除背景、重新打光、HEIC、CPU 渲染模式和六种新界面语言。
- [v0.3.0](https://photocraft.im/zh/releases/v0.3.0)：首次提供中文界面，保存更安全，新增 Flatpak、FreeBSD 和 Windows ARM64 版。
- [v0.2.0](https://photocraft.im/zh/releases/v0.2.0)：相机 RAW、色彩管理画布、沙盒插件和更安全的自动化。
- [v0.1.1](https://photocraft.im/zh/releases/v0.1.1)：照片合并、合并到 HDR Pro、变量和视频时间轴。
- [v0.1.0](https://photocraft.im/zh/releases/v0.1.0)：首个公开版本。

## 反馈指南问题

- **指南写错了或过时了：** 用[指南错误](https://github.com/clearlove567/photocraft-guide/issues/new?template=guide-error.yml)表单，写上页面地址；方便的话附上你测试的 PhotoCraft 版本。
- **想看某个主题：** 用[指南建议](https://github.com/clearlove567/photocraft-guide/issues/new?template=guide-request.yml)表单。
- **PhotoCraft 软件本身闪退或出错：** 请提交到 [PhotoCraft 官方 Issue](https://github.com/storytold/photocraft/issues)，需要附带哪些信息见[故障排除指南](https://photocraft.im/zh/guides/troubleshooting#日志设置与反馈-bug)。

## 许可

本仓库的文字采用 [CC BY 4.0](LICENSE) 许可。PhotoCraft 版权归 ArtCraft 团队所有，以 MIT OR Apache-2.0 许可发布，详见[其仓库](https://github.com/storytold/photocraft)。
