---
layout: post
title:  "Open Claw is taking over..."
author: trevor
categories: [ AI, Tech, OpenClaw ]
tags: [red, yellow]
image: assets/images/2026-04/open-claw.png
description: "Open Claw is now dominating the AI race. And its a very different kind of race."
featured: true
---

#### Open Claw Scares AI Companies

Last month NVidia gave a curious presentation about Open Claw and its new systems to work with it.

[Youtube - NVidias Jenson Hwang launches NemoClaw to the OpenClaw community](https://www.youtube.com/watch?v=kRmZ5zmMS2o)

If you watch this video and dont realize how scared NVidia are of OpenClaw then you are missing the importance of this moment. 

The reality is. OpenClaw is going to dominate AI development and by the end of 2026, if you are not using OpenClaw then you are not in tech. 

The next step is that OpenClaw will become a commodity tool for general uses.

If you are interested in trying out OpenClaw you can find it here:

[Github - Open Claw  Clawhub](https://github.com/openclaw/clawhub)

Word of warning. I would recommend the following for first time users:
- Create separate emails and accounts if you intend to use OpenClaw with emails and services. DO NOT use your personal accounts.
- Run OpenClaw in a VM and DO NOT let it have access to your local files and files system.
- Run OpenClaw using a small amount of test services first. It can become hard to manage if there are many.

When developing solutions with OpenClaw DO NOT expect accuracy. This is still an AI based model system that has at-best 70-80% accuracy with any data sets. Use it for the appropriately matching use cases.

Google is already attempting to compete with OpenClaw (remember this is free) and its trying to limit what OpenClaw can access:

[Gadgets Now - Google bans OpenClas users on its AI coding tool Antigravity](https://timesofindia.indiatimes.com/technology/tech-news/google-bans-openclaw-users-on-its-ai-coding-tool-antigravity-says-weve-been-seeing-a-massive-increase-in-malicious-usage/articleshow/128742339.cms)

This is in response to malicious use, but there are deeper ramifications.

China is concerned now with OpenClaw as well:

[South China Morning Post - Inside OpenClaw mania in China](https://www.scmp.com/tech/tech-trends/article/3346513/inside-openclaw-mania-gripping-china-security-fears-surge-alongside-enthusiasm)

This tool will be extremely hard to lock down in a totalitarian state that fears its citizens becoming empowered which is potentially a huge problem for the CCP.

Companies and Governments all over the world are showing deep concern over OpenClaw because having this sort of power in the hands of the general user removes many of the controls these two groups had spent the last three decades locking-up the internet.

#### How OpenClaw Impacts you.

Teachers and any form of training people shall be heavily impacted by OpenClaw.

[trainingsites.io - The Real Reason Teachers Should Fear OpenClaw](https://trainingsites.io/tutorial/the-real-reason-teachers-should-fear-openclaw/)

In healthcare OpenClaw is already in-use:

[healthcaredigital - How Will OpenClaw Impact Healthcare Technology in 2026?](https://www.healthcare.digital/single-post/how-will-openclaw-impact-healthcare-technology-in-2026)

A 68 yr old brewed a beer... using OpenClaw:

[lobsterlager](https://www.lobsterlager.com/)

And here are many things people are doing with OpenClaw:

[OpenClaw AI - What People are building](https://openclaw.ai/showcase)

#### Beware the hype.

Ok. After reading all of the above you can be forgiven for thinking "I have to jump on the OpenClaw bandwagon or I'll be left behind!".

In some ways you would be right, but in other ways you may be signing your company up for self destruction. In this section we will discuss the hidden dangers of this tech trend and why there are dark and deep ramifications of what is happening and what has been happening in the AI investment and development space in its entirety.

##### The Gotchas

OpenClaw is fundamentally (at its bare bones level) a set of scripts that can be tailored to drive AI based execution and operation of those scripts and the outputs they create. This is not really all that new. AI Agents have been around for quite a long time:

[IBM - The evolution of AI agents](https://www.ibm.com/think/topics/evolution-of-ai-agents)

What is new, is to use AI LLMs as the controllers for those script operations. OpenClaw lets you use ChatGPT or Claude or whatever model you want to control how specific plugins and services operate. In fact, it is beneficial to use more tailored LLMs to work with specific services - ie use a Health Trained LLM for managing how Doctors integrate their patients scheduling into OpenClaw and provide notifications to those patients, write up documentation for auditing and assign script for each patient based on results.

It is easy to see, how a Doctors office can become improved greatly in terms of efficiency using such tools. And importantly, this isnt about replacing the jobs of the office workers, this is giving them more free time to do the more human related work that is needed and thus removing some of their work burdens to become more effective in the workplace - sounds great, right?

Yes, it sounds great. But this is not what happens. You see, all of this assumes the OpenClaw doesnt make a mistake or make decisions without the authority of the Doctors or Managers involved and completely destroy the database:

[Medium - My AI Agent Ordered 500 Pizzas, Deleted a Database, and Emailed my Boss "I Quit"](https://medium.com/@management_33652/my-ai-agent-ordered-500-pizzas-deleted-a-database-and-emailed-my-boss-i-quit-9dad8352adea)

While this is an annecdotal example, the actions are real. And the security and cost implications are real. 

What would the cost to a Health Clinic if they suddenly lost _all_ of their records and OpenClaw ordered all of the wrong drug scripts? This is a serious problem that people, tech people specifically, are not taking seriously. Companies and Tech fanatics of OpenClaw are implementing these systems right now.

The question isnt _if_ OpenClaw does these things, it is _when_ they do these things. You see, in all Nerual Network based systems there is only a maximum level of accuracy any NN can get to, even with the best possible training and data - and this is around 78%. 

##### What is a Neural Network

I want to provide some high level description of the technologies involved in AI which will help understand the serious issues I am about to discuss.

A Neural Network is essentially composed of data structures called tensors. We can consider a tensor to be a long list of numbers that defines some specific attribute the NN is being trained for.

When we train a NN these numbers are adjusted slightly to better represent the result for an attribute. As a real example, it might be a Language Model (LLM) where text is being converted into a tensor to be matched and responded to. A tensor might represent a whole paragraph of text (sometimes with context built in) which is trained from Hamlet. When a person asks about a passage of text, it traverses the network in list order to get the "closest" match of what was asked. The higher the numerical match of each number in the list for the paragraph the stronger the result and thus the higher the likelihood of selection of the Hamlet text as a response.

However, these numbers in the tensors are often "weighted" which means they are adjusted as they are trained. This allows the same tensors to be used for various types of matches and sentences. These tensors are often built to make "tokens" and so you will see LLMs and models in general have a "tokens per second" as a performance metric. This is what that measures, how many matches of tensors a model can do per second on a specific set of hardware.

Ok. But what if it doesnt match? Well, this is where it gets interesting. Nearly all NN based systems use a level of "random noise" on the tensors to ensure that there is a certain level of "matching" that can occur. The main problem with doing this is you will then get matches that make no sense (often referred to hallucinations). These matches are expected because if you do not have this feature, the model will match nothing because the request will always need to be exact.

Thus the noise that needs to be added, must be added or it wont work. This noise can be reduced the more training data is used, or referential systems are ran together with NNs or input is restricted so that specific matching becomes more direct. However, the larger the dataset and the complexity the NN is trying to solve the larger the noise needs to be. This is why that 30% innaccuracy will never disappear and you will never see 100% accurate LLMs or NN based models. 

[Youtube - AI and Stochastic Parrots](https://www.youtube.com/watch?v=jAHRbFetqII)

AI (in its current form) is flawed at the mathematical level not at the implementation or use level. 

This is a discussion on how the underlying systems of LMMs work and how most of the models in use today work within their core. There are input and output systems that massage queries and output data in case of removing bad results, or bad inputs so there are instances where it can "seem" that models have much more accuracy that they actually do.

##### Impacts for OpenClaw

One of the great problems of current AI NN based systems is that it is entering a "data degradation" phase. Where many of the large model makers (like NVidia and Google and Facebook) have literally run out of consumable training data for the models to be trained "better". 

Because of this, most of these companies are now creating data from other models. Now, remember that 30% problem? If you start feeding back in something that has a 30% failure rate into a system that has a 30% failure rate, this will create a never ending cycle of data degradation - you cant get better, only worse.

And if people examine some of the early ChatGPT 4 vs current, you will find in many cases it _is_ worse. In the AI business this is called "Model Collapse" and its a known and well researched problem that has limited solutions.

[IBM - What is model collapse](https://www.ibm.com/think/topics/model-collapse)

Considering this is a problem in current AI systems the ramifications for an Open Sourced system like OpenClaw that utilizes Open Sourced models from [Hugging Face](https://huggingface.co/) you have a recipe for a highly accelerated model collapse and data degradation process.

OpenClaw running automated agent sessions for millions of people and companies all over the world 24/7 can really accelerate the generation of data. On an extremely large scale. The results will not be in five years or two years, we will see some of these problems by the end of 2026.

##### Investments so large the World Economy is at risk

The AI investments at this current time are at such a large level with such long lead times (years to build large AI training centers and AI data centers) they are at extreme risk. Coupled with tech companies having to partner or buy huge energy systems because these centers consume so much energy there is a serious issue in how economically the world has put all its eggs in the AI basket, and OpenClaw is going to make _all_ of that business redundant.

Why redundant? Watch the NVidia video - Huang is scared. NVidia knows its multi-billion dollar investments are all at risk now. This video is not for you the user, it is purely for the investors to say - "Hey, look we are buds with OpenClaw.. we have better tools.. people will use us!"... no they wont. Free vs Paid, Expensive Cloud services vs Local machines in office? We know what people will choose. NVidia is out of the picture and they know it.

Heres an example of someone doing a deep dive into installing and using OpenClaw. Its a good and personal experience which explains the impact this will have:

[AI Maker - Is OpenClaw worth the hype?](https://aimaker.substack.com/p/openclaw-review-setup-guide)

RedHat and others are getting involved as well:

[techcrunch.com - Redhats OpenClaw maintainer just made enterprise Claw deployments a lot safer](https://techcrunch.com/2026/04/28/red-hats-openclaw-maintainer-just-made-enterprise-claw-deployments-a-lot-safer/)

I'll explain why NVidia and Google and other companies are at risk.

AI agents are no longer controlled by these companies. And more importantly, their models are no longer needed in the cloud - they can all be run locally and at whatever scale the local business or person wants.

The funding for nearly all of Google and NVidia comes from enterprise services. And these services will no longer be needed by businesses. They run their own OpenClaw agent and get everything they need without the NVidia agent or service.

An example: Lets consider an OpenClaw agent called Fred that has been setup as a search tool on the internet. Fred has been given specific website search systems to do their searches in, collate and rank the results and provide feedback on what it finds. This is what Google Search currently does, with advertising to make money. Fred, is installed on a mac minim with a local llama model and some other plugins. Fred is _much_ more accurate because Fred's owner is very particular about what search services they use and has far greater success with his searches as well as his results.

This is a simple example. But right away, it is clear, this is a _huge_ loss for Google revenue (advertising). Fred doesnt need it. Consider this problem on scale, as UI systems for OpenClaw improve and end up "common" for the average user - this will be the case in a few months time. 

The ramifications for businesses everywhere that rely on selling a service are substantial. 

There are potential ways for a business to utilize this tool, but it means changing what your business does and what it sells. 

#### OpenClaw for Businesses

Most businesses are looking to leverage this giant wave of uptake of OpenClaw. There are clear ways to leverage the tool from a business perspective:
1. Ensure your business model is not selling an agent or service. These will be supplanted.
2. Move to a data sales and data integration model for you business. OpenClaw uses data and accounts to be able to do its work. If you make your "service" a data api or data system then you can be a great provider for OpenClaw agents and thus make profits from this.
3. Build your own OpenClaw agents (in safe VMs) and trial how you can develop plugins for your own business that you can sell or provide to your customers. Doing this ensures you have some control over OpenClaw interactions with your data systems.
4. Ignore it alltogether - yes, this is a valid strategy. In fact, I think this is the correct strategy if you want to survive this AI storm. Build important customer oriented systems. Build strong data systems with functional and referential capabilities in a traditional form (not AI). After this mess, you will be the winner. 

If a business engages in developing OpenClaw based systems it needs to spend time on security and knowledge and skills for managing the agent and its IO systems. Logging, notifications, and limits are all requirements - not suggestions.


