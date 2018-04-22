---
title: Filters
subtitle: How filters work in Spring Integration!
layout: "page"
icon: fa-code
order: 4
---

- There is often a need to filter out some messages that enter a channel. Applications may only want to get messages formatted in a certain way (XML or JSON). Applications may only be interested in certain types of data. 
- **Filters** are endpoints that sits between channels and accept or reject messages from one channel to be sent to the next channel. 
- **Selection** occurs based on message's payload or metadata.
- **Discard Channel** is used to route the rejected messages.
- **Expression Filter** uses evaluated SpEL against messages to select messages.
- **Xpath Filter** uses Xpath expression against XML Payload to select messages.
- **XML Validating Filter** uses XML Schema to validate XML Payload messages.
- **Custom Filter** can be implemented using MessageSelector interface.

<br>

- Sequence to follow:
	1. Message Selector - File name based
	2. Xpath Filter
	3. XML Validation Filter
   
<br/>
	
### Filters - Message Selector - File	
   
<br/>
		
{% gist a462e58f46ffefe691ea902179256d90 %}
   
<br/>
	
### Filters - XML
   
<br/>
	
{% gist 776b82111ba2d7ff2f40c2603fa57054 %}