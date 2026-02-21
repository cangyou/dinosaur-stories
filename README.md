# 恐龙故事网页

这是一个简单的恐龙故事网页，包含四个恐龙的故事和音频。

## 部署到 Vercel

### 方法一：通过 Vercel CLI

1. 安装 Vercel CLI：
   ```bash
   npm install -g vercel
   ```

2. 登录：
   ```bash
   vercel login
   ```

3. 部署：
   ```bash
   cd dinosaur-stories
   vercel
   ```

### 方法二：通过 GitHub（推荐）

1. 将此文件夹推送到 GitHub 仓库
2. 在 Vercel 中导入该仓库
3. Vercel 会自动检测并部署

## 文件说明

- `index.html` - 主页
- `tyrannosaurus.html` - 霸王龙故事
- `triceratops.html` - 三角龙故事
- `oviraptor.html` - 窃蛋龙故事
- `brachiosaurus.html` - 腕龙故事
- `*.mp3` - 故事音频文件
- `qr-*.png` - 二维码图片