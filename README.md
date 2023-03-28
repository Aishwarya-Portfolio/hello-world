## DevOps project
### Tools used
* EC2 - Amazon Linux 2023
* Github
* Jenkins
* Maven
* Tomcat

![image](https://user-images.githubusercontent.com/91592578/228321681-61cbaf36-90f9-4200-aa98-d06c78a9d2f6.png)

### Reference links
* [Install java on Amazon Linux 2023]https://docs.aws.amazon.com/corretto/latest/corretto-11-ug/amazon-linux-install.html)
* [Install Jenkins on Amazon Linux](https://www.youtube.com/watch?v=dvZ_howX86c)
* Note - amazon-linux-extras does not work on this ec2 image version so used amazon-corretto-devel.
* [Install Apache Maven on Amazon Linux](https://gist.github.com/sebsto/19b99f1fa1f32cae5d00)
* [Install and configure Apache Tomcat on Amazon Linux](https://acloudxpert.com/install-tomcat-on-amazon-linux/)

### Jenkins Plugins used
* Git - To integrate Jenkins and Git.
* Maven Integrations - To integrate Jenkins and Maven.
* Deploy to container - To integrate Jenkins and Tomcat server.
