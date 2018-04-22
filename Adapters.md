---
title: Adapters
subtitle: How adapters work in Spring Integration!
layout: "page"
icon: fa-code
order: 3
---

- **Adapters** are endpoints that connects a channel to external system or technology. Adapters take content from outside of SI and bring it in as messages into SI channels or take SI messages and deposit their content to an external system.
	1. **Inbound Adapters**: Brings messages to the SI Channel
	2. **Outbound Adapters**: Get messages from SI Channel to outside applications.
- It provides a **bridge** between SI and external systems / services.
- **Separation of Concern** of your Message API from transports and Protocols.
  	
<br/>
  
<img src="{{ site.baseurl }}/imgs/Adapters.PNG" style="display: block; padding: 2% 0% 2% 14%;"/>
  
<br/>
   
- Sequence to follow: 
	1. Outbound Adapter with Stdin
	2. Outbound Adapter with File Inbound
	3. Duplicates allowable
   
<br/>
	
{% gist 0436172e3895cb557675d9c894622d94 %}