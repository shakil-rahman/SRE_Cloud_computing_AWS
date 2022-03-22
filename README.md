# SRE Intro
## Useful Links:
- Global Infrastructure: https://aws.amazon.com/about-aws/global-infrastructure/
## User Journey
### User Experience
#### Cloud Computing with AWS

### SRE Role:
- Making sure the user journey is satisfactory (without any errors)

### Benefits of Cloud Computing:
#### Ease of use
- Users are able to quickly and securely host their applications
- You can use AWS Management Console or APIs to access AWS's application hosting platform
#### Flexibility
- Able to select any of the different services you require
- Receive a virtual environment used to load the software and services for your application
- Easy to migrate 
#### Robustness
- If one region goes down the Auto Scaler can redirect to another Availability Zone (AZ)
- Can scale up and down on demand
#### Cost effective
- You only pay resources you use (Compute power, storage)
- No long term contracts or up-front commitments

### AWS Services:
- Amazon Web Services (AWS) - A cloud services provider with the largest market share
- Region represents a separate geographical area (Ireland, London)
- Availability Zones (AZ) are the actual data centres within each region, there must be at least two AZ in each region
- Not all services are available at each AZ

### AWS Global Infrastructure:
![Global Infrastructure](./img/AWS.JPG)

### Content Delivery Network (CDN):
- Servers that are geographically closer to the user and stores your application
- Goal is to provide high availability and performance

### Solutions:
#### On-premise
- User owns all the servers and stores them locally
- More secure but puts the costs on the user for maintenance and security
#### Public cloud
- User rents all the server usage from a provider 
- Provider handles maintenance/security, user only pays for what they use
#### Hybrid
- User keeps some data local (on-prem) and other data in the cloud (Government, Banks)
- Allows for better security where needed and lower cost where it isn't needed

### AWS Diagram:
![AWS Diagram](./img/AWS_diagram.png)
- First you need an IAM role that provides you with permissions
- ec2 (elastic compute service) - Virtual Machine (VM)
- Secure it with Security groups and create a file.pem
- Store the file.pem in the .ssh folder
- VM: Computer file that behaves like an actual computer. AWS needs to know the specs for the VM similar to the specs of a laptop/desktop