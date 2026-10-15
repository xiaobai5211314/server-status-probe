# 腾讯云服务器实时探针

[![Deploy](https://github.com/xiaobai5211314/server-status-probe/actions/workflows/deploy.yml/badge.svg)](https://github.com/xiaobai5211314/server-status-probe/actions/workflows/deploy.yml)
[![Website](https://img.shields.io/badge/online-status.21212121.xyz-blue)](https://status.21212121.xyz)

> 腾讯云上海节点服务器实时系统探针，提供 CPU、内存负载、实时网络上下行流量曲线及 PHP 环境检测。

## 🌐 访问地址
- 官方独立域名：[https://status.21212121.xyz](https://status.21212121.xyz)

## 🛠️ 技术栈
- PHP 8.5 / jQuery / CSS3 Responsive

## 🚀 自动部署与 CI/CD
本项目已配置 GitHub Actions 自动化持续集成：
- 当向 `main` 分支提交（Push）或合并代码时，GitHub Actions 会自动通过安全 SSH 密钥同步最新代码至生产服务器 `/www/wwwroot/status.21212121.xyz`。

## 📄 授权与许可
Personal Open Source Project · All Rights Reserved.
