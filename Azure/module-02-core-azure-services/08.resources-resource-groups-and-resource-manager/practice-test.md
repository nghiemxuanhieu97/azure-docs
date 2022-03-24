# Question 1
Resources in Azure represent …
- [ ] Generic objects that can be anything like server, license, permission assignment, etc.
- [x] Purchased services
- [ ] JSON based files
>**Note:** Azure resources represent **purchased Azure services**. While they use JSON format to do it, it’s simply for 
purposes of storing their configuration in a commonly accepted and readable format.

# Question 2
Resources Groups in Azure can represent a logical grouping of …
- [ ] A. Services by their lifecycle
- [ ] B. Services for billing and tracking purposes
- [ ] C. Services by their resource type
- [ ] D. Services by assigned departments
- [ ] E. Services by geographical location
- [x] All of the above (A, B, C, D, E) are correct
- [ ] Answers A, B and C are correct
- [ ] Answers A, B, D and E are correct
- [ ] Answers C, D and E are correct
>**Note:** Resource groups allow for grouping in any way that suits your organization’s needs. As such all of the mentioned options (A, B, C, D, E) are correct

# Question 3
For better granularity of permissions and management, it is recommended for the resource groups to be nested to represent 
the organizational/application hierarchy. True or false?
- [ ] True
- [x] False
>**Note:** Resource groups can't be nested.

# Question 4
Azure Resource Manager is …
- [ ] Application Interface used to monitor Azure resources
- [x] A centralized management layer for managing all Azure resources
- [ ] Feature of the Azure Resource Groups used to group related resources
>**Note:** Azure Resource Manager (ARM) is a centralized management layer for managing all Azure resources. All requests 
regardless of the interface used go through ARM.

# Question 5
Azure Resource Manager uses which format for its templating system
- [ ] XML
- [ ] YAML
- [x] JSON
- [ ] HTML
- [ ] CSV
>**Note:** Azure Resource Manager uses the **JSON** format to save service configuration. This can be reviewed easily using 
resources.azure.com portal.
 
# Question 6
Contoso company wants to organize their Azure environment so that developers and application owners can build their applications 
without impacting other applications. For security and operation reasons they also need to separate production from non-production 
environments. Which resource group separation strategy should they follow?
- [ ] Separation by department name
- [ ] Separation by resource type
- [ ] Separation by application lifecycle
- [ ] Separation by geographical location
- [ ] Separation by application owners
- [ ] Separation by organization cost center
>**Note:** **Separation by application lifecycle** means naming resource groups by application name and environment name 
(among others). This separation strategy allows customers to have separate groups per application and environment name to 
assign separate privileges to their employees and vendors. As such making sure they don’t impact each other while working with Azure.

# Question 7
Once created, resources can’t be moved to different resource group. True or False?
- [ ] True
- [x] False
>**Note:** Most Azure resources can be moved to a different Azure subscription/resource group with a single press of a button

# Question 8
A single resource can be placed in multiple resource groups for easier management. True or False?
- [ ] True
- [x] False
>**Note:** Azure resources can only be placed only in **a single resource group**

# Question 9
A single resource group can contain resources from different regions. True or False?
- [x] True
- [ ] False
>**Note:** There is no limitation when it comes to resource location based on resource group location.

# Question 10
Resources can be created without any resource group assignment. True or False?
- [ ] True
- [x] False
>**Note:** A resource group assignment is required when creating any resource.