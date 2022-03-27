# Question 1
Virtual Machine is …
- [ ] Service used to virtualize any software in the cloud
- [x] Emulation of a computer system in the cloud
- [ ] Service enabling users to purchase dedicated hardware in the cloud
>**Note:** Virtual machine is a software emulation of physical hardware. It allows customers to **emulate multiple computer 
systems** using a single physical machine.

# Question 2
In order to deploy multiple identical virtual machines which resource should be used?
- [x] Virtual Machine Scale Sets
- [ ] Virtual Machine Availability Sets
- [ ] Virtual Machine Availability Zones
- [ ] Virtual Machine Cluster Nodes
>**Note:** **Virtual Machine Scale Sets** is a resource type that enables customers to deploy and manage a set of identical 
virtual machines using the same image.

# Question 3
Which services allow customers to deploy a web application/service?
- [ ] App Service
- [ ] Virtual Machine
- [ ] Container Instances
- [ ] Kubernetes Service
- [x] All the above answers
>**Note:** I admit. This is a tricky question. While some of those services are better than the others at hosting web
applications/services. In Azure **all of those services** can be used to host web applications/services. Each service has 
it’s merits and can be used in specific scenarios.If you want to learn how to pick the right hosting service review 
this decision flow **https://docs.microsoft.com/en-us/azure/architecture/guide/technology-choices/compute-decision-tree**

# Question 4
Which services allow customers to deploy a containerized solution using a highly customizable and scalable orchestration platform?
- [ ] App Service
- [ ] Virtual Machine
- [ ] Container Instances
- [x] Kubernetes Service
- [ ] All the above answers
>**Note:** **Kubernetes** is an open-source container-orchestration platform for automating application deployment, scaling, 
and management. As such the **Kubernetes Service** is the right choice here. Other services allow for container deployment but they don’t provide a rich orchestration layer.

# Question 5
Which service allows customers to deploy small pieces of code without worrying about the underlying infrastructure and platform?
- [ ] App Service
- [ ] Virtual Machine
- [ ] Virtual Machine Scale Sets
- [x] Functions
- [ ] Container Instances
- [ ] Kubernetes Service
- [ ] All the above answers
>**Note:** **Azure Functions** delivers a serverless hosting platform and SDK that allow customers to develop small pieces of 
code and host them as web services.
 
# Question 6
Contoso company wants to migrate their on-premises applications to the cloud without the need to redesign the application. 
During the assessment it was discovered that the application can’t be containerized. Which service should they choose?
- [ ] App Service
- [ ] Kubernetes Service
- [ ] Virtual Machine Scale Sets
- [x] Virtual Machine
- [ ] Functions
- [ ] Container Instances
>**Note:** **Virtual Machines** are simply an emulation of physical hardware they can accommodate any customer needs, as such 
they are often used for ‘Lift-and-shift’ scenarios. Other services often require a small or major application redesign or 
containerization. In this case this was not an option.

# Question 7
Contoso company is building a new solution. This solution is based on social media and as such it will have a very unpredictable demand. 
They also want to minimize the costs of running the platform and don’t need a high degree of control over the environment. 
Which services best fits their need?
- [ ] App Service
- [ ] Kubernetes Service
- [ ] Virtual Machine Scale Sets
- [ ] Virtual Machine
- [x] Functions
- [ ] Container Instances
>**Note:** **Functions** is a serverless web service hosting platform. It scales nicely and with consumption based pricing it 
is ideal for hosting applications with an unpredictable workload demand.

# Question 8
Which services can be used to host a containerized web application?
- [x] App Service
- [x] Kubernetes Service
- [ ] Virtual Machine Scale Sets
- [ ] Virtual Machine
- [ ] Functions
- [x] Container Instances
>**Note:** **App Services** allow for hosting web applications by either deploying packaged code or entire containers. 
The **Container Instances** and **Kubernetes Service** are designed purely for container deployments.

# Question 9
Choose the option that orders services from the one which provides the highest degree of control to the least one
- [x] Virtual Machine > Container Instances > App Service > Functions
- [ ] Functions > Virtual Machine > Container Instances > App Service
- [ ] Container Instances > Virtual Machine > App Service > Functions
- [ ] Virtual Machine > App Service > Container Instances > Functions
- [ ] Virtual Machine > Container Instances > Functions > App Service
- [ ] Functions > App Service > Container Instances > Virtual Machine
>**Note:** With **virtual machines** customers need to the manage operating system, platform updates, runtimes and the application itself. 
This gives them a total control over everything related to the application runtime environment. **Containers** are similar 
to virtual machines except they virtualize the operating system themselves. So there is a little bit less control over the system part 
but customers can still manage almost every other aspect of the environment. **App Services** totally abstract the underlying 
platform so customers only manage their code and deployment. **Functions** are the least configurable as they are a truly serverless solution.
