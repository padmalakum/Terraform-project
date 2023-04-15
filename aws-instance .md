creating aws instance thru Terraform

first install aws cli using this command
sudo apt install awscli

Next create a user in aws console and give administratoraccess and s3 full access and IM userchangepassword access and create access key and secret access 

![image](https://user-images.githubusercontent.com/92623347/232193698-869e461a-9b97-4dbc-9474-b320476fe031.png)


configuring awscli  by giving access key and secret access key  and exporting to Terraform also.

![image](https://user-images.githubusercontent.com/92623347/232192710-d01bc275-3675-45a9-9bda-9f099be1d118.png)

createinstance.tf file
![image](https://user-images.githubusercontent.com/92623347/232194277-30e89e98-108b-49b4-8fbb-fb0e19ab5975.png)

and run terraforminit, terraform plan, terraform apply and ec2 instance will be created as

![image](https://user-images.githubusercontent.com/92623347/232194329-adbcc340-12e0-4202-be06-2c133ba8ca3b.png)

we can check our instance which is created in aws-console

![image](https://user-images.githubusercontent.com/92623347/232194425-65addca3-9752-4371-99f5-a98e9d299116.png)



