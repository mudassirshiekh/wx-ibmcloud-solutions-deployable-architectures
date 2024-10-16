# Upload New Artifacts

1. Expand the **Navigation menu (A)** and filter for **rag-common-services under Group (B)**. <br> 

    Expand the **AI / Machine Learning (C)** section of the resource list. <br> 

    Select the **rag-common-watsonx-assistant-instance (D)**

![alt text](../images/2.2.1-n-da.png)

2. Select **Launch Assistant (A)** 

![alt text](../images/2.2.2-n-da.png)

3. Check that you are on the correct project that corresponds to your group number. 

![alt text](../images/2.2.3-n-da.png)

4. Under **Assistant architecture**, find **Conversational search** and select **Change (A)**

![alt text](../images/2.2.4-new.png)

5. For the environment select **Draft (A)** and then click **Confirm (B)**

![alt text](../images/2.2.5-new.png)

6. Select **Elasticsearch (A)**

![alt text](../images/2.2.6-new.png)

7. On the **Settings tab (A)** select ***Upload documents to a new index in your Elasticsearch index (B)***. Click **Save (C)**.

![alt text](../images/2.2.8-n-da.png)

-----

9. Follow this [**link**](https://github.com/IBM/gen-ai-rag-watsonx-sample-application/tree/main/artifacts/sample-data/life-insurance-faqs) to where you will be able to download a new set of PDFs to upload. <br> 

Download the following PDF files: <br>

* life-insurance-faq-1.pdf
* life-insurance-faq-2.pdf
* life-insurance-faq-3.pdf
* life-insurance-faq-4.pdf
* life-insurance-faq-5.pdf

Select the file you want to download. Click on the **triple dot (A)** and then select **Download (B)**. 
Repeat for all 5 files. 

![alt text](../images/2.2.9-n-da.png)

10. Select the **Documents tab (A)** and the click **Upload (B)** to upload the new PDFs.  

![alt text](../images/2.2.10-1-n-da.png)

![alt text](../images/2.2.10-2-n-da.png)

10. Once the new documents have been uploaded navigate back to the chatbot tab and ask the questions again and observe the improvement in answers. 
* What are the different life insurance policies?
* When should I buy life insurance? 
* What does life insurance cover

___
Congratulations, you just learned how to integrate new documents into the chatbot, enabling the chatbot to utilize these documents for more accurate and contextually relevant responses.