---
layout: post
title:  "IDEA中Gradle更新同一版本Jar包问题"
categories: 工作
tags: IDEA Gradle Jar
author: zhq
---

* content
{:toc}



## Gradle中jar包文件目录


```text
C:\Users\Administrator\.gradle\caches\modules-2\files-2.1\com.alibaba\druid\1.1.10\5edd3db1f7ef54083e4c56e4743fa8bfbc517de\druid-1.1.10.jar
```

## Gradle中jar相关元数据信息

```text
C:\Users\Administrator\.gradle\caches\modules-2\metadata-2.71\descriptors\com.alibaba\druid\1.1.10\914ad02d4ad4079ffc934cc00b97defa\descriptor.bin
```

需要清理两个目录，才能重新下载最新的jar包
