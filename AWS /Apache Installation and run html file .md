# Installation of Apache and Run HTML Code On AWS Linux
## Go To AWS and Sign In the console

![Awslogin](https://github.com/Parimal-Pradhan/DevOps_Project_2023/assets/86794999/3a0cda98-a254-4340-ab9e-2c8adb2c6d59)

## Select EC2 Instance

![Select_Ec2_Instance](https://github.com/Parimal-Pradhan/DevOps_Project_2023/assets/86794999/7b251ca1-6a0e-4b0a-bedf-9d031d1d64d7)

## Launch EC2 Instance

![Launch_Instance](https://github.com/Parimal-Pradhan/DevOps_Project_2023/assets/86794999/a2c5626a-4d63-4120-906e-fd49b50b6397)

## Type Name and Select AMI

![selectAMI](https://github.com/Parimal-Pradhan/DevOps_Project_2023/assets/86794999/d564614f-649b-45d8-b69f-6b7ade1bf70f)

## Select Instance type t2.micro

![instance_type](https://github.com/Parimal-Pradhan/DevOps_Project_2023/assets/86794999/b1f4ae25-43af-4ae8-a592-34b4925c3bdb)

## Create pem Key

![create_new_pair_key](https://github.com/Parimal-Pradhan/DevOps_Project_2023/assets/86794999/c4b72a09-5db4-4e72-aaa6-c0e4ca1c5f00)

## Select security Group

Allow SSH , HTTP and HTTPS traffic from the internet

![securitygroups](https://github.com/Parimal-Pradhan/DevOps_Project_2023/assets/86794999/c4e3d6aa-34a1-4d5d-9f96-2729ea4ae9fa)

## Now Click On Launch Instance and go to Dashboard.Click On Instance id.

![Ibstance_id](https://github.com/Parimal-Pradhan/DevOps_Project_2023/assets/86794999/e30291db-51d0-4d6e-8fac-898c38aa3c18)

## Click On connect Button

![click_on_connect](https://github.com/Parimal-Pradhan/DevOps_Project_2023/assets/86794999/292136ef-e5c4-4c22-a736-cf210fcf892d)

## Select EC2 Instance Connect

![Select_EC2_Instance_Connect](https://github.com/Parimal-Pradhan/DevOps_Project_2023/assets/86794999/edd7e280-1d28-4633-bb62-d2015537fc86)

## Now CLI screen would be available.Type Below commands

#### sudo su -
### Check /var/www/html directory available or not
#### ls /var/www/html/

![cliscreen](https://github.com/Parimal-Pradhan/DevOps_Project_2023/assets/86794999/3810237f-dbe6-4b54-a588-b9216fdc48e0)

## Update the System

#### yum update -y

![update_system](https://github.com/Parimal-Pradhan/DevOps_Project_2023/assets/86794999/aee15314-d6e8-4a53-8371-3d6b703a1d3b)

## Install apache 

#### yum install httpd -y

![httpd_install](https://github.com/Parimal-Pradhan/DevOps_Project_2023/assets/86794999/f307135b-a956-43aa-8445-caa86fc85046)

## Copy Index.html code and paste it into /var/www/html/ 

#### cd /var/www/html/
#### vi index.html

![htmlcode](https://github.com/Parimal-Pradhan/DevOps_Project_2023/assets/86794999/cdc78f8c-32b9-48bb-8cd1-7f91ce383215)

![htmlandindex](https://github.com/Parimal-Pradhan/DevOps_Project_2023/assets/86794999/07508689-edbb-4ede-bff2-f2f8ed4c5f92)

## Check Apache service is running or not
#### service httpd status

![service_disabled](https://github.com/Parimal-Pradhan/DevOps_Project_2023/assets/86794999/e1a34f77-318e-4290-b04e-7efc13dad312)


## Start the service 
#### service httpd start

![service_running](https://github.com/Parimal-Pradhan/DevOps_Project_2023/assets/86794999/0bbff355-a648-4432-9735-14e5aa0294b3)

## Now copy public ip and paste into web brwoser

![copypubicip](https://github.com/Parimal-Pradhan/DevOps_Project_2023/assets/86794999/ae683270-ac29-486b-94e5-a3a4a4b7dd25)

![Succesfully](https://github.com/Parimal-Pradhan/DevOps_Project_2023/assets/86794999/ba75ad7c-09aa-4c21-ba45-ac8813b111e6)

### We have sucessfully deploy static html code on Apache.
## ThankYou

![thank you](https://github.com/Parimal-Pradhan/DevOps_Project_2023/assets/86794999/87d8f23a-3116-491d-bf53-8495fe5769da)












