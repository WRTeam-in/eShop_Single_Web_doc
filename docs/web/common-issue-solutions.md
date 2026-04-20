---
sidebar_position: 29
title: Common Issue Fixes
---

### 404 Not Found Error on Site

If you are encountering **404 Not Found** errors on your site (especially when navigating to sub-pages), it is often because the server is not correctly routing requests to your application entry point.

### Solution: Add an `.htaccess` file

You need to add a `.htaccess` file to your project's **root directory**. This file tells the Apache server how to handle URLs.

Create a file named `.htaccess` and paste the following code into it:

<a href="/files/htaccess.txt" download>Download .htaccess file</a>  

> **Note:** After downloading, rename the file to `.htaccess` (remove the `.txt` extension) and upload it to your root directory.

### Countries not showing in countries table

If countries are missing, you need to import the SQL file.

1. Download the `countries.sql` file (ensure you have this file from the main package).
2. Import it into your database's `countries` table. 
<a href="/files/countries.sql" download>Download countries.sql file</a>     

### Disable only_full_group_by mode

Disable `only_full_group_by` mode from your server.
Ask on server support he will help you.

### `BILLING_NOT_ENABLE` issue on the register page

![BILLING_NOT_ENABLE](/img/web/blaze_plan_issue.png)
You need to enable the billing from the firebase blaze plan.

### solution :

1. Go to the firebase console.
2. Select your project.
3. Go to the billing section.
4. Enable the billing.

![BILLING_NOT_ENABLE](/img/web/blaze_plan_solution.png)

### Categories not showing on Home page 

1. You must assign a product to the category, or the category must have a child category.

### Version not updating through system updater 
Increase `file_uploads` and `upload_max_filesize` from your server settings.

### Hostname not found error while login / register
Go to your Firebase console -> Authentication -> Settings -> Authorized Domains and add your domain name there.

### Images not Showing Properly
Enable the GD extention from the server