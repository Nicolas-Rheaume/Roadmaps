
# Application Containers

## Business Brief

Application containers are a form of OS-Virtualization in which distributed applications are run on a single virtual machine rather than one for each application. A single host OS can support multiple containers. Containers can be used on multiple systems including cloud instances and virtual machines, as well as across different OS such as Linux, Microsoft, and MAC OS. Application containers have huge benefits with their ability to be deployed in cloud environments. The main advantage to containers is there architecture. Because applications can now be placed on different virtual and physical machines this offers greater availability of those applications. These machines can be within a cloud or not. They offer high flexibility with regards to workload management and allow the developer to make vault-tolerant systems. Application containers transition datacenters from being machine oriented to application oriented. Containers encapsulate the application environment, abstracting away details from the machine, operating system, the application developer, and deployment infrastructure. Because well-designed containers and container images are scoped to a single application, managing containers means managing applications rather than machines. This shift with management APIs from machine-oriented to application oriented dramatically improve application deployment and introspection.

## Technical Brief

It can be useful to look at the concept of container images when trying to understand how containers work. Images can be stacked hierarchically. This is useful because applications can be attached to this hierarchy and each node of the tree allowing the user to share images among applications. This allows for the configuration of binary states meaning you do not have to shift around the entire application’s stack in single files. The relationship between images and containers is analogous to that of a class and object. The image like a class provides the blueprint to the container. The container is like an instance or object of this class. Another big advantage to this is if a vulnerability is discovered within a particular node, the hierarchical tree allows the user to verify all other nodes that are impacted by this vulnerability. In order to create images, it is important to look at an example. Docker uses a Docker file to create images. Containers are used to isolate processes within the OS.

Application containers can be thought of as a form of virtualization similar to Virtual Machines (VM). However instead of virtualizing the entire stack, containers vitualize at an operating system level. Because of this they are extremely lightweight, enabling them to use only a fraction of the memory and processing as only a single OS Kernel is needed to host multiple containers.

## Industry Use

The two major containerization technology vendors are Docker and CoreOS. Docker has been more widely used in the industry due to the fact it was introduced first. Application containers pose their biggest benefit to larger companies. It has been 4 years since Docker’s initial inception into the market. A 2016 survey conducted by Datadog revealed that adoption of Docker had increased 30%+ over the previous year. What is important to note about this statistic is these companies are using the software in production rather than development. This represents that companies are using containers as a long-term approach and not simply on a trial basis.

Docker can be characterized as the container management engine which creates the containers. There have also been several management platforms giving users a host of different tools in order to manage their containers. Three of these tools are OpenShift, Kubernetes, and Rancher. OpenShift uses Docker and Kubernetes as its underlying engine to manage the containers. The software will integrate with Kubernetes to enable the automation of functions such as scaling, health management, and deployment. Kubernetes, created by Google, is a well-designed orchestration tool used in the management of containers. It offers the client a high level API that allows the user to logically group containers as well as load balancing and container pools. Finally, Rancher is a container management tool built on top of the Kubernetes container engine platform.

##Canadian Government Use


As many departments shift their operation environments to a cloud infrastructure, application containers could pose a huge benefit to them. Containers will facilitate easier and more efficient deployment of applications. This can be thought of in the same light as virtual machines, except it will increase the efficiency since now multiple applications can be hosted on a single VM. It also provides great availability to departments using the cloud. This is because multiple containers can be created for a single application. This makes version control a much simpler task. This also makes the application more available as if one container instance stops working then another one can pick up where it left off. Container management platforms such as Rancher and Openshift also allow the user to verify the exact amount of resources their application is consuming. This gives operations teams the necessary information to provision resources correctly.

## Implications for Departments

### Shared Services Canada

#### Value proposition

SSC could benefit greatly from the use of application containers. Like many other departments, its use within cloud environments presents the biggest rewards. In order to do this, however, SSC will need to verify the extent to which it will use these containers and what platforms will facilitate this the best. Application containers can greatly affect the way in which datacenter services can be offered. As a department, it will be important to educate staff on how to correctly use and manage these containers moving forward. Its ability to be used in cloud application development will be its greatest asset. The technology has been proven since its inception in 2014. There are many platforms that are able to facilitate its adoption which limits SSC’s risk when adopting the software.

#### Challenges

There will be four major challenges with the adoption of application containers. The first will be staff education. The proper utilization of containers requires a whole new skill set. It also requires IT teams to be familiar with the container management tool they will be using. The second will be choosing the proper platform to run the containers. This is a crucial decision which will depend on the needs of the department. If the organization is looking for a greater level of abstraction with how their containers are created, a system like Rancher is suitable. However, more simplistically an engine like Docker could be used to create the application containers. The third challenge is re-architecting applications. Legacy applications may not always be suitable for containers. This is because containers can have trouble when developers attempt to update a single feature of their application. Isolating changes can be a challenge to the containers. The final challenge will be security. Security is heightened in this scenario since the cloud and therefore containers are all based on a network. The key factor for security is architecting a solution that grants its users freedom and speed but is not too vulnerable to breach.

Dept X
Implications list
