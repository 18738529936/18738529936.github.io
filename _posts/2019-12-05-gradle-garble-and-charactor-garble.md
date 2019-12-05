---
layout: post
title:  "IDEA中Gradle乱码、Springboot中使用Gradle启动JSP项目、JSP中传输特殊字符"
categories: 开发
tags: IDEA Gradle JSP
author: zhq
---

* content
{:toc}



## IDEA中Gradle乱码


```text
ile->Other Settings->Default Settings->Gradle，在Gradle Vm Options中设置-Dfile.encoding=utf-8
```

## Springboot中使用Gradle启动JSP项目

```text
修改本地启动的方式为：mvn spring-boot:run   
或
gradlew bootRun
```

## JSP中传输特殊字符

```text
在JSP页面中增加encodeURIComponent()函数包裹
```