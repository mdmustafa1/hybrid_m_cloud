# hybrid_m_cloud
Hybrid Multi Cloud
Hybrid_Multi_Cloud_using_AWS _and_Terraform…………..
Note: the screen shot provided for refenrence is provide in pdf under repository as well full explaination and ss too.
Objective: I would like to do followings in one click.
1.	Lunching a new AWS (Amazon Web Services) instance
2.	Creating the EBS (elastic block storage)
3.	Mounting this storage to lunched AWS instance 
4.	Installing a web server in my case (apache web server)
5.	Starting the web services
6.	Cloning the raw html code from git hub to the AWS instance WS and 
7.	Copy these codes into the /var/www/html/ folder so, that web server can read these codes and client can view my webpages through browser.
8.	Lunching my webpage through browser
Requirements: 
1.	AWS Free account
2.	Terraform installed version: v0.12.26
3.	Account on Git hub
4.	Basic Linux Command
5.	Basic Networking and Storage Concept
Note: All Setup must be done himself like, making account on the above following software installation etc.
Setup Process:
•	Step1: login into your git hub account and write some raw html code, after creating one repository.
 

•	Step2: Login into the AWS (I year free subscription) account and see you have no any current instances lunched or other services like EBS.
 
•	Step3:  Now write code in HCL language, by making a working space/folder in terraform & initialize it, use: Terraform init

 
Step4: once initialized, then apply use: Terraform apply

Step5: You have to first write the below code, given only for reference but full code is in git repository, before init or apply the terraform. Because terraform only becomes intelligence by downloading plugins.


 
 
Step6: Once you apply you, may see the following one by on screen and also going to the aws console management.

Here as Above thing are required, all things are done and at last you may also find, below the page/website is running well.
Conclusion:
This is my initial level project mainly on aws and terroaform. But in future I am going to do a great setup using most power tools for automation as well as management, and monitoring purposes like, Jenkins, k8s, Prometheus, Grafana, …. Etc.
If any mistakes are done here, please write in comment and suggest me for doing that with best approach.
I would like to very thanks Mr. Vimal Daga Sir, for his best way of explaining right education under the training of Hybrid Multi cloud. Share and like it, if you really find great efforts here.

 
 
