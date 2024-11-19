# Ex.No:6
 # CREATION IN WEB APPLICATION FOR TEST ENVIRONMENT
 ## NAME:Soundarya J
 ## Reg.No:212223220108
  ## AIM
 To Creation in Web Application for Test Environment.
## PROBLEM STATEMENT
 Creating a web application for a test environment is essential to provide developers and testers with a dedicated platform to simulate, test, and validate software functionalities. The challenge lies in building an easy-to-use, scalable, and efficient application that supports realistic testing scenarios, automates workflows, and ensures smooth collaboration while minimizing setup and maintenance efforts.

## ALGORITHM
# Step 1:
Launch an EC2 instance in AWS using an Amazon Linux 2 AMI with a Security Group allowing HTTP and SSH traffic.
# Step 2:
Connect to the instance using SSH and install a web server like Apache
# Step 3:
Create a simple HTML file in the server's default directory with basic content for testing.
# Step 4:
Access the instance's public IP in a browser to verify the HTML page is displayed.
## COMMANDS
# webserver
To install httpd:
```
yum install httpd -y
```
To enable and start httpd :
```
systemctl enable httpd
systemctl start httpd
```
Create a simple HTML page :
```
cd /var/www/html
```
test.php
```
<!DOCTYPE html>
<html lang="en">
<head>
    <title>MY FIRST PHP!</title>
</head>
</body>
</html>
```

## OUTPUT
# TERMINAL
![image](https://github.com/user-attachments/assets/e180e704-24d9-4e5f-907f-61b0a4f86ea6)

![image](https://github.com/user-attachments/assets/fc482a4f-e84b-4508-8090-5ccc9cea8702)

![image](https://github.com/user-attachments/assets/cb26e8fb-4997-4845-93ae-43414dbb04d7)




# WEBPAGE
![image](https://github.com/user-attachments/assets/79513e42-aaab-40ce-ad8b-148c6ff179d8)

 

## RESULT
Thus the web application for test environment has successfully been created and executed.
 

  


