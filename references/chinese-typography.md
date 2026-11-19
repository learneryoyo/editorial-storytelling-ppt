# 中文字体与放映字号

## 文字角色与最低字号

下表是本技能针对课堂、报告会和投影场景的验收标准，以 PowerPoint 标准宽版 13⅓ × 7.5 英寸为基准。其他物理尺寸按画布高度等比例换算。若生成器用像素，按画布相对比例换算到最终页面，也要考虑图片和 SVG 置入后的缩放。

| 放映时承担的作用 | 最低字号 | 常用区间 |
| --- | ---: | ---: |
| 封面或章节主标题 | 40 pt | 46–68 pt |
| 常规页标题 | 30 pt | 32–40 pt |
| 主要关键词、卡片主题、结论句 | 24 pt | 26–36 pt |
| 观众必须阅读的正文和关键引文 | 18 pt | 22–26 pt |
| 看懂证据所需的表头、单元格、刻度、单位、说明和图例 | 18 pt | 18–22 pt |
| 只用于定位和追溯的页码、出处和版权信息 | 10 pt | 10–12 pt |

用信息的作用决定字号。台词里要解释、听众必须核对或脱离口播仍需看懂的图注是正文。章节号可以缩小，但若编号承担阅读顺序也要适当放大。表格下有关数量、样本或结论适用范围的说明按关键标签处理。数据特写的数字通常 52–90 pt，单位贴近数字并易读。

导出前排查自动缩字。读不下时优先改为两行、简化表头、选最重要的行、拆成两页、将完整材料放备注。遇长时间轴，拆成两个时间段，每次讲两到三个节点。能放大的截图先做裁切或保留全图加局部放大，供观众阅读的文字也可以另排成原生文字。

逐页检查字号以及最终像素下的字重和对比。缩小到约四分之一预览时，仍应能区分题目、焦点和解释的轮廓。实际观看用放映端和预计观看距离复核。核心小字可参考 WCAG 的 4.5:1 对比度作为数字检查起点，照片上应按文字覆盖的实际区域检查。Microsoft 的 PowerPoint 指南以 18 pt 或更大的字体作为可及性建议，这里的角色分级是面向本技能的投影标准。[PowerPoint 无障碍建议](https://support.microsoft.com/en-us/accessibility/powerpoint/make-your-powerpoint-presentations-accessible-to-people-with-disabilities) · [W3C 对比度](https://www.w3.org/WAI/WCAG22/Understanding/contrast-minimum)

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

普通页保持一套正文字。需要换气质时优先换章节展示字、短引文或高亮数字。每页通常用两套中文角色，通过字重和尺寸增加层级。西文数字若需换字体，应测试数字、单位、百分号及基线。

将中文字体写入实际东亚字形设置（例如 DrawingML 的 `a:ea`），包含中英数字时也核对 `a:latin`。确认播放端所用字体、字重、字形覆盖和嵌入许可。字体不可用时选实际可用且气质相近的替代，例如思源宋体可用现场系统里可用的宋体作为备选，并重新渲染。优先以可编辑文本交付。仅在用户接受时将少量特写字转轮廓，并保留可编辑稿或原文。[Microsoft 字体嵌入指南](https://support.microsoft.com/en-us/office/benefits-of-embedding-custom-fonts-cb3982aa-ea76-4323-b008-86670f222dbc)
