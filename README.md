# automated-sponsor-document-distribution-workflow
Power Automate workflow that automates sponsor document distribution using SharePoint Lists and Outlook.

## Project Status

In Progress

## Overview

This project demonstrates how Power Automate, SharePoint Lists, SharePoint Document Libraries, and Outlook can be combined to automate document distribution to project sponsors.

The workflow retrieves sponsor information from a SharePoint List, loops through each record, and sends customized emails with required attachments. The solution reduces manual effort, improves consistency, and creates a repeatable process that can be maintained by future staff.

## Business Problem

Project sponsor communications required staff to manually identify recipients, prepare emails, attach multiple documents, and distribute information to approximately 15 project sponsors. This process was repetitive, time-consuming, and increased the risk of missed recipients, inconsistent communications, or incorrect attachments.

## Solution

A Power Automate workflow was developed to automate sponsor document distribution using an Excel table stored in SharePoint, SharePoint document libraries, and Outlook. The workflow retrieves sponsor information from the Excel table, processes each sponsor record individually, identifies the appropriate sponsor-specific workbook using the WorkbookFileName field, retrieves the workbook from a designated SharePoint folder, and sends customized emails with both sponsor-specific and standard CAPER attachments. The solution standardizes communications, reduces manual effort, minimizes the risk of distribution errors, and creates a repeatable process that can be maintained by future staff.

## Technologies Used

- Microsoft Power Automate
- Microsoft Excel
- SharePoint Document Libraries
- Microsoft Outlook
- OneNote
- GitHub

## Workflow Process

1. User manually starts the workflow.
2. Power Automate retrieves sponsor records from an Excel table stored in SharePoint.
3. The workflow processes each sponsor record using an Apply to Each loop.
4. The WorkbookFileName field is used to identify the sponsor-specific workbook stored in a designated SharePoint folder.
5. Power Automate retrieves the sponsor-specific workbook.
6. Standard CAPER documents are retrieved and attached.
7. Sponsor-specific information is inserted into the email using dynamic content from the Excel table.
8. Outlook sends the email to the sponsor.
9. Distribution status can be tracked through the Excel table and Power Automate run history.

## Results

- Automated distribution of CAPER-related documents to approximately 15 project sponsors.
- Eliminated the need to manually prepare and send individual emails.
- Standardized sponsor communications and document distribution.
- Reduced the risk of missed recipients and incorrect attachments.
- Created a repeatable and scalable process that can be maintained by future staff.

## Skills Demonstrated

- Workflow Automation
- Process Improvement
- SharePoint Administration
- Data Management
- Business Process Analysis
- Technical Documentation
- End-User Support
- Microsoft Power Automate
- Microsoft SharePoint
- Microsoft Outlook
- GitHub Documentation
