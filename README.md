# System Monitor Guide | 系统监控指南

A bilingual (English/Chinese) guide to understanding system monitoring metrics on Linux servers.

一个双语（英文/中文）指南，帮助理解 Linux 服务器上的系统监控指标。

## 🌐 Live Site | 在线网站

**https://joseph19820124.github.io/system-monitor-guide/**

## 📚 Topics Covered | 涵盖主题

| Topic | 主题 | Description |
|-------|------|-------------|
| CPU Usage | CPU 使用率 | Understanding us, sy, id, wa, st metrics |
| Load Average | 负载平均值 | What the 3 numbers mean and how to interpret them |
| Steal Time | Steal 时间 | Why VMs lose CPU time to hypervisors |
| Memory Usage | 内存使用 | Reading free -h output correctly |
| Solutions | 解决方案 | Commands to diagnose and fix issues |

## 🚀 Quick Commands | 快速命令

```bash
# Check CPU and Memory 检查 CPU 和内存
top -bn1 | head -5
free -h

# Top processes by CPU 按 CPU 排序的进程
ps aux --sort=-%cpu | head -10

# Top processes by Memory 按内存排序的进程
ps aux --sort=-%mem | head -10

# Disk usage 磁盘使用
df -h /
```

## 🛠️ Features | 功能

- **Language Toggle** - Switch between English, Chinese, or both
- **Responsive Design** - Works on desktop and mobile
- **Dark Code Blocks** - Easy to read command examples
- **Visual Diagrams** - ASCII art explaining concepts

## 📖 License

MIT

---

Created with [Claude Code](https://claude.ai/code) | 使用 Claude Code 创建
