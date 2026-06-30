# 班主任评语助手

这是一个可部署到 GitHub Pages 的静态网页工具。

## 功能

- 导入 `.xlsx/.xls` 学生花名册
- 兼容左右两栏点名册格式
- 按五育融合勾选学生表现
- 生成可复制的期末评语
- 保存当前学生评语到浏览器本地
- 复制 AI 优化提示词

## 公开版说明

GitHub Pages 只能运行静态网页，不能运行 Python 后端。因此公开版不内置 OpenAI API Key，也不直接调用真实 AI 接口。需要 AI 优化时，请使用页面里的“复制AI提示词”，粘贴到你常用的大模型中继续优化。

## GitHub Pages

把本目录作为一个 GitHub 仓库推送后，在仓库设置中开启 Pages：

- Source: Deploy from a branch
- Branch: main
- Folder: /root

发布后访问：

```text
https://你的用户名.github.io/仓库名/
```

如果仓库名叫 `tools-hub-ai-guide`，也可以用：

```text
https://你的用户名.github.io/tools-hub-ai-guide/#assistant
```
