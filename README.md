# WeChat Article Image Extractor  
**公众号图文图片一键提取/打包/本地预览工具**

> 纯前端实现，无需服务器，打开浏览器即可使用。  
> 支持将微信（公众号）保存下来的 `.html` 文章中的 `<img data-src="...">` 批量替换为真正的 `src`，并可视化预览、单张/批量下载、打包 ZIP、生成 PowerShell 下载脚本或本地化后的 HTML。

---

## 功能特性

| 功能 | 说明 |
|---|---|
|  自动解析 | 把 `data-src` 替换成 `src`，即时预览整篇文章 |
|  缩略图墙 | 右侧自动生成图片网格，序号对应正文顺序 |
|  多种下载 | 单张下载、选中下载、一键打包 ZIP |
|  脚本导出 | 生成 PowerShell 批量下载脚本（带 Referer，可过防盗链） |
|  本地化 | 导出一份新的 HTML，图片路径指向本地 `images/` |
|  深色模式 | 自动跟随系统 |
|  移动友好 | 响应式布局 |

---

## 快速开始

1. 直接访问 GitHub Pages（推荐）：  
   [https://github.com/JA-cool/WeChat_Article_Image_Extractor/index.html](https://ja-cool.github.io/WeChat_Article_Image_Extractor/)
   或把 `index.html` 下载到本地双击打开。

3. 把从公众号保存的 `.html` 文件拖进页面，或点击“选择文件”。

4. 等待解析完成 → 在右侧缩略图墙勾选/全选 → 选择需要的导出方式。
