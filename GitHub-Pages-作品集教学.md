# 用 GitHub Pages 发布你的 Python 作品集

这个网站完全免费，不需要购买域名或服务器。发布后网址格式是：

`https://你的GitHub用户名.github.io`

例如 GitHub 用户名是 `kaiyang`，网址就是 `https://kaiyang.github.io`。

## 一、先改成自己的内容

1. 用记事本或 VS Code 打开 `content.js`。
2. 修改最上方的 `name`（姓名）、`title`（身份）、`email`（邮箱）、`github`（GitHub 地址）和 `location`（所在地）。
3. 在 `projects` 里修改每个项目的 `title`（标题）、`description`（简介）、`tags`（技能标签）、`link`（项目 GitHub 链接）。
4. 保存后双击 `index.html`，即可在浏览器中检查效果。

注意：文字必须保留英文双引号；每一项末尾的逗号不要删错。

## 二、创建自己的网址

1. 注册并登录 [GitHub](https://github.com)。你的 GitHub 用户名会成为网址的一部分，请选一个正式、易读的英文名称。
2. 点击右上角 `+`，选择 `New repository`。
3. Repository name 填入：`你的GitHub用户名.github.io`。
4. 选择 `Public`，点击 `Create repository`。
5. 点击 `Add file` -> `Upload files`，把本作品集文件夹中的 `index.html`、`style.css`、`script.js`、`content.js` 全部拖进去，再点击 `Commit changes`。
6. 打开仓库的 `Settings` -> `Pages`。
7. 在 `Build and deployment` 中选择 `Deploy from a branch`，分支选 `main`，文件夹选 `/ (root)`，点击 `Save`。
8. 等待 1 到 5 分钟，再访问 `https://你的GitHub用户名.github.io`。

## 三、以后怎样更新

在 GitHub 仓库打开 `content.js`，点击铅笔图标编辑，保存并提交。等待一两分钟，网址上的内容会自动更新。

## 小建议

- 项目链接优先填写对应 GitHub 仓库地址。
- 不确定能否公开的数据、登录信息和 Cookie 不要上传。
- 每个作品用一句话说明“采集了什么、处理了什么、最后得到了什么”。
