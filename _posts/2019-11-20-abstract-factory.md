---
layout: post
title:  "抽象工厂模式-笔记"
categories: 设计模式
tags: 设计模式
author: zhq
---

* content
{:toc}


```java

public interface Product {
}

public class ProductA extends Product {
}

public class ProductB extends Product {
}

public interface Channel {
}

public class ChannelA extends Channel {
}

public class ChannelB extends Channel {
}

public interface Factory {
	Product getProduct();
	Channel getChannel();
}

public class FactoryA extends Factory {
	@Override
	public Product getProduct() {
		return new ProductA();
	}
	@Override
	public Channel getChannel() {
		return new ChannelA();
	}
}


public class FactoryB extends Factory {
	@Override
	public Product getProduct() {
		return new ProductB();
	}
	@Override
	public Channel getChannel() {
		return new ChannelB();
	}
}

```


