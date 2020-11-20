# SAM Command lines NOTES:

## Sample Templape (HelloWord)
- `sam init -r nodejs12.x` or `sam init --runtime nodejs12.x`

## Installing the dependencies
- `cd sam-app`
- `cd hello-word`
- `npm install package.json`

## Test lambda function locally (You need docker to do this)
- `cd ..`
- `echo '{}' | sam local invoke HelloWorldFunction`

## Run lambda Function locally
- `sam local start-lambda`

## Running API Gateway Locally with AWS SAM CLI
- `sam local start-api`