# Guest-Inquiry-Management-Lead-Routing-Automation-with-Zapier
Developed a Zapier workflow to automate guest inquiry processing, data capture, lead routing, and email notifications for a property management company. Integrated Google Forms, Google Sheets, and Gmail to reduce manual data entry, prevent duplicate records and improve workflow efficiency.

# Project Overview

Designed and implemented an end-to-end workflow automation for a property management company using Zapier, Google Forms, Google Sheets, and Gmail.

The solution automates guest inquiry capture, validates and updates guest records, routes inquiries to the appropriate department, and sends personalized email notifications—eliminating manual data entry and improving workflow efficiency.

# Business Problem
Lovre Homes managed guest inquiries manually, requiring staff to:
- Monitor new Google Form submissions
- Enter guest information into Google Sheets
- Identify the correct department
- Send acknowledgment emails manually
- Manage duplicate guest records

# This resulted in:
- Time-consuming manual processes
- Delayed responses
- Duplicate records
- Inconsistent communication
  
  # Solution
Built a Zapier automation that:

- Captures guest inquiries from Google Forms
- Validates existing guest records in Google Sheets
- Updates existing records or creates new ones
- Routes inquiries using Zapier Paths
- Sends internal notification emails
- Personalizes guest confirmation emails
- Filters Gmail addresses before sending confirmations
  # Workflow
Google Forms
      │
      ▼
Google Sheets Lookup
      │
      ▼
Guest Exists?
 ├── Yes → Update Record
 └── No  → Create Record
      │
      ▼
Zapier Paths
 ├── Sales
 └── Property Management
      │
      ▼
Notify Team
      │
      ▼
Formatter
      │
      ▼
Filter Gmail Users
      │
      ▼
Send Personalized Email

# Key Features
- Automated guest inquiry capture
- Duplicate record detection
- Automated record creation and updates
- Conditional lead routing
- Personalized email automation
- Internal team notifications
- Gmail validation using Zapier Filters
  
# Tech Stack
- Zapier
- Google Forms
- Google Sheets
- Gmail
- Formatter by Zapier
- Paths by Zapier
- Filter by Zapier
  
# Business Impact
The automation replaced a fully manual inquiry process by:

- Reducing manual data entry
- Preventing duplicate guest records
- Improving data accuracy
- Accelerating response times
- Standardizing inquiry routing
- Improving customer communication
- Increasing operational efficiency
