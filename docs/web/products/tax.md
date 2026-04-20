---
sidebar_position: 5
title: Tax
---

# Tax Management

**Tax Management** allows you to define and configure the various tax rules applicable to your products.  
Accurate tax configuration is essential for legal compliance and correct pricing calculation during checkout.

The **Tax** module provides a simple interface to register tax types (e.g., VAT, GST, Sales Tax) and their corresponding rates.

![Tax Page Overview](/img/web/tax_tab.jpg)

---

## Overview

This page enables administrators to:

- **Create new tax rules** for different regions or product categories
- **Manage existing tax records** via a centralized list
- **Edit or remove** tax entries as regulations change

---

## Add New Tax

To create a new tax record, use the **Add Tax** panel.

![New Tax Form](/img/web/tax3_tab.jpg)

### Configuration Fields

#### Tax Title
Enter a clear, descriptive name for the tax. This label may be visible to customers during checkout.

**Examples:**
- `VAT 20%`
- `GST`
- `State Sales Tax`

#### Tax Percentage
Enter the applicable tax rate as a percentage value.

**Examples:**
- `5` (for 5%)
- `18` (for 18%)

:::tip
Include the percentage in the Title for easier identification in lists (e.g., "VATStandard 20%").
:::

### Actions

- **Reset**  
  Clears the form fields to default values.

- **Add Tax**  
  Saves the new tax rule and makes it available for product assignment.

---

## Tax List Management

The **Tax List** displays all configured tax rules and provides management tools.

### Control Toolbar

- **Search** – Find tax rules by title or ID
- **Refresh** – Reload the list data
- **Filter** – Sort tax records by specific criteria

### Tax Table Columns

| Column | Description |
|------|-------------|
| **ID** | Unique system identifier for the tax rule |
| **Title** | The display name of the tax |
| **Percentage** | The defined tax rate (%) |
| **Action** | Options to edit or delete the tax rule |

### Tax Actions

Each row contains an **Action menu** for maintenance:

- **Edit**  
  Modify the tax title or percentage rate.

- **Delete**  
  Permanently remove the tax rule from the system.

:::caution
Before deleting a tax rule, ensure it is not currently assigned to active products or modifying open orders.
:::
