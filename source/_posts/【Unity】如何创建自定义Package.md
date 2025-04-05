---
title: 【Unity】如何创建自定义Package
date: 2025-04-05
tags:
  - blog
  - 记录
  - unity
  - custom package

---

---

## Step By Step

1. 按照自定义包的文件树建立好文件。 [创建自定义包 - Unity 手册](https://docs.unity.cn/cn/2023.2/Manual/CustomPackages.html)
2. 配置好对应的package.json后上传至github。
3. CHANGELOG.md的编写可以参考。 [如何维护更新日志](https://keepachangelog.com/zh-CN/1.1.0/)
4. LICENSE.md的选择可以从 [SPDX License List](https://spdx.org/licenses/) 中选择适合自己的。
5. 有了这些文件后从unity的Package Manager即可根据git链接安装下载。

## Reference

- [创建自定义包 - Unity 手册](https://docs.unity.cn/cn/2023.2/Manual/CustomPackages.html)
- [如何维护更新日志](https://keepachangelog.com/zh-CN/1.1.0/)
- [SPDX License List](https://spdx.org/licenses/)