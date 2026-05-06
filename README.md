# music

一个简洁的 Web 音乐播放器：
- 首页展示“全球热门 5 首”（每天自动更新）
- 每首歌曲显示完整来源链接
- 支持搜索并直接播放
- 支持连续播放（自动下一首）
- 网页带 Tab 图标（favicon）
- 进入页面需要密码（默认：`music2026`）
- 支持 YouTube 合规播放（官方嵌入播放器）

> 合规说明：
> - 当前 iTunes 播放源通常是试听片段，不一定是整首完整版。
> - YouTube 功能仅使用官方嵌入播放器，不提供音视频解析、下载或绕过版权限制。

## 使用
直接打开 `index.html` 即可。

## 部署到 Vercel
这是纯静态页面项目，可直接部署：
- Framework Preset: `Other`
- Build Command: 留空
- Output Directory: 留空（根目录静态文件）
