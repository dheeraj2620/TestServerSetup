# TestServerSetup

Create an ubuntu instance.

Make sure you are enabling ports 22, 80 and 3306 in the EC2 instance.

Update base url in CollegeMgmt/application/config/config file with IP address of the instance

Connect the instance using putty and then run the below script
```
git clone https://github.com/SmithaVerity/TestServerSetup.git
cd TestServerSetup/
sh deployServer.sh
```

To connect to rds db
```
git clone -b rds https://github.com/SmithaVerity/TestServerSetup.git
cd TestServerSetup/
sh deployServer.sh
```
