# 夜色小说项目（含首页与详情页）

## 文件
- `index.html`：首页落地页
- `detail.html`：通用小说详情页，使用 `?id=` 参数加载对应作品
- `assets/style.css`：深海午夜蓝 + 月光青响应式主题
- `assets/app.js`：分类筛选、搜索、榜单、详情页渲染、浏览器本地收藏
- `data/books.js`：演示作品数据

## 本地预览
推荐 VS Code 安装 Live Server 后打开 `index.html`。详情页示例：`detail.html?id=moon-city`。

## GitHub Pages 部署
1. 新建 GitHub 公开仓库。
2. 解压 ZIP，将所有文件和文件夹上传到仓库根目录。

## 修改作品
编辑 `data/books.js` 的 `window.NIGHT_BOOKS` 数组。每本书的 `id` 必须唯一，首页卡片会自动链接到 `detail.html?id=对应id`。封面由 CSS 渐变生成，无需额外图片。

## 上线提醒
演示书目、作者、简介、人气和章节数据均为虚构样例，请替换为真实且已获授权的资料。项目仅提供展示与详情模板，不含未经授权的正文。成人小说分类面向成年人，请确保内容合法合规并设置适当访问管理。项目为纯静态站点，不含后台和账号系统。
