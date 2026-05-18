# Skills Distill

从公开资料、大师体系中蒸馏出的 Claude Code Skills 集合。

## 结构

```
skills-distill/
├── distill-notes/          # 蒸馏笔记（灵感、素材、草稿）
├── xiaohongshu-framework/  # 小红书起号框架
├── super-master-dating-os/ # 超级大师·恋爱操作系统（31位导师融合）
├── love-panel-perspective/ # 情感大师评审团（30位独立大师）
├── lei-jun-marketing/      # 雷军营销方法论
└── *-perspective/          # 各大师独立视角 Skill
```

## 使用方式

每个 skill 目录通过软链接连接到 `~/.claude/skills/`，Claude Code 自动加载。

## 版本管理

所有 skill 统一在本仓库管理，修改后 commit 即可追溯变更历史。
