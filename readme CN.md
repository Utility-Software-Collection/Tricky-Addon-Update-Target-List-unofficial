# Tricky Addon - 更新目标列表
使用 KSU WebUI 配置 Tricky Store 的 target.txt。  

[![最新发布](https://img.shields.io/github/v/release/KOWX712/Tricky-Addon-Update-Target-List?label=Release&logo=github)](https://github.com/KOWX712/Tricky-Addon-Update-Target-List/releases/latest) 
[![夜间构建](https://custom-icon-badges.demolab.com/badge/Nightly-canary_build-640064?logo=nightly-logo)](https://nightly.link/KOWX712/Tricky-Addon-Update-Target-List/workflows/build/main?status=completed)  

> [!WARNING]  
> 本模块 **不** 属于 Tricky Store 模块。如果遇到问题，请不要向 Tricky Store 报告。  

## 需求
- 安装 [Tricky Store](https://github.com/5ec1cff/TrickyStore) 模块  

## 使用说明

### KernelSU & Apatch
- KSU WebUI  

### Magisk
- 动作按钮可打开 WebUI  
- 支持 [KSUWebUIStandalone](https://github.com/5ec1cff/KsuWebUIStandalone) 和 [WebUI X](https://github.com/MMRLApp/WebUI-X-Portable)  
- 如果未安装以上任意一个，将自动安装 KSUWebUIStandalone  

### 本模块功能

| 功能                                                                                                                                                                      | 状态 |
| :--------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | :----: |
| 使用应用名称显示配置 target.txt                                                                                                                                          | ✅    |
| 长按选择应用的 `!` 或 `?` 模式。[Auto](https://github.com/5ec1cff/TrickyStore/releases/tag/1.1.0)<br>仅在应用无法正常工作时使用 | ✅    |
| 从 Magisk DenyList 中选择应用（可选）                                                                                                                                    | ✅    |
| 取消选择不必要的应用（可选）[more-exclude.json](https://github.com/KOWX712/Tricky-Addon-Update-Target-List/blob/main/more-exclude.json)                                     | ✅    |
| 设置 verifiedBootHash（可选）                                                                                                                                           | ✅    |
| 自动配置 [安全补丁](https://github.com/5ec1cff/TrickyStore?tab=readme-ov-file#customize-security-patch-level-121)，可在 WebUI 中自定义                     | ✅    |
| 提供 AOSP Keybox（可选）                                                                                                                                                | ✅    |
| 从设备存储导入自定义 Keybox                                                                                                                                             | ✅    |
| 添加系统应用（不推荐）                                                                                                                                                   | ✅    |
| Keybox 有效性 **不保证**                                                                                                                                                 | ❌    |
| 定期将所有应用添加到 target.txt                                                                                                                                          | ❌    |

## 本地化
- 阅读 [翻译指南](https://github.com/KOWX712/Tricky-Addon-Update-Target-List/blob/main/module/webui/locales/GUIDE.md)  

## 鸣谢
- [j-hc/zygisk-detach](https://github.com/j-hc/zygisk-detach) - KSU WebUI 模板  
- [markedjs/marked](https://github.com/markedjs/marked) - Markdown 支持  
- [TMLP-Team/keyboxGenerator](https://github.com/TMLP-Team/keyboxGenerator) - 未知 keybox.xml 生成器  

## 链接
[![release](https://custom-icon-badges.demolab.com/badge/-下载-F25278?style=for-the-badge&logo=download&logoColor=white)](https://github.com/KOWX712/Tricky-Addon-Update-Target-List/releases) 
[![issue](https://custom-icon-badges.demolab.com/badge/-提交问题-palegreen?style=for-the-badge&logoColor=black&logo=issue-opened)](https://github.com/KOWX712/Tricky-Addon-Update-Target-List/issues) 
[![changelog](https://custom-icon-badges.demolab.com/badge/-更新记录-orange?style=for-the-badge&logo=history&logoColor=white)](https://github.com/KOWX712/Tricky-Addon-Update-Target-List/blob/main/changelog.md) 
[![Telegram](https://custom-icon-badges.demolab.com/badge/-KOW的微世界-blue?style=for-the-badge&logo=telegram&logoColor=white)](https://t.me/kowchannel)
