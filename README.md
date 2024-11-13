# Welcome to your CDK JavaScript project

This is a blank project for CDK development with JavaScript.

The `cdk.json` file tells the CDK Toolkit how to execute your app. The build step is not required when using JavaScript.

## Useful commands

* `npm run test`         perform the jest unit tests
* `npx cdk deploy`       deploy this stack to your default AWS account/region
* `npx cdk diff`         compare deployed stack with current state
* `npx cdk synth`        emits the synthesized CloudFormation template

## Step by step guide

```sh
# 1. install the CDK
sudo npm install -g aws-cdk-lib

# directory name must be cdk-app/ to go with the rest of the tutorial, changing it will cause an error
mkdir cdk-app
cd cdk-app/

# initialize the application
cdk init app --language javascript
# verify it works correctly
cdk ls

# 2. bootstrap the CDK application
cdk bootstrap

# 3. (optional) synthesize as a CloudFormation template
cdk synth


# 4. deploy the CDK stack
cdk deploy

# 5. empty the s3 bucket

# 6. upload image to s3 bucket and check the dynamoDB table items

# 7. destroy the stack
cdk destroy

```
