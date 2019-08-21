# Module 1: Create an APEX Workspace

## Introduction

Oracle Application Express (APEX) is a feature of Oracle Database, including the Autonomous Data Warehouse (ADW) and Autonomous Transaction Processing (ATP) services. To start, you will need to create an ATP instance and then access APEX from within the Service Console. 

When you first access APEX you will need to log in as an APEX instance administrator to create a workspace. A workspace is a logical domain where you define APEX applications. Each workspace is associated with one or more database schemas (database users) which are used to store the database objects, such as tables, views, packages, and more. These database objects are generally what you base APEX applications on.

***To log issues***, click here to go to the [github oracle](https://github.com/oracle/learning-library/issues/new) repository issue submission form.

## Module 1 Objectives

- Log in to your Oracle Cloud account
- Create an Autonomous Transaction Processing instance
- Create a new workspace in APEX
- Log in to your new workspace

## Parts

### **Part 1:** Log in to your Oracle Cloud account

1. You should have signed up for your Oracle Cloud trial account. If not, return to the Workshop Introduction page and complete Step 1.

2. Once you receive the **Get Started Now with Oracle Cloud** email, make note of your **Username**, **Password**, and **Cloud Account Name**.

3. From any browser go to [https://cloud.oracle.com/en_US/sign-in](https://cloud.oracle.com/en_US/sign-in)

4. Enter your **Cloud Account Name** in the input field and click the **Next** button.

   ![](1-create-an-apex-workspace/images/enter-oracle-cloud-account-name.png)

5. Enter your **Username** and **Password** in the input fields and click **Sign In**.

   ![](1-create-an-apex-workspace/images/enter-user-name-and-password.png)

### **Part 2:** Create an Autonomous Transaction Processing instance

1. From the Cloud Dashboard, select the navigation menu icon in the upper left-hand corner and then select **Autonomous Transaction Processing**.

   ![](1-create-an-apex-workspace/images/select-atp-in-nav-menu.png)

2. Click **Create Autonomous Database**.

   ![](1-create-an-apex-workspace/images/click-create-autonomous-database.png)

3. Leave all of the default selections, enter a password for the ADMIN user, then click **Create Autonomous Database**. Remember the password as it will be required later on.

   ![](1-create-an-apex-workspace/images/atp-settings-1.png)
   ![](1-create-an-apex-workspace/images/atp-settings-2.png)
   ![](1-create-an-apex-workspace/images/atp-settings-3.png)

   After clicking **Create Autonomous Database**, you will be redirected to the Autonomous Database Details page for the new instance. Continue to the next step when the status changes from **PROVISIONING...** to **AVAILABLE**.

### **Part 3:** Create a new workspace in APEX

1. Click the **Service Console** button.

   ![](1-create-an-apex-workspace/images/access-atp-service-console.png)

2. Click **Development** option in the menu on the left, then click the **Oracle Application Express** option.

   ![](1-create-an-apex-workspace/images/access-apex.png)

3. Enter the password for the Administration Services and click **Sign In to Administration**. The password is the same as the one entered for the ADMIN user when creating the ATP instance.

   ![](1-create-an-apex-workspace/images/log-in-as-admin.png)

4. Click **Create Workspace**.
  
  ![](1-create-an-apex-workspace/images/welcome-create-workspace.png)

5. Enter your database user details and click **Create Workspace**:
   -  Database User = **DEMO**
   -  Password = <Your Password> {Note: The password must conform to Oracle Autonomous  standards}
   -  Workspace Name = {Will default to Database User}
  
   ![](1-create-an-apex-workspace/images/create-workspace.png)

6. Click the Account Menu (top right of the screen) and click **Sign Out**. This will log you out of APEX administration so that you can log into your new workspace. Once logged out, click the **Return to Sign In Page** button.
	
   ![](1-create-an-apex-workspace/images/log-out-from-admin.png)

7. Enter your workspace details and click **Sign In**.

   ![](1-create-an-apex-workspace/images/log-in-to-workspace.png)
