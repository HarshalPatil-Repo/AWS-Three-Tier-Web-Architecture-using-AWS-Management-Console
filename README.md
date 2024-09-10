# AWS-Three-Tier-Web-Architecture-using-AWS-Management-Console

![image](https://github.com/user-attachments/assets/31e05999-6825-4515-b694-ec36b23c0fde)

In this architecture, a public-facing Application Load Balancer forwards client traffic to our web tier EC2 instances. The web tier is running Nginx webservers that are configured to serve a React.js website and redirects our API calls to the application tier’s internal facing load balancer. The internal facing load balancer then forwards that traffic to the application tier, which is written in Node.js. The application tier manipulates data in an Aurora MySQL multi-AZ database and returns it to our web tier. Load balancing, health checks and autoscaling groups are created at each layer to maintain the availability of this architecture.

## How to

Download file `AWS Three Tier Web Architecuture - Step by Step.pdf` and refer procedure to create Three Tier, Highly Available and Fault Tolerant Web Architecture by using AWS Management Console



