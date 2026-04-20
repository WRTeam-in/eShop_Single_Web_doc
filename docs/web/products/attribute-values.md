---
sidebar_position: 4
title: Attribute Values
---

# Attribute Values Management

**Attribute Values** define the **specific selectable options** available under an Attribute.  
For example, if the attribute is **Color**, its values may include *Red*, *Navy Blue*, or *Forest Green*.

The **Attribute Values** module provides a centralized interface to **create, manage, and maintain** these options across the product catalog.

![Attribute Values Page Overview](/img/web/attribute_values_tab.jpg)

---

## Overview

The Attribute Values page enables administrators to:

- **Create new values** for existing attributes
- **Edit or update** previously defined values
- **Organize values hierarchically**, where parent–child relationships are applicable

This ensures consistency, accurate filtering, and a better product selection experience.

---

## Add Attribute Value

Use the **Add Attribute Values** panel to define a new selectable option for an attribute.

![Add Attribute Value Form](/img/web/attribute_values_tab3.jpg)

---

### Configuration Fields

#### Select Attribute

Choose the attribute to which this value belongs.

**Examples:**
- Color
- Size
- Storage Capacity

:::info
Only previously created attributes are available for selection.
:::

---

#### Attribute Value

Enter the display name for the attribute option.

**Examples:**
- Red
- XL
- 128GB

:::tip
Use clear, customer-friendly labels that will appear on the product page.
:::

---

#### Parent Attribute Value (Optional)

Select a parent value if the attribute follows a **hierarchical structure**.

**Example Use Case:**
- Attribute: Color  
- Parent Value: Blue  
- Child Value: Navy Blue  

:::note
Leave this field empty if the attribute does not require hierarchical grouping.
:::

---

### Actions

- **Reset**  
  Clears all input fields and restores default values.

- **Add Attribute Value**  
  Saves the value and makes it available for assignment to products.

---

## Attribute Values List

The **Attribute Values List** displays all configured values and provides tools for maintenance and management.

---

### Control Toolbar

- **Search** – Locate values by name or ID
- **Refresh** – Reload the list to reflect recent updates
- **Filter** – Apply sorting or filtering criteria

---

### Table Columns

| Column | Description |
|------|-------------|
| **ID** | System-generated unique identifier |
| **Attribute** | Parent attribute name (e.g., Color) |
| **Value** | Specific option label (e.g., Red) |
| **Status** | Indicates whether the value is active or inactive |
| **Action** | Edit and delete controls |

---

### Value Actions

Each row includes an **Action menu** for managing attribute values:

- **Edit**  
  Modify the value name or adjust its hierarchical assignment.

- **Delete**  
  Permanently removes the value from the system.

:::caution
Before deleting a value, ensure it is not assigned to active products to prevent data inconsistency.
:::

---

## Best Practices

- **Maintain Naming Consistency**  
  Use standardized capitalization and terminology (e.g., *Navy Blue* instead of *navy blue*).

- **Avoid Duplicate Values**  
  Check existing values before adding new ones to keep the catalog clean.

- **Use Hierarchy Only When Needed**  
  Apply parent–child relationships only where they add real organizational value.

---


