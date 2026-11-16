**Cloud-Based Customer Relationship Management System (Cloud CRM)**
Project Overview

The **Cloud-Based Customer Relationship Management System (Cloud CRM)** is a cloud-based application designed to manage customer information, sales leads, interactions, and follow-up activities in one centralized platform.

The main goal of this project is to replace scattered customer records with a shared online system that helps businesses organize customer data, improve teamwork, and manage customer relationships more effectively.

**Objectives**

- Store customer details in a centralized database.
- Track sales leads and their progress.
- Manage customer interactions and communication history.
- Schedule and monitor follow-up tasks.
- Provide secure online access to authorized staff.
- Improve customer service and team collaboration.

** Problem Statement**

Traditional customer management often relies on notebooks and spreadsheets, which can cause:

- Scattered customer information.
- Missed customer follow-ups.
- Difficulty tracking sales leads.
- Duplicate or inconsistent records.
- Limited visibility into customer activities.

Our proposed Cloud CRM system addresses these challenges through a centralized cloud-based solution.

**Key Features**

1. **Secure Login** – Staff authentication with role-based access.
2. **Customer Management** – Add, edit, and search customer information.
3. **Lead Tracking** – Track potential customers through sales stages.
4. **Interaction History** – Maintain records of calls, meetings, and complaints.
5. **Follow-up Tasks** – Schedule follow-ups and monitor pending activities.
6. **Dashboard** – View customer counts, leads, and task progress.

 **Example Workflow**

The system follows a simple customer management process:

1. **Add:** Save the customer's name and contact details.
2. **Track:** Mark the customer as interested in a product.
3. **Plan:** Create a follow-up task with a due date.
4. **Update:** Record the interaction and update the sales status.

**Result:** Customer information, interaction history, and next actions are available in one place.

 **AWS Services Used**

The proposed system uses the following AWS services:

| AWS Service | Purpose |
|---|---|
| Amazon EC2 | Runs the CRM application and backend |
| Amazon RDS | Stores customer, lead, and task data |
| Amazon S3 | Stores uploaded documents and files |
| Amazon Cognito | Supports user authentication and account recovery |
| AWS IAM | Manages permissions and access to AWS resources |
| Amazon CloudWatch | Collects logs and monitors the application |

 ** Proposed System Architecture**

The proposed architecture follows this flow:

```text
       STAFF BROWSER
             |
             v
        AMAZON EC2
     (CRM Application
       and Backend)
             |
             v
        AMAZON RDS
    (Customer and Sales
          Records)

Additional AWS Services:

Amazon Cognito  - Staff Authentication
Amazon S3       - File Storage
AWS IAM         - Access Control
CloudWatch      - Monitoring and Logs
```
 **Motivation**

The project aims to:

- Save time by reducing manual record searching.
- Support teamwork through shared customer information.
- Improve customer service through better follow-ups.
- Provide online access to customer records.
- Make customer relationship management easier and more organized.

** Expected Outcome**

The Cloud-Based CRM system aims to provide:

- Centralized customer information.
- Better sales lead management.
- Organized follow-up activities.
- Improved collaboration among employees.
- Convenient cloud-based access.

 **Project Team**

| Name | Student ID |
|---|---|
| Geethika Chowdary | 2520030354 |
| Tehseen Ashraff | 2500030280 |
| M. Vignesh | 2520030065 |

**Future Enhancements**

- Automated email and notification reminders.
- Advanced sales analytics and reporting.
- Customer communication integration.
- Mobile-friendly CRM application.
- AI-powered customer insights.

**Conclusion**

The **Cloud-Based Customer Relationship Management System** aims to simplify customer management by bringing customer records, sales leads, interaction history, and follow-up activities into one centralized platform.

By using AWS cloud services, the proposed system provides a foundation for a scalable and accessible customer management solution.

---

⭐ Connect with customers. Keep every next step in view.

**Project:** Cloud-Based Customer Relationship Management System  
**Category:** Cloud Computing  
**Platform:** Amazon Web Services (AWS)
