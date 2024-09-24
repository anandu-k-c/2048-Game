
 # Deployed 2048 Game App on AWS Elastic Kubernetes Service (EKS) with Ingress and AWS Fargate for Serverless Compute

In this project, the 2048 game app is containerized and deployed on Amazon Elastic Kubernetes Service (EKS), leveraging AWS Fargate for serverless compute. This setup eliminates the need to manage underlying servers, providing a fully managed, scalable environment for the application.

Key Features of the Deployment:

1) Serverless Compute with AWS Fargate: AWS Fargate is used as the compute engine, enabling serverless deployment of the 2048 game app. By using Fargate, there is no need to manage EC2 instances, as Kubernetes pods are automatically run on a serverless infrastructure, ensuring auto-scaling and cost-efficiency based on demand.

2) Kubernetes Ingress: Kubernetes Ingress is used to expose the 2048 game application to external users. Ingress manages HTTP routing and SSL termination, allowing seamless access to the application through defined routing rules.
   
3) Scalability and High Availability: With AWS EKS and Fargate, the 2048 game app benefits from high availability and automatic scaling. Fargate automatically provisions and de-provisions resources based on traffic, ensuring optimal performance without manual intervention.
 
4) Security: AWS IAM roles and security groups are configured to provide fine-grained access control and secure interaction between services within the EKS cluster.


This project demonstrates the power of AWS Fargate and Kubernetes for deploying scalable, serverless applications while maintaining flexibility and high availability for the end users.
# Sample ScreenShot
 <img width="1440" alt="1" src="https://github.com/user-attachments/assets/8068b40b-465d-4ed7-a2ae-5cd5f2e1a0e7">
<img width="1440" alt="2" src="https://github.com/user-attachments/assets/dcbf8340-e3a9-4ec2-be94-09ce02bd90b7">
<img width="1440" alt="3" src="https://github.com/user-attachments/assets/8d82132f-e5be-4671-ae40-01278bfafee2">
<img width="1440" alt="4" src="https://github.com/user-attachments/assets/76f95f87-2595-4a7f-a911-3c6b6f041c57">
<img width="1440" alt="5" src="https://github.com/user-attachments/assets/0e6b6df9-ba78-4b59-9659-30eb568f18a9">
<img width="1440" alt="6" src="https://github.com/user-attachments/assets/fccaebb7-1978-4235-a9b4-2aa61d4fdf57">
<img width="1440" alt="7" src="https://github.com/user-attachments/assets/7a8d8855-7e26-4079-b1ef-a37eac29553f">
<img width="1440" alt="8" src="https://github.com/user-attachments/assets/b4f15974-378d-4e0c-b455-029a04d7e8e7">
<img width="1440" alt="9" src="https://github.com/user-attachments/assets/c1f82e39-bb4d-4a3c-8d33-eef4f7ace317">
