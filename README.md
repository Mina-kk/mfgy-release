# mfgy-release

当前版本：**1.1.16**（versionCode 161，强制更新）

# mfgy 发布仓库（公开）

本仓库仅存放 **APK 与 update.json**，不含源码。

- 应用：mfgy（`com.mfgy.gg.yyds`）
- 目标游戏：魔法工艺 `com.bilibili.mfgy`
- 最新版本：见 [Releases](https://github.com/Mina-kk/mfgy-release/releases) 与根目录 `update.json`

## 下载

1. 打开 Releases 下载 `mfgy-v1.1.16.apk`
2. 或查看 `update.json` 中的 `apkUrl`

## 更新检测

App 启动时与回到前台时会请求本仓库 `update.json`（多镜像，取最高 versionCode）。当公开仓版本更高时，会引导更新到最新版。

## 1.1.16 要点

- 社区「我的仓库」本地 json/zip 上传：先检测并逐项「命名并上传」，再填标题/描述
- 包内项名使用用户命名，不再出现 `upload_时间戳`
- 合集下载导入：按 meta 逐项名称预填，不再回退为「标题-序号」
- 兼容旧合集包（多云档 gameFile 同名）

## 历史能力概览（1.1.x）

- MD3 液态玻璃界面、亮暗主题、自定义背景
- 底部导航（状态 / 存档库 / 备份 / 社区）与存档库分区
- 社区订阅源、我的仓库、整库导出与恢复
- 公开仓强制更新（多镜像 + 返回再拦截）

源码仓库为私有，本仓不提供源码。
