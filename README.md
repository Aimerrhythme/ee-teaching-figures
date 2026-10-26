# ee-teaching-figures · 电气教学插图与板书矢量库

自绘的电气教学示意图（变压器、馈线、控制框图、PWM 载波…），以 **SVG 为主**、PDF 为辅，可直接放进课件、讲义、板书投影。

## 使用说明
- 图均为自绘，按 MIT 许可可用于教学；建议在课件角落注明「来源：ee-teaching-figures」。
- 优先 SVG（可缩放、可直接改字），需要打印时另附 PDF。

## 目录

```
figures/<slug>/
  <slug>.svg          # 主图
  <slug>.pdf          # 可选
  README.md           # 图说：用途、图中符号、可改处
figures/_template/example-block.svg   # 占位示例
docs/figure-convention.md
themes.md / INDEX.md
```

规范见 [`docs/figure-convention.md`](docs/figure-convention.md)。

## 说明

- **中文为主**，必要处附英文术语。
- 本仓由定时自动化**持续追加**内容：每次从 `themes.md` 取一条 `todo` 主题 → 生成条目 → 更新 `INDEX.md` 与 `CHANGELOG.md` → 将主题标为 `done`。
- 定位为**教学材料**，**不代写**毕业设计 / 课程设计 / 论文。
- 许可：MIT（见 `LICENSE`，含教学声明）。
