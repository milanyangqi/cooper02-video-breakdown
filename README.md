# cooper02-视频拆解

这是一个把视频主题、脚本、素材或参考视频拆解成可执行剪辑方案的工作流与 Codex Skill。

项目来源于本地 Obsidian 笔记：

- `/Users/zhang/Documents/Obsidian Vault/技术文档/seedance/Gemini 视频剪辑一条龙 7 个提示词工作流.md`

## 解决什么问题

这个项目把“从脚本到成片”的后期工作拆成 7 个稳定环节：

1. 剪辑蓝图
2. 爆款风格拆解
3. 脚本节奏优化
4. 导出参数设置
5. 素材分拣
6. 发布前终检
7. 留存率审计

它适合用于：

- 把短视频脚本拆成剪辑执行表。
- 把 Seedance、Gemini、Runway 等工具生成的镜头素材做筛选。
- 拆解参考视频的剪辑风格，并迁移到自己的内容。
- 对初剪版本做留存率审计和发布前检查。
- 给剪辑师、AI 视频生成工具或内容团队交付结构化执行清单。

## 目录结构

```text
.
├── README.md
├── WORKFLOWS.md
├── workflows/
│   └── cooper02-视频拆解工作流.md
└── skills/
    └── cooper02-video-breakdown/
        ├── SKILL.md
        ├── agents/
        │   └── openai.yaml
        └── references/
            └── 提示词模板.md
```

## 如何使用

### 作为工作流使用

阅读：

- `workflows/cooper02-视频拆解工作流.md`

按里面的阶段，把你的主题、脚本、素材清单、参考视频或初剪版本逐步整理成剪辑蓝图、素材分拣表、留存审计和终检清单。

### 作为 Codex Skill 使用

Skill 位于：

- `skills/cooper02-video-breakdown/`

触发方式示例：

```text
使用 $cooper02-video-breakdown，把这个短视频脚本拆成剪辑蓝图、素材分拣建议、留存审计和发布前检查清单。
```

## 来源链接

- 原始 X 线程：<https://x.com/Caijingtianxia/status/2070471224959070535>
- 本项目整理源：`Gemini 视频剪辑一条龙 7 个提示词工作流.md`

## 使用注意

- 本项目提供的是剪辑决策、提示词和交付结构，不替代人工审美判断。
- 参考视频只应迁移结构、节奏和表达方法，不应复制具体创意、画面或文案。
- 商业发布前仍需人工检查版权、事实、品牌调性和平台规范。
