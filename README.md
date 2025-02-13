# Realm 转发脚本

一个用于快速部署和管理 Realm TCP 转发的 Shell 脚本。

### 安装
```bahs
wget https://raw.githubusercontent.com/jinqians/realm/refs/heads/main/realm.sh && chmod +x realm.sh && ./realm.sh
```

## Realm 介绍

Realm 是一个用 Rust 编写的高性能 TCP 转发工具。它可以：
- 支持 IPv4/IPv6 双栈
- 低内存占用
- 高性能转发
- 支持多端口转发
- 配置简单

## 脚本特点

- 一键部署 Realm 环境
- 可视化管理界面
- 自动管理防火墙规则
- 支持在线更新
- 服务状态监控
- 转发规则管理

### 使用说明

1. 部署环境
   - 选择菜单选项 1
   - 脚本会自动下载并安装 Realm

2. 添加转发规则
   - 选择菜单选项 2
   - 输入本地监听端口
   - 输入目标 IP/域名
   - 输入目标端口
   - 确认后自动配置防火墙并重启服务

3. 删除转发规则
   - 选择菜单选项 3
   - 查看当前转发规则列表
   - 输入要删除的规则序号
   - 确认后自动清理防火墙规则并重启服务

4. 管理服务
   - 启动服务：选项 4
   - 停止服务：选项 5
   - 重启服务：选项 6

5. 更新脚本
   - 选择菜单选项 8
   - 自动检查并提示更新

## 功能列表

1. 环境部署
   - 自动下载 Realm
   - 配置系统服务
   - 设置开机自启

2. 转发管理
   - 添加转发规则
   - 删除转发规则
   - IPv4/IPv6 双栈支持
   - 自动防火墙配置

3. 服务管理
   - 启动服务
   - 停止服务
   - 重启服务
   - 服务状态监控

4. 系统维护
   - 在线更新脚本
   - 一键卸载
   - 配置文件备份

## 注意事项

1. 需要 root 权限运行
2. 支持 UFW 和 iptables 防火墙
3. 建议在首次使用时先部署环境
4. 修改转发规则后会自动重启服务
5. 更新脚本后需要重新运行

## 作者信息

- 作者：jinqian
- 网站：https://jinqians.com

## 许可证

MIT License
