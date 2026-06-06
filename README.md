# 🤖 AI Agent Tools

AI Agent工具，支持Agent设计、编排、协作。

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.10+-blue?logo=python" />
  <img src="https://img.shields.io/badge/OpenAI-API-green?logo=openai" />
  <img src="https://img.shields.io/badge/License-MIT-yellow" />
</p>

## ✨ 特性

- 🏗️ Agent系统设计
- 💻 Agent代码生成
- 🤝 多Agent协作设计
- 🧠 Agent记忆设计
- 🔧 Agent工具设计
- 🎯 编排器生成

## 🚀 快速开始

```bash
pip install openai

python tools.py
```

## 📖 使用

```python
from ai_agent_tools import create_tools

tools = create_tools()

# Agent系统设计
system = tools.design_agent_system("客服系统", "中等")

# Agent代码
code = tools.generate_agent_code("研究Agent", ["搜索", "分析"])

# 多Agent协作
collaboration = tools.design_multi_agent_collaboration(agents)

# Agent记忆
memory = tools.design_agent_memory("向量", "个人助手")

# Agent工具
agent_tools = tools.design_agent_tools("研究Agent", ["搜索", "分析"])

# 编排器
orchestrator = tools.generate_orchestrator(["研究", "写作"], "顺序")
```

## 📁 项目结构

```
ai-agent-tools/
├── tools.py       # Agent工具核心
└── README.md
```

## 📄 许可证

MIT License
