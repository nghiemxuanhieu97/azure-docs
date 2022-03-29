# Question 1
To extend their private data center capability Contoso company have decided to leverage Azure Virtual Machines. They need 
to build a unified networking infrastructure between their on-premise environment and Azure. Which service allows them to 
connect their networking infrastructure to Azure?
- [ ] Azure Virtual Network
- [x] VPN Gateway
- [ ] Azure Load Balancer
- [ ] Azure Application Gateway
- [ ] Azure Subnet
- [ ] VNET peering
>**Note:** **VPN Gateway**, also called a virtual network gateway is the service that is used to connect on-premise networks 
to an Azure virtual network via the public internet.

# Question 2
Which services allow for even traffic distribution across multiple services.
- [ ] Azure Virtual Network
- [ ] Virtual Network Gateway
- [x] Azure Load Balancer
- [x] Azure Application Gateway
- [ ] Azure Content Delivery
>**Note:** **Load balancer** services distribute traffic evenly across multiple backend services in the server pool. In Azure, 
non-HTTP (non-web) traffic is distributed using the **Azure Load Balancer**, and HTTP (web) traffic with the **Azure Application Gateway**.

# Question 3
Azure CDN (Content Delivery Network) is a service used for…
- [ ] Even distribution of incoming traffic
- [ ] Storage of flat files in Azure at a low cost
- [x] Caching and global distribution of web application content to minimize latency of delivery to customers
- [ ] Web application content management
>**Note:** Azure CDN caches and distributes web application content across multiple POP (points of presence) locations. 
This allows users to receive their content from a nearby location, as such minimize the latency.

# Question 4
Azure Virtual Network allows customers to replicate their on-premise networking infrastructure in the cloud. True or false?
- [x] True
- [ ] False
>**Note:** Virtual networks allow customers to represent and extend their on-premise networking infrastructure in the cloud.

# Question 5
Subnets can be nested to provide even more granular segmentation of a virtual network. True or false?
- [ ] True
- [x] False
>**Note:** Subnets can’t be nested.
