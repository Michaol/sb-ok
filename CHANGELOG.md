# Changelog

All notable changes to this project will be documented in this file.

## [1.0.0] - 2025-11-25

### Added
- 初始化私有仓库版本 (sb-ok)
- 支持优先导入本地配置文件 (`config.json` 或 `server_config.json`)
- 添加 `.gitignore` 文件

### Changed
- 优化 `install.sh` 安装流程：
    - 移除远程脚本下载依赖，改为直接复制当前脚本
    - 适配私有化部署，不再依赖公共仓库资源
- 更新 `README.md` 为中文私有版说明

### Removed
- 移除所有预设的配置样例目录 (shadowsocks2022, trojan, hysteria, vmess, NaiveProxy)
- 移除英文文档 `README_EN.md`
