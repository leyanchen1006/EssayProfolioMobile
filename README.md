# 乔治与他的朋友们 · Mobile

一个适合手机阅读的静态文学作品网站，可直接部署到 GitHub Pages。

## 文件结构

- `index.html`：页面结构
- `styles.css`：页面样式
- `script.js`：作品数据与页面交互
- `文字作品.txt`：原始文字作品备份

## 本地预览

直接双击 `index.html` 即可打开，或在当前目录运行：

```bash
python3 -m http.server 8000
```

然后访问 `http://localhost:8000`。

## 上传到 GitHub

1. 在 GitHub 新建一个仓库。
2. 将当前文件夹中的文件上传到仓库根目录。
3. 打开仓库的 `Settings` -> `Pages`。
4. 在 `Build and deployment` 中选择：
   `Deploy from a branch`
5. 选择分支：`main`，目录：`/ (root)`。
6. 保存后等待几分钟，GitHub Pages 会生成网站链接。

## 说明

这个项目不依赖打包工具或框架，上传后可直接作为静态网页运行。
