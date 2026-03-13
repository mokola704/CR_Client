# CR Client

Windows 桌面版 Cloudreve V4 客户端（PySide6 + QWebEngine + Aria2），提供接近网盘原生体验的文件浏览与下载管理。
非狗屎官方OneDrive方案，参考百度网盘ui实现。

## 项目特性

- Cloudreve V4 登录与文件浏览
- 文件/文件夹下载（支持批量）
- Aria2 多线程下载、失败重试
- 下载任务列表、状态与速度查看
- 自动保存配置（服务器地址、账号密码、下载参数等）
- 内置一键构建与一键发布脚本

## 运行环境

- Windows 10/11
- Python 3.11+
- 可访问的 Cloudreve V4 服务

依赖见 `requirements.txt`：

- `PySide6`
- `requests`
