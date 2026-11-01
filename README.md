# AveritA 的 DSH 插件

给 [DeepSeek Harness](https://github.com/deepseek-ai/dsh) 做的各种美化+体验改进插件。一个插件一个仓库，可各自安装，无互相依赖/冲突。

## DSH主题集 · averita-dsh-theme-inspiration

简约克制而不失个性的的DSH主题。

四套主题色：昼雾 · 靛夜 / 冷晨 / 暮玫瑰 / 暮紫；两种背景：点阵 / 流光（WebGL 噪声场）；两种个性用户消息框：原生 / 纸品 / 星芒；品牌字标、新会话首屏星标与文案可自定义；设置 → 主题里即时切换。

希望给大家带来一些灵感~

<p align="center"><img src="https://raw.githubusercontent.com/Traveritas/averita-dsh-theme-inspiration/main/preview/shots-new/a-l.png" width="640" alt="昼雾 · 靛夜 浅色实机"></p>

[仓库 →](https://github.com/Traveritas/averita-dsh-theme-inspiration) · [安装说明](https://github.com/Traveritas/averita-dsh-theme-inspiration#安装)

## 侧栏工作区卡片 · dsh-workspace-cards

把侧栏「工作区」换成**正方形卡片网格**：两种视口：**工作区优先**——当前工作区常驻在网格上方（点任意卡片换到常驻位，再点一次收起；分隔条可拖高度）；**会话栏优先**——会话栏贴边铺满，卡片收进底部「工作区」按钮，点开抽屉选工作区就会打开它最近一条会话。

角标区分待处理 / 运行中 / 未读完成。

卡片大小、圆角（0% 方块 → 50% 整圆）、图标大小、名称 / 边框 / 滚动条显隐可调；

图标可用字符、内置图标、自定义 SVG 或本机文件自定义。

<p align="center"><img src="https://raw.githubusercontent.com/Traveritas/dsh-workspace-cards/main/docs/demo.gif?v=0.4.0" width="260" alt="演示：悬停名称、切换两种视口、底部按钮开合卡片抽屉"></p>

[仓库 →](https://github.com/Traveritas/dsh-workspace-cards) · [安装说明](https://github.com/Traveritas/dsh-workspace-cards#安装)

## 推理强度滑条 · dsh-yet-another-slider-thingy

把 composer 的模型位替换成「模型行 + 推理强度滑条」：三套外观、五套特效、独立可自定义配色，逐档 / 平滑两种拖动手感。

<p align="center"><img src="https://raw.githubusercontent.com/Traveritas/dsh-yet-another-slider-thingy/master/docs/skins.gif" width="560" alt="三套外观：紧凑 / 块面 / 胶囊"></p>

[仓库 →](https://github.com/Traveritas/dsh-yet-another-slider-thingy) · [安装说明](https://github.com/Traveritas/dsh-yet-another-slider-thingy#安装)

## 安装

都走 DSH 自带的应用内插件管理器。先克隆要装的那个仓库（以工作区卡片为例）：

```powershell
git clone --depth 1 https://github.com/Traveritas/dsh-workspace-cards.git D:\dsh\dsh-workspace-cards
```

然后 **设置 → 插件 → 添加插件**，spec 填克隆目录的**绝对路径**。看返回的 `application`：`applied` 即生效；`restart-required` 就完全退出桌面端再开。

> 桌面端的 profile 由 Electron 独占，命令行 `dsh plugin --profile desktop ...` 会被拒，安装 / 卸载都走应用内插件管理器。

每个仓库的 README 里写了它自己的配置项、依赖和已知限制。

## 另外

- [petween-dsh](https://github.com/Traveritas/petween-dsh)：桌宠插件，但停止开发了，已转向桌面端，想了想还是放在这儿吧。

## 致谢
[LINUX DO](https://linux.do)

## 许可

各仓库均为 MIT，随便取用、随意魔改。
