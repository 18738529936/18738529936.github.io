---
layout: post
title:  "Command line is too long. Shorten command line for XXXClass.xxx or also for JUnit default configuration."
categories: IDEA
tags: 开发工具 IDEA
author: zhq
---

* content
{:toc}

## Command line is too long. Shorten command line for XXXClass.xxx or also for JUnit default configuration.

解决方案
```text
在项目/.idea/workspace.xml文件中添加一行代码如下

<component name="PropertiesComponent">
  ...
 <property name="dynamic.classpath" value="true" />
</component>
```


