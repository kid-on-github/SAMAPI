# SAM-API

This is a SAM API deployment example that:
- Uses a lambda to handle requests
- Requires an API Key for request auth

In this example, you can authenticate requests by adding the following to the request header:

`X-API-KEY: CiKQkTVDFr1DhfXD8PsrrIPUQv8mDYF35XncLC6F`

## Notes

Deploy to AWS:
`sam deploy --guided`

Run Locally:
`sam local start-api`

Delete Stack:
`aws cloudformation delete-stack --stack-name SAM-API --region {YOUR REGION}`

Helpful Stack Overflow comment can be found [here](https://stackoverflow.com/questions/63524004/how-to-attach-authorization-api-key-to-the-sam-cli-generated-api).