1. What is Cloud Computing
Cloud computing is the on-demand delivery of compute power, database storage, applications, and other IT resources through a cloud services platform via the internet. #aws, #azure, #ibm

~ Cloud is something which is present at remote location. Cloud is not a single computer but rather a Data center which has millions of computers and applications such as DropBox, iCloud, E-mail, Web Conference runs on the cloud.

Example:
AWS is going to provide the following;
    - Compute & Storage
    - Storage
    - Database
    - Application Services
    - Deployment & Management

2. Advantages of Cloud Computing
    - Run your business: don't worry about your IT
    - Stop spending money on running and maintaining data centers
    - Go global in minutes (S3 Bucket)
    - Stop guessing capacity
    - Instant software updates
    - Fewer maintenance cost

3. Types of Cloud Computing
    ~ Infrastructure as a Service (IaaS)
        + Infrasturcture as a Service (IaaS) is a form of cloud computing that provides virtualized computing resources over the internet.
        + Date center Provider will not have access to your server
    ~ Platform as a Service (PaaS)
        + Cloud Servie Provider (AWS) manages the underlying hardware and the O/S
        + Client focus is on applications
        + Cloud Service Provider also handles security patching, updates and maintenance
    ~ Software as a Service (SaaS)
        + Allows the client to connect to and use cloud-based apps over the internet
        + Examples are Email, Calendaring, Office Tools (O365)
    
    * On-Premises       * Infrastructure as a Service       * Platform as a Service     * Software as a Service
        Applications        Applications                        Applications                📌Applications
        Data                Data                                Data                        📌Data
        Runtime             Runtime                             📌Runtime                   📌Runtime
        Middleware          Middleware                          📌Middleware                📌Middleware
        O/S                 O/S                                 📌O/S                       📌O/S
        Virtualization      📌Virtualization                    📌Virtualization            📌Virtualization
        Servers             📌Servers                           📌Servers                   📌Servers
        Storage             📌Storage                           📌Storage                   📌Storage
        Networking          📌Networking                        📌Networking                📌Networking                

4. Types of Cloud Computing Deployments
    ~ Public Cloud - AWS, Azure, IBM
    ~ Private Cloud - (Or on Premise) E.g. VMware
    ~ Hybrid Cloud - Mixture of Public & Private

5. Why Learning AWS
    ~ Fastest Growing Cloud Platform in the Universe
    ~ Largest IaaS - Infra as a Platform
    ~ Largest Public Cloud Platform
    ~ Organizations are Migrating their Products to AWS
    ~ Most popular Certifications for IT and Software Employees
    ~ Cost Efficient

6. Benefits of AWS
    ~ High Availability
    ~ Fault Tolerance
    ~ Scalability
    ~ Elasticity
    ~ Cost Efficient
    ~ Secure
    ~ AWS Documentation - Guide to Use AWS Service

7. AWS Region
    ~ A Region is a geographical area which consist of the AZ
    ~ Each Region consists of 2 or More Availability Zones (AZ) or physical data centers
    ~ A grouping of AWS resources located in a specific geographical location
    ~ Edge Locations are Content Delivery Network (CDN) End Points for Cloud Front and there are more Edge Locations then Regions
        *** Exam Tips ***
        What is Region?
        What is Availabilty Zone?
        What is Edge Location?

    ~ IAM is where you manage your AWS users and their access to AWS account and Services
    ~ The common use of IAM to
        - Manage Users
        - Manage Groups
        - IAM Access Policies
        - Roles
        *** Exams Tips ***
        Understand IAM into details
    ~ Root Account is the email address that was used for Sign up to AWS
    ~ Secure Root Account with MFA
    ~ For security purpose, create another User using IAM and share the details for other users

    ~ You can access the AWS Platform in 3 ways;
        - Via Console
        - Programmatically (Using CML)
        - Using SDK
        *** Exams Tips ***
        Users - End Users
        Groups - A collection of Users under one set of permissions
        Role - You create roles and can then assign them to AWS Resources
        Policies - A document that defines one or more Permissions
    ~ IAM roles are secure way to grant permissions to entities that you trust
        - IAM user in another account
        - Application code running on an EC2 instance that need to perform actions on AWS resources