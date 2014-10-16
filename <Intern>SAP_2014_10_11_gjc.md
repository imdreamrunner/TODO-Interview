##Companay & Registered Project
SAP

CityApp vision: Customer solution built on Mobiliser platform, a state-of-art Service Oriented Architecture based on OSGi which allows true dynamic real-time integration and rapid application development.

Requirement: Basic skills in Java programming. Keen interest in development with OSGi and SpringDM

####I receive interview invitation by
- [x] Email from company
- [ ] Email from NTU system
- [ ] Phone call
- [ ] SMS / Whatsapp
- [ ] Others

####The interview was conducted
- [x] On site
- [ ] Phone call
- [ ] Video Chat
- [ ] Others

####My dress code is
- [x] [Business casual](https://www.google.com.sg/search?client=ubuntu-browser&es_sm=122&tbm=isch&q=Business+Casual&spell=1&sa=X&ei=5j0hVLeAFcu58gWwuoGQAQ&ved=0CBkQvwUoAA)
- [ ] [Formal wear](https://www.google.com.sg/search?client=ubuntu-browser&es_sm=122&tbm=isch&q=Business+Casual&spell=1&sa=X&ei=5j0hVLeAFcu58gWwuoGQAQ&ved=0CBkQvwUoAA#tbm=isch&q=Formal+wear)
- [ ] [Smart casual](https://www.google.com.sg/search?q=Semi-formal&client=ubuntu-browser&es_sm=122&source=lnms&tbm=isch&sa=X&ei=rEAhVKqEOcil8AWKhYLoBA&ved=0CAgQ_AUoAQ&biw=1242&bih=599&dpr=1.1#tbm=isch&q=smart+casual+attire)
- [ ] [Informal attire]()

##Interview Flow
####Self-Introduction
(SAP的两个面试官，其中一个是project leader，另一个应该也是类似leader的，反正不是发邮件给我的那个人。嗯，开始先给我几分钟让我准备自我介绍并且介绍做过的project)
 1. NTU, computer science, year 3
 2. Interest in OSGi and modular programming
 3. Have experience in Java Programming. Course Project for CZ2006 used Java for backend.
 4. Keen to learn more, improve skills and make value.

####Q&A
* What do you know about SAP?

> SAP stands for system, application and product. Customer Solution. Business product. Bring customers closer to enterprises.(面试前看了下wiki, rephrase了一下)

* Our project focused on backend programming. What do you know about front-end, backend and what is their differences?

> (Please google it... 我不是很清楚其实)

* You said you know java, python, c, etc. There are bacially two types, one is scripting language, so what is the other type?

> (我忘了... )structural? Sorry I forget. 

* Compiled language. What's the difference between them?

> Scripting languages are intepreted in run time. Complied languages are translated to machine code before exection so is faster.

* You said you have experience in Java programming and backend programming. Pick one of your projects and briefly discuss about the architecture you designed, the major class diagrams or whatever. 

> (这个讲了很久很久... 我就讲eProctor, 说用了play framework, 画了play的MVC以及每个layer的functionality和message passing. 他估计觉得我讲的太粗略了, 就让我具体讲我是怎么persist data的, controller怎么做, model怎么做, 我就说play用了ebean的ORM, 所以在controller直接call Model的api就可以persist data. 然后他又让我画整个project的directory hierarchy tree, 然后就结束了...) (这一块是挺乱的, 一是play的MVC跟传统的不一样, 他可能觉得我讲的跟他知道的有出入; 二是我对play的architecture了解也不是很清楚, 描述得也不是很清楚)

* How do you think you can further improve this project? Like your design, your architecture, whatever?

> Controllers in Play only have static methods, which means server runs in single thread. Thus server may fail to handel request responsively from a large number of clients.

* You mentioned single thread just now. So you have experience in multithread programming?

> (讲了MDP, rpi, 提到我用multithread handle 3 IO interfaces.)(这个我们也讨论了很久, 他以为我是用multithread写了asychronous IO, 其实我只是开了三个thread读, 然后写==)

* (后来他知道我并不是asychronous IO, 就问我如何用multithread implement asychronous IO)

> (呜呜, 我不知道他想要的asychronous IO是怎么样子, 磨了好久终于说出他想要的答案, 其实我觉得这个是要看你program logic的) One thread keeps reading, after read, new another thread for processing. 

* Tell me what you know about data structures. For example, we have list, linkedlist, map, hashmap, what is the difference between linkedlist and hashmap? In what circustances should you use each one of them?

> (这是个值得讨论的问题, 我们也讨论了很久... Please google it...)

* (interview快结束了) One more question, which is also a simple one: a=3; b=a++; c=++a; what are the values of a, b and c after execution?

> b = 3; a = c = 5;

####Coding/Programming Test
None

####Questions for the interviewers
 1. What do you think is the diffculty level of the quesitions you asked just now? (因为我回答不出来蛮受打击的)
    - Not tough one. I think your academic knowledge is quite strong. Just lack of experience. You will be familar with them through project experiences. One more advice from me is that if you come to our project, you may experience a knowledge gap for the first month. It's diffenent from your academic things. So be prepared. (他这样说是不是表示我有希望？？？)
 2. So what do you think I should catch up with before IA program if I am selected? 
    - It is not what you need to catch up. Just that you should be prepared to learn fast and go through the knowledge gap for the first month. It may be tough.

##Summary
Q&A are all related to projects and programming knowledge.

####Improvement/Suggestions
Algorithm and data structure is the basis.
Make sure you understand the architecture and design of one of you projects.
Be familar with Java Collection Framework

