# cfn-VPC

Tworzenie VPC w AWS

Linux:
```
aws cloudformation create-stack \
  --stack-name WP-vpc \
  --template-body file://cfn-VPC.yaml \
  --parameters file://cfn-VPC.params.json \
  --profile <profile_name> --region eu-west-1
```

Windows:
```
aws cloudformation create-stack ^
  --stack-name WP-vpc ^
  --template-body file://cfn-VPC.yaml ^
  --parameters file://cfn-VPC.params.json ^
  --profile <profile_name> --region eu-west-1
```
