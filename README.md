# [005] Variational-Backpack

[English](README-EN.md) | **中文**

---

## 概述

**[005] Variational-Backpack** 是 AlphaLabs 的双平台交易策略插件，同时支持 Lighter 和 Backpack 交易所的永续合约交易。

### 核心特性

- **双平台集成**: 同时支持 Variational DEX 和 Backpack CEX
- **智能订单管理**: 动态调整订单大小和时间间隔
- **风险控制**: 基于波动率的仓位管理
- **低滑点执行**: 优化的订单执行策略

---

## 快速开始

### 前置条件

1. **AlphaLabs Signer Manager**: 已安装并运行
2. **Chrome 浏览器**: 版本 109+
3. **AlphaLabs 账户**: 在 [alphalabs.app](https://alphalabs.app) 注册
4. **API 凭证**: 配置 Variational 和 Backpack API 密钥

### 安装

1. 下载并解压插件包
2. Chrome 访问 `chrome://extensions/`
3. 启用"开发者模式"
4. 点击"加载已解压的扩展程序"，选择插件目录
5. 配置 API 密钥并登录

---

## 配置

### 主要参数

- **交易对**: 支持 12 个交易对
- **杠杆**: 根据平台确定
- **波动率阈值**:
- **仓位大小**:
- **时间间隔**: 可自定义随机间隔

---

## 使用

### 启动策略

1. 确保 Variational 和 Backpack 账户有足够余额
2. 调整配置参数
3. 点击"启动策略"

### 停止策略

1. 点击"停止策略"
2. 等待仓位平仓完成

---

## 注意事项

### 系统要求

- 运行期间禁止休眠或关机
- 使用稳定网络连接
- 推荐使用住宅 IP

### 风险管理

- 监控 IM/MM 比率
- 遵守仓位大小限制
- 从小仓位开始测试

---

## 支持

**邮箱**: contact@alphalabs.app
**文档**: https://docs.alphalabs.app/products/lighter-backpack

---

## 许可证

本软件根据 AlphaLabs 专有许可协议授权，仅限授权用户使用。

版权所有 © 2025 AlphaLabs. 保留所有权利。
