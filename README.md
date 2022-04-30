# serverless-node.js-typescript-tsoa-mysql
**Sample serverless project using node.js, typescript, tsoa and mysql **


## Getting start    
 - clone repo  
 - npm install 
 - npm run serverless-start

## Technologies uses:
- Node.js / Express  
- Typescript  
- TSOA 
- MySQL
- Serverless

## Deveployment to AWS Lambda
** Prerequestics **
- AWS Account
- AWS access key and secret key

## AWS - Config Credentials
Run this command to set up your serverless credentials on your local machine.
> serverless config credentials \
  --provider aws \
  --key {{your access key}} \
  --secret {{your secret key}} \
  --profile {{profile name as you wish}}

## AWS - Deploy
- sls deploy
 
