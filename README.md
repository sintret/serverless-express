# serverless-express
Amazon AWS Lambda with serverless and expressjs



https://www.youtube.com/watch?v=71cd5XerKss

serverless create --template aws-nodejs --path my-service

serverless config credentials --provider aws --key AKIAITXILVV2S4GXTEPA  --secret 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

serverless deploy



region: us-east-1
stack: my-service-dev
api keys:
  None
endpoints:
  GET - https://mckuan68qf.execute-api.us-east-1.amazonaws.com/dev/users/create
functions:
  hello: my-service-dev-hello
Serverless: Publish service to Serverless Platform...
Service successfully published! Your service details are available at:
https://platform.serverless.com/services/sintret/my-service


serverless deploy --stage production
serverless deploy --production








===============================


C:\express\expressjs>sls deploy
Serverless: Packaging service...
Serverless: Excluding development dependencies...
Serverless: Creating Stack...
Serverless: Checking Stack create progress...
.....
Serverless: Stack create finished...
Serverless: Uploading CloudFormation file to S3...
Serverless: Uploading artifacts...
Serverless: Uploading service .zip file to S3 (694.77 KB)...
Serverless: Validating template...
Serverless: Updating Stack...
Serverless: Checking Stack update progress...
.................................
Serverless: Stack update finished...
Service Information
service: expressjs
stage: dev
region: us-east-1
stack: expressjs-dev
api keys:
  None
endpoints:
  ANY - https://tpndqxkxw2.execute-api.us-east-1.amazonaws.com/dev
  ANY - https://tpndqxkxw2.execute-api.us-east-1.amazonaws.com/dev/{proxy+}
functions:
  app: expressjs-dev-app
Serverless: Publish service to Serverless Platform...
Service successfully published! Your service details are available at:
https://platform.serverless.com/services/sintret/expressjs

C:\express\expressjs>


