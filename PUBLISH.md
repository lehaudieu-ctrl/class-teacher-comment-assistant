# 发布到 GitHub Pages

## 1. 注册 GitHub 账号

打开：

```text
https://github.com/signup
```

按页面提示完成邮箱、用户名、密码、验证码验证。

Codex 不能替你完成注册，因为这一步涉及邮箱、密码和人机验证。

## 2. 新建仓库

登录后新建一个公开仓库，例如：

```text
class-teacher-comment-assistant
```

不要勾选自动生成 README，因为本地已经有文件。

## 3. 本地推送

在本目录运行，把下面的 `你的用户名` 换成 GitHub 用户名：

```powershell
git branch -M main
git add .
git commit -m "Publish class teacher comment assistant"
git remote add origin https://github.com/你的用户名/class-teacher-comment-assistant.git
git push -u origin main
```

如果本机没有配置 Git 身份，先运行：

```powershell
git config --global user.name "你的用户名"
git config --global user.email "你的邮箱"
```

## 4. 开启 Pages

进入仓库：

```text
Settings -> Pages
```

设置：

```text
Source: Deploy from a branch
Branch: main
Folder: /root
```

保存后等待 1-3 分钟。

## 5. 访问地址

```text
https://你的用户名.github.io/class-teacher-comment-assistant/
```

如果你想做成类似：

```text
https://你的用户名.github.io/tools-hub-ai-guide/#assistant
```

就把仓库名建成：

```text
tools-hub-ai-guide
```

或者后续把这个工具合并到已有的 `tools-hub-ai-guide` 仓库中。
