# powerautomate-onboarding-flow
Power Automate flow for automated employee onboarding (accounts, groups, notifications).

# Power Automate – Employee Onboarding Flow

This repository contains a Power Automate flow used to automate **employee onboarding** requests, approvals, and IT account setup.

It is designed for K–12 school districts but can be adapted to other organizations.

---

## What This Flow Does

- Collects new employee details from a **Form** (e.g. Microsoft Forms).
- Routes the request for **approval** (HR, supervisor, or IT).
- Sends **confirmation emails** to:
  - The requester
  - The employee
  - Location/department contacts (optional)
- Triggers follow-up actions, such as:
  - Adding the user to specific **security groups**
  - Notifying IT to create accounts or devices
  - Logging the request in a list or system

---

## Prerequisites

To use this flow, you will need:

- A Microsoft 365 tenant with:
  - Power Automate
  - Outlook (for sending emails)
  - SharePoint or Dataverse (if you use lists/tables)
- Appropriate permissions to:
  - Import solutions or flows
  - Create connections (Forms, Outlook, SharePoint, etc.)

---

## How to Import the Flow

1. Download the `.zip` file from:  
   `flow/onboarding-flow.zip`

2. Go to [Power Automate](https://make.powerautomate.com).

3. In the left navigation, go to **Solutions** (recommended) or **My flows**.

4. Click **Import**:
   - Upload `onboarding-flow.zip`.
   - Review connection references and assign them to the appropriate connections in your environment.
   - Complete the import.

5. Open the imported flow, update:
   - Email addresses
   - Site URLs
   - Group IDs / locations
   - Any organization-specific values

6. Turn the flow **On** and test with a sample request.

---

## Conference / Demo Info

This flow was presented at:  
**CITE Annual Conference - 2026 – Automating the Impossible: How One District Streamlined Tech Operations with Power Automate**  
by **Benjamin Esquivel** – Director of Technology, Imperial USD
