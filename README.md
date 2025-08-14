# AWS-Jenkins-EC2-Demo

This project demonstrates my hands-on experience with AWS EC2 by deploying and configuring Jenkins, an automation server used for Continuous Integration and Continuous Delivery (CI/CD).

I began by launching an EC2 instance in AWS, selecting Amazon Linux 2 as the operating system, and configuring an appropriate instance type. I created and applied a custom security group that allowed inbound access on ports 22 (SSH) and 8080 (Jenkins web interface). Key pairs were used to ensure secure access to the instance.

After connecting to the instance via SSH, I installed Java (a prerequisite for Jenkins) and added the Jenkins repository to the system. Using yum, I installed Jenkins, enabled the service, and confirmed it was running. I then opened port 8080 in the security group, allowing web access to the Jenkins interface using the instance’s public IP.

Once Jenkins was running, I accessed it via a web browser and completed the initial setup using the admin password generated on the server. I created multiple test jobs (test, test2, test3) to simulate build pipelines. These jobs demonstrated how Jenkins can automate tasks such as code builds, testing, and deployment.

The AWS EC2 dashboard shows the running instance, confirming the server environment is active. The Jenkins dashboard screenshot provides evidence of the configured jobs, proving successful deployment and configuration.

Through this project, I practiced key AWS concepts such as EC2 provisioning, security group configuration, and key pair authentication, as well as DevOps skills including Jenkins installation, job creation, and server management. This hands-on work strengthened my ability to deploy and manage applications on AWS while integrating essential CI/CD tools.
