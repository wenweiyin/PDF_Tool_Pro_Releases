# PDF Tool Pro 分发仓库

本仓库是 **PDF Tool Pro**（电力管道PDF材料清单智能提取系统）的公开分发通道，
只放两样东西：

1. **`version.json`** — 远程版本信息。桌面端启动时读取本文件做更新检查
   （软件内"检查更新"读的就是它，公开可达，无需登录）
2. **Releases 里的便携版 ZIP** — `PDF_Tool_Pro_Portable_v<版本>.zip`，
   解压即用，软件内一键更新下载的就是它

代码仓库在 [wenweiyin/PDF_Tool_Pro](https://github.com/wenweiyin/PDF_Tool_Pro)（私有）。
升版 SOP：改主仓库 version.json 与 APP_VERSION → 构建便携 ZIP →
在本仓库 Release 上传 + 更新本仓库 version.json → push。
