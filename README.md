# ECS-EC2-Project
1. Create an AWS CodeCommit repository to store your source code.
2. Create an AWS CodeBuild project that builds your Docker container.
3. Create an AWS CodePipeline project to orchestrate the entire CI/CD pipeline.
4. Create an Amazon Elastic Container Registry (ECR) to store the Docker container images.
5. Create an Amazon Elastic Container Service (ECS) task definition that specifies how to run your       container.
6. Configure the CodePipeline to monitor the CodeCommit repository and trigger the CodeBuild project  whenever a change is detected.
7. Configure the CodePipeline to push the built Docker container image to the ECR repository.
8. Configure the CodePipeline to deploy the container to ECS whenever a change is detected.