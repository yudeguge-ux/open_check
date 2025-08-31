# Open-Check: 轻量级开源网络核查工具

<!-- 在下面这行中，你可以放一些徽章，项目初期可以先空着，后面再添加 -->
<!-- 例如: [![MIT License](https://img.shields.io/badge/License-MIT-green.svg)](https://choosealicense.com/licenses/mit/) [![Python Version](https://img.shields.io/badge/python-3.9%2B-blue.svg)](https://www.python.org/downloads/) -->

一个为个人投资者、财经记者和学生打造的，快速、免费、可扩展的公开信息聚合核查工具。

---

<!-- 关键一步：当你做出Web UI后，一定要录制一个GIF动图放在这里，它比任何文字都更有吸引力！ -->
![Open-Check Demo GIF](https://your-gif-link-here.com/demo.gif)
>

## ✨ 项目愿景 (Vision)

在信息爆炸的时代，快速验证一家公司的背景信息变得至关重要。商业工具（如底稿易、荣大）功能强大但价格昂贵，且主要面向机构用户。

**Open-Check** 旨在成为一个**“乐高式”**的核查工具箱。它免费、开源，核心功能稳定，同时允许社区开发者像搭积木一样，轻松地为其增加新的数据源插件。我们希望为需要做初步尽职调查的个人，提供一个轻便而强大的助手。

## 核心功能 (Features)

*   ✅ **多数据源支持**: 一键查询多家权威公开数据源。
    *   工商信息 (国家企业信用信息公示系统)
    *   司法诉讼 (中国裁判文书网等)
    *   主流媒体新闻 (开发中...)
*   📖 **多种输出格式**: 满足不同使用场景。
    *   **JSON**: 结构化数据，便于二次开发和分析。
    *   **Web界面**: 提供用户友好的在线查询和报告展示。
    *   **Markdown/Word**: 便于复制和存档 (规划中)。
*   🚀 **简单易用**:
    *   **命令行 (CLI)**: 适合开发者，可轻松集成到自动化脚本中。
    *   **Web UI**: 无需任何技术背景，开箱即用。
*   🧩 **插件化架构**: 开发者可以轻松编写新的爬虫插件，扩展系统的数据核查能力。

## 快速开始 (Quick Start)

### 环境要求

*   Python 3.9+
*   Git

### 1. 克隆项目

```bash
git clone https://github.com/[你的GitHub用户名]/[你的仓库名].git
cd [你的仓库名]
