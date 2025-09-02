Created a codebuild project in aws code pipeline console,builded the docker image which is written in java,and finally pushed the image to amazon ECR By making use of the instructions written in buildspec.yaml.
as shown in figure 272,273.

After that created a ECS Cluster with required task definition with required configuration as shown in the screenshot 274,275,276,277.

Then created a code pipeline by making use of the code build stage and deploying the image to the above previously clreated ecs cluster of fargate type  as shown in the screen shot 266,270,271 and we can access the application through the ip address of task in ecs cluster.
