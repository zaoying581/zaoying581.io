# 课堂日记 AI - 部署指南

## 🚀 方案一：GitHub Pages（推荐，需VPN访问GitHub）

### 1. 创建GitHub仓库
手机/PC浏览器打开 https://github.com/new
- 仓库名：`class-diary`（或任意名称）
- 选择 Public（公开）
- 不要勾选任何初始化选项

### 2. 上传文件
将本目录下所有文件上传到仓库根目录：
- `index.html`（主页面）
- `manifest.json`（PWA配置）
- `sw.js`（Service Worker离线缓存）

### 3. 启用GitHub Pages
仓库 → Settings → Pages → Source 选 `main` 分支 → Save
几分钟后访问：`https://你的用户名.github.io/class-diary/`

---

## 🇨🇳 方案二：Gitee Pages（国内直接访问，无需VPN）

### 1. 注册Gitee
https://gitee.com 注册账号

### 2. 创建仓库并上传文件
新建仓库 → 上传 index.html, manifest.json, sw.js

### 3. 启用Gitee Pages
仓库 → 服务 → Gitee Pages → 启动
访问：`https://你的用户名.gitee.io/class-diary/`

> ⚠️ Gitee Pages免费版需要手动点击"更新"按钮来同步最新代码

---

## ☁️ 方案三：Cloudflare Pages（全球CDN，国内部分地区可访问）

1. https://dash.cloudflare.com 注册
2. Workers & Pages → Pages → 上传资产
3. 直接拖拽本目录上传即可

---

## 📱 PWA安装到手机桌面

打开网站后：
- **iPhone Safari**: 分享按钮 → 添加到主屏幕
- **Android Chrome**: 菜单 → 添加到主屏幕

安装后可以像原生App一样使用，支持离线访问！

---

## 🤖 DeepSeek API Key 获取

1. 访问 https://platform.deepseek.com
2. 注册并登录
3. API Keys → 创建新Key → 复制
4. 在App的「AI规划」页面填入

> 新用户有免费额度！deepseek-chat 模型非常便宜

---

## ☁️ JSONBin.io 同步配置

1. 访问 https://jsonbin.io
2. 注册免费账号
3. 创建新Bin → 随便填点初始数据
4. 复制 Bin ID 和 X-Master-Key（在API Keys页面）
5. 在App的「同步」页面填入

> 免费版：10万个请求/月，完全够用
