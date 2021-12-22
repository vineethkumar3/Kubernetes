Setting the Aws Ubuntu ec2 instance

step1:
    Go to ec2 in aws and select instances
    
step2:
    click on Launch instance select the required Amazon Machine Image(AMI) os
    
step3:
    choose instance type go with t2-medium
    
step4:
    In storage change the 8gb to 30gb and in security group select existing one if its other wise select new one
    
step5:
    for keyvalue pair if it is first time choose new give a name to that file and download it 
    that file will help during login for authentication
    
    if you already have one then go with existing one 
   
step6:
    your instance is created wait for it to up and running now download MobaXterm tool for connecting to our instance with SSH
    
    a. click on session and choose ssh
    b. in remote host paste the public id of your instance that id you can find in the aws page 
    when you click on that instance you get deatails 
    c.In advance SSH settings choose use private key there select the keyvalue pair file click on OK
    d.user name for Ubuntu os is "ubuntu" for any other os "ec2-user"
    
                                          
        ALL DONE
