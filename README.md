# mfgy-release

当前版本：**1.1.17**（versionCode 162，强制更新）

# mfgy 发布仓库（公开）

本仓库仅存放 **APK 与 update.json**，不含源码。

- 应用：mfgy（`com.mfgy.gg.yyds`）
- 目标游戏：魔法工艺 `com.bilibili.mfgy`
- 最新版本：见 [Releases](https://github.com/Mina-kk/mfgy-release/releases) 与根目录 `update.json`
- 国内镜像（APK）：[Gitee Mina-kk/mfgyapp](https://gitee.com/Mina-kk/mfgyapp)

## 下载

1. 打开 Releases 下载 `mfgy-v1.1.17.apk`
2. 或查看 `update.json` 中的 `apkUrl`
3. 国内用户也可到 Gitee 仓库下载同名 APK

## 更新检测

App 启动时与回到前台时会请求本仓库 `update.json`（多镜像，取最高 versionCode）。当公开仓版本更高时，会引导更新到最新版。

## 1.1.17 要点

- 悬浮窗单面板接入九宫解密（同源 gua/DS/mfgy.html 算法）
- 云档列表上方「解密」切换同面板 3×3；点格填亮灭后求解；返回云档
- 不改云档热导入原有时序

## 历史能力概览（1.1.x）

- MD3 液态玻璃界面、亮暗主题、自定义背景
- 底部导航（状态 / 存档库 / 备份 / 社区）与存档库分区
- 社区本地上传逐项命名；合集下载导入名称对齐
