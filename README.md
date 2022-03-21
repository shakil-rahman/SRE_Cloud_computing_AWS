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
- Not all services are available at each AZ
- Region represents a separate geographical area (Ireland, London)
- Availability Zones (AZ) are the actual data centres within each region, there must be at least two AZ in each region

### Content Delivery Network (CDN):
- Servers that are geographically closer to the user and stores your application
- Goal is to provide high availability and performance

### Solutions:
#### On-premise
- User owns all the servers and stores them locally
#### Public cloud
- User rents all the server usage from a provider
#### Hybrid
- User keeps some data local (on-prem) and other data in the cloud