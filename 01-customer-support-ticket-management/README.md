# Automated Customer Support Ticket Management System

## Project Overview

A customer support workflow designed to streamline the process of receiving, tracking, prioritising and acknowledging customer enquiries.

This project demonstrates how no-code automation tools can reduce repetitive administrative work and improve customer support operations.

## Business Problem

Customer support teams often manage enquiries manually. This can lead to:
- Delayed responses to customers.
- Poor ticket tracking.
- Inconsistent prioritisation.
- Repetitive administrative tasks.

## Solution

I designed a workflow using Google Forms, Google Sheets, Make.com and Gmail to organise customer enquiries and prepare automated acknowledgement emails.

## Technologies Used

- **Google Forms:** Customer enquiry collection.
- **Google Sheets:** Ticket database and automated classification.
- **Make.com:** Workflow orchestration.
- **Gmail:** Customer acknowledgement emails.

## Workflow

1. A customer submits a support request through Google Forms.
2. The response is recorded in Google Sheets.
3. Spreadsheet formulas automatically assign a priority based on the customer's urgency selection.
4. Each ticket receives an automatically generated reference number.
5. New enquiries are monitored through Make.com.
6. Gmail is configured to send an acknowledgement containing the customer's ticket information.

## Ticket Management Features

| Feature | Description |
|---|---|
| Ticket ID | Automatically generated ticket reference |
| Priority | Low, Medium or High |
| Ticket Status | Automatically marked Open |
| Customer Information | Captured through Google Forms |
| Email Acknowledgement | Configured through Gmail |

## Priority Classification Logic

The spreadsheet uses rule-based classification:

- High urgency → High priority
- Medium urgency → Medium priority
- Low urgency → Low priority

This version uses spreadsheet formulas rather than an AI model.

## Project Structure

```text
01-customer-support-ticket-management/
├── README.md
├── screenshots/
│   ├── 01-google-form.png
│   ├── 02-ticket-database.png
│   ├── 03-make-workflow.png
│   └── 04-gmail-acknowledgement.png
└── sample-data.csv
```

## Testing Status

The Google Forms and Google Sheets components have been tested with fictional customer submissions.

The Make.com scenario and Gmail module have been configured, but end-to-end execution is pending due to the account's scenario limitations.

## Future Improvements

- Integrate AI-powered ticket classification.
- Add automatic escalation for high-priority tickets.
- Introduce customer follow-up reminders.
- Develop a customer support performance dashboard.
- Add error handling and duplicate-ticket prevention.

## Author

**Mercy Mkimbo**

Aspiring AI Automation and Customer Operations Specialist.

Skills and interests:
- Customer Support Operations
- Business Process Automation
- CRM Workflows
- Make.com
- Artificial Intelligence Applications

LinkedIn: https://www.linkedin.com/in/mercy-mkimbo-8628673b8
