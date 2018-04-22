---
title: Channels
subtitle: How channels and messages work in Spring Integration!
layout: "page"
icon: fa-code
order: 2
---

{% highlight java %}
@SpringBootApplication
@ImportResource("/int-config/integration.xml")
public class Application {

	public static void main(String[] args) {
		SpringApplication.run(Application.class, args);
	}
}
{% endhighlight %}


```
@SpringBootApplication
@ImportResource("/int-config/integration.xml")
public class Application {
	public static void main(String[] args) {
		SpringApplication.run(Application.class, args);
	}
}
```