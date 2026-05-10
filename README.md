# 宇宙尺度之旅（Cosmic Journey）

单页互动：从银河系缩放到「你在这里」，含氛围乐、定位与地球贴图等。

## 本地打开

用本地静态服务器打开目录（避免部分浏览器对 `file://` 限制），例如：

```bash
python3 -m http.server 8080
```

浏览器访问 `http://127.0.0.1:8080/cosmic_journey.html` 或根路径 `http://127.0.0.1:8080/`（会跳转到主页面）。

## GitHub Pages

1. 在本目录已初始化 Git 后，推送到 GitHub 上的**新仓库**（仓库名可自定，例如 `cosmic-journey`）。
2. 在 GitHub 仓库 **Settings → Pages**：
   - **Build and deployment**：Source 选 **Deploy from a branch**
   - **Branch**：选 `main`（或你用的默认分支），文件夹选 **`/ (root)`**
3. 保存后约 1～2 分钟，站点地址一般为：  
   `https://<你的用户名>.github.io/<仓库名>/`  
   根路径会跳转到 `cosmic_journey.html`。

若使用 **User/Organization Pages**（`username.github.io` 仓库），请把本仓库内容放到该仓库根目录，主文件同样通过 `index.html` 跳转即可。

## 资源说明

- `p5.min.js` 为本地备份；失败时会从 jsDelivr 加载 p5。
- 场景卡片引用的 `space_scene_*.jpg` 若未放入本目录，图片会 404，可自行补图。
