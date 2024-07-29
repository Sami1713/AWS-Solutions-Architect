# AWS-Solutions-Architect

Amazon EC2:
Amazon EC2, or Amazon Elastic Compute Cloud, is a web service provided by Amazon Web Services (AWS) that allows users to rent virtual servers, called instances, on-demand. These instances can be used for a wide range of applications, such as running websites, hosting applications, or performing complex computations.

Key features of Amazon EC2 include:

Scalability: You can quickly scale your computing capacity up or down based on your needs.
Cost-Efficiency: You only pay for the compute capacity you use, with various pricing options including on-demand, reserved, and spot instances.
Flexibility: EC2 supports a variety of operating systems, instance types, and configurations, allowing you to choose the right resources for your workload.
Security: It provides features such as virtual private clouds (VPCs), security groups, and network access control lists to secure your instances.
Overall, EC2 simplifies the process of deploying and managing scalable and cost-effective computing resources.


            +----------------------+
                |      Amazon VPC       |
                |                      |
   +------------+----------------------+------------+
   |                                            |
+---+---+                                    +---+---+
|  ELB  |                                  |  EC2  |
+---+---+                                    |Instance|
   |                                        +---+---+
   |                                              |
   |         +-----------+      +-----------+  |
   |         |  EC2      |      |  EC2      |  |
   |         |Instance 1 |      |Instance 2 |  |
   |         +-----------+      +-----------+  |
   |                                        |
   |                                        |
   |     +-----------+          +----------+|
   |     |  S3       |          |  RDS     | |
   |     +-----------+          +----------+|
   |
+---+---+
|Security|
|Groups  |
+-------+

