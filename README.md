# 韩嫣 Portfolio

平面设计师个人静态网站，用于展示韩嫣的品牌视觉、广告 KV、商业合成、数字营销视觉和跨媒介版式设计作品。

## 项目结构

- `index.html`: 网站首页，纯 HTML/CSS，无构建依赖。
- `assets/`: 从作品集 PDF 中提取并压缩后的轻量作品图片。
- `.files/`: 本地原始简历和作品集 PDF，仅用于生成素材，不提交到 GitHub。

## 本地预览

直接用浏览器打开：

```text
file:///D:/code_files/hanyan_web_info/index.html
```

## 部署

适合直接部署到 GitHub Pages：

1. 打开仓库 Settings。
2. 进入 Pages。
3. Source 选择 `Deploy from a branch`。
4. Branch 选择 `main`，目录选择 `/root`。

## 维护

更新作品时，先把 PDF 或图片放入 `.files/`，再生成压缩后的图片放到 `assets/`，并在 `index.html` 中引用压缩图。
