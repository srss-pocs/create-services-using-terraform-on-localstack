# create-services-using-terraform-on-localstack

Install Terrafrom and set path
https://developer.hashicorp.com/terraform/downloads

run terrafrom -version command to check terrafrom installation

Make sure docker service is up

Lets create a s3 bucket using terraform on localstack

Run > terraform init

![image](https://github.com/srss-pocs/create-services-using-terraform-on-localstack/assets/145287517/b2a5b014-736f-45ad-a9e4-9561108d1d2a)



Run > terrafrom plan [make sure main.tf is present : moved s3 creation to main.tf]

![image](https://github.com/srss-pocs/create-services-using-terraform-on-localstack/assets/145287517/af0bd8d7-7059-40d7-b274-4665b41167ec)


terraform apply

![image](https://github.com/srss-pocs/create-services-using-terraform-on-localstack/assets/145287517/7fe776e8-5ecd-4685-80ba-24f687eb25c3)

> awslocal s3api list-buckets --region us-east-1

![image](https://github.com/srss-pocs/create-services-using-terraform-on-localstack/assets/145287517/6af9d9fd-7610-4347-b36b-ba950dbbc18b)















