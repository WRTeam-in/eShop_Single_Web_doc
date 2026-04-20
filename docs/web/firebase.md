---
sidebar_position: 3
title: Firebase Configuration
---

## Firebase Configuration

:::warning Critical
**This configuration is mandatory** for Social Login (Google/Apple) and Push Notifications to function correctly.
:::

Follow this step-by-step guide to configure your Firebase project.

---

### Step 1: Create a new Firebase project

**Next steps after click:**

1.  Go to the [Firebase Console](https://console.firebase.google.com/).
2.  Enter **Project Name**.
3.  Enable/disable **Google Analytics** (optional).
4.  Click **Create project**.
5.  Wait 20–30 seconds until the Dashboard opens.

![Add Web App in Firebase](/img/web/firebase/firebase1.png)

---

### Step 2: Enter Your Project Name

Enter your project name and click **Create project** to proceed.

![Add Authorized Domain](/img/web/firebase/firebase2.png)

---

### Step 3: Go to Authentication Section

**Actions:**

1.  Go to the **Authentication** Section in the dashboard.
2.  Click on the **Sign-in method** tab.

This section allows you to configure:
*   Login methods
*   User accounts
*   Security settings

![Firebase Configuration Code](/img/web/firebase/firebase3.png)

---

### Step 4: Configure Sign-In Providers

Enable the following sign-in methods for your application:

#### Email/Password Login
*   **Recommended for most apps.**
*   Under **Native providers**, select **Email/Password**.
*   Toggle **Enable** to **On**.
*   Click **Save**.

#### Phone (OTP) Login
*   Under **Native providers**, select **Phone**.
*   Toggle **Enable** to **On**.
*   Click **Save**.
*   _Note: May require Firebase billing setup._

#### Google Login
*   Under **Additional providers**, select **Google**.
*   Toggle **Enable** to **On**.
*   Select a valid **Support Email** from the dropdown.
*   Click **Save**.

![Firebase Configuration Providers](/img/web/firebase/firebase4.png)

---

### Step 5: Authorized Domains

**What are Authorized Domains?**
In Firebase Authentication, Authorized Domains are the list of domains allowed to use Firebase authentication features (Google Sign-In, Phone Auth, etc.). Firebase blocks requests from unauthorized domains to prevent misuse.

**How to Add a New Authorized Domain:**

1.  Go to the [Firebase Console](https://console.firebase.google.com/).
2.  Select your project.
3.  Navigate to **Build** → **Authentication** → **Settings** → **Authorized domains**.
4.  Click **Add domain**.
5.  Enter your domain name (e.g., `example.com`, `admin.example.com`).

:::warning Mandatory
You **must** add your production domains here, or users will see errors like `auth/unauthorized-domain`.
:::

![Authorized Domains Settings](/img/web/firebase/firebase5.png)
