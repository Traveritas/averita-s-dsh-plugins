# AveritA 的 DSH 插件

给 [DeepSeek Harness](https://github.com/deepseek-ai/dsh) 做的界面与主题插件。一个插件一个仓库，各自安装、各自升级，装哪个都不影响别的。

## 主题集 · averita-dsh-theme-inspiration

四套主题：昼雾 · 靛夜 / 冷晨 / 暮玫瑰 / 暮紫。背景二选一——点阵（四形，缩放 / 浓淡 / 动效可调）或流光（WebGL 噪声场）；品牌字标、新会话首屏星标都能改。设置 → 主题里即时切换。

<img src="https://raw.githubusercontent.com/Traveritas/averita-dsh-theme-inspiration/main/preview/shots-new/a-l.png" width="640" alt="昼雾 · 靛夜 浅色实机">

[仓库 →](https://github.com/Traveritas/averita-dsh-theme-inspiration) · [安装说明](https://github.com/Traveritas/averita-dsh-theme-inspiration#安装)

## 侧栏工作区卡片 · dsh-workspace-cards

把侧栏「工作区」换成图标网格，点卡片原地放大成会话面板；角标区分待处理 / 运行中 / 未读完成，图标可用字符、内置线性图标或自定义 SVG。

<img src="https://raw.githubusercontent.com/Traveritas/dsh-workspace-cards/main/docs/grid.png" width="260" alt="工作区卡片网格">

[仓库 →](https://github.com/Traveritas/dsh-workspace-cards) · [安装说明](https://github.com/Traveritas/dsh-workspace-cards#安装)

## 模型位滑条 · dsh-yet-another-slider-thingy

把 composer 的模型位换成「模型行 + 思考强度滑条」：三套外观、五套特效、独立配色，拖动可切逐档 / 平滑。

<img src="https://raw.githubusercontent.com/Traveritas/dsh-yet-another-slider-thingy/master/docs/skins.gif" width="560" alt="三套外观：紧凑 / 块面 / 胶囊">

[仓库 →](https://github.com/Traveritas/dsh-yet-another-slider-thingy) · [安装说明](https://github.com/Traveritas/dsh-yet-another-slider-thingy#安装)

## 安装

都走 DSH 自带的应用内插件管理器，不用发版：

```powershell
git clone --depth 1 https://github.com/Traveritas/<仓库名>.git D:\dsh\<目录名>
```

然后 **设置 → 插件 → 添加插件**，spec 填克隆目录的**绝对路径**。看返回的 `application`：`applied` 即生效；`restart-required` 就完全退出桌面端再开。

每个仓库的 README 里写了它自己的配置项、依赖和已知限制。

## 另外

- [petween-dsh](https://github.com/Traveritas/petween-dsh)：桌宠插件，同一套 DSH 插件机制，但跟上面这组界面件不是一路，放在这儿只是方便找。

## 许可

各仓库均为 MIT，随便取用、随意魔改。
