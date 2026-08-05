# mfgy 发布仓库（公开）

本仓库仅存放 **APK 与 update.json**，不含源码。

- 应用：mfgy（`com.mfgy.gg.yyds`）
- 目标游戏：魔法工艺 `com.bilibili.mfgy`
- 最新版本：见 [Releases](https://github.com/Mina-kk/mfgy-release/releases) 与根目录 `update.json`

## 下载
1. 打开 Releases 下载 `mfgy-vX.Y.Z.apk`
2. 或查看 `update.json` 中的 `apkUrl`

## 更新检测
App 启动时与回到前台时会请求本仓库 `update.json`（多镜像，取最高 versionCode）。当公开仓版本更高时，会引导更新到最新版；点「立即更新」会打开下载页并退出应用。

## 1.1.5 相对 1.0.21 起的能力概览
- MD3 液态玻璃界面、亮暗主题、自定义背景
- 底部导航（状态 / 存档库 / 备份）与存档库分区
- 分享命名保留、整库导出与恢复
- 公开仓强制更新（多镜像 + 返回再拦截 + 更新后退出）
- 权限入口按授权状态自动显隐

源码仓库为私有，本仓不提供源码。