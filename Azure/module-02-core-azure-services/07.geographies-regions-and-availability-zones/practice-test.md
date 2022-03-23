# Question 1
Which of the following protects your application from region-wide disasters? Select the two most appropriate options.
- [ ] Data Centers
- [ ] Availability Zones
- [ ] Regions
- [x] Region Pairs
- [x] Geographies
>**Note:** Both **Region Pairs** and **Geographies** are designed to be fault-tolerant and help customers replicate their solutions 
across regions as such allowing them to create highly available applications capable of withstanding region-wide failures.

# Question 2
Availability zones are enabled for all Azure regions. True or false?
- [ ] True
- [x] False
>**Note:** This sentence is **false**. Only certain Azure Regions have Availability Zones enabled at this time. 

# Question 3
Availability zones are…
- [ ] Separate data centers with shared IT infrastructure
- [x] Physically separate facilities with independent cooling, power and networking infrastructure
- [ ] Logical groupings of Azure data centers for billing and compliance purposes
>**Note:** Availability Zones are designed to help customers protect from data center failures by logically grouping 
**physically separate facilities that have their own independent cooling, power and networking infrastructure**, and allowing 
services to take advantage of this fact.

# Question 4
An Azure region has…
- [x] One or more data centers
- [ ] One or more region pairs
- [ ] Three or more data centers
>**Note:** Azure region typically has more than one data center, but it’s not a requirement. So a **minimum of one data 
center makes up for an Azure region**

# Question 5
Zone enabled Azure regions must have a minimum of two Availability Zones. True or false?
- [ ] True
- [x] False
>**Note:** Zone enabled regions must have a **minimum of three (3) availability zones**.
 
# Question 6
Select 4 sentences that best describe an Azure Region Pair
- [x] All Azure regions have a region pair
- [ ] Each region always has a minimum of one pair assigned
- [ ] Region pairs are designed for easy migration across the regions
- [x] Updates across region pairs are synchronized to ensure that they are not updated at the same time
- [ ] Users can chose which region their region will be paired to
- [x] Each region always has exactly one pair assigned
- [x] Deploying in region pairs allows customers to maintain data residency
>**Note:** It is a requirement that **all Azure regions have a region pair** but regions **always have exactly one pair assigned**. 
Microsoft ensures that **updates across region pairs are synchronized to ensure that they are not updated at the same time**. 
Region pairs are always within the same geography so customers can maintain their data residency.

# Question 7
Services that allow their customers to choose to which availability zones their services will be deployed, are called …
- [x] Zonal services
- [ ] Zone-redundant services
>**Note:** **Zonal services** allow customers to choose Availability Zone placement for their services.

# Question 8
Which of the following is designed to protect your application from data center level failures?
- [ ] Regions
- [ ] Region Pairs
- [x] Availability Zones
- [ ] Geographies
>**Note:** **Availability Zones** are designed to help customers protect from data center failures by logically grouping 
physically separate facilities which have their own independent cooling, power and networking infrastructure and allowing 
services to take advantage of this fact.