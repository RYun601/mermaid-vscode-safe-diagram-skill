# mermaid-vscode-safe-diagram-skill

一个可安装的 Codex Skill，用于在 VS Code 的 `Markdown Preview Mermaid Support` 插件下稳定生成 Mermaid 流程图/脑图，尽量避免 `Parse error`。

## Skill 路径

- `skills/mermaid-vscode-safe-diagram`

## 安装方式

### 方式1：使用 Codex Skill Installer（推荐）

```bash
python ~/.codex/skills/.system/skill-installer/scripts/install-skill-from-github.py \
  --repo RYun601/mermaid-vscode-safe-diagram-skill \
  --path skills/mermaid-vscode-safe-diagram
```

Windows 示例：

```powershell
python "$HOME/.codex/skills/.system/skill-installer/scripts/install-skill-from-github.py" --repo "RYun601/mermaid-vscode-safe-diagram-skill" --path "skills/mermaid-vscode-safe-diagram"

```

### 方式2：手动安装

1. 克隆本仓库
2. 将 `skills/mermaid-vscode-safe-diagram` 目录复制到 `~/.codex/skills/`
3. 重启 Codex 使 Skill 生效

## 适用场景

- 生成 Mermaid 流程图时经常报 `Parse error`
- 需要中文说明但又要保证 Mermaid 语法稳定
- 需要把复杂条件从图中外提，避免图过大或难以渲染

