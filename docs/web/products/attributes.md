---
sidebar_position: 2
title: Attributes
---

# Attributes Management

Attributes define the **variable characteristics of products**, such as color, size, material, or technical specifications.  
Well-structured attributes are essential for **product organization, filtering, and variation management** across the catalog.

The **Attributes** module provides a centralized interface to **create, manage, and maintain** all product attributes efficiently.

![Attributes Page Overview](/img/web/attribute_tab.jpg)

---

## Overview

The Attributes page consists of two primary sections:

- **Add Attribute Panel** – Used to create new attributes
- **Attributes List** – Displays and manages all existing attributes

---

## Add New Attribute

The **Add Attribute** panel allows administrators to define new product characteristics that can later be assigned to products.

### Configuration Fields

#### Attribute Set

Select an existing attribute group to organize related attributes together.

- Examples: `Technical Specifications`, `Clothing Details`, `General Features`
- Click the **➕ (Plus)** button to create a new attribute set
- Click the **📋 (List)** button to manage existing sets

:::tip
Organizing attributes into logical sets improves product filtering and simplifies attribute assignment.
:::

---

#### Attribute Name

Enter a **unique and descriptive name** for the attribute.

**Examples:**
- Color
- Size
- Material
- Screen Size

:::info
Attribute names should be short, clear, and consistent across the catalog.
:::

---

#### Attribute Values

Define the selectable values associated with the attribute.

**Examples:**
- Color → Red, Blue, Green
- Size → S, M, L, XL
- Storage → 64GB, 128GB, 256GB

:::tip
Add only relevant values to avoid cluttering product selection options.
:::

---

### Actions

- **Reset**  
  Clears all entered data and restores default values.

- **Add Attribute**  
  Saves the attribute and makes it available for product assignment.

---

## Attributes List Management

The **Attributes List** displays all configured attributes and provides tools for managing them.

---

### Control Toolbar

The toolbar above the table provides quick management utilities:

- **Search** – Find attributes by name or ID
- **Refresh** – Reload the attribute list to reflect recent updates
- **View Options** – Customize table layout and column visibility
- **Export** – Download the attribute list for reporting or backup

---

### Attributes Table

| Column | Description |
|------|-------------|
| **ID** | System-generated unique identifier |
| **Attribute Set** | The group to which the attribute belongs |
| **Name** | Display name of the attribute |
| **Status** | Indicates whether the attribute is active or inactive |
| **Action** | Provides edit and delete options |

---

### Attribute Actions

Each attribute row includes an **Action menu** for maintenance tasks:

- **Edit**  
  Modify the attribute name or change its assigned attribute set.

- **Delete**  
  Permanently removes the attribute from the system.

:::caution
Deleting an attribute may affect products currently using it. Ensure the attribute is not actively assigned before removal.
:::

---

## Best Practices

- Group related attributes under meaningful attribute sets
- Keep attribute names consistent and human-readable
- Avoid deleting attributes that are already assigned to products
- Regularly review inactive attributes to keep the catalog clean

---

