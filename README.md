# 🛒 Procurement Process Automation

## 📖 Project Overview

The Procurement Process Automation project is designed to streamline and automate the end-to-end procurement lifecycle, from purchase request creation to vendor selection, purchase order generation,
goods receipt, invoice verification, and payment processing. The solution improves operational efficiency, reduces manual errors, ensures compliance with procurement policies, and provides complete visibility into procurement activities.

---

## 🎯 Business Problem

Traditional procurement processes often involve manual approvals, email-based communication, paper documents, and fragmented tracking mechanisms. These challenges lead to:

- Delayed approvals and order processing
- Increased manual errors
- Limited process transparency
- Compliance risks
- Difficulty in tracking procurement activities
- Challenges in audit and reporting

The organization required a centralized automated solution to standardize and optimize procurement operations. 

---

## 💡 Proposed Solution

Develop a workflow-driven Procurement Process Automation System that:

- Automates purchase request creation and approvals
- Enables RFQ generation and vendor collaboration
- Supports vendor evaluation and selection
- Automates Purchase Order (PO) creation
- Tracks goods receipt and inspections
- Performs invoice verification through 3-way matching
- Facilitates payment processing and exception handling
  
---

## 🎯 Business Objectives

- Improve procurement process efficiency.
- Reduce approval and purchasing cycle times.
- Minimize manual data entry and errors.
- Ensure compliance through automated controls.
- Increase transparency and traceability for auditing and reporting.


---

## 👥 Key Stakeholders

| Stakeholder | Responsibility |
|------------|---------------|
| Requester | Creates purchase requests |
| Manager Level 1 | Reviews and approves requests within threshold |
| Manager Level 2 | Approves high-value requests |
| Purchase Team | RFQ management and vendor selection |
| Purchase Manager | Reviews and approves purchase orders |
| Vendors | Submit quotations and fulfill orders |
| Warehouse Team | Receives and inspects goods |
| Accounts Team | Processes invoices and payments 

---

## 🔄 Procurement Workflow

```text
Purchase Request
        │
        ▼
Manager Approval
(Level 1 / Level 2)
        │
        ▼
RFQ Creation
        │
        ▼
Vendor Quotations
        │
        ▼
Vendor Evaluation
        │
        ▼
Purchase Order Creation
        │
        ▼
PO Approval
        │
        ▼
Vendor Fulfillment
        │
        ▼
Goods Receipt & Inspection
        │
        ▼
3-Way Matching
(PO + GRN + Invoice)
        │
        ▼
Payment Processing
