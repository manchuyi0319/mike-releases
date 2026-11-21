# 觅客 · 本地获客系统

本仓库只做一件事：**托管觅客的安装包更新**。

- 这里不存放任何源码。
- 每个版本对应一个 Release，Release 里挂的就是安装包本体。
- 软件内部会读取本仓库的最新 Release 来判断有没有新版本。

## 下载

进 [Releases](https://github.com/manchuyi0319/mike-releases/releases/latest) 下载最新的 `觅客-安装包-x.y.z.exe`，双击安装即可，会自动覆盖旧版本，数据不会丢。

## 说明

- 数据保存在 `%LOCALAPPDATA%\AILocalLeads`，卸载重装都不会动它。
- 安装包未做代码签名，首次运行 Windows 可能提示"已保护你的电脑"，点「更多信息 → 仍要运行」。
