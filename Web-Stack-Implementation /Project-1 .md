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

e.g.ssh -i "<pemkey>" ubuntu@ec2-18-212-59-147.compute-1.amazonaws.com
  
 ![img7](https://github.com/parimal007/DevOps_Project_2023/assets/86794999/2a63c22d-5b25-4282-a518-dec753a2ec90)
  
### Go to Mobaxterm and paste the ssh command.

![img8](https://github.com/parimal007/DevOps_Project_2023/assets/86794999/c094d0a6-f687-452a-bd9d-e63108c3e87f)
  
 ### Update the system with the below command.
  
 # update a list of packages in package manager
   sudo apt update

![img9](https://github.com/parimal007/DevOps_Project_2023/assets/86794999/631b5391-740b-461b-80d0-e101823d628d)
  
 # Installing Apache on Ubuntu

  Copy and paste sudo apt install apache2
 
#run apache2 package installation
sudo apt install apache2
  
 ![img11](https://github.com/parimal007/DevOps_Project_2023/assets/86794999/ff0e1c7d-0b27-45e3-a726-db75264a676f)

  Now check whether the Apache service is running or not.

sudo systemctl status apache2
  
  ![img12](https://github.com/parimal007/DevOps_Project_2023/assets/86794999/aada3e92-1f1f-4811-b5d3-91aed603412c)
  
  Now check if can we access our apache server locally with the curl command.



  

  

