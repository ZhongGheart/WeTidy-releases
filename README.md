<div align="center">

![WeTidy 微整理](https://shituapp.com/wetidy/assets/WeTidy-horizontal.svg)

**找回文件，也找回空间。**

面向 macOS 的微信、企业微信与本地文件整理工具。

[官网](https://shituapp.com/wetidy/) · [Gitee 主下载](https://gitee.com/yangjin-at/WeTidy-releases/releases/download/v0.1.0-3/WeTidy-0.1.0-3.dmg) · [GitHub 镜像](https://github.com/ZhongGheart/WeTidy-releases/releases/download/v0.1.0-3/WeTidy-0.1.0-3.dmg)

</div>

## WeTidy 是什么

WeTidy（微整理）是一款面向 Mac 的本地文件整理工具。它帮助经常使用微信或企业微信的用户找到接收的文件、看清空间占用，并安全归档或清理不再需要的资料。

文件名搜索、占用报告、归档、清理预览和大部分文件分析都在本机执行，不上传本地文件、文件名或扫描结果。

## 核心功能

- **按文件名搜索**：支持中文字串和拼音，不必逐层翻找聊天目录。
- **占用报告**：按大小、月份、来源、类型和路径查看空间去向。
- **归档与清理**：先预览，再移入 macOS 废纸篓；支持按最近批次撤销。
- **重复文件检测**：用户主动发起，先筛选再以完整 SHA-256 确认，不自动删除。
- **敏感文件提示**：仅在本机按文件名关键词识别，默认从清理预览中排除。
- **媒体检查**：在本机检查图片、视频和音频的格式、尺寸、时长与基本可读性。
- **三台 Mac 授权**：同一买断授权最多激活 3 台匿名设备，支持离线租约。

## 下载

当前公开测试版：**WeTidy 0.1.0（Build 3）**，适用于 macOS 13 及以上，包含 Apple Silicon 与 Intel 通用版本。

| 来源 | 地址 |
| --- | --- |
| 官网 | <https://shituapp.com/wetidy/> |
| Gitee 主下载 | <https://gitee.com/yangjin-at/WeTidy-releases/releases/download/v0.1.0-3/WeTidy-0.1.0-3.dmg> |
| GitHub 镜像 | <https://github.com/ZhongGheart/WeTidy-releases/releases/download/v0.1.0-3/WeTidy-0.1.0-3.dmg> |

安装包已完成 Developer ID 签名、Apple 公证与 DMG stapling。

```text
SHA-256
c2d0b772bb5a86898c7c517340d87874dd87ce6aba439d3c3ee9e31fd3ae950d
```

校验命令：

```bash
shasum -a 256 WeTidy-0.1.0-3.dmg
```

## 安装

1. 下载 `WeTidy-0.1.0-3.dmg`。
2. 打开 DMG，将 `WeTidy.app` 拖入“应用程序”。
3. 首次启动时，按 App 内提示授予文件访问权限。
4. 选择需要整理的微信、企业微信或普通目录，开始更新索引。
5. 先查看搜索结果和占用报告，再执行归档或清理。

## 价格

- 免费版：¥0，包含文件名搜索、基础占用报告和有限额度清理。
- 完整解锁：¥38 一次买断，同一授权最多激活 3 台 Mac。

购买入口：<https://shituapp.com/wetidy/purchase.html>

## 隐私

- 本地文件、文件名、路径和扫描结果不会上传。
- 重复文件检查和媒体检查由用户主动发起。
- 清理只使用 macOS 废纸篓，并保留本机撤销记录。
- 购买、授权码邮件和设备激活需要联网，只处理订单与授权所需信息。

完整说明：<https://shituapp.com/wetidy/privacy.html>

## 发布仓库说明

本仓库仅用于发布安装包、校验文件和发行说明，**不包含 WeTidy 产品源码**。产品源码目前未公开。

WeTidy 是独立开发工具，与微信、企业微信及其所属公司无隶属或官方合作关系。

## 联系

安装、付款或授权码问题请联系：<support@shituapp.com>
