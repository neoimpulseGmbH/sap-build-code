# User Story: Sales Lead Management App

---

## **Description**

As a **salesperson**, I want to **manage my sales leads and their associated contacts**,  
so that I can track sales opportunities, monitor their progress, and improve my ability to convert leads into customers.

---

## **Lead Description**

### Lead

A lead represents a potential sales opportunity involving a person or organization interested in our offerings.

**Typical attributes of a lead include:**
- **Lead ID**: A unique identifier for the lead.  
- **Lead Name**: A descriptive label for the opportunity (e.g., “Miller GmbH Warehouse Expansion”).  
- **Contact / Customer**: The associated individual or company.  
- **Lead Status**: Open, In Progress, Qualified, Lost, Converted.  
- **Priority**: Low, Medium, High.  
- **Expected Close Date**: The estimated date by which the lead may close.  
- **Created On**: Date when the lead was created in the system.  

---

### Contact (Customer / Prospect)

A contact is an individual linked to one or more sales leads.

**Typical attributes of a contact include:**
- **Name**  
- **Company Name**  
- **Contact Information** (email, phone)  
- **Role** in the organization  

---

## **Acceptance Criteria**

---

### Scenario 1: List All Leads

**Given** I am logged into the SAP Fiori sales management app,  
**When** I launch the application,  
**Then** I should see a list of all my leads with key information.

**Lead list view should include:**
- Lead ID  
- Lead Name  
- Contact / Customer Name  
- Status  
- Priority  
- Expected Close Date  

**Available filters should include:**
- Lead Status  
- Priority  
- Date Range (Created On, Expected Close Date)  
- Assigned To (optional, if leads can be shared or reassigned)

---

### Scenario 2: View Lead Details

**Given** I have selected a specific lead from the list,  
**When** I open the detailed view,  
**Then** I should see all relevant information for that lead and its associated contact.

**Lead Details:**

- Lead ID
- Lead Name
- Status
- Priority
- Expected Close Date
- Contact Name
- Company Name
- Contact Email/Phone
