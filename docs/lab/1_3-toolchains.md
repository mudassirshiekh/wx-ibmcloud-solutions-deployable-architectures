# Toolchains

At the Generative application layer, we need to make sure that we follow DevSecOps best practices to develop, test and deploy the Gen AI application on a secure infrastructure.

The Deployable Architecture Stack for the RAG Application includes DevSecOps for Application which is supported through IBM Cloud Toolchain Service the CI/CD/CC pipelines were used to deploy the application on Code Engine Services checking for vulnerabilities and ensuring audit-ability.

The (CI) pipeline is used to develop the application, using DevSecOps best practices including evidence collection, artifact signing, and vulnerability checks.

The (CD) pipeline supports continuous deployment of the application, including evidence collection, GitOps flow, change management, and compliance scans. Once deployed on Code Engine, we can launch the application and make it available for end users.
___

1. Expand the **Navigation menu (A)** and hover over **Platform Automation (B)** then select **Toolchains (C)**
![alt text](../images/1.3.1-newest.png)

2. Select the CI toolchain **rag-lab-##-rag-sample-app-CI-Toolchain (C)** (where ## is replaced with your group number). <br>
    - For example: rag-lab-00-rag-sample-app-CI-Toolchain

![alt text](../images/1.3.2-newest.png)

3. Under Delivery pipelines select **ci-pipeline (A)**
![alt text](../images/1.3.3-n.png)

4. Select the **rag-webhook-trigger (A)**
![alt text](../images/1.3.4-n.png)

5. Select the most recent successful pipeline run
![alt text](../images/1.3.5-n.png)

6. Click on **code-compliance-checks (A)**
![alt text](../images/1.3.6-n.png)

7. Select **run-stage (A)**
![alt text](../images/1.3.7-n.png)

8. The **code-compliance-checks** stage of the CI pipeline is used to detect potential vulnerabilities in the code and ensure that the code adheres to specific standards and guidelines before it is built or deployed. 