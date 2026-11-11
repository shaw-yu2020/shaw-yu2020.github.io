---
title: uv配置
weight: 2
---

## **uv**下载配置

> 官方仓库：<https://github.com/astral-sh/uv/releases>

## **uv**部分命令

* 设置默认**Python**版本：`uv python default 3.14`
* 设置项目**Python**版本：`uv python pin 3.14`
* 初始化：`uv init` & `uv init <project>`
* 添加依赖：`uv add <package>` & `uv add --dev ruff`
* 移除依赖：`uv remove <package>` & `uv remove --dev ruff`
* 清理缓存：`uv cache clean`
* 清理缓存：`rm -r "$(uv python dir)"`
* 清理缓存：`rm -r "$(uv tool dir)"`
