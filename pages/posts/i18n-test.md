---
title: I18n Test
title_zh-CN: 国际化测试
---

<!-- more -->

## 什么是「依赖注入」 {lang="zh-CN"}

## What is "Dependency Injection" {lang="en"}

::: zh-CN

>编程中的「依赖注入」是声明代码（本文中为路径操作函数 ）运行所需的，或要使用的「依赖」的一种方式。
>
>然后，由系统（本文中为 FastAPI）负责执行任意需要的逻辑，为代码提供这些依赖（「注入」依赖项）。
>
>依赖注入常用于以下场景：
>
>- 共享业务逻辑（复用相同的代码逻辑）
>- 共享数据库连接
>- 实现安全、验证、角色权限等……
>
>上述场景均可以使用依赖注入，将代码重复最小化。
:::


::: en

>"Dependency Injection" means, in programming, that there is a way for your code (in this case, your path operation functions) to declare things that it requires to work and use: "dependencies".
>
>And then, that system (in this case FastAPI) will take care of doing whatever is needed to provide your code with those needed dependencies ("inject" the dependencies).
>
>This is very useful when you need to:
>
>- Have shared logic (the same code logic again and again).
>- Share database connections.
>- Enforce security, authentication, role requirements, etc.
>- And many other things...
>
>All these, while minimizing code repetition.
:::