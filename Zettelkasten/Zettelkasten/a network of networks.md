Name: a network of networks
Status: #idea
Tags: [[router]] [[a simple network]] [[a signaler at a railway station]] [[internet]] [[modem]] [[telephone infrastructure]] [[optical fiber cable]]

Description:

So far so good. But what about connecting hundreds, thousands, billions of computers? Of course a single _router_ can't scale that far, but, if you read carefully, we said that a _router_ is a computer like any other, so what keeps us from connecting two _routers_ together? Nothing, so let's do that.

![[Pasted image 20220211151300.png]]

By connecting computers to routers, then routers to routers, we are able to scale infinitely.

![[Pasted image 20220211151325.png]]

Such a network comes very close to what we call the Internet, but we're missing something. We built that network for our own purposes. There are other networks out there: your friends, your neighbors, anyone can have their own network of computers. But it's not really possible to set cables up between your house and the rest of the world, so how can you handle this? Well, there are already cables linked to your house, for example, electric power and telephone. The telephone infrastructure already connects your house with anyone in the world so it is the perfect wire we need. To connect our network to the telephone infrastructure, we need a special piece of equipment called a _modem_. This _modem_ turns the information from our network into information manageable by the telephone infrastructure and vice versa.

![[Pasted image 20220211151713.png]]

So we are connected to the telephone infrastructure. The next step is to send the messages from our network to the network we want to reach. To do that, we will connect our network to an *Internet Service Provider (ISP)*. An ISP is a company that manages some special _routers_ that are all linked together via *optical fiber cables* and can also access other ISPs' routers. So the message from our network is carried through the network of ISP networks to the destination network. The Internet consists of this whole infrastructure of networks.

![[Pasted image 20220211151829.png]]



#### References:
https://developer.mozilla.org/en-US/docs/Learn/Common_questions/How_does_the_Internet_work
https://www.youtube.com/watch?v=x3c1ih2NJEg