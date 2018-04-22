---
title: Enrichers
subtitle: How enrichers work in Spring Integration!
layout: "page"
icon: fa-code
order: 7
---

- An **enricher** adds or enhances a Spring Integration (SI) message with more information or data.
- Some integration path processes may have to calculate or process some data in order to augment the message with data needed on the receiving end. Some messages may need to be augmented with data from a database. Whatever the objectives, the SI enricher is used to “enrich” the message with more information.
- Enricher can be considered as a variant of Transformer, with only difference that it cannot remove anything from a message.
- Enrichers can be classified into two type:
	1. Header Enricher
	2. Payload Enricher
	
  	
<br/>
   
<img src="{{ site.baseurl }}/imgs/Enrichers.PNG" style="display: block; padding: 2% 0% 2% 14%;"/>
   
<br/>
  

- Sequence to follow:
	1. Simple built-in Enricher
	2. Custom Enricher with Service Activator
   
<br/>
	
		
{% gist 7cf6a1d98125853aa018d8ccf0647d42 %}