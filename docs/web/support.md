---
sidebar_position: 6
title: Support Ticket Management
---

# Support Ticket Management

The Support Ticket Management system helps administrators efficiently handle customer inquiries, technical issues, and support requests through an organized ticketing system.

:::tip Key Benefits
- **Organized communication** with customers
- **Track issue resolution** from start to finish
- **Prioritize urgent requests** effectively
- **Maintain support history** for reference
:::

---

## Overview

The support ticket system provides:

- **Ticket Type Management** - Custom categories for different support needs
- **Status Tracking** - Monitor tickets through their lifecycle
- **Admin Dashboard** - Centralized view of all tickets
- **Search & Filter** - Quickly find specific tickets

---

## Ticket Types

### What are Ticket Types?

Categories that organize support requests by nature:

- **Technical Support** - Software bugs, technical issues
- **Billing & Payments** - Payment problems, refunds
- **Product Inquiries** - Questions about products
- **Account Issues** - Login problems, account management
- **General Support** - Other inquiries

### Creating Ticket Types

1. Navigate to **Support** → **Ticket Types**
2. Click **"Add New Ticket Type"**
3. Enter:
   - **Type Name**: Descriptive name (e.g., "Technical Support")
   - **Description**: What this type covers
   - **Status**: Active/Inactive
4. Click **"Save"**

![Support Ticket Types Configuration](/img/web/support_ticket_types.png)

### Managing Types

- **Edit**: Click Edit icon → Update details → Save
- **Delete**: Click Delete icon → Confirm
- **Activate/Deactivate**: Toggle status switch

:::warning
Deleting a ticket type may affect existing tickets. Consider deactivating instead.
:::



## Admin Dashboard

![Support Ticket System Dashboard](/img/web/support_ticket_system.png)

### Dashboard Features

**Ticket Overview:**
- Total tickets count
- Tickets by status
- Recent activity

**Ticket List:**
- Table view with: ID, Customer, Type, Subject, Status, Priority, Date

**Search & Filter:**
- Search by ticket ID, customer name, or subject
- Filter by status, type, priority, or date
 

### Adding Internal Notes

1. Open ticket
2. Click **"Add Internal Note"**
3. Type note (e.g., "Escalated to technical team")
4. Save

:::note
Internal notes are only visible to admin users, not customers.
:::

---

## Quick Reference

### Ticket Workflow

1. Customer submits ticket → **Open**
2. Admin responds → **Pending** (if waiting for customer)
3. Customer provides info → **Open** (back to admin)
4. Admin solves issue → **Resolved**
5. Customer confirms → **Closed**
