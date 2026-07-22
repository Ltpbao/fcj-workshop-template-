---
title: "Week 11 Worklog"
date: 2026-07-20
weight: 11
chapter: false
pre: " <b> 1.11. </b> "
---

# Week 11 Worklog (13/07/2026 – 19/07/2026)

#### 1. Weekly Objectives
- Develop the database reset API for the GearStore system.
- Automate data synchronization and restoration.
- Integrate Amazon DynamoDB and Amazon S3 into the data seeding workflow.

#### 2. Technical Activities Summary
This week focused on developing the **POST /products/reset-database** API to automate the database reset and data restoration process. Implemented backend logic to remove existing product records from Amazon DynamoDB, clean up image resources stored in Amazon S3, and automatically import sample product data into the system. The API also downloaded product images from Unsplash, uploaded them to Amazon S3, generated Public URLs, and associated them with the corresponding product records. Comprehensive testing was performed to ensure the entire data restoration workflow executed successfully with a single API request.

#### 3. Task Breakdown & Schedule

| Day | Task Activity | Status | Reference / Tool |
| :---: | :--- | :---: | :--- |
| **Mon** | Design the database reset workflow | Complete | Project Design |
| **Tue** | Implement the `POST /products/reset-database` API | Complete | Project Source Code |
| **Wed** | Integrate Amazon DynamoDB cleanup and Amazon S3 cleanup | Complete | AWS SDK Documentation |
| **Thu** | Import sample products and upload images from Unsplash | Complete | Unsplash API / AWS SDK |
| **Fri** | Perform end-to-end testing and validate data synchronization | Complete | Postman / AWS Console |

#### 4. Key Deliverables & Outcomes
- **Completed Deliverables**: Successfully developed the database reset API, automated the cleanup of Amazon DynamoDB and Amazon S3 resources, imported sample products, and completed the end-to-end data synchronization process.
- **Skill Acquisition**: Improved backend development skills in API design, workflow automation, cloud resource management, and data synchronization across multiple AWS services.