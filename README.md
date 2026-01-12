# Claude Code Notification Plugin (Windows)

Windows 桌面通知插件，在以下场景发送系统通知（仅当终端在后台时触发）：

- **权限请求** - 需要用户确认权限时
- **空闲等待** - Claude 等待用户输入时
- **任务完成** - Claude 完成任务时

## 安装

```bash
claude /plugins add https://github.com/你的用户名/claude-notification-windows
```

## 功能特点

- 智能检测：只在终端窗口处于后台时发送通知
- 多终端支持：能正确区分不同的终端窗口实例
- 项目路径：通知中显示当前项目的最后两级目录

## 系统要求

- Windows 10/11
- PowerShell 5.1+（系统自带）

## 许可证

MIT
