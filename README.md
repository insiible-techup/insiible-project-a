# insiible-project-a

This project is the first of our capstone projects and will target the implementation part of the training
showcasing the skills we've picked up through out the session;

## Scope

The project will be highlighting the following skills

* Version contol(git, github)
* IAC(terraform)
* Containerization(docker)
* Orchestration(kubernetes, helm)
* GitOps (argocd)
* Harshicorp vault(vault)


## High level overview of the project

This project is loaded indeed and we are going to try to approach it in a very simplified manner to make sure
the core reason why the project exist is understood!

The project will touch a lot of DevOps concepts and will give you a better understanding of the different DevOps
concept and implementation.

## Concepts

### Version Control System

A version control system (VCS) is a software tool that allows developers and teams to manage changes to their code
and documents over time. It keeps track of every modification made to files, enabling users to review, revert, or 
merge changes easily.

The main purpose of a VCS is to provide a collaborative and organized environment for multiple developers to work
on the same codebase simultaneously without conflicts.

[Read more about version control systems](https://www.geeksforgeeks.org/version-control-systems/)


### Infrastructure as Code

IAC stands for "Infrastructure as Code." It is a software engineering approach that involves managing and provisioning
infrastructure resources using code and automation rather than traditional manual processes.

In the context of cloud computing and DevOps practices, IAC allows developers and system administrators to define and deploy 
infrastructure resources, such as virtual machines, networks, storage, and services, through code scripts. These scripts can 
be written in configuration files or programming languages.

By treating infrastructure as code, teams can version control their infrastructure configurations and easily reproduce
environments consistently across different stages of development and deployment. This approach promotes consistency,
repeatability, and scalability while reducing the risk of configuration errors and manual setup discrepancies.

[Read more about IAC](https://www.redhat.com/en/topics/automation/what-is-infrastructure-as-code-iac)


### Containerization

Containerization is a technology that allows applications and their dependencies to be packaged together into a standardized,
isolated unit known as a container. These containers encapsulate everything the application needs to run, such as code, runtime,
libraries, and system tools. They operate independently of the underlying infrastructure and can be easily moved between environments.

The primary advantage of containerization is its portability and consistency. Since containers are self-contained units, developers can
create an application on their local machine and be confident that it will run identically in any environment that supports containers.
This eliminates the common "it works on my machine" issue and streamlines the development and deployment process.

[Read more about containerization](https://www.ibm.com/topics/containerization)\

[Read more about Docker](https://docs.docker.com/?_gl=1*hg2i1a*_ga*MjAwNDY3OTU2Mi4xNjkwMjQwNDU4*_ga_XJWPQMJYHQ*MTY5MDI0MDQ1OC4xLjEuMTY5MDI0MDQ4MS4zNy4wLjA.)


### Orchestration

Orchestration, in the context of software development and IT operations, refers to the automated management and coordination of complex tasks, 
services, and systems in a centralized manner. It involves organizing and controlling various components, such as containers, virtual machines,
 microservices, and networking, to work together efficiently and achieve a desired outcome.

In the realm of cloud computing and containerization, orchestration tools play a crucial role in deploying, scaling, and managing applications
across distributed environments. These tools handle tasks like container scheduling, load balancing, auto-scaling, service discovery, and failure recovery.

One of the most popular orchestration tools is Kubernetes, which automates the deployment, scaling, and operation of application containers. With Kubernetes,
developers can define their desired state and let the platform manage the underlying infrastructure to ensure that the application runs as intended.


[Read more about Kubernetes](https://azure.microsoft.com/en-us/resources/cloud-computing-dictionary/what-is-kubernetes/#overview)\
[Read Helm doc](https://helm.sh/docs/)


### GitOps

GitOps is a modern approach to managing and automating the deployment and operation of applications and infrastructure using version control systems, primarily Git.
It aims to streamline the software delivery process, improve collaboration, and ensure consistency and reliability in the deployment pipeline.

In GitOps, the desired state of the entire system, including application code, configuration, and infrastructure definitions, is declared and stored in a Git repository.
Any changes to the system are made through pull requests and commits to the repository.

The core idea of GitOps is that the entire deployment process is declarative, meaning the desired state of the system is clearly defined and version-controlled. This 
eliminates the need for manual interventions and ad-hoc changes, leading to a more robust and auditable deployment process.

[Read more about GitOps](https://about.gitlab.com/topics/gitops/)\
[More about gitops](https://www.atlassian.com/git/tutorials/gitops)\
[Even More gitops](https://www.gitops.tech/)


### Harshicorp Vault


HashiCorp Vault is an open-source tool and enterprise-grade platform designed for securely managing secrets, encryption keys, and sensitive data in modern IT environments.
It provides a centralized and highly secure repository for storing, accessing, and revoking secrets used by applications, services, and users.

The main features and capabilities of HashiCorp Vault include:

Secret Management: Vault allows users to store and manage various types of secrets, such as API keys, passwords, access tokens, and certificates. These secrets are securely
encrypted and can be accessed by authorized applications or users through APIs or command-line interfaces.

Dynamic Secrets: Vault can generate dynamic secrets on-demand for various services like databases, cloud providers, and more. These dynamically generated secrets have a limited
lifetime, improving security by reducing the exposure window.

Encryption as a Service: Vault provides encryption as a service, enabling applications to offload cryptographic operations and key management tasks to Vault securely.

Access Control: Vault implements fine-grained access control policies, ensuring that only authorized entities can access specific secrets or perform certain operations within
the system.

Auditing and Logging: Vault maintains detailed audit logs, allowing organizations to monitor access patterns and detect potential security breaches or compliance issues.

High Availability: Vault supports high availability configurations, ensuring that secrets remain accessible even during server failures or maintenance.

Integration with Cloud and DevOps Tools: Vault integrates seamlessly with various cloud providers, identity providers, and CI/CD tools, making it well-suited for modern cloud-native
and DevOps environments.

Due to its robust security features and flexibility, HashiCorp Vault is widely adopted by organizations to protect sensitive data, manage secrets securely, and enhance overall security
posture in their infrastructure and application deployments.


[Read more about Harshicorp vault](https://www.vaultproject.io/)