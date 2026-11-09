---
title: uv配置
weight: 2
---

## **uv**下载配置

> 官方仓库：<https://github.com/astral-sh/uv/releases>

## **uv**部分命令

* 设置默认**Python**版本：`uv python default 3.14`
* 设置项目**Python**版本：`uv python pin 3.14`
* 初始化项目：`uv init new_project`
* 生产环境添加依赖：`uv add numpy`
* 生产环境移除依赖：`uv remove numpy`
* 开发环境添加依赖：`uv add --dev ruff`
