10. View the already deployed project.

    a. Find the Security Compliance Center v1 and select **Deployed details (A)** 
    ![alt text](../images/1.1.10-a.png)

    b. Select the arrow **(A)** to expand the Validation successful section. Click the green number that indicates the number of resources created to view the resources. 
    ![alt text](../images/1.1.10-b.png)

    c. Here is a list of created resources by that specific section of the DA. 
    ![alt text](../images/1.1.10-c.png)

    Repeat the same steps for the **Sample RAG App Configurations** section of the DA. 

11. Expand the **Navigation menu (A)** on the upper right-hand corner. Select **Resource list.**  Filter for your resource group under **Group (B)** to view all resource deployed by the DA.
![alt text](<../images/1.1.11-a.png>)
![alt text](<../images/1.1.11-b.png>)

## Deployment Architecture Overview

This Deployable Architecture provides a robust, flexible, and secure framework for deploying RAG-based AI applications. It leverages the power of serverless technologies, advanced AI and data platforms, integrated DevSecOps practices, and stringent security and compliance measures to deliver an efficient deployment solution. The ability to customize and rapidly deploy the architecture within hours makes it an asset for any organization looking to implement AI-driven solutions. Below is a high-level view of the DA and what is deployed.

![alt text](../images/rag-stack.png)

### Expanded Overview of the DA

Serverless Services
* **Function-as-a-Service (FaaS):** Use Code Engine to run backend code without managing servers.

DevSecOps
* **CI/CD:** Automate build, test, and deployment phases with Toolchains.
* **Infrastructure as Code (IaC):** Manage infrastructure using Terraform.
* **Security Integration:** Ensure security across the DevOps lifecycle with ALM.

AI and Data Platform
* **Watson Machine Learning:** Develop, train, and deploy machine learning models.
* **Watson Discovery:** Analyze large volumes of structured and unstructured data with AI.
* **Watson Studio:** Prepare data, develop models, and deploy them in an integrated environment.
* **watsonx.governance:** Ensure AI deployments are compliant and transparent.
* **watsonx.ai:** Simplify AI model creation, training, and deployment.
* **watsonx Assistant:** Integrate AI-powered virtual assistants into applications.

Security and Compliance
* **Encryption and Key Management:** Secure data with Key Protect and Secret Manager.
* **Compliance and Monitoring:** Use Logging, Monitoring, and SCC for compliance and monitoring.

