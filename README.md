# 车间记数 · 安装包

这个仓库**只放已发布的 APK**，源码不在公开仓库。

- 正式版安装包从这里下载：Releases 页面
- 应用内「检查更新」会读这个仓库的 Releases，不需要令牌
- 每个 release 的说明里带 `versionCode=` 与 `SHA256:`，客户端靠它们判断要不要更新、包有没有下坏

为什么要单独开一个公开仓库：GitHub 的 release 附件走国际线路，国内单连接实测 12 KB/s；
公开仓库才能被 ghfast.top / gh-proxy.com / ghproxy.net 这类镜像代理，不挂梯子也能跑到几 MB/s。
