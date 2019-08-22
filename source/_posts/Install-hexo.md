---
title: 用hexo写博客
date: 2019-08-23 01:35:27
categories:
tags:
---

## 缘起

总想找个地方写博客，后来研究来研究去，用 markdown 的方式感觉最合适，hexo 是这方面里比较好的选择。

## 安装

1. 先安装 git，nodejs；
2. 安装 hexo

   ```bash
   npm install -g hexo-cli
   ```

3. 初始化博客

   ```bash
   hexo init <folder>
   cd <folder>
   npm install
   ```

4. 修改配置文件 \_config.yml
5. 配置模板，推荐用 next
6. 开始编写博客

   - 写新文章
     ```bash
     hexo new "My New Post"
     ```
   - 调试预览

     ```bash
     hexo server
     ```

   - 生成待发布文件

     ```bash
     hexo generate
     ```

   - 发布到网站

     ```bash
     hexo deploy
     ```
