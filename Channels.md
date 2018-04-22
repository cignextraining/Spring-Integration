---
title: Channels
subtitle: How channels and messages work in Spring Integration!
cover-photo: ./imgs/banner.jpg
auto-header: none
layout: "page"
icon: fa-code
order: 2
---

<header>
  <h2 class="alt">Producer and Consumer communicate with each other via Pipe / Channel.<br />
  Channels are an integral part of any Spring Integration application.</h2>
  <p>Classified can be classified into: Pollable Channels and Subscribable Channels</p>
</header>

- In Spring Integration:
	- Pipes are called **Channels**.
	- Producers and Consumers are known as **Endpoints**.
	- The communication occurs via **Messages**.
	- Message may consist of either some **data** or some **event information**.

{% gist 65594a8b17318fb1e965a307a8ada260 %}