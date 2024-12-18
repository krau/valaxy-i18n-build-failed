# valaxy i18n build failed

本repo使用 `pnpm create valaxy` 创建, 用于复现 valaxy 对 i18n 文章的构建失败问题.

valaxy 版本: v0.22.2

posts 目录下两篇文章分别为使用了 i18n 和未使用的文章

运行 `pnpm run build` 无法构建成功, 日志:


```shell
[vite-ssg] Rendering Pages... (12)
[vite-ssg] Critical CSS generation enabled via `beasties`
undefined:1
{"title":"I18n Test","description":"","frontmatter":{"title":"I18n Test","title_zh-CN":"国际化测试"},"headers":[{"level":2,"title":"什么是「依赖注入」","slug":"什么是「依赖注入」","link":"#什么是「依赖注入」","children":[]},{"level":2,"title":"What is "Dependency Injection"","slug":"what-is-dependency-injection","link":"#what-is-dependency-injection","children":[]}],"relativePath":"pages/posts/i18n-test.md","lastUpdated":null}

                                                                                                      ^

SyntaxError: Expected ',' or '}' after property value in JSON at position 221 (line 1 column 222)
    at JSON.parse (<anonymous>)
```