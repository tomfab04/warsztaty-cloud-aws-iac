# cfn-VPC

Tworzenie VPC w AWS W regionie eu-west-1 (Ireland)
UWAGA! Jeśli chcesz uruchomić stack w innym regionie, to musisz również zmienić wartości 3 parametrów w pliku `cfn-VPC.params.json`


**Linux:**
```
aws cloudformation create-stack \
  --stack-name WP-vpc \
  --template-body file://cfn-VPC.yaml \
  --parameters file://cfn-VPC.params.json \
  --profile <profile_name> --region eu-west-1
```


**Windows CMD:**
```
aws cloudformation create-stack ^
  --stack-name WP-vpc ^
  --template-body file://cfn-VPC.yaml ^
  --parameters file://cfn-VPC.params.json ^
  --profile <profile_name> --region eu-west-1
```


**Windows Power Shell:**
```
aws cloudformation create-stack `
  --stack-name WP-vpc `
  --template-body file://cfn-VPC.yaml `
  --parameters file://cfn-VPC.params.json `
  --profile <profile_name> --region eu-west-1
```

