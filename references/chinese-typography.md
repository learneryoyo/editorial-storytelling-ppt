# 中文字体与放映排版

## 留白、文字深浅和相对大小

- 先在构图里保留一块连续留白，再安排标题、证据和解释。组内间距紧一些，组与组之间宽一些。删冗词、放宽列、改换行或拆页，可以腾出空间容纳要读的内容。
- 字号按页面职责、中文字面、版面密度和观看距离逐页取舍。一页给主标题、引文或关键数一个明确焦点。时间轴、图例、单位和必读图注随解释文字一起检查。只供定位和追溯的字可以收小。缩小预览检验阅读顺序，实际放映检验每处必读文字。关闭或核查自动缩字，检查导出和截图缩放后的效果。
- 深墨适合标题和关键判断，中等深度可用于需要连续阅读的正文，较浅的中性色留给出处或辅助说明。强调色只落在少数有效词或关键数。深底页可用暖白、偏灰的浅色和单个亮色形成层次。低对比照片区域可局部压暗、改裁切或更换字色。颜色变化以后实际核对投影上的可辨度。可按需要用正式的无障碍标准辅助检查。[PowerPoint 无障碍建议](https://support.microsoft.com/en-us/accessibility/powerpoint/make-your-powerpoint-presentations-accessible-to-people-with-disabilities) · [W3C 对比度](https://www.w3.org/WAI/WCAG22/Understanding/contrast-minimum)

## 先选正文，再为题材选展示字体

下表的气质和用途是按字形特征给出的设计建议。字体来源见每行末尾。

| 字体和角色 | 适合的内容 | 配对与字重 | 字体来源 |
| --- | --- | --- | --- |
| **思源黑体 SC / Noto Sans CJK SC** 作为阅读骨架 | 调查、理工、政策、表格、中文图表。也适合做有力度的现代标题 | 正文 Regular/Medium，页标题 Bold/Heavy。与宋体标题搭配时保持正文与数据一致 | [Adobe 思源黑体](https://github.com/adobe-fonts/source-han-sans) · [Noto CJK](https://github.com/notofonts/noto-cjk) |
| **微软雅黑** 作为常见 Windows 正文备选 | 教学、屏幕说明、口播片段、有较多数字的中文正文 | Regular/Bold。与思源宋体或小薇标题配对。换装后重查列宽 | [Microsoft 字体说明](https://learn.microsoft.com/en-us/typography/font-list/microsoft-yahei) |
| **思源宋体 SC / Noto Serif SC** 作为编辑式展示字 | 饮食、地方文化、历史、纪录叙事、文学细读 | 标题 Semibold/Bold，和思源黑体或微软雅黑配对。展签式短引文可用 Medium | [Adobe 思源宋体](https://github.com/adobe-fonts/source-han-serif) · [Noto CJK](https://github.com/notofonts/noto-cjk) |
| **站酷小薇体 / ZCOOL XiaoWei** 作为有印刷感的短标题 | 地方街市、手艺、展览、旧菜单式章节题 | 配思源黑体正文。使用字体本身提供的字重，先测试生僻菜名 | [字体项目](https://github.com/googlefonts/zcool-xiaowei) |
| **霞鹜文楷 / LXGW WenKai** 作为有书写感的引文 | 人物回忆、菜单旁白、有温度的教学引文、书信 | 用 Medium 做短引文或人物声音，讲解与指标配思源黑体。繁体需按字形地区选版本 | [霞鹜文楷项目](https://github.com/lxgw/LxgwWenKai) |
| **马善政楷体 / Ma Shan Zheng** 作为少量书写式大字 | 「炒」「火」等单字章节、节令场景、书写式海报题 | 配清晰的黑体释义。使用提供的 Regular，先检查该字实际字形及远投清晰度 | [Google Fonts 字体目录](https://github.com/google/fonts/tree/main/ofl/mashanzheng) |

先按整稿的页型分配中文标题字。黑体的重字适合结论、数据页和动作页，宋体可用于需要印刷感的封面、章题或某些叙述页，楷体或文楷可用于人物声音、短引文和单字特写。饮食题材也可在黑体结论、宋体章题和书写式动作词之间切换。同类页面保持字形角色稳定，用同一正文家族或对齐线把全篇串起来，换章时再用字形和字重调整气质。西文数字若需换字体，应测试数字、单位、百分号及基线。

将中文字体写入实际东亚字形设置（例如 DrawingML 的 `a:ea`），包含中英数字时也核对 `a:latin`。确认播放端所用字体、字重、字形覆盖和嵌入许可。字体不可用时选实际可用且气质相近的替代，例如思源宋体可用现场系统里可用的宋体作为备选，并重新渲染。优先以可编辑文本交付。仅在用户接受时将少量特写字转轮廓，并保留可编辑稿或原文。[Microsoft 字体嵌入指南](https://support.microsoft.com/en-us/office/benefits-of-embedding-custom-fonts-cb3982aa-ea76-4323-b008-86670f222dbc)
