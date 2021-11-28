## Setting up S3 Bucket event notifications with SQS and Terraform

#### Running Terraform

```sh
terraform init
terraform plan -var bucket = 'bucket name'
terraform apply -var bucket = 'bucket name'
```

For more details: https://www.coffeeandtips.com/post/configurando-s3-bucket-event-notification-com-sqs-via-terraform