<p align="center">
  <img src="./assets/banner.svg" alt="XXD Panel 035 项目横幅" width="1200">
</p>

<div align="center">

# 🦁 XXD Panel 035

### 把照片重构成一件明艳、可识别的高级像素积木收藏品

[![Codex Skill](https://img.shields.io/badge/Codex-Skill-000000?style=flat-square)](./SKILL.md)
[![Four Modes](https://img.shields.io/badge/Modes-4-d75d32?style=flat-square)](#四种输出共享同一套高级积木艺术系统)
[![Raster Output](https://img.shields.io/badge/Output-PNG-3c6f67?style=flat-square)](#边界与信任)

<strong>简体中文</strong> · <a href="README.en.md">English</a> · <a href="README.ja.md">日本語</a> · <a href="README.ko.md">한국어</a> · <a href="README.ar.md">العربية</a>

</div>

> 单一积木主体 · 明艳源图色 · 哑光 ABS · 安静背景 · 模块文字

XXD Panel 035 是一个面向 Codex 与兼容 Agent 的图像生成 Skill。它先理解源图身份、动作、关系与寓意，再通过方块比例、模块几何、可信拼搭、清晰剪影和有依据的局部夸张，把主体重构成一件可识别的乐高／Minecraft 式体素积木雕塑。

明艳源图色组、可信哑光 ABS、清晰拼缝、阶梯厚度、自然接触阴影、一个极简底座或平面，以及安静低信息背景，让成品像高级玩具品牌艺术品或现代设计收藏品，而不是游戏截图。

## 为什么需要 035

普通“乐高／Minecraft 风”很容易退化成复杂游戏世界、通用角色资产、满地散砖、光滑 CG 玩具渲染或儿童界面。

035 的顺序完全相反：

```text
锁定身份／动作／功能／关系 → 保留至少三个源图线索 → 重构一个清晰积木剪影 → 用可信接点与厚度组织方块和模块层级 → 加入有源图依据的局部夸张 → 提炼明艳源图色组 → 呈现哑光 ABS、拼缝与接触阴影 → 环境退为浅色安静背景 → 对齐克制模块文字
```

如果换成一张无关照片，积木剪影、模块层级、局部夸张、综合色彩身份、拼缝位置、底座关系或文字仍几乎不变，这张图就不属于 035。

## 035 的视觉契约

- **源图身份：** 至少三个专属线索保住主体比例、轮廓走势、姿态、方向、动作、功能与关系。
- **一个可识别积木主体：** 剪影、姿态、方向、功能、开口、叠压、比例、色组与关系保留至少三个源图线索。
- **可信模块拼搭：** 方块单元、阶梯层级、可见厚度、拼缝、接点、重叠和受力关系具有搭建逻辑。
- **明艳源图色组：** 高纯度、高饱和积木色保住源图综合色彩身份，不使用固定红黄蓝套色。
- **可信哑光 ABS：** 克制塑料反光与自然接触阴影表现厚度，拒绝金属、玻璃、镜面和过度 CG。
- **安静陈列背景：** 一个必要底座、平面或阴影承托主体，浅色低信息背景与留白让主体成为绝对焦点。
- **克制模块文字：** 目标语言像素、模块或说明书式排版对齐剪影、底座、拼缝、模块节奏或留白。

## 样张 · 来自 X

> [小小东（@xiaoxiaodong01）](https://x.com/xiaoxiaodong01/status/2090724386001015097) · 2026-08-21<br>
> GPT2 x 乐高 x 转绘 x 美学提示词 x VOL.035

<table>
  <tr>
    <td width="50%"><a href="https://x.com/xiaoxiaodong01/status/2090724386001015097"><img src="./assets/examples/sample-01.jpg" alt="XXD Panel 035 样张 1"></a></td>
  </tr>
</table>

<p align="center"><a href="https://x.com/xiaoxiaodong01/status/2090724386001015097">查看原推文与完整提示词 →</a></p>

这些样张用于展示 035 的美学动机，不会把样张中的主体、构图、配色、文案或旧画幅变成生成参考或当前默认值。

## 四种可组合输出模式

可用 `1`、`1+3`、`1、2、4` 或 `全部` 选择一个或多个模式；`全部` 每张源图输出 7 个独立 PNG。模式确定后，Skill 会在生图前继续询问整张最终成品的画幅：`3:4` 原提示词画幅、明确跟随原图、常用比例，或自定义比例／准确像素。不会再静默套用源图尺寸。

| 模式 | 画幅逻辑 | 成品 |
| --- | --- | --- |
| `top-bottom` | 用户确认的整张成品画幅 | 一次生成完整画布：高保真原图在上，035 设计在下，约 50/50 |
| `left-right` | 用户确认的整张成品画幅 | 一次生成完整画布：高保真原图在左，035 设计在右，约 50/50 |
| `design-only` | 用户确认的整张成品画幅 | 035 设计铺满画布，不显示原照片 |
| `wallpaper-pack` | 逐设备确认 | 手机、iPad、电脑、儿童手表四张独立 PNG |

双联默认把原图作为高保真垫图／编辑参考，用一套完整提示词直接生成一张整体成品，让摄影、设计、色彩、光线、文字与含义自然呼应。只有完整画布针对性重试仍失败、用户要求原片逐像素不变、当前通道无法实现目标画幅，或需要无创像素校准时，才启用确定性拼合兜底。

壁纸可选连贯或独立。连贯套装先批准一张 iPad 定调图，另外三张分别参考原图＋同一定调图重新构图；独立套装的四张都只参考原图。两者都不会裁切其他设备成品或串联衍生图。

## 文字作为模块化辅助设计

正式生图前，先选择自动文案、自定义文案或无文字。有文字时还要指定目标语言或地区。

自动文案从主体身份、动作、情绪、关系或有依据的含义中提炼一个简短标题，只在有用时增加零至两个标签词或微注释，不虚构品牌、套装编号、游戏关卡、产品线或技术规格。

使用目标文字体系中自然的模块、像素或积木说明书式排版，与主体剪影、底座、积木缝、模块节奏或主动留白对齐。用户准确文案逐字保留，拒绝游戏 HUD、玩具 Logo、街机大字、电商标签和伪套装元数据；文案仍需通过换图测试。

用户提供最终成稿时逐字保留。用户提供的是方向或可编辑草稿时，才会在保留受众、目的、必备词、语气和潜台词的前提下专业深化。

语言遵循目标受众，而不是用户下指令时使用的语言：

```text
目标市场或受众 > 指定成品语言 > 用户方向语言；都不明确时生图前询问
```

日本版使用自然日语，韩国受众使用自然韩语与正确空格，英国版使用英式英语，阿拉伯语版默认使用自然的现代标准阿拉伯语和真正的从右到左排版。排版会尊重各文字系统的比例、连接、方向与可读性。

## 完整画布优先与位图边界

图像模型负责整张成品的审美重构，双联也默认一次直出完整画布。`scripts/compose_panel.py` 只保留为条件明确的兜底、无创尺寸校准和只读审计工具，不再预先规划每次任务，也不评价审美是否成功。

全部交付为 PNG 位图。每次调用都在 `~/Desktop/xxd/` 下创建新任务；已配置图像通道只返回脱敏状态，不公开供应商、端点、凭据、请求头、提示词、响应或账户信息。SVG、HTML、Canvas、图表和程序绘图不能替代最终作品。

## 勾选式选择与快捷参数

当运行环境提供真正的交互控件时，Skill 会优先使用卡片式选择：成品模式和普通成品尺寸均可多选，文字方式与壁纸关系为单选。尺寸提供自动适配、跟随原图、1:1、3:4、4:3、4:5、5:4、2:3、3:2、9:16、16:9、21:9、5:7、7:5 和自定义比例／像素。没有交互控件时，会自动改用清楚的多行编号菜单，不显示无法点击的假复选框。

所有设置也可以作为变量直接跟在调用指令后：

```text
/xxd-panel-035 photo.jpg --mode top-bottom,design-only --size auto,3:4,9:16 --text auto --locale ja-JP
```

可使用 `--mode`、可重复或逗号分隔的 `--size`、`--text auto|custom|none`、`--locale`、`--copy`、`--wallpaper linked|independent`、`--wallpaper-size` 和 `--out`。参数齐全时跳过全部问询并直接生成；参数不完整时只补问缺失项。不同比例会分别重新构图，四端壁纸仍是独立设备分支，不与普通尺寸机械相乘。

## 生图模型优先级

GPT Image 2 是默认首选，并继续执行本项目现有的高保真垫图、生成前确认整张画幅、双联一次生成完整画布、脚本仅作条件式兜底等逻辑。

当当前工具或已配置兼容通道确实可用，并能满足原图保真、整张成品比例、目标语言文字和连贯壁纸多图参考等要求时，也支持 Seedance 5.0 Pro、Nano Banana Pro（Gemini Image Pro）、Nano Banana 2（Gemini Image Flash）或其他兼容位图模型。备用模型只替换生成通道，不得改变模式、画幅、文案、语言、壁纸关系和完整画布优先策略。

如果没有合适的生图通道，Skill 会请用户启用生图工具或提供 API Key。用户主动提供的凭据可以用于当前任务，但不得在回复或日志中回显、展示或泄露；未经用户明确要求，不会长期保存凭据或修改供应商、账户、计费及全局路由配置。

## 开始使用

```bash
git clone https://github.com/nevertoday/xxd-panel-035.git
mkdir -p ~/.codex/skills
ln -s "$(pwd)/xxd-panel-035" ~/.codex/skills/xxd-panel-035
```

Claude Code 用户可以把同一目录链接到 `~/.claude/skills/xxd-panel-035`。安装后重新启动 Agent 会话。

```text
$xxd-panel-035
把这张照片做成左右双联，文案由你根据照片内涵创作，使用自然韩语。
```

只上传照片也可以调用。Skill 会先用分行编号菜单询问一个或多个模式，再询问文字设置；选择壁纸时还会确认连贯或独立以及设备尺寸。

完整规范：

- [Skill 工作流](SKILL.md)
- [中文完整提示词](references/xxd-panel-035-prompt.zh-CN.md)
- [英文完整提示词](references/xxd-panel-035-prompt.en.md)
- [原始风格提示词](references/035-source.md)

## 边界与信任

- 每张照片只在自己的任务中使用，不借用其他输入、旧成品或样张里的主体、颜色、文案和构图。
- 每次调用都创建新的任务子文件夹；相同原图和参数也要重新生成，旧成品不能冒充当前任务。
- 最终交付为 PNG 位图，不是 SVG、HTML、Canvas 或程序绘图替代品。
- 已配置位图桥接只返回脱敏状态，不显示供应商、端点、请求头、凭据、提示词或服务器响应正文。
- 每个所选普通模式各返回一张；若选择 `wallpaper-pack`，再返回四张独立壁纸。选择 `全部` 时每张原图共返回 7 个 PNG，分处四个同级模式文件夹，绝不生成拼贴总览。

本地拼版需要 Python 3 和 Pillow。安全位图桥接使用 Python 3.11+ 的 `tomllib`。图像生成仍需要主机 Agent 的内置位图能力或已经配置好的兼容位图路径。

## 项目结构

```text
xxd-panel-035/
├── SKILL.md
├── README.md / README.en.md / README.ja.md / README.ko.md / README.ar.md
├── agents/openai.yaml
├── assets/
│   ├── banner.svg
│   └── examples/（未来本地样张占位）
├── scripts/
│   ├── compose_panel.py
│   └── configured_imagegen.py
└── references/
    ├── xxd-panel-035-prompt.zh-CN.md
    ├── xxd-panel-035-prompt.en.md
    └── 035-source.md
```

## 关于 XXD

XXD 是小小东的品牌名称缩写。项目由 [@xiaoxiaodong01](https://x.com/xiaoxiaodong01) 创建并维护。

## 服务与会员

### 深度咨询 · 299 元/小时

Skills 使用的一对一深度咨询按 299 元/小时收费。请通过下方微信二维码联系小小东预约。

### 小小东 Skills 用户交流群 · 入群 99 元

一次支付 99 元加入用户交流群，用于交流工作流、作品与互助；不包含按小时的一对一深度咨询。扫码后请备注“Skills 用户交流群”。

### 知识星球＋成员提示词库 · 699 元/年

[知识星球](https://wx.zsxq.com/group/15554814142882)与[小小东成员提示词库](https://vip.xiaoxiaodong.ai/)是同一份会员权益：**一次年费同时开通两边，无需重复付费。**

1. 在[知识星球](https://wx.zsxq.com/group/15554814142882)开通后，微信联系小小东领取成员提示词库兑换码。
2. 在[成员提示词库](https://vip.xiaoxiaodong.ai/)自助开通后，微信联系小小东邀请进入知识星球。

<p align="center">
  <a href="https://xiaoxiaodong.pages.dev/assets/wechat-qr.png"><img src="https://xiaoxiaodong.pages.dev/assets/wechat-qr.png" alt="小小东付费服务微信二维码" width="320"></a>
</p>

<div align="center">

**真实世界变得可以搭建，同时不丢失主体为何一眼可认。**

</div>

---

<div align="center">
  <h2>☕ 为开源项目赞助算力</h2>
  <p>如果这个项目为你节省了时间，可以通过微信或支付宝赞助后续测试与生成算力。</p>
  <table>
    <tr>
      <td align="center" width="240">
        <a href="https://colors.xiaoxiaodong.ai/docs/images/wechat-reward-qr.png"><img src="https://colors.xiaoxiaodong.ai/docs/images/wechat-reward-qr.png" alt="小小东微信算力赞助二维码" width="180"></a><br>
        <strong>微信算力赞助</strong>
      </td>
      <td align="center" width="240">
        <a href="https://colors.xiaoxiaodong.ai/docs/images/alipay-reward-qr.png"><img src="https://colors.xiaoxiaodong.ai/docs/images/alipay-reward-qr.png" alt="小小东支付宝算力赞助二维码" width="180"></a><br>
        <strong>支付宝算力赞助</strong>
      </td>
    </tr>
  </table>
  <p><sub>赞助完全自愿，不会改变这个开源项目的使用权限。</sub></p>
</div>
