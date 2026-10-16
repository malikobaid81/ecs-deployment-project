# ecs-deployment-project
This project demonstrates a CI/CD pipeline using AWS CodePipeline, CodeBuild, and ECS for containerized applications. The pipeline builds Docker images, pushes them to Amazon ECR, and updates ECS services via imagedefinitions.json. Rollback is handled by redeploying previous image tags from ECR, showcasing practical rollback strategies in production environments.
