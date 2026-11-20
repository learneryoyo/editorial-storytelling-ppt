# Editorial Storytelling PPT

一个面向调查报告、课堂案例和文本细读的 PPT 设计 Skill。从观众需要理解的问题出发，决定每页放什么证据、图片怎么裁切，以及用什么版式把内容讲清楚。

## 适合做什么

| 演示类型 | 可以怎么讲 |
| --- | --- |
| 调查报告、研究汇报 | 用一个关键数字开场，再交代样本和口径。把调查结果和可比基准画在同一刻度上。 |
| 社会议题、技术案例 | 从观众熟悉的情景切入，用照片、界面示意和事件路径解释系统如何运作。 |
| 文学、人物与引文细读 | 以原文入场，用关键词、物件或图像细节支撑解读。 |

## 设计方法

- **图片跟着讲述任务走。** 交代场景可用满版图或横幅，讲细节可用主图加局部，比较证据时可用等权图集。先定图位与裁切，再找能保住关键内容的素材，记录原始出处。
- **字体随内容和放映条件变化。** 按语气挑选中文标题字，用大小、字重、深浅和留白区分主次。大数字和单位按可见字形留出空隙，灰色说明按阅读需要精简。
- **图形让关系更容易读。** 用连续路径串起时间轴，按关系安排分支和回线。表格优先靠对齐、横线和留白分组。示意插图可以用连续线条和少量平涂色块绘制。
- **动效配合讲述节奏。** 常规翻页可用短淡化，重点入场按台词、动作、读序或状态变化安排。交付可编辑 PPTX 时，优先保留文本、图表和表格的编辑能力。
- **以导出画面检查效果。** 通看缩略图判断整套节奏，再按实际播放尺寸检查字形、颜色对比、裁切、重叠和动画。

## 安装到 Codex

将整个仓库下载到个人技能目录中。若已经通过其他方式安装，更新原有的 `editorial-storytelling-ppt` 文件夹即可。设置过 `CODEX_HOME` 时，使用该目录下的 `skills/`。

**Windows（PowerShell）**

```powershell
$skillRoot = Join-Path $HOME '.codex/skills'
New-Item -ItemType Directory -Force -Path $skillRoot | Out-Null
git clone https://github.com/learneryoyo/editorial-storytelling-ppt.git (Join-Path $skillRoot 'editorial-storytelling-ppt')
```

**macOS / Linux**

```sh
mkdir -p ~/.codex/skills
git clone https://github.com/learneryoyo/editorial-storytelling-ppt.git ~/.codex/skills/editorial-storytelling-ppt
```

如果没有 Git，可以下载 [仓库 ZIP](https://github.com/learneryoyo/editorial-storytelling-ppt/archive/refs/heads/main.zip)，将解压后的目录重命名为 `editorial-storytelling-ppt` 并放到上面的技能目录中。确认该目录下直接包含 `SKILL.md`、`references/` 和 `assets/`。安装后重新打开 Codex 即可调用。

## 使用示例

在 Codex 中输入：

```text
$editorial-storytelling-ppt
把我上传的校园通勤调查做成一份约 8 页的可编辑 PPTX，用于课堂汇报。
从一个反常识发现开场，交代样本和口径。用现场照片引入，再用图表比较两组结果。
保留出处，加入适合现场讲述的翻页和重点入场动画。
```

也可以用它评审现有演示。附上 PPTX 或截图，说明播放场合和要修改的页，例如「第 4 页的图片裁掉了关键细节，第 6 页的时间轴跨行后读序不清」。实际导出和动效验证取决于当前环境可用的演示工具。

## 仓库内容

| 文件 | 用途 |
| --- | --- |
| [SKILL.md](SKILL.md) | 技能入口，负责叙事、资料、版式和交付流程。 |
| [版式案例](references/layout-recipes.md) | 调查报告、场景叙事、文本细读的拆解。 |
| [图片构图](references/image-layouts.md) | 成品参考、图位选择和裁切方法。 |
| [中文排版](references/chinese-typography.md) · [视觉设计](references/visual-design.md) | 字体、留白、圆角、配色、路径和表格。 |
| [动效与插图](references/motion-and-illustration.md) · [设计复查](references/design-direction-and-review.md) | 动效选择、道具绘制、关系图与放映检查。 |
| [assets/](assets/) | 用代码绘制的 SVG 插图示例。 |
