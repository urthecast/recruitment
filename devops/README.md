# EC2 S3 Grabber

Use the following command to launch our EC2 S3 Grabber stack.

**NOTE:** you must provide an already provisioned ssh keypair as input

```
aws cloudformation create-stack --stack-name ec2-s3-data-fetcher --template-body file:///<path to ec2.yaml> --parameters KeyName=<my ec2 keypair>
```