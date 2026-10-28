# PS 切图

Windows x64 Photoshop 辅助工具，支持选中图层导出 PNG/TGA、连接已启动的多个 Photoshop 版本、文字转换、按钮多态、冗余数据清理和界面目录导入。

## 下载与运行

前往 [最新正式版本](https://github.com/ooccll/ps-slice-releases/releases/latest)，下载 `PS切图_Tga.exe` 到本机运行。需已安装 Photoshop；程序不需要 Python、Git 或 GitHub 登录。

此仓库仅分发可执行程序、更新说明与校验文件。每个正式版本提供：

- `PS切图_Tga.exe`：Windows x64 程序。
- `update.json`：版本、下载地址、更新说明和 SHA-256 校验信息。
- `SHA256SUMS.txt`：EXE 的 SHA-256 校验值。

## 更新

首次使用 GitHub 版时，旧版用户需手动下载替换一次。之后程序启动及每 10 分钟后台检查更新，发现新版显示金黄色“更新”菜单；也可从“帮助 → 关于”手动检查。

点击更新后下载并校验，等待当前任务结束，再退出替换并重启。失败时保护或恢复旧版。请勿从共享库直接运行，也不要在网络盘原地更新。

## 第三方许可

第三方依赖与声明见 [NOTICES.txt](NOTICES.txt)。完整许可见 [licenses](licenses)：Dear ImGui 与 nlohmann/json 使用 MIT 许可，OpenCC 词库使用 Apache License 2.0。本仓库未授予应用程序源码的开源许可。
