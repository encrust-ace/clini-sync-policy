# Clini Sync

Clini Sync is a clinic operations platform for doctors, administrators, and healthcare teams. It centralizes patients, appointments, consultations, prescriptions, lab workflows, invoicing, inventories, staff access, subscriptions, and clinic settings in one application across Android, Web, and Windows.

This README also includes a public privacy policy section that can be used for a website or store listing.

## Overview

Clini Sync is designed for practical clinic work. It reduces paperwork by keeping day-to-day clinical, billing, and operational workflows in one place.

The product currently supports:

- Patient registration and history tracking
- Appointment scheduling and follow-up workflows
- Consultation notes and digital prescriptions
- Lab test catalog management and lab report generation
- Automatic invoicing during consultation and lab workflows
- Medicine and lab inventory management
- Staff authorization with role-based access
- Clinic profile, logo, and report theme settings
- Subscription management and usage tracking
- Analytics for operational and financial visibility
- Google sign-in and email/password authentication
- Password reset for email/password users

## Core Features

### Patient Management

- Register and manage patient demographic records
- Store phone, email, age, gender, and allergy information where entered
- Keep consultation, invoice, and report history linked to the patient
- Search patients quickly across clinic workflows

### Appointments

- Schedule appointments with date, time, and visit reason
- Link appointments to existing or newly created patients
- Track consultation and lab-oriented bookings

### Consultations and Prescriptions

- Record clinical observations and advice
- Build prescriptions from clinic medicine inventory
- Capture dosage schedule, duration, and quantity clearly
- Generate invoices automatically from consultation flow when required

### Lab Workflow

- Maintain a clinic lab-test catalog
- Import tests from a master list
- Create lab reports for patients
- Track test results and generate invoice-linked lab output

### Billing and Documents

- Generate invoices for consultations, medicines, and lab services
- Track payment state and apply discounts
- Produce branded invoices, consultation documents, and lab reports
- Customize report and invoice appearance with clinic theme settings

### Inventory and Operations

- Manage medicine stock, pricing, and prescription-linked usage
- Manage lab inventory, pricing, and availability
- Use search and paginated selectors across high-volume lists

### Staff and Access Control

- Authorize staff and doctors by email from the clinic admin panel
- Assign roles such as Admin, Doctor, and Staff
- Configure doctor specialization and consultation fee settings
- Enforce clinic-level access restrictions for disabled users or clinics

### Authentication

- Sign in with Google
- Sign in with email and password
- Set up a new clinic through either Google auth or email/password auth
- Recover forgotten passwords through the in-app reset flow
- Restrict access to users already authorized by the clinic

### Clinic Settings

- Update clinic name, address, phone, and country
- Upload and crop clinic logo
- Control whether the clinic logo appears on reports and invoices
- Change app theme mode and report or invoice theme
- Manage subscription state and staff access from the More tab

### Analytics and Subscription

- View clinic revenue and operational summaries
- Review billing and workload trends
- Track subscription status, plan, and limits
- Open subscription management for upgrades or plan changes

## Platform Support

- Android
- Web
- Windows

Platform notes:

- Windows includes native protocol registration and deep-link handling for Supabase auth callbacks
- PDF export and document delivery behavior adapts by platform
- Web and desktop use the same clinic data model and auth system

## Authentication Summary

Clini Sync supports two authentication methods:

1. Google sign-in
2. Email and password

Authentication alone does not grant clinic access. Users must also be authorized within the clinic's access model.

Current behavior:

- Existing authorized users can sign in with Google or email/password
- New clinics can be created after authentication and setup completion
- Password reset is supported for email/password users
- Users who are not authorized for a clinic cannot access clinic data even if authentication succeeds

## Technology Stack

- Flutter
- Supabase
- Provider
- Shared Preferences
- Razorpay for subscription payment flow

## Privacy Policy

**Effective Date:** 03-04-2026

### 1. Introduction

Clini Sync is a clinic management and healthcare operations application used by clinics, doctors, and authorized staff.

This Privacy Policy explains what data is collected through the app, how it is used, and how it is protected.

For patient and clinic records, the Clinic or Doctor using Clini Sync is the Data Controller. Clini Sync acts as the Data Processor by providing the software and infrastructure used to manage that information.

### 2. Information We Collect

We collect information that is entered into or generated through the app.

**Clinic and Staff Information**

- Clinic name
- Clinic address
- Clinic phone number
- Country and clinic configuration data
- Clinic logo
- Report and invoice theme preferences
- Staff and doctor names
- Staff and doctor email addresses
- Staff and doctor roles
- Doctor specialization and consultation fee settings where applicable

**Patient and Clinical Information**

- Patient name
- Age
- Gender
- Phone number
- Email address where entered
- Allergy information where entered
- Appointment schedules and appointment history
- Consultation observations, prescriptions, and advice
- Lab tests, lab results, and lab reports
- Invoice and billing records tied to patient care workflows

**Authentication and Access Information**

- Google authentication data where Google sign-in is used
- Email/password authentication data managed by Supabase Auth where email login is used
- Password recovery and verification workflow state related to authentication

**Subscription and Payment Information**

- Subscription plan and usage information
- Payment-related metadata required to process subscription upgrades through the configured payment provider

**Support and Diagnostic Information**

- Support ticket information submitted from the app
- Diagnostic information included by the app to help investigate support issues, such as app version, clinic identifier, platform details, and related metadata

### 3. How We Use Information

We use the collected information only to operate, secure, support, and improve Clini Sync.

- To authenticate users and manage secure access
- To authorize clinic staff access based on clinic-controlled permissions
- To manage patient, appointment, consultation, lab, and invoice workflows
- To generate clinic documents and branded outputs
- To operate subscription and payment flows
- To provide support, maintenance, and issue resolution
- To improve app reliability, compatibility, and operational quality

We do not sell personal data or patient data.

### 4. Third-Party Services

Clini Sync uses the following third-party services to operate the product:

- **Supabase:** authentication, database, storage, and backend services
- **Google Authentication:** OAuth sign-in where the Google option is used
- **Razorpay:** subscription-related payment processing

These services operate under their own privacy and security policies.

### 5. Data Security

We use practical and industry-standard safeguards to protect data handled through Clini Sync.

- Clinic-scoped access controls
- Role-based access restrictions
- Secure backend authentication through Supabase Auth
- Protected backend storage and database access rules
- Encrypted data transmission using HTTPS and provider-managed security controls

No internet-based system can guarantee absolute security, but Clini Sync is designed to reduce unauthorized access and limit cross-clinic data exposure.

### 6. Data Retention and Deletion

Data is retained for as long as the clinic continues using the service, unless it is deleted through available administrative controls.

- Clinic administrators can disable staff access
- Clinic administrators can delete the clinic and associated records through administrative workflows
- Deletion actions may permanently remove related clinic data, including users, patients, appointments, consultations, lab records, and invoices

### 7. User Rights and Responsibilities

Depending on jurisdiction, users or patients may have the right to request access, correction, or deletion of personal data.

Because the clinic controls patient records, requests concerning patient medical information should be directed to the relevant clinic or doctor first.

### 8. Changes to This Privacy Policy

This Privacy Policy may be updated from time to time. When updated, the revised version and effective date will be published in the app repository or related distribution channels.

### 9. Contact

If you have questions about this Privacy Policy or Clini Sync data handling, contact:

- **Email:** encrustace@gmail.com
- **Organization:** Encrust Ace

## Keywords

Clinic management, doctor app, EMR, patient records, appointment scheduling, prescription management, lab reports, invoice generation, clinic software, medical inventory, healthcare operations, staff authorization.
