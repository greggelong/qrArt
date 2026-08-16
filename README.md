# Art is Obeying / 艺术就是服从

**A Participatory QR Art Project**

---

## Overview

We scan QR codes dozens of times a day – on menus, tickets, payment terminals, posters. We never stop to look at them. They are the invisible infrastructure of our digital lives.

This project takes that silent, ubiquitous icon and turns it into a collective act of making. A message is chosen, encoded into a QR code, and then translated into a set of numbered coordinates – a list of rules. Participants receive a blank grid and the rules. They fill the cells, cell by cell, following instructions. When the grid is complete, the QR code appears – made by many hands, built through trust and obedience.

**Art is obeying.**

---

## Concept

_“Art is obeying.”_

This is not a paradox. It is a recognition.

Art has always involved obedience. The painter obeys the paint. The sculptor obeys the stone. The poet obeys the language. The QR code obeys the algorithm. And the algorithm obeys the message.

In this project, participants become the material. They become the modules. They obey the rules. And by obeying, they create something that works.

The QR code is a rigid grid with fixed rules: size, error correction, encoding limits. If you deviate – if you place a module even slightly off – the code breaks. It will not scan. It will not speak.

But within that obedience, meaning emerges.

---

## How It Works

### For Organisers (Artists / Curators)

1. **Choose a message** – a URL, a word, a statement. This project uses _“Art is obeying / 艺术就是服从”_ as its default.

2. **Use the web tool** (see below) to generate:
   - A **QR code** (for verification).
   - A **numbered list of rules** – every dark module becomes a coordinate (e.g., `1. A1`, `2. A3`, `3. B5`…).
   - A **blank grid** – with row labels (A, B, C…) and column numbers (1, 2, 3…).

3. **Print the blank grid** on large paper or a wall. Provide the rules list to participants.

4. **Participants fill the cells** – using markers, paint, stickers, or any medium.

5. **When complete**, scan the finished grid with any QR code reader. The message appears.

### For Participants

You receive:

- A **blank grid** – labelled with letters and numbers.
- A **list of rules** – telling you exactly which cells to fill.

You do not know what you are making. You are not asked to be creative. You are asked to be precise.

Fill the cells. One by one. Trust the system. Obey the coordinates.

When everyone has finished, the QR code appears. It is readable. It works. Because everyone obeyed.

---

## The Web Tool

The project includes a self‑contained HTML tool that generates everything you need:

- **QR code preview** – for verification.
- **Blank grid** – with row/column labels, ready for printing.
- **Filled grid** – a reference image showing the correct solution.
- **Numbered rules** – a text list of all dark‑cell coordinates.
- **Download options** – QR PNG, grid PNG, rules.txt.
- **Language toggle** – English / 中文.
- **Speak rules** – uses the browser’s text‑to‑speech (with stop control).

### How to Use the Tool

1. Open the HTML file in any modern browser (no server needed).
2. Enter your message (URL or text) in the input field.
3. Click **Update**.
4. Adjust the language, toggle “Show filled” to see the solution, and download the outputs.
5. Print the blank grid and distribute the rules.

### Technical Details

- **QR Code Library**: [QRCode.js](https://github.com/davidshimjs/qrcodejs) – used under the hood.
- **Error Correction Level**: H (≈30% redundancy) – ensures the code remains scannable even with minor imperfections.
- **Grid Labeling**: Excel‑style column naming (A, B, … Z, AA, AB…) and 1‑based row numbers.
- **Maximum Text Length**: Approximately 2,950 characters for mixed Chinese/English (the tool will warn you if the data is too long).
- **Output Formats**: PNG images (download) and plain text (rules).

---

## Why “Art is Obeying”?

Because obedience is not the opposite of creativity.

- The material obeys the artist.
- The artist obeys the material.
- The audience obeys the work.
- The work obeys the world.

In this project, participants become the material. They obey the rules. And by obeying, they create.

---

## Credits & License

**Concept & Code**: [Your Name / Studio]  
**Tool Development**: [Your Name / Studio]  
**QR Code Library**: QRCode.js (MIT License)

This project is open for non‑commercial use and adaptation. Please credit the original concept when exhibiting or redistributing.

---

## Contact

For inquiries, exhibitions, or collaborations, please reach out via [email / website / social media].

---

## 中文版本

---

### 艺术就是服从

**一个参与式 QR 艺术项目**

---

我们每天扫描 QR 码数十次——在菜单上、门票上、支付终端上、海报上。我们从未停下来看它们一眼。它们是我们数字生活中隐形的、无声的基础设施。

这个项目把这个沉默的、无处不在的图标变成了一种集体的创作行为。选择一个信息，编码成 QR 码，然后将其翻译成一组编号的坐标——一组规则。参与者拿到一张空白网格和规则列表。他们按照指令，一格一格地填充格子。当网格完成时，QR 码出现了——由许多双手共同完成，建立在信任和服从之上。

**艺术就是服从。**

---

### 核心理念

_“艺术就是服从。”_

这并非悖论，而是一种认知。

艺术从来都包含服从。画家服从颜料。雕塑家服从石材。诗人服从语言。QR 码服从算法。算法服从信息。

在这个项目中，参与者成为了材料。他们成为了模块。他们服从规则。而通过服从，他们创造了可以工作的东西。

QR 码是一个严格的网格，拥有固定的规则：尺寸、纠错等级、编码容量。如果你偏离——如果某个模块的位置稍微偏移——整个代码就会失效。它无法被扫描，也无法传达信息。

但正是在这种服从之中，意义显现出来。

---

### 如何使用

#### 组织者

1. 选择一条信息（URL、词语、陈述）。本项目的默认信息是 _“艺术就是服从 / Art is Obeying”_。

2. 使用在线工具（见下文）生成：
   - QR 码（用于验证）
   - 编号规则列表（例如 `1. A1`, `2. A3`, `3. B5`…）
   - 带标签的空白网格（字母与数字坐标）

3. 打印空白网格（可放大到墙面或大幅纸张），并将规则分发给参与者。

4. 参与者用记号笔、颜料、贴纸等填充单元格。

5. 完成后，用手机扫描完成的网格，信息将显现出来。

#### 参与者

你会收到：

- 一张空白网格（带字母和数字标签）
- 一张规则列表（告诉你哪些格子需要填充）

你不知道你在制作什么。你不需要发挥创意。你只需要精确。

填充格子，一个接一个。信任系统。服从坐标。

当所有人都完成时，QR 码出现了。它可以被扫描。它有效。因为每个人都服从了。

---

### 工具说明

该项目包含一个自包含的 HTML 工具，可生成所有所需内容：

- QR 码预览（用于验证）
- 空白网格（带坐标标签，可打印）
- 已填充网格（参考图像）
- 编号规则（纯文本列表）
- 下载选项（QR PNG、网格 PNG、规则 TXT）
- 语言切换（英文 / 中文）
- 朗读规则（使用浏览器的语音合成，带停止控制）

#### 使用方法

1. 用浏览器打开 HTML 文件（无需服务器）。
2. 在输入框中输入你的信息（URL 或文本）。
3. 点击“更新”。
4. 切换语言、勾选“显示填充结果”查看正确答案，下载所需文件。
5. 打印空白网格并分发规则。

#### 技术细节

- QR 码库：[QRCode.js](https://github.com/davidshimjs/qrcodejs)（MIT 许可）
- 纠错等级：H（约 30% 冗余），确保即使有轻微瑕疵也能扫描。
- 网格标签：Excel 式列名（A, B, … Z, AA, AB…）和 1 基行号。
- 最大文本长度：中英混合约 2950 个字符（工具会在超限时警告）。
- 输出格式：PNG 图片（下载）和纯文本（规则）。

---

### 为什么是“艺术就是服从”？

因为服从并非创造力的反面。

- 材料服从艺术家。
- 艺术家服从材料。
- 观众服从作品。
- 作品服从世界。

在这个项目中，参与者成为了材料。他们服从规则。而通过服从，他们创造了作品。

---

### 版权与许可

**概念与代码**：[你的姓名 / 工作室]  
**工具开发**：[你的姓名 / 工作室]  
**QR 码库**：QRCode.js（MIT 许可）

本项目允许非商业用途和改编。请在展览或分发时注明原始概念。

---

### 联系方式

如需咨询、展览或合作，请通过 [邮箱 / 网站 / 社交媒体] 联系我们。
