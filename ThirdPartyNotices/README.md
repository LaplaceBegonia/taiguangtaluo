# 素材与许可

所有必需资源均已放入工程；PrimeTween 由 Unity Package Manager 从 npm 安装。

| 内容 | 来源 | 许可与说明 |
| --- | --- | --- |
| 78 张牌面 | [metabismuth/tarot-json](https://github.com/metabismuth/tarot-json)，仓库版权人为 equokka | MIT；原始 RWS 牌面扫描。许可见 `RWS-MIT-LICENSE.txt`。不使用其解读代码或第三方中文释义。 |
| 补间动画 | [PrimeTween 免费版](https://assetstore.unity.com/packages/tools/animation/primetween-high-performance-animations-and-sequences-252960) | 原作者许可允许在免费和商业游戏中以二进制使用；工程以 npm 依赖安装，未把源代码或 tgz 重新分发。准确版本锁定为 1.5.1。 |
| 十二面骰子网格 | [3D Assets 桌游组件](https://3dassets.dev/packs/tabletop-game-components) 中 D12，资源编号 20842 | CC0。原页面明确标记为 AI 生成。仅提取骰体，材质与骰面标记为本项目制作。详见 `Dice-CC0.txt`。 |
| 中文字体 | [霞鹜文楷](https://github.com/lxgw/LxgwWenKai)，Regular 1.530 | SIL Open Font License；见 `WenKai-OFL.txt`。 |
| 图标字体 | [Lucide](https://lucide.dev) / npm `lucide-static` | ISC；见 `Lucide-LICENSE.txt`。 |
| 植物地图桌面、月夜桌面、绿金牌背 | 用户指定的图像 API，模型 GPT Image 2 | 为本工程生成；原始提示词保存在 `Research/image-prompts.jsonl`。牌背保留完整构图，重采样到 896 × 1536，严格为 7:12。 |
| 纸纹面板、阴影、星盘线稿、粒子贴图 | 本工程 `Tools/prepare_assets.py` | 本项目制作。 |
| 粒子与骰子物理 | Unity/Tuanjie 内置 ParticleSystem、Rigidbody、MeshCollider | 使用引擎标准组件，无需购买粒子或物理插件。 |
| 操作音效 | Kenney Casino Audio 1.1、Interface Sounds 1.0 | CC0；14 个原包 OGG 文件，许可和下载来源见 `KenneyAudio/`。 |
| 环境和声 | 本工程 `GameAudio.cs` | 原创程序合成，不使用视频 BGM。 |
| 星轨、玫瑰、银月、日轮牌背 | 本工程 `Tools/prepare_card_backs.py`、`Assets/ArtSources/CardBacks/*.svg` | 原创矢量线刻；SVG 为可编辑源文件，resvg 仅用于导出 PNG，不加入游戏运行时。 |
| 中文正逆位牌义、每日行动建议、牌阵文案 | 本工程 `TarotDomain.cs` | 本项目制作。 |

参考视频只用于研究布局、色彩、抽牌节奏、翻面和光点效果。没有提取或分发视频中的角色、牌背、背景、音乐、UI 图片或代码。

已检索 Unity Asset Store 的免费骰子、卡牌、Particle Pack 和动画资源。需要账号领取的商店资源没有被当作匿名可下载文件重新分发。实际工程优先使用官方内置系统、免费 Unity 专用动画库及许可明确的外部图像和网格，避免把付费素材包作为必需依赖。
