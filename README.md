


# Amazon Fargate Quick Start Guide

<a href="https://www.packtpub.com/virtualization-and-cloud/amazon-fargate-quick-start-guide?utm_source=github&utm_medium=repository&utm_campaign=9781789345018"><img src="https://d1ldz4te4covpm.cloudfront.net/sites/default/files/imagecache/ppv4_main_book_cover/B11157_MockupCover.png" alt="Amazon Fargate Quick Start Guide" height="256px" align="right"></a>

This is the code repository for [Amazon Fargate Quick Start Guide](https://www.packtpub.com/virtualization-and-cloud/amazon-fargate-quick-start-guide?utm_source=github&utm_medium=repository&utm_campaign=9781789345018), published by Packt.

**Learn how to use AWS Fargate to run containers with ease**

## What is this book about?
Amazon Fargate is new launch type for the Amazon Elastic Container Service (ECS). ECS is an AWS service for Docker container orchestration. Docker is the de facto containerization framework and has revolutionized packaging and deployment of software. The introduction of Fargate has made the ECS platform serverless.

This book covers the following exciting features: 
* Running Docker containers with a managed service
* Use Amazon ECS in Fargate launch mode
* Configure CloudWatch Logging with Fargate
* Use an IAM Role with Fargate
* Understand how ECS CLI is used with Fargate

If you feel this book is for you, get your [copy](https://www.amazon.com/dp/1789345014) today!

<a href="https://www.packtpub.com/?utm_source=github&utm_medium=banner&utm_campaign=GitHubBanner"><img src="https://raw.githubusercontent.com/PacktPublishing/GitHub/master/GitHub.png" 
alt="https://www.packtpub.com/" border="5" /></a>


## Instructions and Navigations
All of the code is organized into folders. For example, Chapter02.

The code will look like the following:
```
{
  "Version": "2012-10-17",
  "Statement": [
    {
      "Sid": "",
      "Effect": "Allow",
      "Principal": {
        "Service": "ecs-tasks.amazonaws.com"
      },
      "Action": "sts:AssumeRole"
    }
  ]
}
```

**Following is what you need for this book:**
This book is for Docker users and developers who want to learn about the Fargate platform. Typical job roles for which the book is suitable are DevOps Architect, Docker Engineer, and AWS Cloud Engineer. Prior knowledge of AWS and ECS is helpful but not mandatory.

With the following software and hardware list you can run all code files present in the book (Chapter 1-7).

### Software and Hardware List

| Chapter  | Software required                   | OS required                        |
| -------- | ------------------------------------| -----------------------------------|
| 1 to 7   | Only an AWS account.                | Windows                            |



We also provide a PDF file that has color images of the screenshots/diagrams used in this book. [Click here to download it](http://www.packtpub.com/sites/default/files/downloads/AmazonFargateQuickStartGuide_ColorImages.pdf).

### Related products
* Effective DevOps with AWS [[Packt]](https://www.packtpub.com/application-development/effective-devops-aws?utm_source=github&utm_medium=repository&utm_campaign=9781786466815) [[Amazon]](https://www.amazon.com/dp/1786466813)

* AWS Automation Cookbook [[Packt]](https://www.packtpub.com/virtualization-and-cloud/aws-automation-cookbook?utm_source=github&utm_medium=repository&utm_campaign=9781788394925) [[Amazon]](https://www.amazon.com/dp/1788394925)

## Get to Know the Author
**Deepak Vohra**
Deepak Vohra is consultant and principle a member of the NuBean software company. He is a Sun Certified Java Programmer (SCJP) and Sun Certified Web Component Developer (SCWCD) and has worked in the fields of XML, Java programming, and J2EE for over 10 years. He is the coauthor of the Apress book Pro XML Development with Java Technology. Deepak is the author of several Packt Publishing books, including Processing XML documents with Oracle JDeveloper 11g and Java EE Development with Eclipse. Deepak is also a Docker Mentor and has published four other Docker-related books.

## Other books by the authors
* [Processing XML documents with Oracle JDeveloper 11g](https://www.packtpub.com/application-development/processing-xml-documents-oracle-jdeveloper-11g?utm_source=github&utm_medium=repository&utm_campaign=9781847196668)
* [JDBC 4.0 and Oracle JDeveloper for J2EE Development](https://www.packtpub.com/application-development/jdbc-40-and-oracle-jdeveloper-j2ee-development?utm_source=github&utm_medium=repository&utm_campaign=9781847194305)
* [EJB 3.0 Database Persistence with Oracle Fusion Middleware 11g](https://www.packtpub.com/big-data-and-business-intelligence/ejb-30-database-persistence-oracle-fusion-middleware-11g?utm_source=github&utm_medium=repository&utm_campaign=9781849681568)

### Suggestions and Feedback
[Click here](https://docs.google.com/forms/d/e/1FAIpQLSdy7dATC6QmEL81FIUuymZ0Wy9vH1jHkvpY57OiMeKGqib_Ow/viewform) if you have any feedback or suggestions.
### Download a free PDF

 <i>If you have already purchased a print or Kindle version of this book, you can get a DRM-free PDF version at no cost.<br>Simply click on the link to claim your free PDF.</i>
<p align="center"> <a href="https://packt.link/free-ebook/9781789345018">https://packt.link/free-ebook/9781789345018 </a> </p>