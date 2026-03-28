# Agentic Assets

> 可复用的 AI Agent Skills、框架组件和开发方法论

## 🎯 是什么

这是一个沉淀 AI Agent 开发经验的知识库，包含：
- **Skills**: 可被 AI Agent 直接调用的技能定义
- **Frameworks**: 开发方法和流程框架
- **Playbooks**: 实战复盘和最佳实践

## 📦 核心资产

```
agentic-assets/
├── skills/                    # Skills 目录
│   ├── transcription/         # 语音转文字
│   │   └── eve-transcriber/  # Qwen3-ASR 本地转录
│   ├── content/              # 内容处理
│   ├── research/             # 研究方法
│   └── development/          # 开发框架
├── frameworks/               # 方法论框架
├── playbooks/                # 实战复盘
└── references/               # 参考资料
```

## 🚀 快速开始

### 安装 Skills

```bash
# 克隆仓库
git clone https://github.com/mahaoxuan/agentic-assets.git ~/agentic-assets

# 链接到 Claude Code
ln -s ~/agentic-assets/skills ~/.claude/skills/agentic-assets

# 或选择性安装单个 Skill
cp -r skills/transcription/eve-transcriber ~/.claude/skills/
```

### 使用 Eve Transcriber

```bash
# 转录本地音频
~/.claude/skills/eve-transcriber/scripts/transcribe.sh /path/to/audio.mp4

# 转录 B站视频
~/.claude/skills/eve-transcriber/scripts/transcribe.sh "https://www.bilibili.com/video/BVxxx"
```

## 📚 目录结构

### Skills

| Skill | 描述 | 触发词 |
|-------|------|--------|
| **eve-transcriber** | Qwen3-ASR 本地语音转文字 | 转录、语音转文字 |
| **meta-flywheel** | 开发过程元认知飞轮 | 复盘、迭代优化 |

### Frameworks

| 框架 | 描述 |
|------|------|
| **meta-flywheel** | 感知→决策→执行→沉淀→进化的自我增强系统 |

## 🔄 框架理念

```
┌─────────────────────────────────────────────────────┐
│                    META FLYWHEEL                    │
│                                                      │
│  感知层 ──→ 决策层 ──→ 执行层 ──→ 沉淀层 ──→ 进化层  │
│    ↑                                              ↓  │
│    └──────────────── 反馈循环 ←──────────────────┘  │
└─────────────────────────────────────────────────────┘
```

每次开发任务都是一次飞轮转动：
1. **感知**: 识别任务模式
2. **决策**: 选择执行策略
3. **执行**: 完成具体工作
4. **沉淀**: 记录经验教训
5. **进化**: 迭代优化框架

## 📖 文档

- [SKILL.md 编写指南](./references/skill-guide.md)
- [框架设计原则](./references/framework-principles.md)
- [发布流程](./references/release-process.md)

## 🤝 贡献

欢迎提交 PR！

## 📄 License

MIT

---

*Built with [Claude Code](https://claude.ai/code) and [Meta Flywheel](https://github.com/mahaoxuan/agentic-assets) methodology*
