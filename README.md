### Cloud infrastructure &amp; deployments made easy, curated for Indie Game Developers.

- [x] Covers the very basics to complex stuff
- [x] With everything simplified, and explained in layman's terms

### Table Of Contents

- FAQ
  - [ ] Why do I need to learn 'The Cloud' as a game developer?
  - [ ] How can it affect my games?
  - [ ] What cloud concepts & technologies are necessary for me to learn?
  - [ ] Got step by step guides?
- Basic Concepts
  - [ ] Domain & DNS
  - [ ] Nameservers & Records (A, AAAA, CNAME, MX, etc.)
  - [ ] IPV4 & IPV6
  - [ ] HTTP & HTTPS
  - [ ] Bits & Bytes
  - [ ] TCP, UDP & Websockets
  - [ ] Port-forwarding
  - [ ] Latencies
- Cloud Concepts & Technologies
  - [ ] Cloud Pricing
    - Compared to VPS & Dedicated Hosting
    - No upfront costs
    - Pay only for what you use
    - No termination fees
    - Use Of Spending Limits
  - [ ] Data Centers
    - Local Facilities, Regions, Zones
  - [ ] Virtual Machines
    - SSD & HDD IOPS
    - Network Throughput
    - Cores
    - RAM
    - Vertical vs Horizontal Scaling
  - [ ] Virtual Networks
    - Ingress vs Egress
  - [ ] Load Balancers
  - [ ] Traffic Managers
  - [ ] Databases
    - Relational (SQL) & Non-Relational (NoSQL)
  - [ ] Redis Cache
  - [ ] Cloud Storage
  - [ ] CDN's (Cloud Delivery Networks)
  - [ ] Metrics
- Cloud Providers
  - [ ] Microsoft Azure
  - [ ] Amazon Web Services
  - [ ] Google Cloud Platform
  - [ ] Free Tiers (& Limits)
  - [ ] Pricing & Calculators
  - [ ] Feature-By-Feature Comparisons
- Step-By-Step Guides / Examples
  - [ ] Basic Virtual Machine Deployment
  - [ ] Single-Region VM-Scale-Set w/ Load Balancer
  - [ ] Opening Ports For Your Virtual Machine
  - [ ] Multi-Region Single Virtual Machine Deployment, w/ Traffic Manager
  - [ ] Multi-Region VM-Scale-Set w/ Load Balancer & Traffic Manager
  - [ ] Using Cloud DNS Service
  - [ ] Deploying Single-Region Readable NoSQL DB
  - [ ] Deploying Multi-Region Readable NoSQL DB
  - [ ] Deploying Redis Cache Instances
  - [ ] Using CDN's (Cloud Delivery Network) In Serving Game Assets
- Misc
  - [ ] Connecting to your Virtual Machine
    - FTP / SFTP / SCP (winscp / filezilla)
    - SSH (putty)
  - [ ] Installing Node.js & NPM
  

### Basic Concepts

#### Cloud Computing
  - Cloud computing is a type of Internet-based computing that provides shared computer processing resources and data to computers and other devices on demand.
  - Simply put, at today's age of computers, the cloud allows you to lease virtual networks, servers, storage & related services which are **instantaneously** provisioned and released for your use, with minimal management effort.
  - References
    - https://en.wikipedia.org/wiki/Cloud_computing

#### Cloud Computing Service Models
  - *Software as a Service (SaaS).* 
  - *Platform as a Service (PaaS).* 
  - *Infrastructure as a Service (IaaS).* 
![img](http://i.imgur.com/b5mZnHu.png)
  - References
    - https://en.wikipedia.org/wiki/Cloud_computing#Service_models
- **[DNS / Domain Name System](https://en.wikipedia.org/wiki/Domain_Name_System)**
  - Computers (in your local area network, and on the internet) identify each other by IP Addresses & domain names. The whole internet (which on the higher level involve most of our ISP's) operate on this Domain Name System. These IP Addresses & domain names can be assigned for free on your local area network; however on the internet, these IP Addresses & domain names are LEASED - which means you have to pay for them on a monthly / yearly basis for the ISP's .
  - **[DNS Record Types](https://en.wikipedia.org/wiki/List_of_DNS_record_types)**
  - Domain Name
    - A domain name is an identification string that defines a realm of administrative autonomy, authority or control within the Internet.
    - **[List of Internet top-level domains](https://en.wikipedia.org/wiki/List_of_Internet_top-level_domains)**
