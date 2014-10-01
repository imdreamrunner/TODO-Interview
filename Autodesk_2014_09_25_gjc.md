##Companay & Registered Project
Autodesk

* security vulnerabilities and performing static code analysis
* Research on software security vulnerabilities and best coding practices
* Develop a new Product Security Web portal with architecture of Core UI framework, Oracle DB and Web Services to perform static code analysis and collaborate secure software development lifecycle results


* Web programming & database
* Javascript and AJAX
* Knowledge of OOP
* scripting languages like Perl, Python would be plus

####I receive interview invitation by
- [x] Email from company (confirmation)
- [ ] Email from NTU system
- [x] Phone call
- [ ] SMS / Whatsapp
- [ ] Others

####The interview was conducted
- [x] On site
- [ ] Phone call
- [ ] Video Chat
- [ ] Others

####My dress code is
- [ ] [Business casual](https://www.google.com.sg/search?client=ubuntu-browser&es_sm=122&tbm=isch&q=Business+Casual&spell=1&sa=X&ei=5j0hVLeAFcu58gWwuoGQAQ&ved=0CBkQvwUoAA)
- [x] [Formal wear](https://www.google.com.sg/search?client=ubuntu-browser&es_sm=122&tbm=isch&q=Business+Casual&spell=1&sa=X&ei=5j0hVLeAFcu58gWwuoGQAQ&ved=0CBkQvwUoAA#tbm=isch&q=Formal+wear)
- [ ] [Smart casual](https://www.google.com.sg/search?q=Semi-formal&client=ubuntu-browser&es_sm=122&source=lnms&tbm=isch&sa=X&ei=rEAhVKqEOcil8AWKhYLoBA&ved=0CAgQ_AUoAQ&biw=1242&bih=599&dpr=1.1#tbm=isch&q=smart+casual+attire)
- [ ] [Informal attire]()

##Interview Flow
####Self-Introduction

1. 上来不是让做自我介绍 是让你讲做过的project.我没准备这个，我本想等他问具体project的时候随便说说的. 所以说的时候磕磕绊绊的.

2. 问会什么语言

####Q&A
**针对project require的语言，结合你会的，提问题**

* 问java有没有multiple inheritance, interface和class的区别

>Java do not have multiple inheritance, but can have multiple implementation.

>I cannot new an interface, but I can new a concrete class

>Interface only have anstract methods. Concrete class can hava additional attritubes and methods and must implement every method.

* 问我对自己写java的水平打几分（10-1）

>我说六七分吧，他说cool，其实我随便说的

* 问当用户login后，怎么用mysql验证用户名和密码是否正确
```
 SELECT * 
        FROM users
        WHERE username = $['username'] AND password = $['password']
```
>(我问密码要不要加密，要不要写完整的php语句，都说不需要)

* 问表单验证常用的technique是什么

>Regular Expression 正则表达式

* 问如何用正则表达式验证一个string是否只由数字字母组成
```
'/[\w]+/'.test(string)
```
>(我问我可不可以用js写因为我只记得js的语法，他说可以)

**project相关: 我apply的project是关于software security的，我的简历上有放我这学期做的ureca project: Vulnerability in Android Application. 也是关于security的，所以我们讨论了蛮久这个。**

HR: 我注意到你做过software security的project，你可以讲一讲吗

>Android supporting libraries have some vulnerabilities that can be exploited by hackers, like getting your personal data, contact information, password, etc. So this project is to locate these vulnerabilities and report them to Google Play. For my part, I am responsible for using machine learning algorithms to map unprotected API to user permissions. 

HR: 你们的project到现在已经locate了那些vulnerability了（不知是不是这么问的...）
>I don't know. I've just started this project and because I just knew some basics about machine learning, I am currently learning about it.

HR: No Problem... Do you know any issues of software security? Anything that you have encountered.
>（想了一会）For example, in web application, if the user input is not validated properly, the user may send a script to another user and cost problems. （前几天学node.js的时候正好看到的...）

HR: You mentioned password encryption just now, so do you know about any password encryption?
>hmm... password encryption is... to encrypt the password...

HR: Or say, do you know about public key?
>Yup I know about that. （大概讲了一下）

**中间问到的一些我说我不熟悉的东西**

HR: You know node.js?
>I am just a beginner.

HR: What kind of database technology you have use? Do you know NoSQL?
>Sorry I haven't use NoSQL.

HR: No problem. We are not coming here to test you. Just want to know more about you.


HR: Regarding form validation, do you know what is white testing and black testing?
>...No.

HR: Have you know about checksum? 
>I have heard about this term but do not know how to implement it...

看我学过computer network，还问我知道哪些protocol
>我说sliding window protocol，他大笑，他说是application layer的, tcp/ip, http, ftp什么的....

**问的其他的一些**

- 兴趣：我说就很普通的看电影看书听音乐，还喜欢跟一些奇怪的程序员讨论算法题
- 平时通过什么渠道获得最新的计算机技术信息：social network, wechat... （还可以说博客。。）
- 还问了一下CCA

**问我有什么问题问**

* 可以跟我讲一下这个projecct具体是怎样的吗
* If I join this project, or say, if i am fortunate enough to be selected, what knowledge should I catch up?
* (因为他前面问我有没有学过nosql) Will you use nosql in the project? (他说目前不会..)
* (因为他之前问我我不会) 能给我讲讲black testing和white testing的区别吗

##Summary
* 问的问题很project-specific, 问我java, js, mysql都是project requirement里的, 还讨论了很久我的ureca project
* 问题不算难吧...
* 我走的是求知好学路线，总是跟他强调我虽然不会，但是会去学

###Remarks

English is not a problem