# What is LAMP?

LAMP is an open-source Web development platform that uses Linux as the operating system, Apache as the Web server, MySQL as the relational database management system and PHP/Perl/Python as the object-oriented scripting language.

What is a Technology stack? A technology stack is a set of frameworks and tools used to develop a software product. This set of frameworks and tools is very specifically chosen to work together in creating well-functioning software. They are acronyms for individual technologies used together for a specific technology product.

So let's start installing them one by one:

LAMP (Linux, Apache, MySQL, PHP or Python, or Perl)


## Installing Ubuntu on AWS

### Go To AWS Console and log in.
![img1](https://github.com/parimal007/DevOps_Project_2023/assets/86794999/a06fdaab-61d7-4c6a-8b7d-35ac1a2cc6cc)

### Now click on Launch instance and select Operating system Ubuntu.

![img2](https://github.com/parimal007/DevOps_Project_2023/assets/86794999/ce118aa3-780f-43c9-a80b-78c4f2d2f4ca)

![img3](https://github.com/parimal007/DevOps_Project_2023/assets/86794999/cad4ac82-c7fe-4e68-8dbf-1320a120daf1)

### Now create Key Pair.

![img4](https://github.com/parimal007/DevOps_Project_2023/assets/86794999/56ac4ce3-b9b6-45e3-a9a5-e703ba8052ed)

### Now go to Network Settings and select Allow SSH, HTTP and HTTPS options.

![img5](https://github.com/parimal007/DevOps_Project_2023/assets/86794999/ef2aace1-a6ad-40db-ad5f-ff8788c2e67f)

### Now click on Launch instance. then go to the dashboard and click on connect.

![img6](https://github.com/parimal007/DevOps_Project_2023/assets/86794999/06aa5216-27fb-41e8-8b1c-312fb125ac09)

### Once you are done with connecting copy the ssh command.
'''
ssh -i "<pemkey" ubuntu@ec2-18-212-59-147.compute-1.amazonaws.com
'''
### Go to Mobaxterm and paste the ssh command.
### Update the system with the below command.
## Installing Apache on Ubuntu
### Now we have installed Ubuntu on AWS. Let's start installing Apache.
### Now check whether the Apache service is running or not.
### Now check if can we access our apache server locally with the curl command.
### Now go to the AWS dashboard and Select Instance id.
### Now copy Public ip and paste it into webrowser.
### you can see we have successfully finished our task. Now our machine has Linux (ubuntu) and Apache. In the next blog, we will finish our remaining installation

Thank you for reading this blog.Happy Learning!!!!!

You can follow me on LinkedIn for my daily updates:- linkedin.com/in/parimal-pradhan-b62021168
