1. Topics Covered
   AWS Cloud
   AWS AC Creation
   EC2 Theory
   Windows Instance Launch

2. What I Understood:
  -> Cloud computing refers to the on-demand delivery of IT resources
  such as compute power, storage, and applications via the internet
  through a cloud services platform like AWS.
  -> Instance, Box, Compute are all names for Server.
  -> Servers can also be said as the physical storage or database located somewhere far away and being used through the internet by paying an amount

  # Key concepts :
   -> On-Demand
   -> Scalable
   -> Pay-as-you-Go

  -> Free AWS acc. creation (Basic steps followed)

3. EC2 :
     -> EC2 is an AWS compute service stands for (Elastic Compute Cloud).
     -> It is basically a virtual machine that allows us to quickly launch virtual servers that are known as instances
     -> These servers can be build with the required configuration as the name suggests (Elastic).
     -> configurations such as CPU, RAM, storage etc

   # Key Components of EC2 -:
     1. AMI (Amazon Machine Image) - it is the OS in AWS, like there is a OS in windows. AWS has no. of predefined operating systems for both windows and linux.
     2. Instance/Server Type - Here you select the combination of CPU cores and RAM. Nowadays AWS offers predefined optimized combinations of configuration for the best performance.
     3. EBS (elastic block storage) - Its like virtual storage or hard-disk that we attach to our server/instance. it can store both OS and additional data.
     4. Name or Tag - it is a name assigned to an EC2 instance.
     5. Security groups (SG) - this manages the ports that allows traffic to and from your instance, its like a door for an instance and range varies between 0-65535.
       -> RDP(3389) - This is to access windows instances, stands for (Remote Desktop Protocol).
       -> SSH(22) - this is to access linux instances, stands for (Secure Socket Shell).
       -> HTTP(80) and HTTPS(443) - Used for web traffic
     6. Key Pair - It is like a secured key or similar to a password. It is a '.pem' file (privacy-enhanced mail)key file. Basically used to access windows instance.
                   This ".pem" file is further converted to a decrypted password,








   
