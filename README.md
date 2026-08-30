# peachch.github.io

Yuxi Sun 的个人主页，托管在 GitHub Pages 上，部署后访问地址：<https://peachch.github.io>

## 文件说明

| 文件 | 作用 |
|---|---|
| `index.html` | 主页内容（所有文字都在这里，搜索 `TODO` 逐个替换） |
| `style.css` | 样式（改主题色只需改文件开头的 `--accent` 变量） |
| `assets/avatar.jpg` | 头像（替换成你自己的照片，保持文件名即可） |

## 部署到 GitHub Pages（一次性操作）

1. 在 GitHub 上新建仓库，名称必须为 **`peachch.github.io`**（公开）。
2. 然后在本地执行：

```bash
cd peachch.github.io
git remote add origin https://github.com/peachch/peachch.github.io.git
git push -u origin main
```

3. 稍等 1~2 分钟，访问 <https://peachch.github.io> 即可看到主页。

## 本地预览

```bash
cd peachch.github.io
python -m http.server 8000
# 浏览器打开 http://localhost:8000
```

## 日常更新

改完 `index.html` 后：

```bash
git add -A
git commit -m "update homepage"
git push
```

推送后约 1 分钟线上生效。
