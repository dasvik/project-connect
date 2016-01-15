# Project-Connect
Solving world's connectivity problems with algorithms and mobiles
=====

As we speak, more and more people are buying smartphones. Lot of these people reside in areas where there is no internet connectivity. What would it take to connect the unconnected of this world?

My take is that its lot easier than we think and the solution is in our minds and our pockets. With clever use of technology and these mobile phones (pretty much every phone since 2012), we can connect the unconnected. Infact I have a proof of concept that allows us to communicate with users who are well over 150m distance apart.

The Eureka moment
====
Stage 1:
It was just a brainstorming session between we founders on solving key issue for India. Ability for our app to work without internet.

It was pretty much clear that various technology were there, with its own set of pros & cons. Though they needed bit of hack to work seamlessly for our needs. We chose the most viable technology for use in our app. The POC looked great. Infact for lot of our use cases, it was perfect solution.

But for me, the most nagging problem was the limitation of distance that these technologies served and I couldn't let this go off my mind.

Stage 2:
This is where the main idea came into being. Is there a way to remove this limitation of distance or atleast make it appear as there is no limitation?

Yes, human behavior, social nature of human and algorithms can infact solve it. I did a quick re/search and found out no one has attacked this problem yet, from this angle. So I thought it was worth a try.

I even pissed my co-founder because instead of focussing on our app, I started working on some fancy idea which may not matter at all.

But I got an early crude form of the algorightm that breaks the limit/barrier of 100-150mts of communication distance that these mobiles present. Lets call it V1. 

What is in this algo?
====
While I may not delve all the details for reasons cited below, let me outline what I can. 
It has 4 main parts
* Encrypt messages (messages can be of any format)
* Recursively choose the ideal postman nearest to sender to carry the message
* Recursively choose ideal postman to nearest to recipient to deliver the message
* Between 2 & 3, choose the best path/method to send

It uses part of the phone to carry encrypted messages for the recipient. 
These messages are completely harmless as 
* they cannot be opened by anyone other the intended recipient.
* these messages can be overwritten at anytime 

What is the current status?
=========
Currently I am working on a V2. Very soon you would see V1 in action in our app. I believe V5 or V6 would be a marvel that I would personally be proud of.

Opensource yet?
====
Everyone who knows me, would vouch for the fact that I would opensource every damn thing in the world. So why not this?

In a Centralized platform like Facebook, Twitter etc. we can monitor, curb and moderate expression. While this might not sound great it has a very positive impact as well, as long as these moderations are done on terrorist activities. 

Our algorightms are designed for Point-to-Point and One-Many communication without internet over large distances. Most of the messages for most of the time might be travelling without going through a central server. Infact the messages may not reach a central server at all. This makes moderation impossible. My biggest concern is that terrorists can use it to freely spread their propaganda without moderation.

We can still have a way to moderate them through NLP. Do not distribute messages that NLP powered algos think are anti-human. But even that would be rendered useless if this is OpenSource. So the last thing I want to do is simply hand over the blue print of an algorithm that can help them succeed. Let them hire the best minds to do this for them, but I would never be the one that would help them.

But once we ensure that it's pretty safe even in wrong hands and it is pretty stable, I will not wait for a second to make it open-source.

What's in here for the connected ones?
===========
As you can imagine. This not only impacts the unconnected, but the connected ones too. Making this algorightm more robust and intelligent (v5 or V6) we can actually save lot of data cost. And I can see that pretty soon these bunch of algorithms can help us communicate across the world with minimal/no data usage at near internet speed. But even before V5 there are tons of applications which can make our lives easier. I am sure you already have guessed a few and thinking of building businesses around it. You can thank me later.


Want to help?
=======
If you have a passion to help connect the world and believe this is one way of doing it, lets join hands. Reach out to me via a pull request. Or email my associate neha.ras4u@gmail.com
