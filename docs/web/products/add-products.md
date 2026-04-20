---
sidebar_position: 1
title: Add Products
---

# Add New Product

The **Add Product** page is your command center for creating and publishing new items in your store. This comprehensive guide walks you through every step, from basic details to complex configuration settings.

![Add Product Page](/img/web/product/add-product-1.png)

---

##  Quick Start Guide

1. **Basic Info**: Name, Brand, and Description.
2. **Categorization**: Select the correct category (Mandatory).
3. **Media**: Upload high-quality images.
4. **Configuration**: Choose between Simple or Variable product types.
5. **Inventory**: Set stock levels and pricing rules.
6. **Delivery**: Define shipping and return policies.
7. **Publish**: Save and go live!

---

## 1. Product Information (Basic Details)

Start by defining the core identity of your product.

| Field | Description | Importance |
| :--- | :--- | :--- |
| **Product Name** | The public display name of your product. |  **Required** |
| **Short Description** | A brief summary shown in listings. |  Recommended |
| **Product ID (SKU)** | Internal unique identifier for tracking. |  Optional |
| **Made In** | Country of origin. |  Optional |
| **Brand** | Manufacturer or Brand name. |  Recommended |
| **Tags** | Keywords for internal search optimization. |  Optional |
| **Product Type** | Physical or Digital product classification. |  Info Only |

###  AI-Assisted Description
Never write from scratch again. Use the **AI Tool** to generate professional descriptions instantly.

1. Enter a clear **Product Name**.
2. Click the **AI Icon** ✨ next to the Short Description field.
3. Review and **Edit** ✏️ the generated text to perfectly match your tone.

:::tip Professional Descriptions
A well-crafted product name helps the AI generate significantly better descriptions.
:::

---

## 2. Categories (Mandatory)

Categorization is critical for customer navigation.

- **Action**: Select the most specific category for your product from the tree.
- **Rule**: You **must** select at least one category to save the product.

:::warning Critical Step
You cannot add a product without selecting a category. ensure you select the deepest relevant sub-category (e.g., *Electronics > Audio > Headphones* instead of just *Electronics*) for better SEO and filtering.
:::

👉 [Manage Categories Here](/docs/web/categories.md)

---

## 3. Product Images

Visuals sell products. Upload clear, high-resolution images.

- **Main Image**: The specific image shown on the catalog page.
- **Other Images**: The gallery images shown on the detailed product page.

:::info Media Best Practices
Use high-resolution images with a white background for the best visual appeal.
:::

👉 [Full Media Guide](/docs/web/media-management.md)

---

## 4. Product Configuration (Core Settings)

This is the most critical step where you define **what** you are selling. Choose the path that matches your product:

###  Option A: Simple Product
*Best for: Standard items with no variations (e.g., A hammer, a standard book).*

1. Go to the **General** tab.
2. **Type Of Product**: Select `Simple Product`.
3. **Price**: Enter the regular selling price.
4. **Special Price**: (Optional) Enter a discounted price.
5. **Stock Management**: Check `Enable Stock Management` to track quantity.
6. **Dimensions**: Enter Weight (kg), Height, Breadth, and Length (cms). **Required** for shipping.

###  Option B: Variable Product
*Best for: Items with options (e.g., T-Shirt with Sizes S/M/L and Colors Red/Blue).*

This is a **2-step process**:

#### Step 1: Define Attributes
1. Go to the **Attributes** tab.
2. Select an attribute (e.g., `Color`) and click **Add Attributes**.
3. Choose values (e.g., `Red`, `Blue`).
4. **CRITICAL**: Check ☑️ **"Check if the attribute is to be used for variation"**.
5. Click **Save Attributes**.

:::caution Configuration Alert
If you do not check **"Used for variation"**, the attribute will only be displayed as text and cannot be selected by the customer.
:::

#### Step 2: Configure Variations
1. Switch to the **Variations** tab.
2. You will see a list of created variations (e.g., `Color: Red`, `Color: Blue`).
3. Click the arrow ⬇️ to expand a variation.
4. Set specific **Price**, **Image**, and **Stock** for *each* variation.
    * *Example: XXL size might cost $5 more than S size.*
5. Save your changes.

---

## 5. Inventory & Usage Settings

Control how customers can purchase your product.

###  Quantity Rules

| Setting | Function | Ideal For |
| :--- | :--- | :--- |
| **Indicator** | Show "In Stock" / "Low Stock" badge. | Urgency marketing |
| **Total Allowed Qty** | Max purchase limit per order. | Limited editions |
| **Min Order Qty** | Minimum purchase required. | B2B / Wholesale |
| **Qty Step Size** | Force multiples (e.g., buy in packs of 5). | Bulk items |

###  Bulk Discounts
Encourage larger orders by offering volume-based pricing.
* **Min Qty**: The threshold to trigger the discount (e.g., "Buy 10+").
* **Discount**: The % or fixed amount off (e.g., "Get 5% off").

:::tip Sales Strategy
Use bulk discounts to clear excess inventory or increase average order value.
:::

###  Warranty & Guarantee
Build trust with your customers.
* **Warranty**: Repair/Service coverage (e.g., "1 Year Manufacturer Warranty").
* **Guarantee**: Return/Refund assurance (e.g., "30-Day Money Back").

---

## 6. Delivery & Shipping Settings

Define the logistics for this specific product.

| Feature | Action |
| :--- | :--- |
| **Deliverable Type** | Restrict to specific delivery methods or allow "All". |
| **Zipcodes** | Whitelist specific zipcodes for delivery (leave empty for national). |
| **For Standard Shipping** | **Required**. Select your **Shiprocket Pickup Location** to calculate accurate shipping rates. |
| **COD Allowed** | Toggle to enable/disable Cash on Delivery. |
| **Returnable** | Toggle to allow customer returns. |
| **Cancelable** | Toggle to allow order cancellation. |

:::note Shipping Note
Ensure your "Pickup Location" is accurately set to calculate shipping costs correctly.
:::

---



🎉 **Click `Add Product` to publish your item to the store!**
