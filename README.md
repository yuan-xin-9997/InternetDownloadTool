# InternetDownloadTool

支持并行下载和断点续传的桌面下载器，适用于 Windows x64、macOS（Apple Silicon 和 Intel）与 Ubuntu 24.04 x64。支持 HTTP/HTTPS、磁力链接、BT 种子，以及 Chrome 和 Edge 下载接管。

**2.99 美元一次性买断**。最多两台电脑可永久使用所购版本，无需订阅。安装包免费下载，启动下载任务前需要激活。适用税费由 Creem 在结账时显示。

- [下载安装包](https://github.com/yuan-xin-9997/InternetDownloadTool/releases)
- [商店](https://internetdownloadtool.yuan-xin.top/)（正式收款启用后可购买）
- 技术支持：support@yuan-xin.top

解压后运行桌面应用，在「授权 → 购买／激活」复制机器码。付款后用机器码领取激活码，粘贴回应用即可离线激活。命令行可用 IDT CLI 的 `--machine-code` 查看机器码，使用 `--activate` 从标准输入导入激活码。

暂停后，用相同链接、保存位置和来源网址继续。HTTP 续传需要服务器支持分段请求，且能够确认远程文件版本。浏览器接管请先在应用的「浏览器」菜单连接，再把发布包内的 browser 目录加载为 Chrome 或 Edge 扩展。

macOS 安装包目前未做 Developer ID 签名和公证。
