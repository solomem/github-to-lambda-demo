# github-to-lambda-demo

CodeBuild is used to deploy this lambda function.
We need: 
1. Codebuild
2. IAM role 

The CodeBuild uses the lambda as the source and webhook as the event trigger for the pipeline to be auto triggered.
