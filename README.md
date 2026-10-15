# 腾讯云服务器实时探针 (xbtz.php)

[![Deploy](https://github.com/xiaobai5211314/server-status-probe/actions/workflows/deploy.yml/badge.svg)](https://github.com/xiaobai5211314/server-status-probe/actions/workflows/deploy.yml)
[![Website](https://img.shields.io/badge/online-21212121.xyz%2Fxbtz.php-blue)](https://21212121.xyz/xbtz.php)

> 腾讯云上海节点服务器实时系统探针，提供 CPU、内存负载、实时网络上下行流量曲线及 PHP 环境检测。已收拢至主博客目录下统一维护，消除独立二级域名的暴露面。

---

## 🌐 访问地址与服务信息
- **在线访问路径**：[https://21212121.xyz/xbtz.php](https://21212121.xyz/xbtz.php)
- **生产服务器路径**：`/www/wwwroot/21212121.xyz/xbtz.php`
- **状态说明**：独立二级域名 `status.21212121.xyz` 已按计划停用收拢，由主站路径统一承载。

## 🛠️ 技术栈与加速
- **后端**：PHP 8.5
- **前端库**：jQuery 1.7.2（托管于又拍云 CDN 高速存储：`https://tc1.21212121.xyz/asite/assets/vendor/jquery/jquery-1.7.2.min.js`，避免消耗服务器外网带宽）
- **站群互联**：页眉集成全景导航栏，双向直达主站博客与站群导航总中心。

## 🚀 自动部署与 CI/CD
本项目已配置 GitHub Actions 自动化持续集成：
- 当向 `main` 分支提交（Push）或合并代码时，GitHub Actions 会自动通过安全 SSH 密钥同步最新代码至生产服务器 `/www/wwwroot/21212121.xyz/xbtz.php`。

## 📄 授权与规则
详细架构边界与维护约定请参考 [AGENTS.md](./AGENTS.md)。
Personal Open Source Project · All Rights Reserved.
