## What is Client-Server Model?

- The client-server model is a way of organizing computer systems where one device (the `server`) stores and manages information and another device (the `client`) requests and receives that information.
- The client sends a request to the server, and the server responds with the requested information or performs an action.
- This model is commonly used in networked computers and the internet, where a web browser (the `client`) sends requests to a web server (the `server`) to retrieve web pages.

![clientservermodel](https://github.com/ashikkumar23/aws-notes-cpe/blob/master/Images/clientservermodel.png)

- A `client` can be a web browser or desktop application that a person interacts with to make requests to computer servers.
- A `server` can be a service such as Amazon Elastic Compute Cloud (Amazon EC2), a type of virtual server.
- In Amazon Web Services (AWS), this model is often used to set up web applications, where clients (e.g., web browsers) send requests to an application server, which then retrieves data from a database and sends back the appropriate response.

**Example**:

- A user interacts with an e-commerce website, which is hosted on an EC2 instance (server) in AWS. The user's browser (client) sends a request to the EC2 instance to view a product. The EC2 instance processes the request by querying a DynamoDB (database) for the product information and sends it back to the user's browser as a response.
- A web-based email application where the client is a web browser and the server is an Amazon Simple Email Service (SES) running on AWS. The client sends a request to the server to send an email, and the server processes the request and sends the email.

In both of the above examples, the client and server communicate over the internet using standard protocols such as HTTP or HTTPS.

## What is Cloud Computing?

Cloud computing is the on-demand delivery of IT resources and applications through the internet with pay-as-you-go pricing.

- You pay only for what you use.
- In simpler terms, Cloud computing is a way to store and access data and programs over the internet instead of on a computer or server in your home or business.

**Example**:

- Instead of storing your files on your personal computer, you can store them on a cloud storage service like Google Drive or Dropbox. This allows you to access your files from any device that has internet access, rather than being limited to just the device you saved them on.

## Cloud Computing Deployment Models

Cloud computing deployment models refer to the different ways in which cloud services can be delivered to customers.

The three main cloud computing deployment models are public cloud, private cloud, and hybrid cloud

### Public cloud

Services are delivered over the internet and are owned and operated by a third-party provider. Examples include Amazon Web Services (AWS), Microsoft Azure, and Google Cloud Platform (GCP).

- Everything runs in the cloud.
- This model allows you to build or move new applications to the cloud.
- There are different levels of services ranging from low to high.
- The level of service has different requirements for your management, architecting, and infrastructure.

**Example**:

- A small business owner wants to use a cloud-based customer relationship management (CRM) system. She signs up for Salesforce, which is a public cloud service and can access the CRM system through the internet.

### Private cloud

Services are delivered over a private network and are owned and operated by the organization using them. Large enterprises and government agencies usually use these.

- Deploy resources by using virtualization and resource management tools.
- Though this model is much like legacy IT infrastructure, its application management and virtualization technologies make it more effective.

**Example**:

- A large corporation wants to use a cloud-based enterprise resource planning (ERP) system. The corporation sets up its own private cloud, which is operated and managed by the IT department and uses the ERP system on the private cloud.

### Hybrid cloud

A combination of public and private clouds, where some services are delivered over the internet, while others are delivered over a private network. This allows organizations to take advantage of the benefits of both deployment models.

- Connect cloud-based resources to on-premises infrastructure.
- Integrate cloud-based resources with legacy IT applications.

**Example**:

- A retail company wants to use a cloud-based point of sale (POS) system. The company sets up a private cloud for sensitive data such as credit card information, and a public cloud for non-sensitive data such as inventory management. The POS system can access both the private and public clouds, allowing the company to take advantage of the benefits of both deployment models.

## Benefits of Cloud Computing

### Cost Savings

Cloud computing allows businesses to pay for only the resources they need, instead of having to invest in expensive hardware and software upfront.

**Example**:

- Dropbox uses cloud computing to provide file storage and sharing services to its users at a fraction of the cost of traditional storage solutions.
- A small business can use cloud-based accounting software instead of having to purchase and maintain its own accounting software.

### Scalability

Cloud computing allows businesses to scale up or down their resources as needed, without having to invest in expensive hardware or software.

**Example**:

- Netflix uses cloud computing to handle the sudden influx of traffic during peak viewing hours.
- A company that experiences a sudden increase in demand for its online services can easily add more servers and storage space to meet that demand without having to invest in expensive hardware.

### Flexibility

Cloud computing allows businesses to access resources from anywhere, at any time, making it easy to work remotely or on-the-go.

**Example**:

- Salesforce is a cloud-based CRM software that allows sales teams to access customer data and collaborate on deals from anywhere.
- A sales team can access customer information and sales data from their laptops while on the road.

### Reliability

- Cloud computing providers often offer built-in disaster recovery and backup solutions, ensuring that data is always available, even in the event of a power outage or network failure.

**Example**:

- AWS provides disaster recovery solutions to businesses, ensuring that their data is always safe and accessible.

### Improved Security

Cloud computing providers invest heavily in security measures to protect their customer's data.

**Example**:

- AWS provides a wide range of security services, including identity and access management, data encryption, and network security.

### Easy Collaboration

Cloud computing makes it easy for teams to work together on projects, regardless of location.

**Example**:

- Google Docs is a cloud-based word processing and collaboration tool that allows multiple users to work on a document simultaneously.
- A team of designers and developers can collaborate on a project using a cloud-based project management tool, allowing them to share files and communicate in real-time.

## Resources

- [AWS Glossary](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html)

- [Whitepaper: Overview of Amazon Web Services](https://d0.awsstatic.com/whitepapers/aws-overview.pdf)

- [AWS Fundamentals: Overview](https://aws.amazon.com/getting-started/cloud-essentials/)

- [What is cloud computing?](https://aws.amazon.com/what-is-cloud-computing/)

- [Types of cloud computing](https://aws.amazon.com/types-of-cloud-computing/)

- [Cloud computing with AWS](https://aws.amazon.com/what-is-aws/)
