# Clouds-Are-Us: Proof-of-Concept Cloud Architecture

This repository contains the coursework and supporting files for my Cloud Services assignment from CCT College Dublin, where I implemented a proof-of-concept cloud architecture for a fictional company called **Clouds-Are-Us**.

---

## Project Overview

Clouds-Are-Us is a start-up specializing in digital technology solutions, agile software development, and cloud consulting services. This project involved designing and deploying a scalable, highly available cloud infrastructure on AWS that includes:

- Static website hosting using Amazon S3  
- A group of Linux web servers behind an Application Load Balancer (ALB)  
- Auto-Scaling Group (ASG) integrated with the ALB for fault tolerance and load distribution  

---


- **Report.pdf** — The main research report describing the architecture design, implementation, and analysis.  
- **script.sh** — Contains the Linux startup script used for web server provisioning.  
- **screenshots/** — Visual evidence of the static website and load balancer configurations.  

---

## Key Features & Technologies

- AWS S3 for static website hosting with secure, durable, and scalable object storage  
- AWS EC2 Linux instances configured via user data scripts  
- Application Load Balancer (ALB) distributing traffic across multiple web servers  
- Auto-Scaling Group (ASG) ensuring high availability and scalability  
- Infrastructure deployed in a custom AWS VPC for enhanced network management  

---

## How to Use

This repository is for reference and demonstration purposes. The infrastructure was deployed using the AWS Academy environment and can be reproduced by following the report instructions.

---

## Acknowledgements

Assignment completed as part of the BSc Computing & IT programme at CCT College Dublin. Instructor: Michael Weiss.

---

## License

This project is released under the MIT License.

