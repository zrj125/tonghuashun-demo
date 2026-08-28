# 证券 Demo PWA

这是一个可部署到手机浏览器的 PWA 版本。

## 文件说明
- `index.html`：主页面
- `manifest.webmanifest`：PWA 配置
- `sw.js`：离线缓存
- `icon-192.png` / `icon-512.png`：App 图标

## 手机上怎么用
1. 把整个文件夹上传到任意静态网站托管平台：
   - Netlify
   - Vercel
   - GitHub Pages
2. 得到一个 https 网址后，用 iPhone Safari 打开。
3. 点击 Safari 的“分享”按钮。
4. 选择“添加到主屏幕”。
5. 之后桌面上会出现一个 App 图标，打开时更像原生 App。

## 注意
- 本地 `.html` 文件直接在 iPhone 上一般不能完整触发 PWA 效果。
- 最好部署成真正的网址（https）后再添加到主屏幕。
- 页面中的数据保存在浏览器本地 localStorage 中。
