---
title: "Week 12 Worklog"
date: 2024-01-01
weight: 12
chapter: false
pre: " <b> 1.12. </b> "
---



### Week 12 Objectives:

* Build a complete AI processing pipeline for the system: OCR (Textract) and summarization/classification with Amazon Bedrock.
* Test the entire end-to-end flow of the AI-Powered Smart Document Assistant system.

### Tasks to be carried out this week:
| Day | Task | Start Date | Completion Date | Reference Material |
| --- | --- | --- | --- | --- |
| 2 | - Continue developing the AI processing pipeline for the AI-Powered Smart Document Assistant system using AWS AI services. | 06/07/2026 | 06/07/2026 | Amazon Textract Documentation Amazon Bedrock Documentation |
| 3 | - Deploy Amazon Textract using Asynchronous Processing, integrating Amazon SNS and AWS Lambda to automatically receive OCR results and update document status. | 07/07/2026 | 07/07/2026 |  |
| 4 | - Extract content from PDF, image, DOCX and PPTX formats; save OCR results to storage and sync metadata to Amazon DynamoDB. | 08/07/2026 | 08/07/2026 |  |
| 5 | - Integrate Amazon Bedrock to automatically summarize and classify documents based on extracted content, updating processing results in real time via AWS AppSync Subscription. | 09/07/2026 | 09/07/2026 |  |
| 6 | - Test the entire flow from document upload, OCR, AI processing, result storage to status update; evaluate system performance and optimize the processing flow. | 10/07/2026 | 10/07/2026 |  |


### Results achieved in week 12:

* Successfully deployed Amazon Textract with asynchronous processing, automatically receiving OCR results via SNS + Lambda.
* Successfully extracted content from multiple document formats (PDF, image, DOCX, PPTX) and synced metadata to DynamoDB.
* Successfully integrated Amazon Bedrock to automatically summarize and classify documents based on OCR content.
* Updated processing results in real time on the Angular UI via AWS AppSync Subscription (GraphQL real-time).
* Completed end-to-end testing of the entire system (upload → OCR → AI processing → save results → real-time display); the system runs stably and is ready for the graduation report.
