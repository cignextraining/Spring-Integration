---
title: Routers
subtitle: How routers work in Spring Integration!
layout: "page"
icon: fa-code
order: 6
---

- **Routers** direct messages to an appropriate message channel typically based on what is in the payload or header of a message.
- Routers do not alter the message like a transformer. Routers don’t remove messages from the system like a filter can.
- They simply provide forks in the road of message channels in a Spring Integration (SI) application.

<br/>


### **Content Routers**
  
- Examine incoming message content to determine destination of message.
- Uses payload type or header value to determine route.
  
  <br/>
      
### **Recipient List Routers**
  
- Incoming messages are delivered to all listed recipient channels.
- Don't examine the message.

  	
<br/>
   
<img src="{{ site.baseurl }}/imgs/Routers.PNG" style="display: block; padding: 2% 0% 2% 14%;"/>
   
<br/>
  

- Sequence to follow:
	1. Content Routers
	2. Recipient Routers
   
<br/>
	
		
{% gist bea22a04e1416cdbe282b5aa4121c25a %}