# Question 1
BLOB is a synonym for a file. True or false?
- [x] True
- [ ] False
>**Note:** **BLOB** stands for **B**inary **L**arge **OB**ject. Typically binary files are considered a computer-readable and not human-readable 
files. But they are files nonetheless. Personally I feel like every file can be considered a BLOB, because even human 
readable files (txt, csv, etc) are saved as series of binary data (0’s and 1’s).

# Question 2
Contoso company wants to build new application and store their application assets in Azure. Application assets might 
consist photos, movies, text files, etc. Which service suites their need best?
- [ ] Azure Table Storage
- [ ] Azure Blob Storage
- [ ] Azure File Storage
- [ ] Azure Queue Storage
- [ ] Azure Disk Storage
>**Note:** **Azure Blob Storage** is a general purpose file storage in Azure.

# Question 3
Which services are part of Azure Storage Account service?
- [x] Azure Table Storage
- [x] Azure Blob Storage
- [x] Azure File Storage
- [x] Azure Queue Storage
- [x] Azure Disk Storage
>**Note:** While using Azure Storage Account in Azure portal you will see four services. Those services are blob, file, queue 
and table storage. But disk storage is also a sub-service of the Azure Storage Account. This means that both unmanaged 
and managed disks are part of it. Even if Managed Disks are shown as a separate resource, underneath it’s still the same service.

# Question 4
Customers who need to add persistent storage for their Azure VMs can use which two services?
- [ ] Azure Table Storage
- [ ] Azure Blob Storage
- [x] Azure File Storage
- [ ] Azure Queue Storage
- [x] Azure Disk Storage
>**Note:** Azure **file** storage and **disk** storage provide customers with ability to mount drives on their PM. Disk storage 
is emulation of typical disk and file storage is a shared drive. But both can be used to provide persistent storage 
capabilities for a virtual machines.

# Question 5
Form of data that fits nicely into tabular structure with very strict schema. Every row of that table must follow defined schema. 
Multiple tables often are tied together using relationships. It is a very formalized form of data. This category of data is called?
- [ ] Unstructured data
- [ ] Semi-structured data
- [x] Structured data
>**Note:** **Structured data** is the correct answer. Structured data sets are often defined using schema and relationships.

# Question 6
Form of data that does not fit into tabular structure with very strict schema as every entry might have different set of 
properties defined. It is a less formalized form of data. This category of data is called?
- [ ] Unstructured data
- [x] Semi-structured data
- [ ] Structured data
>**Note:** **Semi-structured data** is the correct answer. Semi-structured data sets can fit into tabular form but they 
do not follow very strict schema, they only have a common column (or multiple columns) that define unique entries.

# Question 7
Form of data that does not have any pre-defined schema or is not organized in pre-defined manner. This can mean data in 
any shape or format. This category of data is called?
- [x] Unstructured data
- [ ] Semi-structured data
- [ ] Structured data
>**Note:** **Unstructured data** is the correct answer. Unstructured data often can’t be put into any pre-defined shape 
or form. Typical cases are images, binary files, etc.

# Question 8
Service used to store small pieces of information (messages) used to build scalable solutions with asynchronous messaging patterns is?
- [ ] Azure Table Storage
- [ ] Azure Blob Storage
- [ ] Azure File Storage
- [x] Azure Queue Storage
- [ ] Azure Disk Storage
>**Note:** **Azure Queue Storage** is a service designed to store messages and allow multiple services to pick them up at any 
time. Usually used in load-leveling and background processing tasks.
