---
title: "Week 9 Worklog"
date: 2026-07-20
weight: 9
chapter: false
pre: " <b> 1.9. </b> "
---

# Week 9 Worklog (29/06/2026 – 05/07/2026)

#### 1. Weekly Objectives
- Develop the S3 Image Handler for the GearStore backend.
- Integrate Amazon S3 image upload functionality.
- Store image Public URLs in Amazon DynamoDB.

#### 2. Technical Activities Summary
This week focused on implementing the **S3 Image Handler** module in the GearStore backend. Integrated Amazon S3 into the product management workflow, allowing administrators to upload product images directly to cloud storage. After a successful upload, the backend automatically generated the image's Public URL and stored it in Amazon DynamoDB together with the corresponding product information. Conducted integration testing to ensure image uploads, URL generation, and database updates worked correctly and consistently.

#### 3. Task Breakdown & Schedule

| Day | Task Activity | Status | Reference / Tool |
| :---: | :--- | :---: | :--- |
| **Mon** | Design the S3 Image Handler architecture | Complete | Project Design |
| **Tue** | Implement image upload functionality using Amazon S3 | Complete | Project Source Code |
| **Wed** | Generate Public URLs and integrate with Amazon DynamoDB | Complete | AWS SDK Documentation |
| **Thu** | Connect the image upload service with the product management API | Complete | Project Source Code |
| **Fri** | Perform integration testing and validate uploaded images | Complete | Postman / AWS Console |

#### 4. Key Deliverables & Outcomes
- **Completed Deliverables**: Successfully developed the S3 Image Handler, integrated image uploads with Amazon S3, generated Public URLs automatically, and stored image information in Amazon DynamoDB.
- **Skill Acquisition**: Strengthened backend development skills by integrating Amazon S3 with Java applications, managing cloud-based media resources, and synchronizing image data with Amazon DynamoDB.