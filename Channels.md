---
layout: page
title: Channels
subtitle: How channels and messages work in Spring Integration!
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

### Channel and Message   
<img src="{{ site.baseurl }}/imgs/channels-messages.png" style="display: block; padding: 2% 0% 2% 2%;" width="90%" height="auto"/>  
  
<br/>
  
### Messages

- **Message** consists of the Header and the Payload.
- **Header** contains system information. E.g. timestamp, id, some metadata.
- **Payload** contains the data or event that's needs to be exchanged inside of SI environment.
  
  <br/>
    
### Subscribable Channels 

- Multiple subscribers **subscribe** to the channel.
- **Doesn't buffer** messages and don't have any queue.
- Messages are **delivered to all** the registered subscribers.
- Used for sending **“event”** messages.
- **Notify subscribers** that something happened and to take appropriate action.
  
  <br/>
  
### Pollable Channels

- Consumers actively poll to receive messages.
- Requires a queue with designated capacity to hold the messages.
- Point-to-point channel with only one receiver of a message in the channel.
- Used for sending “document ” messages between endpoints.
- If there are more then one subscribers, it picks 1st one.
  
  <br/>
  
### Channel - EIP
<img src="{{ site.baseurl }}/imgs/Channels.PNG" style="display: block; padding: 2% 0% 2% 14%;"/>
  
<br/>

#### You can checkout source-code from <a href="https://github.com/cignextraining/Spring-Integration-src">here</a>.
  
<br/>
  
- Sequence to follow: 
	1. Subscribable Channel
	2. Pollable Channel
	3. Direct Channel
	
<br/>
	
{% gist 59904706bf418a2efa19fd48e42d408c %}