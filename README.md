# AveritA 的 DSH 插件

给 [DeepSeek Harness](https://github.com/deepseek-ai/dsh) 做的各种插件。一个插件一个仓库，可各自安装，无互相依赖/冲突。

## DSH主题集 · averita-dsh-theme-inspiration

四套主题：昼雾 · 靛夜 / 冷晨 / 暮玫瑰 / 暮紫。背景二选一——点阵（四形，缩放 / 浓淡 / 动效可调））或流光（WebGL 噪声场；可自定义的品牌字标、新会话首屏。设置 → 主题里即时切换。

<p align="center"><img src="https://raw.githubusercontent.com/Traveritas/averita-dsh-theme-inspiration/main/preview/shots-new/a-l.png" width="640" alt="昼雾 · 靛夜 浅色实机"></p>

[仓库 →](https://github.com/Traveritas/averita-dsh-theme-inspiration) · [安装说明](https://github.com/Traveritas/averita-dsh-theme-inspiration#安装)

## 侧栏工作区卡片 · dsh-workspace-cards

把侧栏「工作区」换成图标网格，点卡片原地放大成会话面板；角标区分待处理 / 运行中 / 未读完成，图标可用字符、内置线性图标或自定义 SVG。

<p align="center"><img src="https://raw.githubusercontent.com/Traveritas/dsh-workspace-cards/main/docs/grid.png" width="200" alt="工作区卡片网格"> <img src="https://raw.githubusercontent.com/Traveritas/dsh-workspace-cards/main/docs/panel.png" width="200" alt="点卡片原地展开成会话面板"></p>

[仓库 →](https://github.com/Traveritas/dsh-workspace-cards) · [安装说明](https://github.com/Traveritas/dsh-workspace-cards#安装--卸载)

## 推理强度滑条 · dsh-yet-another-slider-thingy

把 composer 的模型位替换成「模型行 + 推理强度滑条」：三套外观、五套特效、独立可自定义配色，逐档 / 平滑两种拖动手感。

<p align="center"><img src="https://raw.githubusercontent.com/Traveritas/dsh-yet-another-slider-thingy/master/docs/skins.gif" width="560" alt="三套外观：紧凑 / 块面 / 胶囊"></p>

[仓库 →](https://github.com/Traveritas/dsh-yet-another-slider-thingy) · [安装说明](https://github.com/Traveritas/dsh-yet-another-slider-thingy#安装)

## 安装

都走 DSH 自带的应用内插件管理器：

```powershell
git clone --depth 1 https://github.com/Traveritas/<仓库名>.git D:\dsh\<目录名>
```

然后 **设置 → 插件 → 添加插件**，spec 填克隆目录的**绝对路径**。看返回的 `application`：`applied` 即生效；`restart-required` 就完全退出桌面端再开。

每个仓库的 README 里写了它自己的配置项、依赖和已知限制。

## 另外

- [petween-dsh](https://github.com/Traveritas/petween-dsh)：桌宠插件，但停止开发了，已转向桌面端，想了想还是放在这儿吧。

## 许可

各仓库均为 MIT，随便取用、随意魔改。
