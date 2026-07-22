---
title: "Week 10 Worklog"
date: 2026-07-20
weight: 10
chapter: false
pre: " <b> 1.10. </b> "
---

# Week 10 Worklog (06/07/2026 – 12/07/2026)

#### 1. Weekly Objectives
- Develop an automatic resource cleanup mechanism for Amazon S3.
- Remove outdated product images when products are updated or deleted.
- Optimize cloud storage usage and resource management.

#### 2. Technical Activities Summary
This week focused on improving the image management workflow in the GearStore backend by implementing an automatic cleanup mechanism for Amazon S3. Developed backend logic to detect product updates and deletions, ensuring that obsolete images stored in Amazon S3 were removed automatically. This approach prevents unused files from accumulating in the bucket, reduces storage costs, and maintains consistency between product information and image resources. Conducted functional testing to verify that image deletion operations were executed successfully under different scenarios.

#### 3. Task Breakdown & Schedule

| Day | Task Activity | Status | Reference / Tool |
| :---: | :--- | :---: | :--- |
| **Mon** | Analyze the image lifecycle and cleanup requirements | Complete | Project Design |
| **Tue** | Implement automatic image deletion in the backend | Complete | Project Source Code |
| **Wed** | Integrate Amazon S3 DeleteObject API into product services | Complete | AWS SDK Documentation |
| **Thu** | Test image deletion during product updates and removals | Complete | Postman / AWS Console |
| **Fri** | Optimize cleanup logic and validate storage consistency | Complete | Self-testing |

#### 4. Key Deliverables & Outcomes
- **Completed Deliverables**: Successfully implemented automatic image cleanup for Amazon S3, integrated the DeleteObject API into the product management workflow, and verified consistent synchronization between product data and cloud storage.
- **Skill Acquisition**: Enhanced backend development skills by implementing cloud resource lifecycle management, optimizing Amazon S3 storage usage, and improving application reliability through automated resource cleanup.