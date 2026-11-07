# GitHub Desktop 简体中文维护指南

## 维护方与上游

- 本机维护与打包方：非洲项目。
- 上游翻译作者：Johnserf-Seed。
- 上游项目：[GitHub-Desktop-Chinese-Language-Pack](https://github.com/Johnserf-Seed/GitHub-Desktop-Chinese-Language-Pack)。
- 上游 README 标注汉化工具采用 MIT 许可。若以后分发上游内容，应同时保留原作者署名和对应许可文本。GitHub Desktop 及其依赖仍遵循各自的许可。
- 此前为本机 GitHub Desktop 3.6.10 生成汉化包时使用的上游快照：[40415b067331bf73fd77c74293a7c3fb83e2baa9](https://github.com/Johnserf-Seed/GitHub-Desktop-Chinese-Language-Pack/commit/40415b067331bf73fd77c74293a7c3fb83e2baa9)，提交日期为 2026-10-18。该记录只说明当时使用的来源版本，不代表上游当前版本，也不表示本仓库提供对应安装包。

## 检查更新与版本适配

1. 从上游项目页面查看最新说明、源文件和许可信息。不要把本仓库的 `origin` 当作上游汉化仓库。
2. 确认本机 GitHub Desktop 版本，并核对上游是否提供对应版本的资源和脚本。
3. 若没有匹配版本，按上游当前 README 的流程从上游源文件生成；不要跨版本复用生成包，也不要覆盖上游署名或许可信息。
4. 安装前核对目标应用版本、原文件校验值和备份。发现版本或校验不匹配时停止。

## 本机安装与恢复

安装会修改本机 GitHub Desktop 应用文件。退出应用后，只使用与本机版本及原始文件校验值匹配的上游安装脚本；保留原版备份。恢复时使用同一版本配套的恢复脚本。重启后检查菜单和界面，并核对上游包内的文件清单。

机器专属的截图、日志、哈希记录和安装结果留在本机项目证据目录，不要提交到这个公开仓库。本仓库只维护通用操作说明，不分发翻译词典、安装脚本、生成包或修改后的 GitHub Desktop 程序文件。
