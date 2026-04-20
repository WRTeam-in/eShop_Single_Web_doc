---
sidebar_position: 3
title: Zipcode
---

# Zipcode Management

Zipcode Management allows you to configure specific zipcodes (postal codes) where you provide delivery services. For each zipcode, you can set delivery charges and minimum order amounts for free delivery, providing more granular control than city-level settings.



## Zipcode Dashboard

The zipcode dashboard displays all configured zipcodes with their delivery settings.

**Table Columns:**
- **ID**: Unique zipcode identifier
- **ZIPCODE**: Postal code (e.g., 370815, 203601, 411002)
- **CITY NAME**: Associated city (e.g., Dar, Pune, Nashik)
- **MINIMUM FREE DELIVERY ORDER AMOUNT**: Order value required for free delivery
- **DELIVERY CHARGES**: Shipping cost for orders below the minimum
- **ACTIONS**: Edit (green) and Delete (red) buttons

---

## Adding a New Zipcode

### Step 1: Open Add Zipcode Form

Click the **"Add Zipcode"** button to open the add zipcode form.

![Manage Zipcodes](/img/web/zipcode.png)

The "Manage Zipcodes" form displays with four required fields.

### Step 2: Fill Zipcode Form

#### **1. Zipcode** *

- Enter the postal code/zipcode
- **Required field**
- **Examples**: "370815", "203601", "411002", "10001"

:::tip Zipcode Format
- Enter zipcodes without spaces or special characters
- Use the exact format customers will enter at checkout
- Verify zipcodes are valid for the selected city
:::

#### **2. City** *

- Select the city this zipcode belongs to
- **Required field**
- Choose from the dropdown list of configured cities
- **Example**: Select "Dar", "Pune", or "Nashik"

:::important City is Mandatory
**You must add cities first before adding zipcodes.** Every zipcode must be linked to a city. If you haven't added any cities yet, go to [City Management](/docs/web/location/city) first.
:::

#### **3. Minimum Free Delivery Order Amount** *

- Set the minimum order value for free delivery
- **Required field**
- **Example**: If set to 50, orders above $50 get free delivery
- Enter **0** if you don't offer free delivery for this zipcode

:::note How It Works
**Order $100, Minimum $50** → Free delivery  
**Order $40, Minimum $50** → Delivery charge applied  
**Minimum set to 0** → Delivery charge always applied
:::

#### **4. Delivery Charges** *

- Enter the delivery/shipping cost for this zipcode
- **Required field**
- **Example**: 0, 30, 50 (representing $0, $30, $50)
- This charge applies to orders below the minimum free delivery amount

:::important
Zipcode-level delivery charges override city-level charges. Use this for precise zone-based pricing.
:::

### Step 3: Save Zipcode

- Click **"Add Zipcode"** (green button) to save the new zipcode
- Click **"Reset"** (yellow button) to clear the form
- The new zipcode will appear in the zipcode list below

:::tip
Add zipcodes for high-demand areas first, then expand to additional zones as needed.
:::

---

## Editing a Zipcode

### Step 1: Open Edit Zipcode Form

1. Locate the zipcode in the zipcode list
2. Click the **Edit** button (green pencil icon) next to the zipcode
3. The "Edit Zipcode" modal opens with current settings

The "Edit Zipcode" form displays with the same four fields, pre-filled with current values.

### Step 2: Update Zipcode Details

#### **Zipcode**
- Update the postal code if needed
- **Example**: Change from "370815" to "370816"

#### **City**
- Change the associated city if needed
- Select from the dropdown list

#### **Minimum Free Delivery Order Amount**
- Change the threshold for free delivery
- **Example**: Change from 50 to 100
- Set to **0** to disable free delivery

:::note
Adjusting minimum amounts per zipcode allows you to optimize delivery economics for different areas.
:::

#### **Delivery Charges**
- Update the shipping cost
- **Example**: Change from 30 to 50
- This applies when order is below minimum free delivery amount

:::important
Changes to delivery charges affect new orders immediately. Existing orders keep their original delivery charges.
:::

### Step 3: Save Changes

- Click **"Update Zipcode"** (green button) to save changes
- Click **"Reset"** (yellow button) to revert to original values
- Changes take effect immediately in the zipcode list

---

## Deleting a Zipcode

### How to Delete

1. Find the zipcode you want to remove
2. Click the **Delete** button (red trash icon) next to the zipcode
3. Confirm deletion in the popup
4. Zipcode is permanently removed

:::warning
Deleting a zipcode may affect:
- Customers in that zipcode won't see it as a delivery option
- They may fall back to city-level delivery settings
- Existing orders from that zipcode remain unaffected
:::

