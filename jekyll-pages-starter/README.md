# GitHub Pages + Jekyll 最小可用模板

## 使用方法（极简）
1. 把整个仓库名命名为 `你的用户名.github.io`（必须，用于个人主页）。
2. 把这里的 `<your-username>` 改成你的 GitHub 用户名：`_config.yml` -> `url: "https://<your-username>.github.io"`。
3. 进入仓库 `Settings -> Pages`，把 *Build and deployment* 设为 **Deploy from a branch**，分支选 `main`，目录选 `/ (root)`。
4. 等几分钟后访问：`https://你的用户名.github.io`。
5. 每天写文章：在 `_posts/` 新建 `YYYY-MM-DD-你的标题.md`，前面加上三杠 YAML：
   ```
   ---
   layout: post
   title: "今天的日志标题"
   date: 2025-01-01 09:00:00 -0500
   categories: [日志]
   tags: [学习, 生活]
   ---
   这里是正文（支持 Markdown）。
   ```

## 自定义
- 修改 `_config.yml` 里的 `title`, `author`, `description`。
- 顶部导航通过 `header_pages` 控制，例如把 `about.md` 放进去。
- 首页使用 `layout: home`（minima 主题会自动列出文章）。