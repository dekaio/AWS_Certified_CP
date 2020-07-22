# AWS_Certified_CP
AWS Certified CP

# 1. What is cloud computing?
The process or using a network of remote servers hosted on the Internet to store, manage and process data rather than a local server or a personal computer.
## On-Premise
    1. You own the servers
    2. You hire the IT people
    3. You pay or rent the real-estate
    4. You take all the risk
## Cloud providers
    1. Someone else owns the servers
    2. Someone else hires the IT people
    3. Someone else pays or rents the real-estate
    4. You are responsible for your configuring cloud services and code, someone else takes care of the rest.
# 2. Six Advantages and benefits of cloud computing
    1. Trade capital expense for variable expense
    2. Benefit from massive economies of scale
    3. Stop guessing capacity
    4. Increase speed and agility
    5. Stop spending money on running and maintaining data centers
    6. Go global in minutes
# 3. Types of cloud computing
    1. Saas (For customers): A completed product that is run and managed by the service provider.
    2. Paas (For developers): Removes the need for your organization to manage the underlying infrastructure. Focus on the deployent and management of your applications. Eg. Heroku.
    3. Iaas (For Admins): The basic building blocks for cloud IT. Provides access to networking features, computers and data storage space.
# 4. Cloud computing deployment models
    1. Cloud
      Fully utilising cloud computing- Startups, Saas Offerings, New projects and companies
    2. Hybrid
      Using both cloud and on-premise - Banks, FinTech, Investment Management, Large professional service providers
    3. On-Premise
      Deploying resources on-premises using virtualization and resource management tools, is sometimes called 'private cloud' -Public sector eg Government, super sensitive data ex. hospitals, large enterprise with heavy regulation eg. Insurance companies.
# 5. AWS Gobal Infrastructures: Where does all this cloud computing run?
    69 Availability zones, 22 Geographic regions around the world with way more edge locations than the AZs. (This count may vary)  
    1. Regions: Physical location (Geographically distinct) in the world with multiple availability zones. Every region is physically isolated from and independent of evry other region in terms of location, power, water supply.    
                 Each region has atleast two AZs.   
                 AWS largest region is US-EAST.   
                 Services almost alwyas become available first in US-EAST.   
                  Not all services are available in all regions.   
                 US-EAST-1 is the region where you see all your billing information.  
         1A. Govclloud regions      
         allow customers to host sensitive controlled unclassified information and other types of regulated workloads.    
         Gov cloud regions are only operated by employees who are US citizens on US soild. They are only accessible to US entities and root account holders who pass a screening process.    
    2.Availability zones: One or more discrete data centers. An AZ is a datacenter owned and operated by AWS in which AWS services run. AZs are represented by a Region code followed by a letter identifier. eg. us-east-1a.   
    Distributing your instances across multiple AZs allows failover configuration for handling requests when one goes down.   
    <10ms latency between AZs.   
    3.Edge location: Datacenter owned by a trusted partner of AWS which has a direct connection to the AWS network. These locationse serve requests for CloudFront and Route 53. Requests going to either of these services will be routed to the nearest edge location automatically. S3 Tranfer Acceleration traffic and API Gateway endpoint traffic also use the AWS Edge Network. This allows for low latency no matter where the end user is geographically located.   
    
  
