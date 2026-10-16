# ecs-deployment-project
CI/CD pipeline with AWS CodePipeline, CodeBuild, and ECS. Builds Docker images, pushes to ECR, and updates ECS services via imagedefinitions.json. Rollback handled by redeploying previous image tags from ECR.
