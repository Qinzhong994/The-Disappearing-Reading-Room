# 消失的阅览室 | The Disappearing Reading Room
校园治愈系视觉小说 / Campus Healing Visual Novel

## 作品简介
《消失的阅览室》是基于 Ren'Py 制作的高三校园治愈向VN，讲述女主苏柚在神秘阅览室发现十年银杏书签，揭开学长江屿默默治愈历届学子的温柔故事。

## 游玩方式
### 方式1：网页在线游玩
部署 Github Pages / Cloudflare Pages 打开链接即玩。
### 方式2：本地运行网页版
1. 下载 Releases 中的 web-build.zip
2. 解压，在文件夹内打开 cmd，执行 `python -m http.server 8080`
3. 浏览器访问 http://127.0.0.1:8080

## 制作流程
1. Excel表格撰写剧本台词
2. Excel2RpyScript 批量转 rpy 脚本
3. Ren'Py 配置角色、立绘、转场、BGM旁白系统
4. 音频统一转 ogg 适配引擎
5. 支持打包 Windows 客户端 & Web网页端

## 项目结构
- `game/script.rpy`：全部剧情脚本
- `game/images/`：背景、人物立绘、侧边头像
- `game/audio/`：背景音乐、配音、音效
