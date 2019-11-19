---
layout: post
title:  "简单工厂模式-笔记"
categories: 设计模式 
tags: 设计模式 
author: zhq
---

* content
{:toc}


## 简单工厂模式-一
```java
public class SuperClass {
}

public class A extends SuperClass {
}

public class B extends SuperClass {
}

public class SimpleFactory {
    public static final String TYPE_A = "A";
    public static final String TYPE_B = "B";
    pulic static SuperClass getSuperClass(String type) {
        if (Objects.equals(type, TYPE_A) {
	    return new A();
	}
	if (Objects.equals(type, TYPE_B) {
	    return new B();
	}
	return null;
    }
}
```



## 简单工厂模式-二

```java
public class SimpleFactory {
    public static SuperClass getA() {
	return new A();
    }
    public static SuperClass getB() {
	return new B();
    }
}
```


