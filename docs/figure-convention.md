# 插图规范

## 命名
- 目录 `figures/<slug>/`，文件 `<slug>.svg`；变体加后缀：`<slug>-simple.svg`、`<slug>-en.svg`。
- slug 小写短横线。

## 格式
- **SVG 优先**：手写或脚本生成的纯 SVG，`viewBox` 设定，不嵌入位图，文字用 `<text>`（字体：`sans-serif`，中文回退 `"Noto Sans CJK SC","Microsoft YaHei"`）。
- 线宽 2 px，主色黑 `#222`，强调色蓝 `#1f6feb` / 红 `#d1242f`，背景透明或白。
- 画布建议 800×450（16:9）或 600×600。
- PDF 可选，由 SVG 转换（如 `rsvg-convert -f pdf`）。

## 图说 `README.md`
1. 用途（哪门课 / 哪一节）
2. 图中符号与含义
3. 可修改处（如参数标注）
4. 教学使用提示：「本图自绘，可用于教学，注明出处」

## 禁止
- 不直接复制教材、论文、厂商手册中的受版权保护图片。
