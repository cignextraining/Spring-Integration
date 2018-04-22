---
# You don't need to edit this file, it's empty on purpose.
# Edit theme's home layout instead if you wanna make some changes
# See: https://jekyllrb.com/docs/themes/#overriding-theme-defaults
layout: page
title: Spring Integration
icon: fa-home
order: 1
---

## Enterprise Application Integration

<br>
**Enterprise Application Integration (EAI)** is the middleware that allows applications across an Enterprise to communicate and work together.
<br>
<blockquote>
  <p>According to <em>Gartner</em>, EAI can be defined as unrestricted sharing of data and business processes among any connected application or data sources in the enterprise.
</p>
</blockquote>
<br>

  
### Why do we need EAI?
<br>
<blockquote>
  <p>Sometimes, Applications share data and processes that they probably weren't originally designed to share and in ways that may not have been even conceivable at the time of their creation.
</p>
</blockquote>
<br>

### Problem Perspective
<img src="./imgs/Picture1.png" style="display: block; padding: 2% 0% 2% 14%;"/>

- Producer application provide data in XML Format.
- Consumer application can only consume JSON Format data.
- EAI Solution transforms XML data to JSON data so it can be consumed.
  
## Spring Integration Framework
  
<br>  
- There are well known solutions to common needs in EIA world, which are called **Enterprise Integration Patterns (EIP)**. EIPs can be considered as Design Patterns of EIA world.

<br>
- **Spring Integration(SI)** is a physical embodiment of the EIP in Java which is built on top of Spring Framework.

<br>
- With Spring Integration, you can leverage features of Spring like:
	- [x] Dependency Injection and Spring Container.
	- [x] POJO driven capabilities and Bean Wiring.
	- [x] AOP
	- [x] Spring Security
	- [x] Other benefits of Spring Ecosystem