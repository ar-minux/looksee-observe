# LookseeObserve
**BankX Studio**

> LookseeObserve —— 面向3D游戏与大型软件的编程语言 & 引擎
> 底层由 **Java** 开发，是 Looksee 的高性能升级版。

## 📌 项目介绍
Looksee 是 Python 编写的轻量2D原型引擎。
**LookseeObserve 使用Java实现**，目标用来制作复杂3D游戏、大型软件。
两者共用一套 `.lk` 脚本语法风格，但底层运行时完全独立。

- 源码脚本后缀：`.lk`
- 单行注释符号：`/#`

## ✨ 基础语法示例 demo.lk
```lk
/# LookseeObserve 基础演示
create cube 1 1 1        /# 创建1×1×1立方体
set cube position 0 0 0  /# 设置立方体坐标
set cube color 1 0.4 0.2 /# 设置RGB颜色
render                    /# 渲染画面

