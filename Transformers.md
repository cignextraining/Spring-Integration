---
title: Transformers
subtitle: How transformers work in Spring Integration!
layout: "page"
icon: fa-code
order: 5
---

- **Transformers** are the endpoints that converts the payload or structure of the message into a modified message with different structure.
	- e.g.: Converts XML payload into a JSON Payload message.
- In the world of integration, data providers and data consumers don’t always speak the same language. So transformers provide SI applications the means to convert messages between formats to facilitate non-homogeneous message exchange.
- Allows provider and consumer of the information to communicate via SI without having to settle on common format.
  
  	
<br/>
   
<img src="{{ site.baseurl }}/imgs/Transformers.PNG" style="display: block; padding: 2% 0% 2% 2%;"/>
   
<br/>
  
#### You can checkout source-code from <a href="https://github.com/cignextraining/Spring-Integration-src" target="_blank">here</a>.
  
<br/>
  
- Sequence to follow:
	1. String reversal Transformer
	2. PigLatin Customer Transformer
	3. XML Transformer
   
<br/>
	
### Simple Transformer - String Reversal
   
<br/>
		
{% gist af1e2493da81fe68d44a2d9984bcb6cc %}
   
<br/>
	
### XML Transformer - Unmarshalling Transformer
   
<br/>
		
{% gist 86378344e9d43db01d30b1f69149ae9b %}