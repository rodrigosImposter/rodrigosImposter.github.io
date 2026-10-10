# rodrigos 的笔记

用 Jekyll 搭建、由 GitHub Pages 自动发布的学习笔记博客。

网址：https://rodrigosimposter.github.io/

## 写一篇新文章

在 `_posts/` 里新建一个文件，文件名格式是 `年-月-日-英文短名.md`，比如 `2026-10-12-present-perfect.md`。开头写：

```
---
layout: post
title: 文章标题
description: 一句话说明这篇文章讲什么（会显示在首页列表里）
---
```

下面用 Markdown 写正文。推送到 `main` 分支后，几分钟内网站自动更新。

## 其他约定

- 交互式图解放在 `_includes/` 里，在文章中用 `{% include 文件名.html %}` 插入。
- 答案折叠：用 `<details markdown="1"><summary>展开答案</summary> … </details>` 包住。
- 例题框：用 `<div class="example" markdown="1"> … </div>` 包住。
- 修改旧文章时，可以在开头加一行 `last_modified_at: 2026-10-20`，文章页会显示更新日期。
