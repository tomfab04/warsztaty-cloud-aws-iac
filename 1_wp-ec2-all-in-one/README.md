# cfn-VPC

Tworzenie Instancji WordPress

Linux:
```
aws cloudformation create-stack \
  --stack-name WP-instance \
  --template-body file://cfn-app.yaml \
  --parameters file://cfn-app.params.json \
  --profile <profile_name> --region eu-west-1
```


Windows:
```
aws cloudformation create-stack ^
  --stack-name WP-instance ^
  --template-body file://cfn-app.yaml ^
  --parameters file://cfn-app.params.json ^
  --profile <profile_name> --region eu-west-1
```
