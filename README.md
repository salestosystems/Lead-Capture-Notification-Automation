**Project Information**

**Project Name:** Lead Capture & Notification Automation
**Category:** Revenue Operations (RevOps)
**Business Function:** Marketing Operations → Sales Operations
**Project Type:** Automated Lead Capture & CRM Synchronisation Workflow
**Built With:** Make.com, Tally Forms, HubSpot CRM, Google Sheets, Gmail, Router Logic
**Status:** ✅ Production-Ready Portfolio Project

**Lead Capture & Notification Automation**
An automated Revenue Operations workflow that captures inbound leads from Tally Forms, instantly creates CRM records, logs every submission, and notifies stakeholders in real time—eliminating manual data entry and reducing lead response time.

💡 **Architect's Note**

One of the biggest mistakes companies make isn't failing to generate leads.
It's failing to handle them properly after they arrive.

I've seen organizations spend thousands on marketing campaigns only to lose potential customers because someone forgot to copy data into the CRM, update a spreadsheet, or notify the sales team.

Every minute between lead submission and first response reduces the chances of conversion.

I built this automation to remove that delay.

Instead of relying on manual processes, every new lead is automatically captured, routed into HubSpot CRM, logged for reporting, and shared with stakeholders through email notifications.

The objective isn't simply to automate form submissions.

It's to build the first operational layer of a scalable Revenue Operations system where every lead is captured, visible, and ready for immediate action.

This project represents another step in my transition from Enterprise Sales to Revenue Operations, where systems improve execution before problems occur.

**Primary Objective**

Automatically capture inbound leads, synchronize CRM records, notify teams instantly, maintain centralized reporting, and eliminate lead leakage caused by manual processes.

**Overview**

Lead generation doesn't create revenue.

Lead management does.

Many businesses collect leads through landing pages, websites, webinars, or forms—but the real challenge begins after someone clicks Submit.

Without automation:
- Leads sit unnoticed.
- CRM updates are delayed.
- Sales teams respond hours later.
- Marketing loses attribution.
- Data becomes inconsistent.
- Opportunities disappear before conversations even begin.

This workflow creates an automated lead intake system that processes every submission instantly.

Each lead is:
- Captured from Tally Forms
- Routed through workflow logic
- Stored in Google Sheets
- Added or updated in HubSpot CRM
- Shared through Gmail notifications

Everything happens automatically within seconds.

**Business Problem**

Growing B2B organisations often struggle with:
- Manual lead entry
- Delayed sales notifications
- Missing CRM records
- Duplicate customer data
- Inconsistent reporting
- Poor response times
- Marketing and Sales misalignment

These small operational issues create the first layer of revenue leakage.

**Solution**

This automation creates an automated lead intake system.

Instead of manually copying form submissions:

✔ Capture every lead instantly
✔ Synchronize CRM automatically
✔ Maintain centralized reporting
✔ Notify stakeholders immediately
✔ Standardize lead management
✔ Eliminate manual data entry

**Workflow Architecture**
Customer
     │
     ▼
 Tally Form Submission
     │
     ▼
   Router
 ┌──────────────┬──────────────┐
 │              │
 ▼              ▼
Google Sheets   HubSpot CRM
(Add Row)     (Create/Update Contact)
      │
      ▼
 Gmail Notification
      │
      ▼
 Sales Team
 
**Workflow Screenshot**

<img width="1837" height="860" alt="Lead Capture   Notification Automation" src="https://github.com/user-attachments/assets/1270143b-cd92-4808-8b3b-b88db8f1c3c8" />

**Tech Stack**
| Layer          | Technology    |
| -------------- | ------------- |
| Automation     | Make.com      |
| Form Builder   | Tally Forms   |
| CRM            | HubSpot CRM   |
| Database       | Google Sheets |
| Notifications  | Gmail         |
| Workflow Logic | Router        |

**Revenue Operations Layer**

This project supports:

✅ **Marketing Operations**
- Lead Capture
- Form Automation
- Lead Distribution
  
✅ **Sales Operations**
- CRM Synchronization
- Contact Creation
- Sales Notifications

✅ **Revenue Operations**
- Lead Routing
- Data Standardization
- CRM Hygiene
- Operational Visibility
- Lead Response Optimization

**Business Logic**
**Traditional Process**

Customer fills form
↓
Marketing receives email
↓
Someone copies data
↓
CRM updated later
↓
Sales notified manually
↓
Lead contacted after several hours

**Problems**
- Slow response
- Human error
- Missing CRM records
- Lost opportunities
- Duplicate work

**Automated Process**
Customer submits form
↓
Make.com triggers instantly
↓
Router validates workflow
↓
Google Sheets updated
↓
HubSpot Contact created
↓
Gmail notification sent
↓
Sales team responds immediately

**Benefits**
- Faster response
- No manual entry
- CRM always updated
- Better reporting
- Higher lead conversion

**Automation Steps**
**Step 1**
Tally Forms

Monitors new form submissions in real time.

**Step 2**
Router

Directs the incoming lead through predefined workflow paths.

**Step 3**
Google Sheets

Creates a structured record for:

- Lead Name
- Company
- Email
- Phone
- Submission Time
- Source

**Step 4**
HubSpot CRM
Automatically:

- Creates Contact
- Updates existing record if found
- Maintains CRM consistency

**Step 5**
Gmail

Sends an instant notification containing:

- Lead information
- Contact details
- Submission timestamp

Allowing the sales team to respond quickly.

**Business Rules**

Examples include:

New Form Submission
↓
Validate Required Fields
↓
Create CRM Contact
↓
Store Lead Record
↓
Notify Sales Team

Additional rules can include:

- Duplicate email detection
- Lead source tagging
- Owner assignment
- Territory routing
- Lifecycle stage assignment
- UTM parameter capture
- AI lead scoring (future)

**Screenshots**




**Challenges Solved**
**Challenge 1**

Manual lead entry

Solution

Automated CRM synchronization

**Challenge 2**

Slow sales response

Solution

Instant email notifications

**Challenge 3**

Scattered lead records

Solution

Centralized logging in Google Sheets

**Challenge 4**

CRM inconsistency

Solution

Automatic contact creation and updates

**Business Impact**
Estimated Benefits

✔ Faster lead response time
✔ Improved CRM data quality
✔ Reduced manual work
✔ Better marketing-to-sales handoff
✔ Increased operational efficiency
✔ Lower lead leakage
✔ Higher sales productivity
✔ Standardized lead management process

**RevOps Components Demonstrated**
- Marketing Operations
- Lead Capture Automation
- CRM Synchronization
- Sales Notifications
- Workflow Automation
- Data Governance
- Lead Routing
- Operational Reporting
- Revenue Operations Foundations

**Future Improvements**
**Version 2**
- AI Lead Qualification
- Lead Scoring Engine
- Slack Notifications
- Microsoft Teams Alerts
- Round Robin Lead Assignment
- Territory-Based Routing
- Duplicate Detection Engine
- WhatsApp Notifications
- CRM Activity Logging
- Dashboard & Analytics

**Learning Outcomes**

Through this project I learned:

- Webhook-based workflow automation
- Real-time lead processing
- CRM synchronization architecture
- Marketing-to-sales handoff design
- Router logic in Make.com
- Data consistency strategies
- Automated notification systems
- RevOps workflow documentation
- End-to-end lead management automation
