---
ID: 113
post_title: 'Cloud Computing Platforms &#8211; My Thoughts'
author: cauchyabel
date: 2016-03-19
---
# Cloud Computing Platforms: My Thoughts

In my last blogs I have discussed about how to use Microsoft Azure and Amazon Web Services to deploy your own Java web application. In this blog, we will first look into Google Cloud Platform and then I will share my thoughts on different cloud computing platforms I have used so far. 

## Google Cloud Platform - Not Even Good 
Yes, Google Platform is not as good as other services provided by Google. Let's take Java Web Application deployment for example. To deploy an application on Google Platform, we need to create a new project for this application. Then for Java, we need to have Maven framework and Google Java SDK ready so that our application could be deployed onto the platform. The reason behind this mechanism of deployment is that the whole Google Cloud Platform is built on the Google App Engine, GAE (I assume a lot of programmers know this). The minimum managed unit on Google Cloud Platform is 'project'. In a 'project', you are able to create applications, virtual machines. Before you start, you will create a project, and based on the project, applications and virtual machines are created. If user switches to another project, then the virtual machine is not visible until the user switch back. Pros: Google offers pretty good starting offer with a credit of $300 USD, which allows a new user to do a lot of stuff at the beginning. The extension of each project is very flexible. It is a platform more friendly to project based work. Cons: Comparing with the experience to AWS or Azure, Google Cloud Platform is not as friendly as the other two. The deployment of web app is not as simple and fast. The creation of project is annoying while it is a must before you can start anything. 

## Amazon Web Services - Strong and Stable 
As mentioned in my previous blogs, AWS was one of the earliest cloud platform. Even so, AWS have always been providing good service and presenting stable products to all users. EC2 instance, as their flagship product, is very easy to create and use. The security key pair and security groups guarantee that each user will be able to create a safe environment that the user needs. Elastic Beanstalk, as their later product on PaaS, provides many deployment choice for users. By simplifying the whole deployment to one button, it saves programmer a lot of time for better code. Also, their user interface is very friendly with all their products laid out on the console main page, while the user won't feel overwhelmed because they are all well introduced in simple words. AWS provides a very wide product line for cloud computing, Storage, Database, IOT and even game deployment. AWS's stable performance has been recognized by a lot of users too. Pros: Very good user experience with a lot of helping documentation available. One year of free experience with a lot of choices available is attractive. More discount for college user is available. Stable performance proved by a lot of online service providers, including NETFLIX, Airbnb, Yelp, Adobe and etc. Very wide choice of EC2 instance allows an outstanding IaaS service. EC2 access is secured that user only had one chance to download key pair for instance password. Cons: My Elastic Beanstalk has been broken for a while for the Glassfish server, however, it might be a Glassfish issue. 

## Microsoft Azure - Integration and Flexible 
I would say that I had a good experience with deploying on Azure platform. With the solution category provided by Microsoft, a user could easily find what is that he really needs. The deployment of a Java web app is simple and easy with the help of basic FTP access. Azure provides good support on .NET, Java, PHP and Python. A web application instance can also change its application type after it created, which made it very simple for programmer to switch between different application type. For Java web app, the whole deployment is as simple as uploading just a war file. Also, user can choose to deploy more than one web application under the same Web App instance. The strong integration with Microsoft Visual Studio 2013 or higher is also a highlight. A user can easily deploy its .NET application through VS to Azure platform. This feature makes Azure standing out of the other two platforms, using Microsoft's way. Pros: Very simple deployment for web application. A lot of choice on market place are available to users with different needs. The integration with VS is very attractive to .NET developers. They also have good Dreamspark promotion to students too. Cons: The IaaS service is not as strong as their PaaS service. However, it is not Microsoft's expertise.        