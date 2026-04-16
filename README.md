# RyuuJiWarudoMods

[中文](README.md) | [English](README_EN.md)

这是一个用于发布 Warudo / Unity Mods 的开源仓库。

我会在这里整理并分享为 [Warudo](https://warudo.app/) 制作的场景、特效和扩展功能。当前内容主要面向 Unity URP 环境，也可以在经过简单的调整后用于其他基于 Unity URP 的长期支持版本项目。

我还在整理一些旧资产，并计划在优化后逐步补充到本仓库。除此之外，我也在准备 Unity / Godot 开发框架、游戏模板，以及其他独立软件项目。

由于完整 Unity 工程通常包含大量缓存和工程文件，本仓库不会直接提交完整工程，而是以 `.unitypackage` 的形式发布可导入资源。

## 当前内容

### RyuujiSceneNo59

`RyuujiSceneNo59` 是一个风格化太空舞台场景，包含特效、Volume 配置、动态物体，以及可通过配套 Playground 脚本控制的交互内容。

![RyuujiSceneNo59 Cover](Scenes/RyuujiSceneNo59/Cover.png)

资源路径：

```text
Scenes/RyuujiSceneNo59/RyuujiSceneNo59.unitypackage
```

主要特性：

- 风格化太空舞台环境。
- URP 视觉效果与 Volume 配置。
- 动态物体与可控粒子效果。
- `AutoAnime`：简洁、可复用的程序化动画组件。
- `DynamicPar`：面向 Warudo 的粒子系统控制组件。

## 使用方式

1. 下载或克隆本仓库。
2. 在 Unity 中打开你的 Warudo / URP 项目。
3. 导入目标 `.unitypackage`。
4. 按对应场景目录下的 `readme.md` 检查 Unity、uMod 和依赖版本。

当前 `RyuujiSceneNo59` 的推荐环境：

- Unity `2021.3.45f2`
- uMod `2.9.0` 或更新版本
- Unity Render Pipeline：URP

## 许可与署名

本仓库主体内容采用 MIT License 发布。你可以自由使用、修改和分发这些内容。

项目中可能包含第三方开源或授权资源；相关来源、作者和许可证会记录在对应资源目录的 `readme.md` 中。使用时请遵守原作者的授权要求。

虽然 MIT License 不强制要求署名，但如果你愿意标注 `KatouRyuuji` 或本仓库链接，我会非常感谢。

## 交流与支持

欢迎进行技术交流，方向包括 Unity、Unreal Engine、Godot、软件开发、虚拟制作与动捕等。

- GitHub：[KatouRyuuji](https://github.com/KatouRyuuji)
- Bilibili：[加藤龙儿的个人空间](https://space.bilibili.com/445111)
- Email：1984211921@qq.com

目前暂未开放捐助渠道。如果你喜欢这个项目，可以通过 Star 本仓库或关注我的 B 站来支持我。
