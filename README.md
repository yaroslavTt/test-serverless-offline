# Prerequisites: 
1. AWS account
  - Guide: https://repost.aws/knowledge-center/create-and-activate-aws-account
2. IAM user configured, keys aquired
  - Guide: https://docs.aws.amazon.com/IAM/latest/UserGuide/getting-set-up.html#create-an-admin 
3. AWS CLI installed AND configured ( `aws configure` )
  - Guide to install: https://docs.aws.amazon.com/cli/latest/userguide/getting-started-install.html
  - Guide to configure: https://docs.aws.amazon.com/cli/latest/userguide/cli-chap-configure.html#cli-configure-quickstart-config
4. Serverless installed globally using `npm`: 
  - run: `npm install -g serverless`, restart command line 

### Complete guides can be found here(RECOMMENDED TO WATCH VIDEO):
- https://www.youtube.com/watch?v=JL_7Odb7GLM - video
  - https://blog.tomasztarnowski.com/getting-started-with-aws-lambda-and-serverless-framework#prerequisites - text guide from video

## To run this, you have 2 options: 
- serverless deploy -> this deploys your lambda to configured AWS
- serverless offline -> runs local server that imitates AWS
