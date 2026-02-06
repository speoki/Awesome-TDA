# 部署指南

本文档说明如何将Awesome TDA文档部署到GitHub Pages。

## 自动部署（推荐）

### 一. 启用GitHub Pages

1. 进入GitHub仓库设置
2. 点击左侧的 **Pages** 选项
3. 在 **Source** 下拉菜单中选择 **main** 分支
4. 选择 **/docs** 文件夹作为根目录
5. 点击 **Save** 保存

### 二. 访问网站

等待几分钟后，访问：
```
https://你的用户名.github.io/Awesome-TDA/
```

## 本地预览

### 使用Docsify CLI

1. 安装Docsify CLI：
```bash
npm i docsify-cli -g
```

2. 在项目根目录运行：
```bash
docsify serve docs
```

3. 打开浏览器访问 `http://localhost:3000`

### 使用Python简单服务器

```bash
cd docs
python -m http.server 3000
```

然后访问 `http://localhost:3000`

## 更新文档

1. 编辑 `docs/` 目录下的Markdown文件
2. 提交并推送到GitHub
3. GitHub Pages会自动更新

## 文档结构

```
docs/
├── index.html          # Docsify配置文件
├── README.md           # 中文首页
├── _sidebar.md         # 中文侧边栏
├── 01_软件包.md        # 中文文档
├── 02_持久性变体.md
├── ...
└── en/                 # 英文文档
    ├── README.md
    ├── _sidebar.md
    └── ...
```

## 自定义

### 修改主题颜色

编辑 `docs/index.html`，修改CSS变量：

```css
:root {
  --theme-color: #42b983;  /* 修改为你喜欢的颜色 */
}
```

### 添加插件

在 `docs/index.html` 中添加插件脚本。

参考：https://docsify.js.org/#/plugins
