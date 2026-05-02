# Claude Code 安装脚本

一键安装 [Claude Code](https://code.claude.com) CLI 工具。

## 系统要求

- **macOS / Linux**：bash 或 zsh，需要 `curl` 或 `wget`
- **Windows**：64 位 Windows，PowerShell 5.1+

## 安装

### macOS / Linux

```bash
curl -fsSL https://raw.githubusercontent.com/cn-ywcw/claude-code-install/main/cc.sh | sh
```

### Windows PowerShell

```powershell
irm https://raw.githubusercontent.com/cn-ywcw/claude-code-install/main/cc.ps1 | iex
```

## 安装后

- 安装完成后，如果找不到 `claude` 命令，请重新打开终端，或手动将以下路径加入 `PATH`：
  - macOS / Linux：`$HOME/.local/bin`
  - Windows：`C:\Users\<用户名>\.local\bin\`

## 审查脚本

建议在运行前先审查脚本内容：

- [cc.sh](https://raw.githubusercontent.com/cn-ywcw/claude-code-install/main/cc.sh)
- [cc.ps1](https://raw.githubusercontent.com/cn-ywcw/claude-code-install/main/cc.ps1)
