# AWS Solutions Architect Quiz 6 🎓 (IAM)

The AWS solutions architect certification shows that you can use AWS services to solve software engineering problems and understand core best practices of the industry. In this article, I will quiz you on one of the sections from the material required for the exam: IAM.

![](https://cdn-images-1.medium.com/max/2800/1*p4U3M2JgXaMfaKLlFRAIYA.png)

I will now briefly state some key facts about this AWS service, and then provide some example questions for the exam.

N.B: The following information on its own will not be enough to answer the questions.

### IAM

The Identity and Access Management (IAM) service enables authorisation and authentication on AWS resources.

**Authentication** — *are you who you claim to be?*

**Authorisation** — *are you allowed to do what you want to do?*

![IAM Service Diagram — [Source](https://docs.aws.amazon.com/IAM/latest/UserGuide/intro-structure.html)](https://cdn-images-1.medium.com/max/2000/1*Szzt_F9MpGtxz85lhBricA.png)*

IAM Service Diagram — [Source](https://docs.aws.amazon.com/IAM/latest/UserGuide/intro-structure.html)*

It is also useful to know that:

* The top level user is called a ***principal*** and is allowed to interact with AWS resources — Root user, IAM user, and Roles are principles.

* **A Root user** is created when the AWS account is created and has console and programmatic access.

* **IAM users + groups** — persistent identities that can be controlled through IAM. IAM user must have the rights to assume the role.

* **Roles —** allow people or processes the ability to operate temporarily with a different identity. Assume a role by being granted a temporary security token.

* A **policy** is a JSON document that defines one or more permissions to interact with AWS resources. Each permission includes: Effect, Action and Resource.

* You can write your own policies or use one of the [managed policies](https://docs.aws.amazon.com/IAM/latest/UserGuide/access_policies_managed-vs-inline.html) provided by AWS.

* IAM enables rotation by allowing two active access keys.

## Quiz 🎓



The quiz can also be accessed in full size [here](https://docs.google.com/forms/d/e/1FAIpQLSe1ob9pRCxTwpzjJaQi0vYMqHHonJ8YVOvvq_4VQfm6Hqa0Pg/viewform?usp=sf_link). These questions were sourced from multiple locations (mainly the [certification sample test](https://d1.awsstatic.com/training-and-certification/docs-sa-assoc/AWS-Certified-Solutions-Architect-Associate_Sample-Questions_v4.0_FINAL.pdf)) over a long period of time.

## Thanks For Reading

I hope you have enjoyed this article. If you like the style, check out [T3chFlicks.org](https://t3chflicks.org/Projects/aws-solutions-architect-quiz/) for more tech focused educational content ([YouTube](https://www.youtube.com/channel/UC0eSD-tdiJMI5GQTkMmZ-6w), [Instagram](https://www.instagram.com/t3chflicks/), [Facebook](https://www.facebook.com/t3chflicks), [Twitter](https://twitter.com/t3chflicks)).

We hope to cover the rest of the topics with similar articles very soon ⭐

## Quiz 1
[**AWS Solutions Architect Quiz 🎓(VPC, Load balancing, CloudWatch Autoscaling)
**T*he AWS solutions architect certification shows that you can use AWS services to solve software engineering problems…m*edium.com](https://medium.com/@t3chflicks/aws-solutions-architect-quiz-vpc-load-balancing-cloudwatch-autoscaling-aa3edee34d16)

## Quiz 2
[**AWS Solutions Architect Quiz 2 🎓 (S3, EC2, EBS)
**T*he AWS solutions architect certification shows that you can use AWS services to solve software engineering problems…m*edium.com](https://medium.com/@t3chflicks/aws-solutions-architect-quiz-2-s3-ec2-ebs-173d40515dd)

## Quiz 3
[**AWS Solutions Architect Quiz 3 🎓 (CloudFront, ElastiCache)
**T*he AWS solutions architect certification shows that you can use AWS services to solve software engineering problems…m*edium.com](https://medium.com/@t3chflicks/aws-solutions-architect-quiz-3-cloudfront-elasticache-f77fd08949e8)

## Quiz 4
[**AWS Solutions Architect Quiz 4🎓 (SQS, SNS)
*** The AWS solutions architect certification shows that you can use AWS services to solve software engineering problems…m*edium.com](https://medium.com/@t3chflicks/aws-solutions-architect-quiz-4-sqs-sns-b0b4390d5475)

## Quiz 5
[**AWS Solutions Architect Quiz 5 🎓 (DNS and Route53)
**T*he AWS solutions architect certification shows that you can use AWS services to solve software engineering problems…t*3chflicks.medium.com](https://t3chflicks.medium.com/aws-solutions-architect-quiz-5-dns-and-route53-1ca28cf9c5a1)