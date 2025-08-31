# Open-Check: 轻量级开源网络核查工具

<!-- 在下面这行中，你可以放一些徽章，项目初期可以先空着，后面再添加 -->
<!-- 例如: [![MIT License](https://img.shields.io/badge/License-MIT-green.svg)](https://choosealicense.com/licenses/mit/) [![Python Version](https://img.shields.io/badge/python-3.9%2B-blue.svg)](https://www.python.org/downloads/) -->

一个为个人投资者、投行实习生、初级投行承做人员、学生打造的，快速、免费、可扩展的公开工商、信用信息聚合核查工具。
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
git clone https://github.com/yudeguge_ux/open_check.git
cd open_check
```

### 2. 安装依赖
```bash
pip install -r requirements.txt
```
### 3. 使用命令行 (CLI)
```bash
# 查询单个数据源
python main.py --company "小米科技有限责任公司" --source "工商"
```
### 4. 启动Web界面
```bash
streamlit run app.py
启动后，在浏览器中打开 http://localhost:8501 即可访问。
```

## 🗺️ 项目路线图 (Roadmap)
我们正按照以下计划，一步步构建 Open-Check：
阶段一: 核心CLI工具 (Q3 2025)
完成核心数据源爬虫：工商信息
完成数据源爬虫：司法诉讼
实现聚合查询的CLI功能
阶段二: 产品化Web界面 (Q4 2025)
基于 Streamlit 开发用户友好的查询界面
在Web上美化查询结果的展示
实现查询结果下载功能
阶段三: 社区化与扩展 (2026)
完善插件化架构和开发者文档
增加更多数据源插件（如：专利、招投标、新闻舆情）
探索报告导出为 Word/Markdown 格式

## 🤝 如何贡献 (Contributing)
我们热烈欢迎任何形式的贡献！无论是提交Bug、建议新功能，还是直接贡献代码。
如果你想为 Open-Check 贡献一个新的数据源爬虫，请阅读我们的贡献指南 <!-- 你需要创建一个名为CONTRIBUTING.md的文件来写贡献说明 -->。
我们尤其需要以下方面的帮助：
新的数据源爬虫开发
前端界面优化
文档撰写和校对
## ⚠️ 免责声明 (Disclaimer)
本项目是一个出于技术学习和交流目的的开源工具。所有数据均来源于公开的官方网站。
使用者应严格遵守各数据源网站的 robots.txt 协议和用户协议。因滥用本项目而导致的任何法律风险和责任，由使用者自行承担。
详细信息请参阅 法律免责声明 <!-- 你也需要创建一个DISCLAIMER.md文件 -->。
## 📄 开源许可 (License)
本项目采用 MIT License 开源许可。
Created with ❤️ by xiaxia
<!-- 在这里放上你的个人链接，比如GitHub主页或领英 -->
