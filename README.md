# SB-OK

**Sing-Box 一键安装管理工具**

> 基于 sing-box 的快捷安装和管理脚本

## 🚀 快速安装

```bash
bash <(curl -Ls https://raw.githubusercontent.com/Michaol/sb-ok/main/install.sh) install
```

> 💡 需要先在服务器上配置环境变量 `GITHUB_TOKEN` 和 `CONFIG_GIST_ID`

## 📖 使用说明

### 快捷命令

```bash
sing-box              # 显示管理菜单
sing-box start        # 启动服务
sing-box stop         # 停止服务
sing-box restart      # 重启服务
sing-box status       # 查看状态
sing-box log          # 查看日志
sing-box update       # 更新服务
```

## ⚙️ 关键路径

- 配置文件: `/usr/local/etc/sing-box/config.json`
- 二进制文件: `/usr/local/bin/sing-box`
- 日志文件: `/usr/local/sing-box/sing-box.log`

---

**版本**: v1.0.0  
**基于**: [sing-box](https://sing-box.sagernet.org/)

---

**维护者**: Michaol  
**最后更新**: 2025-11-25
