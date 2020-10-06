---
layout: post
title:  "AWS Solution Architect - Associate Revision Materials"
date:   2020-10-06 19:23:00 +0530
categories: ["tech"]
author: "Yichen Liu"
---
Last week I have passed AWS Solution Architect Associate level certification. So I plan to share some experience and notes that I've made in the studying progress.

***Resources***

- My own [notes](https://yichen96.github.io/AWS-overview.pdf) on AWS topics, focused on the architecting principals.
- [Whizlab](https://www.whizlabs.com) is a good resource for practicing exam questions. 
- Very comprehensive [free cheat sheet](https://digitalcloud.training/certification-training/aws-solutions-architect-associate/) broken down by AWS product.

***Experience***

I have no previous knowledge of AWS. I know many people started with Cloud Practitioner Certification and that definitely gave them an advantage in know a broad range of AWS offerings. I have used limited AWS products outside my 'business as usual'. My cloud projects includes creating web app, mini-app, making chatting bot, creating VPN & shadowsocks server because of the <small>Great Chinese Wall</small>. 

So I've been quite familiar with services such as:

- Cognito (abstract web app user authentication)
- Lambda (because I cannot be bothered to manage the CI/CD)
- KMS (encrypting my username/password for the chat bot)
- DynamoDB (noSQL database for the mini-app, because I have not finalised my schema yet)
- CloudFormation (excellent tool for deploying a VPN server, just find the template on MarketPlace)
- EC2 (install shadowsocks server)

However, the solution architect exam incorporates a much wider topic, and its questions are mostly scenario based, so the know-how-to-use is less relevant. In addition, given that I don't come from a computer science background, I have limited knowledge about networking (VPC) or database design (replication, sharding). So I think the one thing that ended up helping me passing the exam is the actual Whizlab mock exams. I've spend around 40hrs in total to go through almost 700 exam questions. <small>Sometimes I feel like a Machine Learning algo, my brain is like a blackbox, I just learn the pattern which matches questions and answers</small>.

In my opinion, the frequent topics are:

- Network (VPC, on-premise to AWS, Network Load Balancing)
- Storage classes (S3, EBS, EFS, RDS Aurora, DynamoDB)
- Cost
- Event-driven architecture

