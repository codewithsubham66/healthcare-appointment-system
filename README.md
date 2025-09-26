Healthcare Appointment Scheduling System
A comprehensive, enterprise-grade Healthcare Appointment Scheduling System developed on the Salesforce Platform. This capstone project demonstrates the full software development lifecycle from initial planning through configuration, customization, integration, and deployment.

Project Overview
This application addresses inefficiencies in manual healthcare appointment management by creating a centralized Salesforce-based platform that automates scheduling, enhances patient and staff experience, and secures sensitive health data.

Features & Technologies
Feature Area	Salesforce Technologies Used
Data Model	Custom Objects (Patient__c, Appointment__c, Doctor__c), Master-Detail & Lookup Relationships
Security & Sharing	Profiles, Permission Sets, Organization-Wide Defaults (OWD) Private, Record Ownership
Business Logic	Validation Rules, Record-Triggered Flow, Approval Processes
Backend Development	Apex Triggers, Batch Apex, Schedulable Apex
Frontend Development	Lightning App Builder, Lightning Web Components (LWCs)
Integration	Apex Callouts, Remote Site Settings
Data Management	Salesforce Data Loader, CSV Import
Deployment	Salesforce DX (SFDX), Visual Studio Code, package.xml Manifest
Analytics	Custom Reports and Dashboards with Funnel and Gauge Charts
Development Phases

Phase 1 & 2: Project Setup and Configuration
Defined business requirements and secure Salesforce environment setup. Created user personas for patients, doctors, and admin staff. Configured Organization-Wide Defaults (OWD) as Private for key objects to enforce data security.

Phase 3: Data Modeling
Designed core database schema with custom objects like Patient__c, Doctor__c, Appointment__c, and related fields. Established lookup and master-detail relationships to model healthcare appointment workflows efficiently.

Phase 4: Process Automation
Automated scheduling workflows including validation that appointments are linked to valid patients and doctors. Created record-triggered flows to automate appointment status updates and notifications. Implemented approval processes for appointment rescheduling and cancellations.

Phase 5: Apex Backend Logic
Developed Apex triggers to enforce data integrity and prevent duplicate appointments. Created batch Apex classes to send automated reminders for upcoming appointments. Scheduled recurring Apex jobs to maintain system health and data synchronization.

Phase 6: User Interface Development
Built the "Healthcare Scheduler" Lightning App with a branded and intuitive interface. Customized record pages and navigation using Lightning App Builder. Developed LWCs for interactive appointment booking and calendar views.

Phase 7: Integration
Integrated with external healthcare APIs using Apex callouts. Secured external endpoints with Remote Site Settings. Displayed live data within LWCs based on API responses to enhance patient and staff information access.

Phase 8: Data Management & Deployment
Used Salesforce Data Loader to bulk import patient and appointment data via CSV files. Managed metadata and deployment lifecycle using Salesforce DX with version control in Visual Studio Code and package.xml manifests.

Phase 9: Reporting & Security Validation
Created detailed reports and dashboards visualizing appointment trends and patient visits. Configured sharing settings and verified record-level permissions with test logins to ensure strict data access controls.

Phase 10: Final Presentation
Prepared a persona-driven live demo script highlighting core features and user experiences. Developed sample patient and appointment data for a smooth presentation. Summarized project value and key technical skills showcased.

Demo Video Link
https://drive.google.com/file/d/1JbWXt42UTFJVY9lRxHub1bTjx3u3Xc_U/view?usp=drive_link
