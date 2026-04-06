# Dazi Todo 发布版本

每日待办桌面浮窗应用 - Windows 可执行文件发布包

## 文件说明

| 文件 | 说明 |
|------|------|
| `dazi-todo.exe` | 主应用（GUI 浮窗） |
| `dazi-todo-cli.exe` | 命令行控制工具 |
| `start.bat` | 快速启动脚本 |
| `README.txt` | 使用说明 |
| `SKILL.md` | Agent 集成文档 |
| `workspace` | 工作区模板文件（可配置） |

## 快速开始

1. 双击 `start.bat` 启动主应用
2. 使用 `dazi-todo-cli.exe` 进行控制

## CLI 命令示例

```bash
# 显示/隐藏窗口
dazi-todo-cli.exe show
dazi-todo-cli.exe hide

# 添加待办
dazi-todo-cli.exe add "任务内容"

# 列出待办
dazi-todo-cli.exe list

# 启动番茄钟（专注模式）
dazi-todo-cli.exe focus "写代码" 25
```

## 版本

- 版本: v1.0.0
- 发布日期: 2026-04-06
- 支持平台: Windows 10/11

## 源码

https://github.com/yourusername/dazi-todo
