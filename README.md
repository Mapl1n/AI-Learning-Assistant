# 📚 AI 学习助手

基于 Python + PySide6 的桌面应用，帮助自动拆分考点、生成题库、整理笔记。

## ✨ 功能
- **考点拆分**：将章节内容拆解为结构化考点清单（★/★★/★★★标注重点）
- **生成题库**：自动出选择题+简答题，含答案和解析
- **整理笔记**：杂乱内容→分层级结构化笔记
- **自由对话**：随时向 AI 提问

## 🛠 技术栈
- Python 3.12
- PySide6（桌面 GUI）
- DeepSeek API
- QThread 多线程 + 流式输出

## 🚀 快速运行
```bash
pip install PySide6 requests
python main.py
