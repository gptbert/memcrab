# MemCrab 🦀

**四层上下文工程栈 AI CLI**  
持久指令 + 自动压缩 + 工具治理 + 外置记忆  
让长期对话、大型代码库永不爆上下文！

![Python](https://img.shields.io/badge/Python-3.11+-blue)
![License](https://img.shields.io/badge/license-MIT-green)
![Stars](https://img.shields.io/github/stars/bertgpt/tgtmemcrab)

## 🚀 快速开始

```bash
pip install -e .
memcrab init
memcrab chat --model grok-beta
```

✨ 核心特性
	- 分层 rules/（global → project → task）
	- 自动 pre-flush + 压缩（MEMORY.md）
	- 严格 tool_call/result 配对永不破坏
	- ChromaDB 向量检索 + git-like checkpoint
	- 内置 read_file / list_dir 等工具

📋 命令一览

```bash
memcrab init
memcrab chat
memcrab compress [--level aggressive]
memcrab checkpoint save "v1.0"
memcrab memory "搜索关键词"
```

## 安装

```bash
git clone https://github.com/gptbert/memcrab.git
cd memcrab
pip install -e .
```


欢迎 Star ⭐ 支持！ 有问题或想加功能（Docker、更多工具、autotest 闭环）随时提 Issue！

MIT License

Copyright (c) 2026 bert

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction...

https://choosealicense.com/licenses/mit/
