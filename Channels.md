---
title: Channels
subtitle: How channels and messages work in Spring Integration!
layout: page
auto-header: none
icon: fa-code
order: 2
---

- Producer and Consumer communicate with each other via **Pipe / Channel**. Channels are an integral part of any Spring Integration application.
- Channels can be classified into: **Pollable Channels and Subscribable Channels**
- In Spring Integration:
	- Pipes are called **Channels**.
	- Producers and Consumers are known as **Endpoints**.
	- The communication occurs via **Messages**.
	- Message may consist of either some **data** or some **event information**.
	
<br/>

- Sequence to follow: 
	1. Subscribable Channel
	2. Pollable Channel
	3. Direct Channel
	
<br/>
	
{% gist 59904706bf418a2efa19fd48e42d408c %}

